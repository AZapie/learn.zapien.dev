This install process will look very similar to the one for [[Creo 6]]. I also made this one myself since I couldn't find a tutorial to rehash on the network drives.

For the sake of easier functionality with [[ProPrint]], we'll be installing and setting up Creo 9.0.4. 

### Installing and Setting Up Creo 9
---
1. Navigate to [this](file:///%5C%5Cprod%5Croot%5COther_Drives%5CCAD-Ilox%5CIntralox_Molds%5Cproe_stuff%5CCreo_Installation_Files%5CCreo_9%5CMED-100WIN-CD-460_9-0-4-0_Win64) folder in the network drives.

![[Installation Folder.png]]

--- 
2. Right click on the "setup.exe" file and run it as an administrator.

	![[Software/Attachments/Creo 9/Run-as-Admin.png]]
---
3. If it pops up, fill out the IT security audit form to grant the installer administrator rights
	![[IT-Log.png]]

---
4. Make sure "Install new software" is selected and then click "Next" in the bottom right

![[Installer-main-page.png]]

---
5. Accept the software license agreement and check the box below it

![[Licensing-agreement.png]]

---
6. As a source for the license, add "7788@ilox_ptc_lic" and wait for the status to become "Available"

![[Software/Attachments/Creo 9/License-source.png]]

---
7. Now make sure you have the following applications selected to install:
   
- Creo
	- Creo Parametric
- Utilities
	- Creo 9 Platform Services
	- Microsoft .NET Framework 4.8 Setup

**NOTE:** Leave the installation path as "C:\\Program Files\\PTC". Things were installed under a different path for [[Creo 6]] but going forward, Creo versions should be installed to the "Program Files" folder as shown.

---
![[Software/Attachments/Creo 9/Application-Selection.png]]

---

8. Under the "Application Features" tab in, make sure the following are selected:

- Creo Parametric
- Extensions
	- Creo Simulation Live
	- Creo Simulate
	- Creo Render Studio
	- Creo Flow Analysis
	- Creo Mold Analysis
- Options
	- Creo Modelcheck
	- Mold Component Catalog
	- Clearance and Creepage
	- NC-GPOST
	- Creo Parametric Distributed Computing Extension
	- Direct Modeling Converter
- API Toolkits - ***all***
	- Web.Link for Creo Parametric
	- VB API for Creo Parametric
	- Creo Parametric TOOLKIT
	- Creo Object TOOLKIT C++
	- Legacy Toolkit Application Runtime
	- Creo Object TOOLKIT Java and Jlink
	- Creo UI Editor

---
![[Application-Features-One.png]]

---
![[Application-Features-Two.png]]

---
9. Now, click the "Install" button on the bottom right corner and let the program install

![[Installing-Apps.png]]

---
10. Once all applications are installed, click on "Finish" and you should now have Creo 9.0.4 properly installed.

![[Finished-Installing.png]]