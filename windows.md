# Windows
https://www.microsoft.com/software-download/

## Manual de instalación de Windows 11 o MacOS

Opción 1: Microsoft_Azure_Education -> https://portal.azure.com/#view/Microsoft_Azure_Education/EducationMenuBlade/~/software

Opción 2: Windows 11 -> https://developer.microsoft.com/es-es/windows/downloads/virtual-machines/

Opción 3: MacOS -> https://support.apple.com/es-es/HT201372


## Medios de instalación

[Crear medios de instalación de Windows](https://support.microsoft.com/es-es/windows/crear-medios-de-instalaci%C3%B3n-de-windows-99a58364-8c02-206f-aa6f-40c3b507420d)


## Windows 11

### Instalación de Windows 11 cuando el procesador no está entre los elegidos.
**Entradas de registro**
```
Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SYSTEM\Setup\MoSetup]
"AllowUpgradesWithUnsupportedTPMOrCPU"=dword:00000001
"BypassTPMCheck"=dword:00000001
"BypassCPUCheck"=dword:00000001
"BypassRAMCheck"=dword:00000001
"BypassSecureBootCheck"=dword:00000001
````

---
## Subsistema de Windows para Linux (WSL) > [Instalación de Linux en Windows con WSL](https://learn.microsoft.com/es-es/windows/wsl/install)
### Prerrequisitos
Para ejecutar los siguientes comandos, debe ejecutar Windows 10 versión 2004 y posteriores (compilación 19041 y posteriores) o Windows 11. Si está en versiones anteriores, consulte la [página de instalación manual](https://learn.microsoft.com/es-es/windows/wsl/install-manual).

---
## Lista de Consolas .MSC de windows

Los archivos con extensión .MSC son «consolas» o «programas» que sirven para configurar ciertos aspectos de Windows, nos son muy útiles y hay muchos.

A continuación, hay la lista de comandos que nos abren las diferentes consolas en Windows. Algunas solo están disponibles en Windows Server y en algunas versiones solo.
Por defecto los archivos .msc estan en Windows\System32.
Podemos ejecutar qualquier archivo .msc pulsando Windows-R y escribiendo el nombre del archivo msc y la extensión y pulsando la tecla Enter del teclado. Ej: perfmon.msc

### Lista de archivos MSC para cualquier Windows
.MSC file
Console	Description
azman.msc	Authorization Manager	Manage Authorization Stores
certlm.msc	Certificates Local Computer	Loads the list of certificates of the local computer.
certmgr.msc	Certificates	Loads the list of certificates of the user
comexp.msc	Component Services	Loads Component Services, Event Viewer, and Services.
compmgmt.msc	Computer Management	Includes System Tools (Task Scheduler, Event Viewer, Shared Folders, Local Users and Groups, Performance and Device Manager), Storage (Disk Management), and Services and Applications (Services and WMI Control)
devmgmt.msc	Device Manager	Opens the Device Manager to manage hardware and devices.
devmoderunasuserconfig.msc	User Manager	Complete customization of the start menu items and the taskbar.
diskmgmt.msc	Disk Management	Opens Disk Management to administrate connected storage devices.
eventvwr.msc	Event Viewer	Opens the Event Viewer which displays operating system, software, and hardware events.
fsmgmt.msc	Shared Folders	Loads the list of shared folders, sessions, and open files
gpedit.msc	Group Policy Editor	Loads the Group Policy Editor to manage system policies
lusrmgr.msc	Local Users and Groups	Interface to manage local users and user groups.
perfmon.msc	Performance Monitor	Loads the Windows Performance Monitor
printmanagement.msc	Print Management	Manage printers.
rsop.msc	Resultant Set of Policies	List policies, full results only available through command line tool gpresult
secpol.msc	Local Security Policy	Loads policies such as account policies, public key policies, or advanced audit policy configuration
services.msc	Services Manager	Loads the list of installed services to manage them.
taskschd.msc	Task Scheduler	Loads the Task Scheduler to manage tasks
tpm.msc	Trusted Platform Module Management	Manage the TPM on the local device.
wf.msc	Windows Firewall	Starts Windows Firewall with Advanced Security.
wmimgmt.msc	WMI Management	Configure and Control the Windows Management Instrumentation Service.

### Lista de archivos MSC para Windows Server
.MSC file
Description
adfs.msc	Active Directory Federation Services
AdRmsAdmin.msc	Active Directory Rights Management Services
adsiedit.msc	ADSI Edit
certim.msc	Local Computer Certificates
certsrv.msc	Certification Authority
certtmpl.msc	Certification Templates
ciadv.msc	Indexing Service
cluadmin.msc	Failover Cluster Manager
da6to4.msc	Network Interfaces Performance Monitor
daihttps.msc	HTTPS Traffic Performance Monitor
daipsecdos.msc	IPSec Performance Monitor
daisatapmsc	ISATAP Performance Monitor
dfsmgmt.msc	DFS Management
dhcpmgmt.msc	DHCP Management
dnsmgmt.msc	DNS Manager
domain.msc	Active Directory Domains and Trust
dsa.msc	Active Directory Users and Computers.
dssite.msc	Active Directory Sites and Services
fsrm.msc	File Server Resource Manager
fxsadmin.msc	Microsoft Fax Service Manager
gpmc.msc	Group Policy Management
gpme.msc	Group Policy Mangement Editor
gptedit.msc	Group Policy Starter GPO Editor
hcscfg.msc	Health Registration Authority
idmumgmt.msc	Microsoft Identity Management for Unix
iis.msc	Internet Information Services Manager
iis6.msc	Internet Information Services Manager 6.0
lsdiag.msc	RD Licensing Diagnoser
napclcfg.msc	NAP Client Configuration
mfsmgmt.msc	Services for Network File System
nps.msc	Network Policy Server
ocsp.msc	Online Responder
pkiview.msc	Enterprise PKI
remoteprograms.msc	RemoteApp Manager
rrasmgmt.msc	Routing and Remote Access
sanmmc.msc	Storage Manager for SANs
sbmgr.msc	Remote Desktop Connection Manager
scanmanagement.msc	Scan Management
servermanager.msc	Server Manager
storagemgmt.msc	Share and Storage Management
storexpl.msc	Storage Explorer
tapimgmt.msc	Telephony
tsadmin.msc	Remote Desktop Services Manager
tsconfig.msc	Remote Desktop Session Host Configuration
tsgateway.msc	RD Gateway Manager
tsmmc.msc	Remote Desktops
virtmgmt.msc	Hyper-V Manager
wbadmin.msc	Windows Server Backup
Wdsmgmt-msc	Windows Deployment Services
winsmgmt.msc	WINS
wbiadmin.msc	Windows Server Backup
wsrm.msc	Windows System Resource Manager
wsus.msc	Update Services
