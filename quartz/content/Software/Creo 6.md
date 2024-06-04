Creo is the CAD modeling software of choice by engineers in the Engineering Mold Shop. This guide will walk you through installing Creo 6. Double check with Chris before installing this program, as it may no longer be in usage. In which case, please don't delete this file but instead dereference it from the steps listed in [[Setup_Main|The Software Setup Guide]].

Note that this tutorial was almost verbatim copied from [here.](file:///%5C%5Cprod%5Croot%5COther_Drives%5CCAD-Ilox%5CIntralox_Molds%5Cproe_stuff%5CCreo_Installation_Files%5CCreo_Installation_Instructions.docx)

### Installing and Setting Up Creo 6:

1. To begin with, go ahead and open [this](file:///%5C%5Cprod%5Croot%5COther_Drives%5CCAD-Ilox%5CIntralox_Molds%5Cproe_stuff%5CCreo_Installation_Files%5CCreo_6%5C6-0-4-0) folder. It should look something like this:

![[Setup-Folder.png]]

2. Right click on the "setup" application and *run it as an administrator.*

![[Software/Attachments/Creo 6/Run-as-admin.png]]

3. Make sure "Install new software" is selected and click next on the bottom right. Note that your UI color scheme may look different depending on whether you have dark mode enabled on Windows or not.

![[Installation-Start.png]]

4. Accept the software license agreement and check the box below it to proceed.

![[Accept-Agreements.png]]

5. **DO NOT ENTER THE LICENSE SOURCE IN THE ENTRY BOX**. This will freeze the installer for some reason and you'll have to restart the process. 
   Instead, in the bottom section under "License Summary", enter the license server source "7788@ilox_ptc_lic" and hit enter and wait until the status says "Available as shown"
   
![[Software/Attachments/Creo 6/License-Source.png]]

6. We have a custom installation path for Creo. It is "C:\creo". Make sure to change the installation path to this if it is not already. Setting it to the right installation path, **press Enter to save changes.** 

![[Installation-Path.png]]

7. Application Selection:
   There are a number of applications that we need to make sure are installed through this installation process. Make sure the following are selected/deselected

- Creo - **Selected**
		Creo Parametric - **Selected**
		Creo Simulate - **Deselect**
		Creo Layout - **Deselect**
- PTC MathCad - **Optional**
- Utilities - **Selected**

8. Now click on the "Customize ..." button. Within the pop-up window, select "PTC Creo Parametric in the left pane"

![[Software/Attachments/Creo 6/Application-Selection.png]]

9. Make sure you're on the "Application Features" tab on the top and go through and ensure the following are checked for each section
   
- Options:
	Creo ModelCHECK
	Mold Component Catalog
	Clearance and Creepage
	Creo Mold Analysis
	NC-GPOST
	Creo Photo-Realistic Rendering

- API Toolkits - Select all of the options under this tab. **This is the most important part of the install**
	Web.Link for Creo Parametric
	VB API for Creo Parametric
	Creo Parametric TOOLKIT
	Creo Object TOOLKIT C++
	Creo Object TOOLKIT Java and Jlink
	Creo UI Editor

10. Finally, click OK on the bottom right to save the changes and close the pop-up window.

11. Click on the "Install" button on the bottom right corner and give it some time to install.

![[Select-Install.png]]

12. Finally, click on "Finish" and you're done! All the Creo APIs that you'll be interacting with in this role should be properly installed.

![[Finish-Install.png]]