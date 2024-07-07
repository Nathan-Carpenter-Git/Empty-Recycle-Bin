# Empty Recycle Bin

## Author
_Created by Nathan Carpenter_

## About
Empties recycle bin without having to confirm it.

## Prerequisites
- Supports only Windows operating systems.
- Windows system is remote signed, if it is not, the script will not run. See "How to remote sign Windows" below.

## How to remote sign Windows
1. Open PowerShell as administrator
2. Type in the following command: *Set-ExecutionPolicy RemoteSigned*
3. Now you should be able to run the script. 

*Warning:* **Will not prompt you to delete files, only use this if you are sure you want files in the recycle bin to be deleted.**
