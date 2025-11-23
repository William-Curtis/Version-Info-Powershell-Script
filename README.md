# Version Info Powershell Script

[Setup]
* Copy VersionInfo.ps1 into C:\temp
* Open VersionInfo.ps1 Properties and unblock it
* Open VersionInfo.ps1 in notepad or any other text editor
* Set $filePath to the File Path of a .txt file with a list of computers names (Copy as Path)
* Set $applicationFilePath to the path from "c$\" of the application you want to get the version of (Copy as Path) (Make sure to remove everything before and including "c$\" or "C:\")
* Set $outputFile to the File Path of where you want the output log (Copy as Path) (Script will create the file if it doesn't exist)
* Save VersionInfo.ps1

[Run the Script]
* Run Powershell as Admin
* Enter: Set-ExecutionPolicy RemoteSigned
* When prompted, enter "A" for Yes to All
* Enter: cd C:\temp
* Enter: .\VersionInfo.ps1
* Once you see "VersionInfo Script Completed" in Powershell, the script is finished and the data will be in the output log
