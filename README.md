<img align="left" alt="system-information" height="58" src="https://img.icons8.com/fluency/48/system-information.png" width="58"/><h2>Requirements</h2>
<center><table>
<thead>
<tr>
<th></th>
<th><img src="https://upload.wikimedia.org/wikipedia/commons/e/e6/Windows_11_logo.svg" style="width: 200px;"/></th>
<th><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Windows_10_Logo.svg" style="width: 200px;"/></th>
</tr>
</thead>
<tbody>
<tr>
<td rowspan="2"><img height="60" src="https://img.icons8.com/fluency/96/null/windows-update--v1.png" style="float: left;" width="60"/><h4>Windows Build Number<h4></h4></h4></td>
<td>Windows™ 11: Build 22000.526 or higher.</td>
<td>Windows™ 10: 22H2 10.0.19045.2311 or higher. <br/><br/><b><i>May work on Windows™ 10: 20H1 10.0.19041.264 or higher.<b></b></i><sup>1</sup><br/><br/><sub><sup>1. You may need to install <a href="https://www.catalog.update.microsoft.com/Search.aspx?q=KB5014032" rel="noopener noreferrer" target="_blank">KB5014032</a> then install <a href="https://www.catalog.update.microsoft.com/Search.aspx?q=KB5022834" rel="noopener noreferrer" target="_blank">KB5022834</a> to use WSA on these older Windows 10 builds<b><br/><br/><b></b></b></sup></sub></b></td>
</tr>
<tr>
<td colspan="2"><h5><b><i>Custom/modfied Windows OS installations (such as ReviOS, Tiny 10/11 and Ghost Spectre etc.) may have issues with running WSA.<br/></i></b></h5></td>
</tr>
<tr>
<td><img height="60" src="https://img.icons8.com/external-smashingstocks-flat-smashing-stocks/66/null/external-RAM-technology-and-devices-smashingstocks-flat-smashing-stocks.png" style="float: left;" width="60"/><h4>RAM<h4></h4></h4></td>
<td colspan="2"><ul><li>4 to 6 GB (Not Recommended)</li><li>8 GB (Minimum)</li><li>16 GB (Recommended)</li></ul></td>
</tr>
<tr>
<td rowspan="2"><img height="60" src="https://img.icons8.com/3d-fluency/94/null/electronics.png" style="float: left;" width="60"/><h4>Processor<h4></h4></h4></td>
<td colspan="2"><b><i>CPU Architecture: x86_64 or arm64<b><i></i></b></i></b></td>
</tr>
<tr>
<td>Your PC should meet the basic Windows™ 11 requirements i.e Core i3 8th Gen, Ryzen 3000, Snapdragon 8c, or above</td>
<td>N/A <br/><br/> This is a bit of a hit or miss, but it is highly recommended that your processor is listed in the <a href="https://learn.microsoft.com/en-gb/windows-hardware/design/minimum/windows-processor-requirements" rel="noopener noreferrer" target="_blank">supported CPU lists for Windows 11 requirements</a></td>
</tr>
<tr>
<td><img height="60" src="https://img.icons8.com/3d-fluency/94/null/video-card.png" style="float: left;" width="60"/><h4>GPU<h4></h4></h4></td>
<td colspan="2">Any compatible Intel, AMD or Nvidia GPU. <br/> GPU Performance may vary depending on its compatibility with Windows Subsystem For Android™  <br/><h4>Users with Intel HD Graphics 530 and older</h4><h5> WSA may not start or graphical glitches will occur when Intel HD Graphics 530 and Older iGPUs are used. This is a known issue, but unfortunately there are no fixes that I currently know of, plus, these GPUs are too old and do not meet Windows 11 requirements and hence are not official supported. <a href="https://github.com/MustardChef/WSABuilds/blob/master/Documentation/Usage%20Guides/General%20Usage%20Guides/ChangingGPU.md" rel="noopener noreferrer" target="_blank">Follow this guide</a> to switch to another iGPU/dGPU/eGPU that you may have or Microsoft Basic Renderer</h5><h4>Users with Nvidia GPUs</h4><h5> Nvidia GPUs are known to cause problems. If Windows Subsystem For Android™ does not start or there are graphical glitches when an Nvidia GPU is used, <a href="https://github.com/MustardChef/WSABuilds/blob/master/Documentation/Usage%20Guides/General%20Usage%20Guides/ChangingGPU.md" rel="noopener noreferrer" target="_blank">follow this guide</a> to switch to another iGPU/dGPU/eGPU  that you may have or Microsoft Basic Renderer</h5></details></td>
</tr>
<tr>
<td rowspan="2"><img height="60" src="https://img.icons8.com/3d-fluency/94/null/ssd.png" style="float: left;" width="60"/><h4>Storage<h4></h4></h4></td>
<td colspan="2"><b><i>Solid-state drive (RECOMMENDED)<i><b> <br/>OR<br/> <b><i>Hard Disk Drive (HDD)<i><b>   (NOT RECOMMENDED)<i></i></b></i></i></b></b></i></i></b></td>
</tr>
<tr>
<td colspan="2"><b><i>Minimum Storage Requirements: You must have at least 10GB free on the system drive (C:\)<b><i></i></b></i></b></td>
</tr>
<tr>
<td><img height="60" src="https://img.icons8.com/stickers/100/null/storage.png" style="float: left;" width="60"/><h4>Partition<h4></h4></h4></td>
<td colspan="2"><b><i>NTFS ONLY<b><i> <br/><br/> Windows Subsystem For Android™ can only be installed on a NTFS partition, not on an exFAT partition</i></b></i></b></td>
</tr>
<tr>
<td rowspan="3"><img height="58" src="https://user-images.githubusercontent.com/68516357/230764789-ad8f7361-4a3b-49a8-a8e9-24fdc87d5781.png" style="float: left;" width="66"/><h4>Windows Features Needed<h4></h4></h4></td>
<td colspan="2">Virtual Machine Platform Enabled</td>
</tr>
<tr>
<td colspan="2">Windows Hypervisor Platform Enabled</td>
</tr>
<tr>
<td colspan="2"><sub><b><i>These optional settings are for virtualization and provide components that are needed to run WSA. You can enable these settings by pressing the Windows Key + R on your keyboard and typing "OptionalFeatures.exe" into the box, pressing enter and selecting the features above followed by pressing apply</i></b></sub></td>
</tr>
<tr>
<td><img height="60" src="https://user-images.githubusercontent.com/68516357/230759907-5d11950e-1b17-4811-8f4e-a0f82e598079.png" style="float: left;" width="60"/><h4>Virtualization<h4></h4></h4></td>
<td colspan="2">The Computer must support virtualization and be enabled in BIOS/UEFI and Optional Features. <br/> <h3><a href="https://support.microsoft.com/en-us/windows/enable-virtualization-on-windows-11-pcs-c5578302-6e43-4b4b-a449-8ced115f58e1" rel="noopener noreferrer" target="_blank">Guide on how to enable</a><h3></h3></h3></td>
</tr>
</tbody>
</table>

<h1>Installation</h1></a>

### Text Guide:
1. Go to the Releases page
2. In the latest release, go to the Assets section and download the Windows Subsystem For Android™ version of your choosing (do not download "Source code")
3. Extract the .7z archive and rename the folder (that you extracted) to ``WSA``
4. Delete the .7z archive
5. Move the newly extracted folder to a suitable location (Documents folder is a good choice), as you will need to keep the folder on your PC to use MagiskOnWSA

> [!NOTE]   
> If you're updating WSA, merge the folders and replace the files for all items when asked

6. Open the Windows Subsystem For Android™ folder: Search for and double-click `Run.bat`
   - If you previously have a MagiskOnWSA installation, it will automatically uninstall the previous one while preserving all user data and install the new one, so don't worry about your data.
   - If the popup windows disappear without asking administrative permission and Windows Subsystem For Android™ is not installed successfully, you should manually run Install.ps1 as administrator:
      
      - Press Win+x and select Windows™ Terminal (Admin)
      
      - Input the command below and press enter, replacing {X:\path\to\your\extracted\folder} including the {} with the path of the extracted folder
        ```Powershell
        cd "{X:\path\to\your\extracted\folder}"
        ```  
        
      - Input the command below and press enter   
        ```Powershell
        PowerShell.exe -ExecutionPolicy Bypass -File .\Install.ps1
        ```
        
      - The script will run and Windows Subsystem For Android™ will be installed
      - If this workaround does not work, your PC is not supported for WSA
      
7. Once the installation process completes, Windows Subsystem For Android™ will launch (if this is a first-time install, a window asking for consent to diagnositic information will be shown instead. Sometimes two identical windows will show, this is fine and nothing bad happens if you click OK in both windows)
8. Click on the PowerShell window, then press any key on the keyboard, the PowerShell window should close
9. Close File Explorer
10. **Enjoy**

--- 

### Notice (Applicable for both Windows 10 and 11):

1. You can NOT delete the Windows Subsystem For Android™ installation folder.
   What `Add-AppxPackage -Register .\AppxManifest.xml` does is to register an appx package with some existing unpackaged files,
   so you need to keep them as long as you want to use Windows Subsystem For Android™. 
   Check https://learn.microsoft.com/en-us/powershell/module/appx/add-appxpackage?view=windowsserver2022-ps for more details.
2. You need to register your Windows Subsystem For Android™ appx package before you can run Windows Subsystem For Android™. 
   For [WSABuilds](https://github.com/MustardChef/WSABuilds) and [MagiskOnWSALocal](https://github.com/LSPosed/MagiskOnWSALocal) users, you need to run `Run.bat` in the extracted dir.
   If the script fails, you can take the following steps for diagnosis (admin privilege required):
    1. Open a PowerShell window and change working directory to your Windows Subsystem For Android™ directory.
    
    2. Run the command below in PowerShell. This should fail with an ActivityID, which is a UUID required for the next step.
       ```Powershell
       Add-AppxPackage -ForceApplicationShutdown -ForceUpdateFromAnyVersion -Register .\AppxManifest.xml
       ```
       
    3. Run the command below in PowerShell. This should print the log of the failed operation.
       ```Powershell
       Get-AppPackageLog -ActivityID <uuid>
       ```
    4. Check the log for the reason of failure and fix it.

<HR>

<h1>Updating</h1>

### How do I update without losing any of my apps and data on Windows Subsystem for Android (WSA)

> [!IMPORTANT]
> Make sure that WSA has been turned off from the settings and that tools such has WSA-System-Control, WSA-Sideloader, WSAPacman etc are not running.

1. [Download the latest build](https://github.com/MustardChef/WSABuilds#downloads) (that you want to update to)

2. Make sure Windows Subsystem For Android is not running (Click on "Turn off" in the WSA Settings and wait for the spinning loader to disappear)

2. Using 7-Zip, WinRAR or any other tool of choice, open the .7z archive 

3. Within the .7z archive, open the subfolder 
    - Example: 
        - WSA_2xxx.xxxxx.xx.x_xx 
        
        or 
        
        - WSA_2xxx.xxxxx.xx.x_xx_Release-Nightly-with-magisk-xxxxxxx-MindTheGapps-xx.x-RemovedAmazon)

4. Select all the files that are within this subfolder and extract them to the current folder where the file for Windows Subsystem For Android (the folder you extracted, and installed WSA from) are located 

5. When prompted to replace folders, select "Do this for all current items" and click on "Yes" 

6. When prompted to replace files, click on "Replace the files in the destination"

7. Run  the ``Run.bat`` file

8. Launch Windows Subsystem For Android Settings app and go to the ``About`` tab using the sidebar

9. Check if the WSA version matches the latest version/ the version number that you want to update to

<HR>

<h1>Uninstallation</h1>

> [!NOTE]   
>
> If you want to preseve your data, make a backup of the `%LOCALAPPDATA%\Packages\MicrosoftCorporationII.WindowsSubsystemForAndroid_8wekyb3d8bbwe\LocalCache\userdata.vhdx` file. After uninstalling, copy the VHDX file back to the `%LOCALAPPDATA%\Package\MicrosoftCorporationII.WindowsSubsystemForAndroid_8wekyb3d8bbwe\LocalCache` folder. For a more comprehensive and detailed guide, take a look at the **Backup and Restore section** in this README markdown

### To remove WSA installed through WSABuild:

- **1.)** Make sure that Windows Subsystem For Android™ is not running
<br/>

- **2.)** Search for ``Windows Subsystem For Android™ Settings`` using the built-in Windows Search, or through Add and Remove Programs and press uninstall
  
<br/>

- **3.)** Delete the WSA folder that extracted you extracted and Run.bat was run from to install WSA (MagiskOnWSA folder)

<br/>

- **4.)** Go to ``%LOCALAPPDATA%/Packages/`` and check if the folder: ``MicrosoftCorporationII.WindowsSubsystemForAndroid_8wekyb3d8bbwe`` is still present:
   - If the folder is still present: ****Delete it****
      - If you get an error that states that the file(s) could not be deleted, make sure that WSA is turned off
   - If the folder does not exist: ****Skip this step****
           
<br/>

### To remove WSA installed from the Microsoft Store: 
        
   - **1.)** Search for ``Windows Subsystem For Android™ Settings`` using the built-in Windows Search, or through Add and Remove Programs and press uninstall

<HR>
 
<h1>Backup and Restore Userdata</h1>
      
In order to make a backup of your WSA data you must copy the ``Userdata.vhdx`` (which includes, but is not limited Android Apps and their data, settings etc.), located at ``%LOCALAPPDATA%\Packages\MicrosoftCorporationII.WindowsSubsystemForAndroid_8wekyb3d8bbwe\LocalCache\userdata.vhdx``, to a safe location     
      
## Restoring Your Backup

Before attempting to restore your backup, you must remove WSA if installed. Then before you run the ``Run.bat`` script (to reinstall WSA after removing it), you need to remove these lines from ``Install.ps1``, located in the your extracted WSA folder:
      
      
> [!TIP]
> The Lines (as shown below) that you need to remove in ``Install.ps1`` may vary depending on the type of WSA Build that you are trying to install.    
      

#### Android Settings:
```pwsh
Start-Process "wsa://com.android.settings"
```
#### Official Magisk:
```pwsh
Start-Process "wsa://com.topjohnwu.magisk"
```
#### Magisk Delta:
```pwsh
Start-Process "wsa://io.github.huskydg.magisk"
```
#### Magisk Alpha:
```pwsh
Start-Process "wsa://io.github.vvb2060.magisk"
```
#### Google Play Store:
```pwsh
Start-Process "wsa://com.android.vending"
```
#### Amazon Appstore:
```pwsh
Start-Process "wsa://com.amazon.venezia"
``` 

After removing the lines above, run the script. 

When the Powershell window states "Press any key to quit", at that time multiple dialouge boxes will open:

![image](https://github.com/MustardChef/WSABuilds/assets/68516357/53ba5738-a504-4c31-a414-40258180ee09)

> [!IMPORTANT]
> ****Ignore these and do not click on anything or close these popups****

Go to ``%localappdata%\Packages`` and (if these folders/directory do not exist, create them) in ``MicrosoftCorporationII.WindowsSubsystemForAndroid_8wekyb3d8bbwe\LocalCache\`` paste the userdata.vhdx

Now close the popups and run WSA and your userdata should hopefully be restored

</add>    

<HR>
      
<h1>App Compatibility</a></h1></a></summary>

## Updated on 05/03/2024

## Legend

This page currently uses Unicode characters from [Unicode Emoji (1.0)](https://unicode.org/Public/emoji/1.0/emoji-data.txt). If you are unable to see these characters, please open an issue.

- ✅ Works
- 🆖 Works, but needs Google Mobile Services
- ⚠️ Works, but with some notable problems
- ❌ Broken

## Support table (OS features)

| Feature | Support level | Notes |
|---------|---------------|-------|
| Multi-touch | ✅ | Demo: [Arcaea](https://www.bilibili.com/video/BV1Ph411n7M5)
| Virtual Wifi (VirtWifi) | ✅
| Bluetooth | ❌ ([GitHub issue](https://github.com/microsoft/WSA/issues/103))
| IPv6 | ✅ | Loading `ipv6.google.com` in Fennec F-Droid on a PC with IPv6 access, works well
| Fingerprint Reader | ❌ | Test failed on ROG Flow X13, with SATRIA app
| VPN | ❌ | VPN Connection request dialog does not appear
| OpenGL ES 3.1 | ❌
| Vulkan | ✅ | Added as experimental feature in [2307.40000.2.0](https://github.com/microsoft/WSA/discussions/374)

### Workarounds

#### VPN

There is no `com.android.vpndialogs` in WSA. However, it's possible to manually grant the VPN activation permission with AppOps via `adb shell`:

```shell
appops set [package name] ACTIVATE_VPN allow
```

#### Launching Android Apps with URI scheme

Microsoft provides a custom URI scheme for WSA, making it easier to launch apps:

```shell
wsa://[App Package Name]
```

For example, to launch Apple Music in WSA, use:

```shell
wsa://com.apple.android.music
```

<HR>

### Is this GitHub Repo affiliated with Microsoft™?

<center><h3>NO!</h3></center>

###### - Microsoft and the Dev team at MSFT are the developers of Windows Subsystem For Android. We do not claim to develop, or have a part in developing this emulator. We also have no real influence on the direction of development of WSA and nor do we claim to.

###### - What the WSABuild repo does is that it provides prebuilt WSA builds with Root and GMS built using the MagiskOnWSALocal project (and WSAPatch for the Windows 10 patch.) That is that we simply modify the emulator to add extra functionality to it.

###### - All this is, is an unofficial project not related in any way to Microsoft and the team working on Windows Subsystem For Android.

---

### Is this GitHub Repo affiliated with Google™ or Android™?

<center><h3>NO!</h3></center>

###### This is an unofficial project not related in any way to Google and the team working on Android.

---

<br/>

> [!IMPORTANT]
> ***The repository is provided as a utility.***
>***Android is a trademark of Google LLC. Windows™ and Windows Subsystem for Android™ are trademarks of Microsoft LLC.***

</center>


---

- ##### This GitHub repository/project is license under the "AGPL v3" License.
   - ([License File](https://github.com/MustardChef/WSABuilds/blob/master/LICENSE)) 
- ##### ["WSABuilds Project Logo"](https://github.com/MustardChef/WSABuilds/assets/68516357/35cd1d5d-e464-4eb8-a676-b451341f65ad) and other media (images and videos) are licensed under "Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International" License.
   - ([License File](https://github.com/MustardChef/WSABuilds/blob/master/LICENSE-CC-BY-NC-ND))
- ##### Images from Icons8.com are licensed under the Icons8 License.
   - ([License](https://intercom.help/icons8-7fb7577e8170/en/articles/5534926-universal-multimedia-license-agreement-for-icons8))

Please read the following Licenses in full before copy, modifiying, adapting and forking any of the content, code, images, videos and/or information from this GitHub repository.
