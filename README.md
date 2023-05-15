# Notes Desktop Application

## Goal
Create a note-taking application that allows users to create, edit, delete and save notes.
The GUI application includes menu bar, tool bar, window resizing, undo-redo, cut-copy-paste 
text, text styling and more. The console application launches the notes application.
The web service allows for remote data storage and communication with the GUI application 
through HTTP protocol.

## Quick-start
Must be running the service before you run the application.  
To run the service:  
[service-readme](service/readme.md)  
For application, go to releases and unzip file, go to the bin directory and run the executable.  

## Additional Functionality  
### Login  
Create password when first opening application.   
When opening application next, you will be asked to input the password saved.  

### Multiple Instances
If application is already opened, opening further instances will make those instances readonly.  
The new instances will not allow users to edit or create new notes or folders.  

### Light/Dark Mode
When toggling dark mode, the application will apply dark styling to the application.  
If you close the application, it will persist the light/dark style such that when opening up again the style will be what it was last set as.  

### Recently Deleted Folder
Note files that are deleted will be moved to the recently deleted folder.  
These files cannot be edited once they are in the recently deleted folder.  
Once the file is in recently deleted folder, you can move the file back to the folder.  
You can delete the individual files permanently or delete all the files at once with the empty button.  

### Error Checking
Cannot create or rename file or folder with empty name or just whitespaces.  
Cannot create or rename duplicate notes or folder names.  

Check Release Notes for further information on features implemented.  
