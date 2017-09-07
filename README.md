## DESCRIPTION
This script will recursively enumerate and log a directory with all its associated subdirectories and files. 
You will be prompted for the target path. When the script completes, you will be prompted to open the log file and review the results.

PARAMETERS	: $TargetPath, $LogPath
INPUTS		: You will be prompted for the home directory share or local path path for the $TargetPath varialbe, as well as the log path for the $LogPath variable. 
OUTPUTS		: $Log
AUTHOR(S)	: Preston K. Parsard
EDITOR(S)	: 
REFERENCES	: 
1. https://technet.microsoft.com/en-us/magazine/2008.02.powershell.aspx

KEYWORDS	: Directory, files, folders

EXAMPLE 1
Get-AclsRecursivelyForDirectory.ps1

REQUIREMENTS:

1. PowerShell Version 4.0 or later
2. Run as administrator
3. Windows OS (Windows 7/Windows Server 2008 R2 or greater)

**FEEDBACK**
Feel free to ask questions, provide feedback, contribute, file issues, etc. so we can make this even better!