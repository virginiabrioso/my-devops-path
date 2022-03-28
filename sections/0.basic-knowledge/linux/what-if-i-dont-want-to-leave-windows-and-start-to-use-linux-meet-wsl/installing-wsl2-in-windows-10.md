---
description: Tutorial time!
---

# Installing WSL2 in Windows 10

_****_

According to Microsoft you must be running Windows 10 version 2004 and higher (Build 19041 and higher) or Windows 11

1. Open Windows Prompt with administrator privileges and then run

```
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart 
```

Now reboot your PC and move to the next section.

2\. Download [WSL2 Linux kernel update package for x64 machines](https://wslstorestorage.blob.core.windows.net/wslblob/wsl\_update\_x64.msi). Run the application and follow the prompts to install it

3\. Set WSL2 as default

```
wsl --set-default-version 2
```

4\. Download your desired distro in Microsoft Store.
