# Windows

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
