# How to

1) start terminal as admin
2) run these commands:
```ps1
REG ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Search /v BingSearchEnabled /t REG_DWORD /d 0
```
```ps1
REG ADD HKCU\Software\Microsoft\Windows\CurrentVersion\Search /v CortanaConsent /t REG_DWORD /d 0
```
