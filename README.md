Corrected install instructions
Download the intune.win file from my repository or create your own intune.win file based on the files in my repository. 

Open the MEM Portal
Navigate to Apps -> Windows
Click Add
Select Windows app (Win32) as App type

Click Select app package file
Click upload und select the .intunewin file
Click OK

Give the application a name and customize the app information.
Click Next

Enter install.bat and deinstall.bat as install/unistall command
Change the Device restart behavior to No specific action
Click Next

Select 32-bit and 64-bit as Operation system architecture
Select a minimum OS Version
Hints: If you want to specify further requirements, such as minimum free disk space, you can do this in this step.
It is also possible to specify a file, a registry value or a script as a requirement.


Select Manually configure detection rules as Rules format
Click Add
Select File as Rule type
Enter “C:\Windows\_Tools\” as file path and “IntuneSystemTrayV2” as folder.
The detection method is File or folder exists
Click Next

Skip the depentencies and supersedence step click next.
Click Next

Click Create
