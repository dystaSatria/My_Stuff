# GuideLines

* Surely if you use the latest version on Windows. For check it
  ```
  winver 
  ```
 on the window symbol

 * RUN POWERSHELL as administrator

```
 Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```

RESTART
```
 dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```
```
 dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```
RESTART
