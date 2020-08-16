# win10script
This is a Script to setup Windows

## Run
Open the Powershell and run the following Command:
```
powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JJ8R4')"
```

## My Additions
- Dark Mode
- One Command to launch and run
- Chocolatey Install
- O&O Shutup10 CFG and Run
- Added Install Programs
- Added Debloat Microsoft Store Apps

## Added Software
- 7zip
- Adobe Acrobat Reader
- Firefox
- Git
- Notepad++
- Powertoys
- Thunderbird
- VLC

## Modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
- Uninstalling OneDrive (This is on in my script)
- Installing Adobe, Chocolatey, Notepad++, MPC-HC, and 7-Zip

Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
