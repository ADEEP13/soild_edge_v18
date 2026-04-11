# Solid Edge V18 Installation Files

This repository contains Solid Edge V18 installation files and resources.

## 📁 Contents

- **Solid Edge/** - Main Solid Edge V18 installation files
- **Solid Edge Viewer/** - Solid Edge Viewer installation files
- **SELicense.dat** - License file
- **.gitattributes** - Git LFS configuration for large files

## ⚠️ Important: Git LFS Required

This repository uses **Git Large File Storage (LFS)** because some installation files are larger than 100 MB (such as DLLS.cab - 152 MB).

If you download without Git LFS, you will get text pointer files instead of actual binary files, which will cause installation errors like:
```
Error 1311: Source file not found: 
C:\CAID\solid_edge_v18-main\Solid Edge\DLLS.cab
```

## ✅ How to Download Properly

---

## 🪟 **WINDOWS**

### Step 1: Install Git LFS (One-time setup)

- Download from https://git-lfs.github.com/
- Run the installer
- Follow the installation prompts

### Step 2: Clone the Repository

Open **PowerShell** or **Command Prompt** and run:

```powershell
# Navigate to where you want the folder (e.g., Desktop, Documents)
cd C:\Users\YourUsername\Desktop

# Clone the repository
git clone https://github.com/ADEEP13/soild_edge_v18.git

# Navigate to the cloned folder
cd soild_edge_v18

# Pull the large files from LFS
git lfs pull
```

### Step 3: Verify Files

The folder should now be at:
```
C:\Users\YourUsername\Desktop\soild_edge_v18\
├── Solid Edge/
│   ├── DLLS.cab (152 MB) ← Must be actual file, not pointer
│   ├── Data1.cab
│   └── ... (other .cab files)
├── Solid Edge Viewer/
├── SELicense.dat
├── README.md
└── .gitattributes
```

### Step 4: Run Installation

1. Open File Explorer
2. Navigate to: `C:\Users\YourUsername\Desktop\soild_edge_v18\Solid Edge\`
3. Find and run the setup/installer file
4. Installation should proceed without errors

---

## 🍎 **MAC**

### Step 1: Install Git LFS (One-time setup)

**Option A: Using Homebrew (Recommended)**
```bash
brew install git-lfs
git lfs install
```

**Option B: Manual Download**
- Download from https://git-lfs.github.com/
- Run the installer
- Follow the installation prompts

### Step 2: Clone the Repository

Open **Terminal** and run:

```bash
# Navigate to where you want the folder (e.g., Desktop, Documents)
cd ~/Desktop

# Clone the repository
git clone https://github.com/ADEEP13/soild_edge_v18.git

# Navigate to the cloned folder
cd soild_edge_v18

# Pull the large files from LFS
git lfs pull
```

### Step 3: Verify Files

The folder should now be at:
```
~/Desktop/soild_edge_v18/
├── Solid Edge/
│   ├── DLLS.cab (152 MB) ← Must be actual file, not pointer
│   ├── Data1.cab
│   └── ... (other .cab files)
├── Solid Edge Viewer/
├── SELicense.dat
├── README.md
└── .gitattributes
```

Check the file sizes with:
```bash
ls -lh Solid\ Edge/DLLS.cab
# Should show ~152M, NOT 130 bytes
```

### Step 4: Run Installation

1. Open Finder
2. Navigate to: `~/Desktop/soild_edge_v18/Solid Edge/`
3. Find and run the setup/installer file
4. Installation should proceed without errors

---

## 🐧 **LINUX**

### Step 1: Install Git LFS (One-time setup)

```bash
# Ubuntu/Debian
sudo apt-get install git-lfs

# Fedora
sudo dnf install git-lfs

# Then initialize LFS
git lfs install
```

### Step 2: Clone the Repository

```bash
# Navigate to where you want the folder
cd ~/Desktop

# Clone the repository
git clone https://github.com/ADEEP13/soild_edge_v18.git

# Navigate to the cloned folder
cd soild_edge_v18

# Pull the large files from LFS
git lfs pull
```

### Step 3: Verify Files

```bash
# Check file size
ls -lh Solid\ Edge/DLLS.cab
# Should show ~152M, NOT 130 bytes

# Or use git lfs to verify
git lfs ls-files
```

## 🚫 What NOT to Do

- ❌ **Don't download as ZIP** - This won't work with LFS files
- ❌ **Don't clone without Git LFS** - You'll get pointer files instead of real files
- ❌ **Don't try to use pointer files** - They're only 130 bytes and won't install

## 💾 File Sizes

| File | Size | Status |
|------|------|--------|
| DLLS.cab | 152 MB | Tracked by LFS |
| Data1.cab | 93 MB | Tracked by LFS |
| Other .cab files | Various | Tracked by LFS |
| **Total** | **~500 MB** | **Git LFS enabled** |

## ❓ Troubleshooting

**Q: I'm getting "Source file not found" error**
- A: You didn't install Git LFS or didn't run `git lfs pull`. Follow the steps above for your OS.

**Q: How do I check if LFS is working?**

**Windows:**
```powershell
git lfs ls-files
```

**Mac/Linux:**
```bash
git lfs ls-files
```
Should show 54 tracked files (not error)

**Q: Can I just download the ZIP?**
- A: No, ZIP downloads don't support LFS. You must use `git clone`.

**Q: File is only 130 bytes instead of 152 MB**
- A: This is a pointer file. You need Git LFS installed. Reinstall and run `git lfs pull`.

**Q: I already cloned without LFS, how do I fix it?**
- A: Install Git LFS, then run:

**Windows:**
```powershell
git lfs pull
```

**Mac/Linux:**
```bash
git lfs pull
```

## 📝 Repository Information

- **Owner:** ADEEP13
- **Repository:** https://github.com/ADEEP13/soild_edge_v18
- **Branch:** main
- **License:** Check individual file licenses with Solid Edge

---

**Last Updated:** April 11, 2026
