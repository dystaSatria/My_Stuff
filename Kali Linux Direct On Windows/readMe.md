# GuideLines

* Surely if you use the latest version on Windows. For check it
  ```
  winver 
  ```
 on the window symbol. If there "Build" so here we go lets start it. If not don't worry just update to latest version

 * So lets go to the road
   
 * RUN POWERSHELL as administrator

* Copy this and just paste it
```
 Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```

* RESTART
* Repeat that way again (Copy and Paste)
```
 dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```
* Again and again (Copy and Paste)
```
 dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```
* RESTART again
* Download Linux Kernel: ``` https://aka.ms/wsl2kernel ```

