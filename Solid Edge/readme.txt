--------------
Legal Notices
--------------
© 2005, 
UGS Corp.

All Rights Reserved
Software, file formats, and audiovisual displays may be used pursuant to the 
applicable Software License Agreement and contain confidential and proprietary 
information of UGS Corp.; which is protected by 
copyright and trade secret law.  Such materials may not be reproduced or 
transferred to other documents or used or disclosed to others for manufacturing 
or for any other purpose except as specifically authorized within the terms of 
the Software License Agreement, or as specifically authorized in writing by 
UGS Corp.

UGS Corp.
5800 Granite Parkway
Suite 600
Plano, TX. 75024


-------------------
Version Information
-------------------
Product:        Solid Edge
Number:         SE289-ENG or SE290-ENG
Version:        18.00.00.69
Date:           09-Nov-2005
Description:    Solid Edge is a revolutionary computer-aided 
                design (CAD) system for mechanical assembly, 
                part modeling and drafting. Written specifically 
                for the Windows operating systems, you can effortlessly 
                integrate Solid Edge with office automation programs as 
                well as mechanical design, engineering, and manufacturing 
                systems.

                For more information about our software and 
                services, visit our home page on the World Wide 
                Web at:
                   http://www.solidedge.com
--------------------------
End of Version Information
--------------------------

----------------------------------------------
Solid Edge System Requirements and Information
----------------------------------------------
 · OPERATING SYSTEM REQUIREMENTS AND INFORMATION

   This release of Solid Edge has been certified to run on the following:
    · Windows XP Professional® operating system (32-bit) running Service Pack 2
    · Windows XP Professional® operating system (64-bit) running on EM64T hardware
    · Windows 2000 Professional® operating system running Service Pack 4
    · Internet Explorer 6.0 or higher
    
   Solid Edge V18 requires these versions (or later) to install due to system
   files delivered with these versions that Solid Edge relies on for proper
   operation.  Also taken into consideration is Microsoft's support timeline 
   of these versions. 

   Solid Edge V18 will not install on machines without Internet Explorer 6.0 or higher.  
   Internet Explorer is not required to be the default browser.

  Solid Edge is not supported on Intel Itanium processors. 

   Solid Edge V18 has been certified to run on 64-bit Windows XP as a 32-bit application.  
   Below are the known issues running on this operating system:
   - No thumbnail previews display for Solid Edge documents in Windows Explorer 
   - The "Status" and "Project" tabs are not displayed on the File Properties dialog
     if activated from Windows Explorer.
   - The Windows Add Network Place command is not supported on 64-bit Windows XP yet.  A 
     short-term work-around is available through Windows 2003, Service Pack 1.  If you 
     enter the full URL to save a Word document to an Insight document library, the
     Network Place is added.  We are actively working with Microsoft for a better solution.
   - Solid Edge Web Parts do not display if running the 64-bit version of Internet Explorer.  
     The user is prompted to Install the .NET framework.  The workaround is to use the 
     32-bit Internet Explorer.
   - Windows XP 64-bit machines using dongles will require a 64-bit Sentinel driver.  
     This 64-bit Sentinel driver has not been released yet.  Once it is released, 
     it will be posted to the Solid Edge GTAC download site.  Windows XP 64-bit support 
     for the parallel SPRO dongle is scheduled to be available in Q1 2006.

   Solid Edge stops certifying new releases against an operating system shortly after
   Microsoft drops mainstream support for it.  Solid Edge V18 will continue to 
   support and install on Windows 2000.  Solid Edge Version 19 will not be certified on 
   Windows 2000 and as such will not install on that operating system.  

   It is not recommended that you run Solid Edge on server operating systems.

   Windows ME, Windows 98, and Windows NT 4.0 are unsupported operating systems. 
   Solid Edge will not install on these operating systems.

 · HARDWARE SYSTEM REQUIREMENTS

   Recommended System Configuration:
   - Intel Xeon or AMD Opteron processor
   - Windows XP Professional Service Pack 2
   - 1 GB or more RAM
   - True Color (32-bit) or 16 million colors (24-bit)  
   - Screen resolution of 1280x1024

   Minimum System Configuration:
   - Intel Pentium, Intel Xeon, AMD Athlon, or AMD Opteron
   - Windows 2000 or Windows XP Professional 
   - 512 MB RAM
   - Minimum Resolution: 1024x768, 65K colors
   - Disk space required for installation:  1.1 GB

   Solid Edge Version 18 is delivered via multiple CDs.  Beginning with Solid Edge 
   Version 19, we will deliver the product on a single DVD instead.  For more details
   on this corporate-wide direction, please refer to http://support.ugs.com/DVD/.

 · DISPLAY SYSTEM REQUIREMENTS AND INFORMATION

   Solid Edge will run on any graphics driver that supports
   Windows 2000 or Windows XP. Contact your graphics driver manufacturer to 
   determine whether their graphics adapter/driver supports these operating systems.

   For optimal performance, it is recommended to use a professional graphics card 
   that is designed for CAD applications. For information about cards used in testing
   Solid Edge and results, refer to http://www.solidedge.com/graphics/default.htm.

   Note that running with extremely high screen resolution and
   color depth increases the memory requirements on the system 
   and may result in apparent performance degradation. If 
   experienced, reconfigure the display system to the recommended 
   resolution and color depth for improved performance.

 · SYSTEM RESOURCE REQUIREMENTS AND INFORMATION

   Solid Edge has been enhanced to access the extended address space that is 
   available on Windows XP Professional. Each process running has 4 GB of 
   addressable memory available, regardless of the amount of physical RAM. 
   Normally, the operating system reserves 2 GB of space, and leaves 2 GB for 
   applications. Running Windows XP Professional with the /3GB switch added to 
   the BOOT.INI file, only reserves 1 GB for the operating system, and leaves 
   3 GB for applications.  This allows you to create draft files of larger 
   assemblies without running out of addressable space. Note: there were some 
   XP SP1 problems on some machines trying to boot using these /3GB switch. 
   Microsoft has resolved these issues in XP SP2.

   Page file size should be the maximum size possible. In general, the page file 
   size should be at least twice the amount of memory in the machine, plus the 
   size of files you will use.

   To better manage the system memory resources while running
   Solid Edge, it is important to turn off the option to  
   "Show window contents while dragging". This prevents unnecessary
   allocation/deallocation of memory for displaying the window contents 
   while dragging a window. To change this option, go to Control Panel -> 
   Display.  On Windows 2000, select the Effects tab. On Windows XP, select 
   the Appearance tab and the Effects button.
  
 · TEMP FILE SPACE
   Solid Edge uses temp file space for saving files and for storing 
   memory mapped display files. Using temp file space when saving files
   helps significantly reduce the size of the resulting file on the
   destination file system.  Temporary files are mostly created in the
   c:\temp directory. 

   Users should ensure they have twice the size of the largest file being saved 
   available as free temp file space prior to saving their files.  Note, 2x the
   file size for an assembly should include the size of the assembly, plus the 
   size of the subassemblies that are being used, plus the size of the part files.
 
   Running SE will create files with .000, .001, etc. extensions. These are
   memory mapped files that are used in the display pathway. When an assembly or 
   part file is opened, memory mapped files are created in the temp directory 
   during display of the assembly/part. These files are cleaned up by Solid Edge when 
   the process exits. If the user is running short on temp space, they can 
   optionally set an environment variable called JRENDER_TEMP and point it to 
   any folder with sufficient space. If this variable is defined, Solid Edge 
   will create memory mapped files in that folder.

   Running SE will create a file named DCCACHE.CAC in the C:\TEMP folder.  
   This file is a cache of the file icons displayed on the FILE OPEN/FILE SAVE/
   BROWSE dialogs.

   When a Solid Edge file is opened, but Solid Edge cannot gain exclusive write access
   to that file, a message box is displayed stating, "The requested file is currently
   write locked, open as read-only". If the user selects the copy button on this
   message dialog, the file will be copied to the temp folder using the naming 
   convention tmp<filename>.par, tmp<filename>.psm, tmp<filename>.asm, 
   tmp<filename>.dft.

   It is good practice to periodically check the files in the temp folder when
   not running Solid Edge and delete any that might remain from an abnormal
   termination of Solid Edge.

 · HARD DRIVE CONFIGURATION INFORMATION
   Machines delivered with the C: partition set to a 4GB FAT file system are
   problematic in this configuration. It is recommended that the C: partition
   in this case be changed to a 2GB (2047MB) FAT. This is consistent with the 
   maximum allowable FAT file system size. Failing to do this may cause random 
   errors and may also prevent Solid Edge or other applications from working 
   correctly and in some cases working at all.

------------------------------------------
End of System Requirements and Information
------------------------------------------
---------------------------------------
What's New in Version 18.0 of Solid Edge
---------------------------------------
Version 18 demonstrates the ever increasing value of the 
Solid Edge product. Many new features have been added to this 
release, all of which continue the focus on implementing 
state-of-the-art technology with outstanding usability.  

For a complete list of V18 enhancements, start Solid Edge and choose
"What's New" from the Help menu or choose the "What's New"
topic under the "Solid Edge V18 Release Notes" available on the
Support Web Page: 

      http://support.ugs.com/docs/solid-edge.html

----------------------------------------------
End of What's New in Version 18.0 of Solid Edge
----------------------------------------------

----------------------
Installing Solid Edge 
----------------------

  ·Insert the Solid Edge CD.  Autorun should start automatically.
   Click the "Solid Edge" button.  The InstallShield Wizard will guide 
   you through the installation.  

   If Autorun does not start, you can double-click Autorun.exe located 
   on the Solid Edge CD or you can double-click setup.exe located in 
   the Solid Edge folder.

   If your company is running a floating license, refer to the Solid Edge\Sesetup.pdf file 
   on the Solid Edge CD.  Follow the instructions outlined in the "Configuring
   Floating Licensing” section.

   The Solid Edge License Utility is not automatically started following installation.  
   The License Utility will display the first time Solid Edge is run, if the 
   SElicense.dat file is the one delivered by default. If the SElicense.dat file 
   is different in any way, the standard license checking will occur.  The License 
   Utility is available on the Solid Edge Start menu.

 · SOLID EDGE INSIGHT SERVER/CLIENT VERSIONS
   It is strongly recommended that the installed Solid Edge version and Insight 
   Server version be equivalent. That is, if you install Solid Edge version 18
   on your client machines, then you should install Insight Server version 18
   on your server.  Any other combinations have not been tested and will not be 
   supported. 

 · INSTALLATION NOTES

   Starting with Version 15, the .net framework is required for certain Solid Edge
   components.  The Solid Edge setup.exe automatically installs the .net framework
   if it does not exist on the machine.  The msiexec utility, commonly used for
   silent install, will not install .net.   

   Solid Edge V18 builds on the Windows Installer technology. During 
   installation Solid Edge will detect whether the necessary version of
   Windows Installer is installed and inform you if an older version was detected.
   If you receive this message, accept it and continue with your installation.

   Solid Edge V18 enables users to optionally install add-in products by choice. 
   These are selectable through the custom installation option during install or through
   the Control Panel's Add/Remove Programs, Modify option.  

   When installing Solid Edge, if a message displays regarding insufficient
   disk space, it is a good practice to exit the installation, free up the 
   recommended disk space + 25mb (required for the Windows Installer operations
   during setup) then restart the installation.

   Licensing on Demand - With floating license installations, Solid Edge checks 
   out licenses on demand - meaning that the first user to request a license for a 
   module (e.g. Solid Edge XpresRoute) checks out the license and has it 
   checked out for the duration of their Solid Edge session. 

   Solid Edge will ALWAYS install some files on the drive 
   where your operating system is loaded, regardless of the 
   <drive>:\Directory you specify for your product installation. 
   These files are loaded to:
         <o/s drive>:\Program Files\Common Files\Solid Edge
   Do not delete these files or your installation of Solid Edge 
   will fail to operate.

 · INSTALLATION REQUIREMENTS
   
   Solid Edge files are NOT backward compatible between primary released versions. 
   For example, a file created in Solid Edge Version 18.0 will NOT open in earlier 
   versions of Solid Edge. Solid Edge files ARE upward compatible. Files created 
   in Solid Edge versions prior to 18.0 will open in Solid Edge Version 18.0.

   You should reboot your machine following installation of Solid Edge
   prior to running it to ensure optimal performance. The first login performed after 
   the reboot should be completed by the administrator account to ensure that the 
   install is complete.

   You cannot install Solid Edge Version 18.0 and stand-alone Insight Connect on the 
   same machine. All the capability of Solid Edge Insight Connect is included in Solid 
   Edge Version 18.0, so it is not necessary to download it on a machine, which has 
   Solid Edge installed on it.

   Solid Edge will detect whether you have an existing version of Solid Edge loaded 
   and prompt you appropriately prior to installing this version. Two versions of Solid 
   Edge cannot be installed via Windows Installer on the same machine. Please refer to the 
   section "Uninstalling Solid Edge" in this README file for information on proper 
   uninstallation techniques.

   You must load and remove Solid Edge from an account that has Administrator privileges. 
   Solid Edge will run under User, Administrator, or Guest privileges.

   If rebuilding a system with existing multiple partitions to WinXP on the C:\drive, 
   WinXP does not assign user or group privileges to the existing partitions, resulting 
   in errors stating insufficient privileges to load SE when trying to install SE to a 
   partition other than C:\. The machine administrator should manually add sufficient
   user/group privileges to these drives then the installation will succeed.

 · SILENT (or Remote) INSTALLS

   The following is a complete commandline argument set for silently installing 
   Solid Edge. Setup no longer supports the use of the ADDLOCAL property. 
   All arguments should be encased in double quotes if there are spaces in the paths.

   C:\>msiexec /i "D:\CM_SETUP\DISK1\Solid Edge V18.msi" MYTEMPLATE=2 USERFILESPECXML="K:\temp\My Docs\Options.xml" USERFILESPEC="K:\temp\My Docs\selicense.dat" KERNELTYPE="P4" INSTALLDIR="C:\Program Files\Silent Solid Edge\" /qn+ /l*v k:\temp\mysilentsetup.log

   The string “D:\CM_SETUP\DISK1\Solid Edge V18.msi" represents the fully qualified 
   path to the Solid Edge MSI file.

   The MSI Property MYTEMPLATE indicates which type template files are to be installed. 
   The integer 1 is for Metric and the integer 2 is for English. Ignoring this property 
   defaults the installation to Metric template files.

   The MSI Property USERFILESPECXML allows the user to optionally provide the optional 
   installation of an SE Admin file. The user should supply a fully qualified path and 
   filename. This file will be copied to the Solid Edge Program folder and processed at 
   the end of the setup.

   The MSI Property USERFILESPEC allows the user to optionally provide a license file 
   that setup will copy to the Solid Edge Program folder at the end of the setup.

   The MSI Property KERNELTYPE is used to install either the P3 or P4 Parasolid Kernel.

   The MSI Property INSTALLDIR is used to specify the installation folder for Solid Edge.

   The argument “/qn+” instructs the Windows installer to provide NO user interface 
   and alert the user at the completion of the setup with a dialog box. Refer to the 
   Windows help system for further information about Windows Installer arguments. 
   Leaving this argument off the command line will display the setup user interface  
   with selections made and fields provided.

   The argument “/l*v” tells the Windows installer to create a log file of important 
   messages, warnings and errors and write it to the location provided, in this example, 
   k:\temp\mysilentsetup.log.

   The V18 setups use a new Installshield scripting engine found at the root of Solid Edge 
   called ISScript1050.msi. The setup.exe provided will automatically bootstrap this 
   scripting engine onto your system the first time it is run. Once this is accomplished, 
   silent or scripted installs using the msiexec.exe Windows Installer engine will 
   function as expected. If you continue to have silent install errors, please add 
   the following argument to your command line and review the resulting log file.   
   Please add    /L*v   “%TEMP%\install.log”

----------------------------
End of Installing Solid Edge
----------------------------
------------------
Running Solid Edge 
------------------

 · Select Start => Programs => Solid Edge V18 => Solid Edge

   -OR- 

 · The following synatax can be used to start Solid Edge from the command 
   line or short-cut: 
   "c:\program files\solid edge v18\program\edge.exe" /environment
   where environment is either part, assembly, sheetmetal, weldment, or draft.

   For example:  "c:\program files\solid edge v18\program\edge.exe" /part

   You would need to edit the syntax to reflect the location of the edge.exe 
   on your machine. 
   
-------------------------
End of Running Solid Edge
-------------------------

----------------------------------------
Solid Edge V18 Miscellaneous Information 
----------------------------------------
· NX version 4.0 is scheduled to release after Solid Edge version 18.  Solid Edge V18 
  Service Pack 1 or higher will be required for Solid Edge V18 to open NX 4.0 files.

· Solid Edge Insight users are strongly encouraged to review the Insight 
   Implementation Guide delivered with Solid Edge.
   (Program Files\Solid Edge V18\Program\ResDLLs\0009\sespimpgde.chm).
   This guide contains a wealth of information on installing and
   configuring SharePoint and Insight Server. Additionally it
   provides information that will aid in a successful experience in importing legacy 
   documents and creating new documents in the managed workspace. This document contains
   helpful hints, tips and techniques and is posted to the Solid Edge support web site: 

        http://support.ugs.com/docs/solid-edge.html


· Solid Edge Version 18 will be the last release to provide the Insight SPDataMigration.exe  
  data migration tool.  Any SharePoint V1 data should be migrated to SharePoint V2 
  before moving to Solid Edge Version 19. 

· Start Up Screen and Apprentice Mode
  The Solid Edge start up screen provides user assistance, such as tutorials and 
  Tip of the Day.  It also provides access to basic operations, such as creating 
  and opening files.

  You can select Apprentice Mode, in which text is displayed on toolbar buttons, 
  Command Assistant is enabled, and enhanced tool tip text is enabled.  Also, 
  when Apprentice Mode is enabled, the Activate All Parts option under Apply 
  Activation Override of Parts is set when you open assembly files.  You can clear
  Apprentice Mode to go back to the non-apprentice behavior.
 
  The Solid Edge start up screen includes a link to Solid Edge support.  You can click 
  Add or Remove Links to edit the Links list.

· Here are the changes made to the V18 template files. 

  Draft:
  - Open save method
  - Set new option in Tools/Options/Edge Display
     "Derive reference display from assembly" to "On"

  Part, Sheet Metal:
  - Open save method
  - Change Specific Heat units to: J/kg C for Metric templates. 
  - Change Datum terminator to Anchor for ANSI(in) and ANSI(mm) dimension
    styles.
  - Change dimension style font to be Arial.
  - Change Construction Style Edge color RGB to 0,0,1 (Blue)
  - Added Linear Distance UOM (lbm/ft, kg/m)
  - Change view display default style 
      Light Locations and RGB values
      Gradiant, Drop Shadows

  Weldment
  - Open save method
  - Change Specific Heat units to: J/kg C for Metric templates.
  - Change Datum terminator to Anchor for ANSI(in) and ANSI(mm) dimension
    styles 
  - Change dimension style font to be Arial.
  - Change Construction Style Edge color RGB to 0,0,1 (Blue)
  - Added Linear Distance UOM (lbm/ft, kg/m)
  - Add Weld Bead Style
  - Change view display default style 
      Light Locations and RGB values
      Gradiant, Drop Shadows
  - Color Manager: 
      Added weld bead style
      Set Construction Style to Weld Bead Style

  Assembly:
  - Open save method
  - Added Weldment.asm, WeldmentEng.asm and WeldmentMet.asm templates.
    These templates are set as assembly weldments.
  - Change Specific Heat units to: J/kg C for Metric templates.
  - Change Datum terminator to Anchor for ANSI(in) and ANSI(mm) dimension
    styles 
  - Change Construction Style Edge color RGB to 0,0,1 (Blue)
  - Change dimension style font to be Arial.
  - Added Linear Distance UOM (lbm/ft, kg/m)
  - Added Weld Bead Face Style
  - Added Thread Face Style
  - Change view display default style 
      Light Locations and RGB values
      Gradiant, Drop Shadows
  - Assy Color Manager
      Set Bead Style
      Set Construction Style
      Set Thread Style

 · V18 offers options on using graphics cards to accelerate SE display, software 
   acceleration, or a combination of the two (backingstore). If you experience display 
   problems, you can determine whether this is a Solid Edge or graphics card driver 
   problem by setting the display to software driven. If the problem no longer occurs, 
   check to be sure the latest available driver for the graphics card is installed 
   on the system and if so, report the problem to the card manufacturer. 

   An Automatic Selection option on the View tab of the Options dialog box allows 
   Solid Edge to automatically set the appropriate display settings based on the 
   installed graphics card. 

 · Tooltips on Windows XP are repeatedly affected by Microsoft Updates.  If you experience
   tooltip problems while running Solid Edge on Windows XP, please refer to the Microsoft web 
   site http://support.microsoft.com/?kbid=814135.

 · Pipes, pipe fittings, frames, and fastener systems will not explode using the Automatic 
   Explode command.  These items should be exploded manually, using the Explode 
   command instead.

 · Certain Microsoft security patches released as hot fixes in 2003 result in the 
   inability of HTML Help topics to display URL links.  If you have installed any of 
   these hot fixes, the Related Topics and How To help links may not be correctly 
   displayed in Solid Edge Help.  Microsoft has corrected this limitation in their 
   most recent service packs, and you can download the fixes from Microsoft web sites, 
   as described in http://support.microsoft.com/?kbid=811630.

 · The holes.txt file delivered to the Solid Edge Program folder was updated in 
   Version 16 to better support the new Fastener command in the Assembly environment. 
   Because of this change, a small number of hole features that were created in 
   Version 6 or before and never recomputed may experience feature failures when 
   recomputed in Version 16 or higher. To provide a mechanism to correct these failures, 
   the previous version of holes.txt is being delivered as holes_old.txt to the 
   same folder. You can correct the failures by doing the following:
   - Save a copy of the new holes.txt to a safe location
   - Rename holes_old.txt to holes.txt then recompute and save the affected files.
   - Drop the holes.txt you saved to a safe location into the Solid Edge Program folder.

 · Solid Edge Standard Parts
   The Standard Parts functionality in Solid Edge requires the "Microsoft Data 
   Access Components (MDAC)" in support of the Standard Parts database.  Standard Parts 
   requires MDAC 2.7 or higher.  MDAC can be downloaded from Microsoft from the following 
   site:  http://www.microsoft.com/downloads/.  Expand the "Most Popular Downloads" list 
   and follow the MDAC 2.8 link in the list.
   
   IMPORTANT NOTE: The above and higher versions of the Microsoft Data Access Components 
   (MDAC) are not supported on SQL Server 7.0 or 6.5 clustered installations. Please do 
   NOT install any of these releases of MDAC on such servers; doing so will break your cluster. 

 · Updating Standard Parts Database
   In support of some V18 new functionality, the format for the standard parts 
   database changed. You must replace your V17 standard parts database with a 
   new V18 database to include the V18 Machinery Design 
   parts stored in the 3D-Standard_Parts_V7.0 folder. 
   Follow these steps to update your database:
   - Run Configuration Wizard to specify the location of the existing database.
     Note: Before running Configuration Wizard, you should rename the V17 database 
     or change the default name of the V16 database specified in the Configuration Wizard.
   - Load the V18 Machinery Design parts by identifying the top level standard parts 
     folder name during Configuration Wizard setup.
   - Run Solid Edge Administrator and use the Add Parts command on the 3D-Standard_Parts_V7.0 
     folder. By adding the parts through setup, the V17 standard parts will not be over-written 
     by the V18 standard parts. 
    The V18 standard parts will be written to a different folder.
    If you added custom parts to your V17 standard parts database, you will need to add 
    these parts again to your V18 database. Depending on the age of the custom parts, 
    you may be required to edit the part in PartEditor during the process.


 · Standard Parts Folder Properties
   Make sure that the Inherit Parent Permissions option is not set for the Standard 
   Parts top-level folder. To update your standard parts folder, do the following:
   - Right click on the top folder (Solid Edge Standard Parts)
   - Click Properties on the short-cut menu
   - Select the Security tab on the folder Properties dialog box
   - Click the Advanced button at the bottom of this dialog
   - On the Advanced Security Settings dialog, clear (un-check) the “Inherit from parent 
     the permission entries that apply to child objects. Include these entries explicitly 
     defined here.”  
   - On the Advanced Security Setting dialog, set the permissions as you need and then 
     click the “Replace permission entries on all child objects with entries shown here 
     that apply to child objects.” option and click OK. Another Security dialog will display 
     while the folder permissions are updated.  Allow this to complete.
   - Click OK on the folder Properties dialog.

 · In V15 you gained the functionality to display sketches, constructions, reference 
   planes, and tube centerlines in drawing views with the Parts List Options button 
   on the Drawing View Properties dialog box.  You should update the drawing views 
   in pre-V15 files to use this functionality.

 · Microstation to Solid Edge Data Translator
   Microstation .dgn is no longer a widely accepted format for mechanical drawings. 
   As a result, the Microstation translation capability is being moved to an 
   “Extended Support” status. This means that we will continue to deliver this 
   capability and will still provide support to customers who have an active 
   maintenance contract. However, we will no longer make fixes or enhance the 
   Microstation translation functionality. We strongly recommend that your organization 
   begin planning now for alternative translation means, such as DXF and DWG drawing 
   translators.

 · Broken Out Section View
   Problems can occur when the Broken Out Section View profile is constrained 
   to geometry that is modified or removed by the Broken Out Section View itself.
   This only occurs when the Broken Out Section View profile is applied to the 
   same drawing view on which it is defined.  In most cases, constraints will 
   simply be deleted automatically, however, rare conditions have occured where 
   the profile actually moves after the Broken Out Section View is updated.

 · Ideas Data Migration

   The following recommendations are for the Ideas Data Migration command:
   - Windows 2000 Server running SP3 or Windows XP running SP1
   - Ideas versions 10M2 running PTF 1 or higher -OR- Ideas 11M2 or higher
   - Disable the Ideas Auto Save Reminder during the data migration.
   - Run the Ideas Data Migration command when no other users are accessing 
     the Ideas server. 
   - Do not run the Ideas Data Migration command and Solid Edge simultaneously.

 · Solid Edge Templates
   If you intend to use the template files supplied with Solid Edge V18, it is a 
   good idea to open them and customize them further for your company's specific 
   needs.  Modifying the templates supplied with Solid Edge is the best way to keep 
   up to date with template files and new capabilities and settings in Solid Edge.

   If you intend to use your existing template files with Solid Edge V18, please follow 
   these recommendations:
   1) Open your existing template files in Solid Edge V18 and save and close them.  The act 
      of opening and saving brings all information stored in the template up to date and
      will save time when creating new draft files from these template files.
   2) After saving the template files, open them a second time and inspect all data in the 
      templates for accuracy.

   Other template recommendations:
   - If you put symbols on the background sheet of draft files, we recommend you 
     not use the "linked" option.  We recommend the use of "insert as geometry" 
     for symbols in template files.  Linked or embedded files may offer advantages 
     in some situations, but our findings have been that workflow and process problems 
     associated with keeping up with linked files, modifying files linked to 
     released drawings, and similar issues make the use of linked files to background 
     sheets less than desirable.
   - You should avoid the use of drawing views of parts or assemblies on background sheets.
   - It is good practice to put property text callouts on the background sheet for sheet
     file name, author, linked file name, etc.  The use of property text in background 
     sheets of template files can save considerable work in many workflows.

   Warning: If your draft file templates have linked or embedded Autocad  
   files on the background sheet using the Viewdata tool supplied with early versions of 
   Solid Edge, you are working in an inefficient and non-recommended manner.  Direct 
   embedding of Autocad files using Viewdata was disabled in V9, although 
   display of existing files with these embeddings is still provided. 
 
   If you have templates with embedded or linked Autocad files 
   follow these steps:
   1) Locate the original Autocad  file used in the link or embed.
   2) Open your draft template file and view the background sheet
   3) Delete the linked or embedded Autocad object on the background sheet.
   4) Open the Autocad file you want to use as on the background sheet in Solid Edge Draft, 
      thus using the translator to bring the data into Solid Edge native format. 
   5) Copy the translated data and paste it in your template file on the background sheet.
   6) Save your template in Solid Edge V18.

 · Revision Manager should not be used to edit the links of files that will continue to be 
   opened by an earlier version of Solid Edge, or the out-of-date status indicator of Draft 
   drawing views may be incorrect.

 · Weldments
   Display control of weldment components in cutaway views - if any of the components 
   of weldment in an assembly are set to shown, then the entire weldment will be shown. 
   If all of the components of the weldment are hidden, then the weldment will be hidden. 
 
 · WINDOWS 2000 limitation for guest accounts: 
   When using a Guest (non-admin) login in Windows 2000 the data path 
   "Documents & Settings\Guest\My Documents" is treated by Windows 2000
   as a temporary storage area.  SE uses this as a default location when 
   creating a Tube or Wire and Create In Place.  This area and the files in it    
   are lost when you log out of Guest.  This problem does not exist when
   logging in with administrative privileges.

 · ADD-INS
   Web Publisher
   Immersive Design provides Web Publisher as an add-in module for SE. When a 
   user views a web published file, the latest viewer is automatically obtained
   from the Immersive Design website if it doesn't already exist on the local 
   machine. Therefore, it is important that the user has internet access when 
   viewing web published files.  

   Simply Motion
   Users can affect display performance in Simply Motion through the 
   reflection display option. Setting this to ON can result in 
   slower performance in rotation than with it set to OFF.
   
   Weldments are not supported in Simply Motion.

·  Solid Edge writes debug information in the unlikely 
   event of an abort. This debug information is written to a file 
   named crashlogf.txt in your system temp folder. Debug data is 
   appended to this file. Users may be asked to provide this 
   file to Solid Edge customer support if reporting a problem that 
   this data could help determine root cause. Due to writing this 
   debug information, the user may experience a slight wait on abnormal 
   exit of Solid Edge. You have the option to automatically email crashlog 
   information to the Solid Edge development team for investigation. 

·  Some performance problems when installing or running Solid Edge have been
   observed as attributable to virus scanners running on the machine and
   scanning all files being installed or used. Solid Edge files are all
   scanned for viruses prior to delivery. If users experience performance
   degradations, consider modifying the select set for virus scanning operations.

 · Parasolid versions for Solid Edge
   Solid Edge and Unigraphics share embedded Parasolid files to communicate. 
   There may be problems if they are not running the same version of Parasolid. 
   For example, software running an earlier version of Parasolid cannot read files 
   created in software running a later version of Parasolid. The following 
   specifies the Parasolid versions for releases of Solid Edge.

   Solid Edge Version		Parasolid Version
 	6				10.0
	7				11.0
	8				11.1
	9				12.0
	10				13.0
	11				13.0
	12				14.0
	14				14.1
        15                              15.0
	16				16.0
	17				16.1
	18				17.0

 · If running English language Solid Edge on a non-English language 
   operating system, the delimiters in the Holes.txt or Pipethreads.txt file 
   must correspond to the delimiters set in the Control Panel. Contact 
   Solid Edge Customer Support for further information.

 · The file separator in the delivered DraftList.txt is set to a comma 
   and the delimiter is set to a period. These two items are not read from 
   the delimiter setting in the Control Panel.

 · If there is a question whether the most current version of the 
   Solid Edge fonts is loaded on the user's machine, simply delete 
   the Solid Edge fonts through the Control Panel then install them 
   from the Fonts directory on the Solid Edge CD into the Windows\Font 
   directory on the machine.
-----------------------------------------------
End of Solid Edge V18 Miscellaneous Information 
-----------------------------------------------
-----------------------
Uninstalling Solid Edge 
-----------------------
UNINSTALLING SOLID EDGE 
 · Click the ADD / REMOVE PROGRAMS on CONTROL PANEL.  A 
   list of products installed on your system will be presented.  
   Select the Solid Edge entry and click the REMOVE button to 
   begin the uninstall process.

 · Once you remove Solid Edge, be sure to reboot your
   system to ensure optimal operation from subsequent
   installations of Solid Edge. If you encounter any problems
   when uninstalling Solid Edge, refer to the "Uninstallation 
   Tips" section of this README file.
------------------------------
End of Uninstalling Solid Edge 
------------------------------

-------------------
Uninstallation Tips
-------------------
 · Always reboot your machine after uninstalling Solid Edge, 
   prior to initiating the installation of another version of
   the product.

UNINSTALLATION HALTS
 · Error Message: "An error occurred while trying to remove 
   Solid Edge Vx.x. Uninstallation has been canceled."

   Solution: The removese.exe file is part of the suite of 
   Solid Edge components removed from the system during an 
   uninstall. Because the file is in use by the operating 
   system during the uninstall, it is flagged for removal upon 
   restart of the system. You must not have restarted the system 
   after a previous uninstall and therefore when you installed 
   Solid Edge Version 18.0 and restarted your system, the file 
   was deleted by the system. You should copy this file from 
   your delivery media to the System32 or System folder
--------------------------
End of Uninstallation Tips
--------------------------

-------------
Documentation
-------------
 · If you would like to send comments about Solid Edge documentation, 
   email them to seedumedia@UGS.com.

 · Self-teaching Tutorials and Help are provided on-line with 
   the product.  

 · For online Product Release Notes visit:

        http://support.ugs.com/docs/solid-edge.html

 · For online technical tips (Maintenance Customers Only) visit: 

        http://uganswer.ugs.com

 · For additional information relating to Solid Edge visit: 

    http://www.solidedge.com

--------------------
End of Documentation
--------------------
--------
Training
--------
Instructor-led training for the Solid Edge product is optional. 
It is recommended that the on-line delivered Educational Media 
tools be used to become familiar with Solid Edge. A complete set 
of instructor-led training courses is offered for each module in 
the product. These courses are offered for users who wish to 
increase their productivity in the use of Solid Edge.

The Solid Edge courses available are:

TR01413         Solid Edge Fundamentals
TR01418         Solid Edge Surface Modeling
TR01415         Solid Edge Assembly
TR01419         Solid Edge Sheet Metal

Training information is also available on the Solid Edge Training 
Web Page:

    http://www.solidedge.com/training/default.htm.

To register for scheduled Solid Edge training, call Solid Edge 
Educational Services at (800) 955-0000 (option 4).

Customers outside the United States should contact their local
Solid Edge office or reseller.
---------------
End of Training
---------------

---------------------------
Solid Edge Technical Support
---------------------------
Visit the Global Technical Access Center web site to obtain additional
Product Support information:

    http://support.ugs.com/

You can obtain Warranty support for Solid Edge for a period of 
30 days after product purchase by calling 1-800-955-0000 in the 
US and Canada, or if outside the US and Canada, by calling your 
local Solid Edge Reseller Office.

Maintenance features:
 · Software Updates
 · Live first-call Technical Support
 · Toll-free line for opening Technical Support Calls
 · Electronic Call Logging via WWW browser
 · Electronic Call Tracking via WWW browser
 · Symptom Solution Database
 · Newsgroup Access

To sign-up for maintenance contact your Solid Edge reseller or 
Solid Edge salesperson.

There are two ways maintenance customers can report problems
or request enhancements:

1) Place a call to our live *first-call-technical-support*
toll-free phone number and make the appropriate menu selection. 
Your call will be forwarded directly to a technical Solid Edge
Support Engineer who will assist you with your problem. 
(Note - first-call-technical-support may not be available 
in all countries.)

Dial: 1-800-955-0000

After you hear the Global Technical Access Center welcome 
message, select the following menu options for Solid Edge: 

   Press (2) for Technical Software Support

   Enter your Sold To / Server ID followed by a # sign

   Press (2) for Solid Edge

   Press (1) for Solid Edge Application Issues
   or
   Press (2) for Solid Edge Insight Issues
   or 
   Press (3) for Solid Edge Installation & Licensing Issues
 
Your call will then be routed to the next available Solid Edge 
Support Engineer.

Once you reach a Support Engineer and relay all pertinent 
information, your call will be assigned an Incident Report (IR) 
number. This is the only number you will ever need to track and 
follow up on this particular call. Even if the IR results in a 
Problem Report (PR - software bug) or an Enhancement Request (ER), 
you will only need to keep track of the one number.


2) Support calls can be opened from your World Wide Web browser
by connecting to the Technical Support web page and selecting 
"IR - Incident Report Creation". Or connect directly to the 
online call logging system using the following URL:

    http://qtac.ugs.com/logir

Enter your WebKey login and password, enter your "Sold-To ID", 
select Submit, then fill out the information on the form, including 
"IR Problem Text", and select Submit.

Note: International calls opened using WEB IR will be deposited 
in the local Solid Edge Post-Sales database for follow up.

-----------------------
End of Technical Support
-----------------------

