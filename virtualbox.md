# https://www.virtualbox.org/


[User Manual](https://download.virtualbox.org/virtualbox/7.0.4/UserManual.pdf)

En la página principal de virtualbox nos dan la bienvenida **Welcome to VirtualBox.org!** iindicandonos que la versión 7 ya está disponible para instalar. 


## Paso 1: Hacemos clic en 

[![Image](https://user-images.githubusercontent.com/15022199/203301429-2c177250-e24f-467e-8947-35c7a2683e19.png)](https://www.virtualbox.org/wiki/Downloads)

## Paso 2: Seleccionamos los paquetes a instalar y los descargamos.

Mi portátil funciona con Windows 11 así elijo descargar la última versión en el momento de la instalación:

[VirtualBox](https://www.virtualbox.org/wiki/VirtualBox) 7.0.4 platform packages
[ Windows hosts](https://download.virtualbox.org/virtualbox/7.0.4/VirtualBox-7.0.4-154605-Win.exe)

[VirtualBox](https://www.virtualbox.org/wiki/VirtualBox) 7.0.4 Oracle VM VirtualBox Extension Pack
[ All supported platforms](https://download.virtualbox.org/virtualbox/7.0.4/Oracle_VM_VirtualBox_Extension_Pack-7.0.4.vbox-extpack)

## Paso 3 Procedemos a la ejecución del instalador 

Primero VirtualBox-7.0.4-154605-Win.exe (Botón derecho Ejecutar como Administrador) y el sistema nos avisa que necesitamos cosas

** ATENCIÓN:**  En Windows con **_Ctrl+Alt+Shift + ImpPa_** (capturamos la ventana que tiene el foco)

![Image](https://user-images.githubusercontent.com/15022199/203303197-d97ee434-0197-4f5f-a201-7df6085abdaf.png)

Le damos a OK

![Image](https://user-images.githubusercontent.com/15022199/203303860-e96c8cd8-d78a-4c2e-9282-cabe9765cd3b.png)



En Windows con **_Ctrl+Alt+Shift + ImpPa_** (capturamos la ventana que tiene el foco)



## Paso 4 Solución de problemas en la instalación.

Debido a que el sistema no dispone del paquete **Microsoft Visual C++  2019 Redistributable** buscamos en internet información:

Búqueda por palabras [Microsoft Visual C++  2019 Redistributable for VirtualBox](https://www.google.es/search?q=Microsoft+Visual+C%2B%2B++2019+Redistributable+for+VirtualBox&ei=s7d8Y-mIBKqgkdUPquOY0AY&ved=0ahUKEwiprqDQ3MH7AhUqUKQEHaoxBmoQ4dUDCA8&uact=5&oq=Microsoft+Visual+C%2B%2B++2019+Redistributable+for+VirtualBox&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIFCAAQogQyBQgAEKIESgQIQRgASgUIQBIBMUoECEYYAFAAWABgzgJoAHAAeACAAYUBiAGFAZIBAzAuMZgBAKABAcABAQ&sclient=gws-wiz-serp)

Entramos en [Últimas descargas de Visual C++ Redistributable compatibles](https://learn.microsoft.com/es-es/cpp/windows/latest-supported-vc-redist?view=msvc-170)

## Paso 5 Instalamos Microsoft Visual C++

X64	https://aka.ms/vs/17/release/vc_redist.x64.exe	Permalink para obtener la versión x64 compatible más reciente. El paquete X64 Redistributable contiene archivos binarios ARM64 y X64. Este paquete facilita la instalación de los archivos binarios de Visual C++ ARM64 necesarios cuando X64 Redistributable se instala en un dispositivo ARM64.



![Image](https://user-images.githubusercontent.com/15022199/203308806-897cf2f6-f839-4f07-ab78-bc9a83651d26.png)

Aceptamos los términos y le damos a instalar

![Image](https://user-images.githubusercontent.com/15022199/203309370-fbff4c88-d14b-4fc3-b696-a81119e1ab07.png)

**Reiniciamos pues**

## Paso 6 Continuamos con la instalación de VirtualBox-7.0.4-154605-Win.exe 



![Image](https://user-images.githubusercontent.com/15022199/203310836-8c5e42a0-ae2a-4dc0-aeca-115125d50e7a.png)



![Image](https://user-images.githubusercontent.com/15022199/203310932-f74d0a0d-b9b9-4d84-8451-9d454630b626.png)




![Image](https://user-images.githubusercontent.com/15022199/203310972-02512cf3-822b-4c35-8208-59b1be27cdd4.png)




![Image](https://user-images.githubusercontent.com/15022199/203311030-0478187e-f4e0-4d93-aadd-3c16d49097d2.png)



![Image](https://user-images.githubusercontent.com/15022199/203311121-2dcdbfad-8460-46a5-b4e2-446b2e43635f.png)



![Image](https://user-images.githubusercontent.com/15022199/203311223-2c5732b9-2a99-4d38-8e45-0ef6899cbef3.png)



![Image](https://user-images.githubusercontent.com/15022199/203311319-bc99fdbb-7ee1-4ec3-bd65-cc87bf53e88f.png)



![Image](https://user-images.githubusercontent.com/15022199/203311415-42204613-f6f8-4d71-8a75-db6135c44802.png)


## Paso 7 Instalación del [Oracle_VM_VirtualBox_Extension_Pack-7.0.4.vbox-extpack](https://download.virtualbox.org/virtualbox/7.0.4/Oracle_VM_VirtualBox_Extension_Pack-7.0.4.vbox-extpack)

Seleccionamos en Herramientas la opción de menú Extensiones


![Image](https://user-images.githubusercontent.com/15022199/203312017-04e0576b-f322-4c03-a000-af8495d77ad5.png)

Nos aparecerá ahora la opción de instalar

![Image](https://user-images.githubusercontent.com/15022199/203312244-9c00213c-35cd-4fc2-be69-65d0d8ea98c2.png)


Una vez hagamos clic en instalar nos permitirá seleccionar el paquete, en nuestro caso, buscamos la descarga de Oracle_VM_VirtualBox_Extension_Pack-7.0.4.vbox-extpack



![Image](https://user-images.githubusercontent.com/15022199/203312692-07251e8a-7e53-4666-a7e0-2f1c2fb8b6c0.png)

Le damos a instalar



![Image](https://user-images.githubusercontent.com/15022199/203312864-00da1689-548a-401b-bc23-20c4ce480e25.png)

Aceptamos las cuestiones legales... (hay que hacer scroll)

¡y voila ya está! la extensión pack


![Image](https://user-images.githubusercontent.com/15022199/203313104-10d5459c-55bf-45ab-b7bb-439a99878dbf.png)


## Paso 8 Fin

Ya lo tenemos todo preparado para trabajar en VirtualBox, por ejmplo, instalando una maquina virtual de windows

Ya puedes trabajar en casa la instalación de Windows para VirtualBox

https://developer.microsoft.com/es-es/windows/downloads/virtual-machines/


---


[Aquí tienes otras formas de virtualizar máquinas en Windows](https://learn.microsoft.com/es-es/virtualization/)







