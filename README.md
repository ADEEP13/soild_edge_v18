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

### Step 1: Install Git LFS (One-time setup)

- **Windows/Mac/Linux:** Download from https://git-lfs.github.com/
- Run the installer and follow the instructions

### Step 2: Clone the Repository

```bash
# Clone the repository
git clone https://github.com/ADEEP13/soild_edge_v18.git

# Navigate to the folder
cd soild_edge_v18

# Pull the large files from LFS
git lfs pull
```

### Step 3: Verify Files

The folder should now contain:
```
soild_edge_v18/
├── Solid Edge/
│   ├── DLLS.cab (152 MB) ← Must be actual file, not pointer
│   ├── Data1.cab
│   └── ... (other .cab files)
├── Solid Edge Viewer/
├── SELicense.dat
└── .gitattributes
```

### Step 4: Run Installation

1. Navigate to the `Solid Edge/` folder
2. Run the setup/installer
3. Installation should proceed without errors

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
- A: You need to install Git LFS and run `git lfs pull`. See Step 1-2 above.

**Q: How do I check if LFS is working?**
- A: Run `git lfs ls-files` - Should show 54 tracked files (not error)

**Q: Can I just download the ZIP?**
- A: No, ZIP downloads don't support LFS. You must use `git clone`.

## 📝 Repository Information

- **Owner:** ADEEP13
- **Repository:** https://github.com/ADEEP13/soild_edge_v18
- **Branch:** main
- **License:** Check individual file licenses with Solid Edge

---

**Last Updated:** April 11, 2026
