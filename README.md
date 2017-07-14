This is a little script I create to automate the cloning of the packages in the "packages" folder. This is  a .bat script that steps through the folders and clones each one from the repository.

Please note:
 - This script is specific to the Unisa E-Content system.
 - There is one for Windows and one for Linux
 
 
Windows
-------
Simply copy the auto_package_clone_win.bat file into the "packages" folder, and either double click it, or run it from cmd by typing:
 
    auto_package_clone_win.bat
    
Linux
-------
Copy the auto_package_linux.sh file into the packages folder. From the terminal execute the following commands:

 1. chmod 755 auto_package_linux.sh
 2. ./auto_package_linux.sh
