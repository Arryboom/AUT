# AUT
# A Simple Tool use WINAPI to Add User On Windows  

**AUT-LITE-1.1**

|     Params      | Readme                                       |
| :----------: | ---------------------------------------- |
|   -h   | This help text  |
| -a | Add user |
| -d | Del user |
| -l | List a user's information |
| -f | Auto Add a user to Admin and RDP group that username is "POPYOU$",and password is "Rock@#!you$"    |
| -fd | Del user that add by -f |
| -ar | Add a user to Administrators and Remote Desktop Users Group |
| -ag | Add a user to a Specific Group,Can use RDP to replace "Remote Desktop Users"  |
| -aa | Add a user and add to Administrators Group at the same time |


**Example:**

- add user:  
aut -a jason pa33w0rd

- del user:  
aut -d jason

- add to a group:  
aut -ag administrators jason

- list user info:  
aut -l jason

- add user and set to administrators:  
aut -aa jason pa33w0rd


------------------------------------
**File Info:**
+ Size: 1626112 bytes  
+ File Version: 1.1.0.0  
+ MD5: F13234921CC60460D18343DCD6C973EF  
+ SHA1: ED266380C12EAA582F919417695F557C3907AA1D  
+ CRC32: 06D304C1  
