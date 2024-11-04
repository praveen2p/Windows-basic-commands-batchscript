#### NAME:PRAVEEN.K
#### REGNO:212223040152
# EX 08 -  Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab

![1](https://github.com/user-attachments/assets/d6b97f78-b80b-447b-8a08-bcd1606ff887)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![2](https://github.com/user-attachments/assets/0e5cb65c-bde8-4542-9dd0-574a3597ec63)
![3](https://github.com/user-attachments/assets/511a8332-541d-437b-8e43-21720a27eb53)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab

![4](https://github.com/user-attachments/assets/a0ff7965-f4a6-49fe-9098-ac491e663e56)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![5](https://github.com/user-attachments/assets/cbca65ec-4701-4084-aa0d-050f51485426)

![6](https://github.com/user-attachments/assets/d29b2879-c993-416c-9df7-10085a13600e)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![7](https://github.com/user-attachments/assets/444cac54-fa05-4546-80e5-cd4743fc15a7)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!





## OUTPUT

![Screenshot 2024-11-04 173620](https://github.com/user-attachments/assets/9ade0cb3-54ff-44c7-bd90-b490e6f5223b)




# RESULT:
The commands/batch files are executed successfully.

