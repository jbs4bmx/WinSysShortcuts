# **WinSysShortcuts**
## Windows Control Panel & System Settings Shortcuts



  Author: Jace (jbs4bmx)

    Date: 09/02/2020

Synopsis: Collection of shortcuts for Windows system settings for quick reference or scripting.



### **References/Resources**
https://www.anoopcnair.com/sccm-shortcut-commands-windows/

https://www.askvg.com/list-of-commands-to-launch-specific-settings-page-directly-in-windows-10/



## => MS Settings App Shortcuts

When scripting, precede each command with 'start'. It is the same for both CMD and PowerShell.
If used in a .lnk file (Windows Shortcut File), just use the command in the "Location" field.

Settings Page | Commands
------------ | -------------
Settings main page | <code>ms-settings:</code>
System | .
Display | <code>ms-settings:display</code>
Display -> Night light settings | <code>ms-settings:nightlight</code>
Sound | <code>ms-settings:sound</code>
Notifications & actions | <code>ms-settings:notifications</code>
Focus Assist | <code>ms-settings:quiethours</code>
Power & sleep | <code>ms-settings:powersleep</code>
Battery | <code>ms-settings:batterysaver</code>
Battery -> Battery usage by app | <code>ms-settings:batterysaver-usagedetails</code>
Battery -> Battery saver settings | <code>ms-settings:batterysaver-settings</code>
Storage | <code>ms-settings:storagesense</code>
Storage -> Change where new content is saved | <code>ms-settings:savelocations</code>
Storage -> Change how we free up space | <code>ms-settings:storagepolicies</code>
Tablet mode | <code>ms-settings:tabletmode</code>
Multitasking | <code>ms-settings:multitasking</code>
Projecting to this PC | <code>ms-settings:project</code>
Shared experiences | <code>ms-settings:crossdevice</code>
Clipboard | <code>ms-settings:clipboard</code>
Remote Desktop | <code>ms-settings:remotedesktop</code>
About | <code>ms-settings:about</code>
Devices | .
Bluetooth & other devices | <code>ms-settings:bluetooth</code>
Printers & scanners | <code>ms-settings:printers</code>
Mouse | <code>ms-settings:mousetouchpad</code>
Touchpad | <code>ms-settings:devices-touchpad</code>
Typing | <code>ms-settings:typing</code>
Pen & Windows Ink | <code>ms-settings:pen</code>
AutoPlay | <code>ms-settings:autoplay</code>
USB | <code>ms-settings:usb</code>
Phone | .
Phone | <code>ms-settings:mobile-devices</code>
Network & Internet | .
Status | <code>ms-settings:network-status</code>
Cellular & SIM | <code>ms-settings:network-cellular</code>
Wi-Fi | <code>ms-settings:network-wifi</code>
Wi-Fi -> Manage known networks | <code>ms-settings:network-wifisettings</code>
Wi-Fi calling | <code>ms-settings:network-wificalling</code>
Ethernet | <code>ms-settings:network-ethernet</code>
Dial-up | <code>ms-settings:network-dialup</code>
VPN | <code>ms-settings:network-vpn</code>
Airplane mode | <code>ms-settings:network-airplanemode</code>
Mobile hotspot | <code>ms-settings:network-mobilehotspot</code>
Data usage | <code>ms-settings:datausage</code>
Proxy | <code>ms-settings:network-proxy</code>
Personalization | .
Background | <code>ms-settings:personalization-background</code>
Colors | <code>ms-settings:colors</code>
Lock screen | <code>ms-settings:lockscreen</code>
Themes | <code>ms-settings:themes</code>
Fonts | <code>ms-settings:fonts</code>
Start | <code>ms-settings:personalization-start</code>
Taskbar | <code>ms-settings:taskbar</code>
Apps | .
Apps & features | <code>ms-settings:appsfeatures</code>
Apps & features -> Manage optional features | <code>ms-settings:optionalfeatures</code>
Default apps | <code>ms-settings:defaultapps</code>
Offline maps | <code>ms-settings:maps</code>
Apps for websites | <code>ms-settings:appsforwebsites</code>
Video playback | <code>ms-settings:videoplayback</code>
Startup | <code>ms-settings:startupapps</code>
Accounts | .
Your info | <code>ms-settings:yourinfo</code>
Email & app accounts | <code>ms-settings:emailandaccounts</code>
Sign-in options | <code>ms-settings:signinoptions</code>
Access work or school | <code>ms-settings:workplace</code>
Family & other people | <code>ms-settings:otherusers</code>
Sync your settings | <code>ms-settings:sync</code>
Time & language | .
Date & time | <code>ms-settings:dateandtime</code>
Region & language | <code>ms-settings:regionlanguage</code>
Speech | <code>ms-settings:speech</code>
Gaming | .
Game bar | <code>ms-settings:gaming-gamebar</code>
Game DVR | <code>ms-settings:gaming-gamedvr</code>
Broadcasting | <code>ms-settings:gaming-broadcasting</code>
Game Mode | <code>ms-settings:gaming-gamemode</code>
TruePlay | <code>ms-settings:gaming-trueplay</code>
Xbox Networking | <code>ms-settings:gaming-xboxnetworking</code>
Ease of Access | .
Display | <code>ms-settings:easeofaccess-display</code>
Magnifier | <code>ms-settings:easeofaccess-magnifier</code>
Color filters | <code>ms-settings:easeofaccess-colorfilter</code>
High contrast | <code>ms-settings:easeofaccess-highcontrast</code>
Narrator | <code>ms-settings:easeofaccess-narrator</code>
Audio | <code>ms-settings:easeofaccess-audio</code>
Closed captions | <code>ms-settings:easeofaccess-closedcaptioning</code>
Speech | <code>ms-settings:easeofaccess-speechrecognition</code>
Keyboard | <code>ms-settings:easeofaccess-keyboard</code>
Mouse | <code>ms-settings:easeofaccess-mouse</code>
Eye control | <code>ms-settings:easeofaccess-eyegaze</code>
Other options | <code>ms-settings:easeofaccess-otheroptions</code>
Cortana | .
Talk to Cortana | <code>ms-settings:cortana</code>
Permissions & history | <code>ms-settings:cortana-permissions</code>
Notifications | <code>ms-settings:cortana-notifications</code>
More details | <code>ms-settings:cortana-moredetails</code>
Privacy | .
General | <code>ms-settings:privacy-general</code>
Speech, inking, & typing | <code>ms-settings:privacy-speechtyping</code>
Diagnostics & feedback | <code>ms-settings:privacy-feedback</code>
Activity History | <code>ms-settings:privacy-activityhistory</code>
Location | <code>ms-settings:privacy-location</code>
Camera | <code>ms-settings:privacy-webcam</code>
Microphone | <code>ms-settings:privacy-microphone</code>
Notifications | <code>ms-settings:privacy-notifications</code>
Account info | <code>ms-settings:privacy-accountinfo</code>
Contacts | <code>ms-settings:privacy-contacts</code>
Calendar | <code>ms-settings:privacy-calendar</code>
Call history | <code>ms-settings:privacy-callhistory</code>
Email | <code>ms-settings:privacy-email</code>
Tasks | <code>ms-settings:privacy-tasks</code>
Messaging | <code>ms-settings:privacy-messaging</code>
Radios | <code>ms-settings:privacy-radios</code>
Other devices | <code>ms-settings:privacy-customdevices</code>
Background apps | <code>ms-settings:privacy-backgroundapps</code>
App diagnostics | <code>ms-settings:privacy-appdiagnostics</code>
Automatic file downloads | <code>ms-settings:privacy-automaticfiledownloads</code>
Documents | <code>ms-settings:privacy-documents</code>
Pictures | <code>ms-settings:privacy-pictures</code>
Videos | <code>ms-settings:privacy-videos</code>
File system | <code>ms-settings:privacy-broadfilesystemaccess</code>
Update & security | .
Windows Update | <code>ms-settings:windowsupdate</code>
Windows Update -> Check for updates | <code>ms-settings:windowsupdate-action</code>
Windows Update -> Update history | <code>ms-settings:windowsupdate-history</code>
Windows Update -> Restart options | <code>ms-settings:windowsupdate-restartoptions</code>
Windows Update -> Advanced options | <code>ms-settings:windowsupdate-options</code>
Windows Security / Defender | <code>ms-settings:windowsdefender</code>
Backup | <code>ms-settings:backup</code>
Troubleshoot | <code>ms-settings:troubleshoot</code>
Recovery | <code>ms-settings:recovery</code>
Activation | <code>ms-settings:activation</code>
Find My Device | <code>ms-settings:findmydevice</code>
For developers | <code>ms-settings:developers</code>
Windows Insider Program | <code>ms-settings:windowsinsider</code>
Mixed reality | .
Audio and speech | <code>ms-settings:holographic-audio</code>


## => SCCM Shortcuts (ConfigMgr Shortcut Commands)

Applet | Commands
------------ | -------------
Configuration Manager SCCM Control Panel Applet | <code>Control smscfgrc</code>
Configuration Manager SCCM Run Advertised Programs (RAP) | <code>control SMSRAP</code>
Configuration Manager SCCM Program Download Manager (PDM) | <code>control SMSPDM</code>


## => Windows Control Panel Commands

Control Panel Applet | Commands
------------ | -------------
Add Remove Programs | <code>AppWiz.cpl</code>
Bluetooth Devices | <code>BthProps.cpl</code>
People Near Me (Only for Windows 7 and below) | <code>CollAb.cpl</code>
Screen Resolution | <code>DESK.cpl</code>
Windows FireWall | <code>FireWall.cpl</code>
Flash Player Settings | <code>FlashPlayerCPLApp.cpl</code>
Device Manager | <code>HdwWiz.cpl</code>
Intel Graphics and Media Control Panel (Intel graphics required) | <code>Igfxcpl.cpl</code>
Internet Properties | <code>Inetcpl.cpl</code>
Region and Language Setting | <code>Intl.cpl</code>
Game Controllers – Joystick Properties | <code>Irprops.cpl</code>
Mouse Properties | <code>Main.cpl</code>
Mail Setup – Outlook (RUN prompt only) | <code>MLCFG32.cpl</code>
Sound Properties | <code>mmsys.cpl</code>
Network Connections | <code>ncpa.cpl</code>
Power Options | <code>powercfg.cpl</code>
Realtek Audio Manager (Realtek only) | <code>RTSnMg64.cpl</code>
Symantec Live Update Configuration (Symantec required) | <code>S32LUCP2.cpl</code>
Speech Properties (Not working in Windows 10) | <code>sapi.cpl</code>
System Properties (Change Computer Name) | <code>sysdm.cpl</code>
Tablet PC Configurations | <code>TabletPC.cpl</code>
Location Information (And Telephone Configuration) | <code>Telephon.cpl</code>
Time and Date | <code>TimeDate.cpl</code>
Action Center | <code>Wscui.cpl</code>


## => Administrative Control Panel Commands

Control Panel Applet | Commands
------------ | -------------
Bit Locker Encryption | <code>control /name Microsoft.BitLockerDriveEncryption</code>
Admin Tools | <code>control admintools</code>
AutoPlay | <code>control /name Microsoft.AutoPlay</code>
Color Management | <code>control /name Microsoft.ColorManagement</code>
Credential Manager | <code>control /name Microsoft.CredentialManager</code>
Default Programs | <code>control /name Microsoft.DefaultPrograms</code>
Printers | <code>control printers</code>
Task Sheduler | <code>control schedtasks</code>
Windows Update | <code>control /name Microsoft.WindowsUpdate</code>
User Account | <code>control userpasswords</code>


#### => License
_The Unlicense_

.
