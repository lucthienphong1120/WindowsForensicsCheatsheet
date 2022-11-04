# WindowsForensicsCheatsheet

## System info and accounts

OS Version:
```
SOFTWARE\Microsoft\Windows NT\CurrentVersion
```
Current Control set:
```
HKLM\SYSTEM\CurrentControlSet
SYSTEM\Select\Current
SYSTEM\Select\LastKnownGood
```
Computer Name:
```
SYSTEM\CurrentControlSet\Control\ComputerName\ComputerName
```
Time Zone Information:
```
SYSTEM\CurrentControlSet\Control\TimeZoneInformation
```
Network Interfaces and Past Networks:
```
SYSTEM\CurrentControlSet\Services\Tcpip\Parameters\Interfaces
```
Autostart Programs (Autoruns):
```
NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\Run
NTUSER.DAT\Software\Microsoft\Windows\CurrentVersion\RunOnce
SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce
SOFTWARE\Microsoft\Windows\CurrentVersion\policies\Explorer\Run
SOFTWARE\Microsoft\Windows\CurrentVersion\Run
```
SAM hive and user information:
```
SAM\Domains\Account\Users
```












