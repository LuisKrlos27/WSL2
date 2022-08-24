
# __¿Para que sirve WSL2__?

La finalidad principal de WSL es permitir a los administradores de sistemas, y a los programadores, usar todas las herramientas y todos los servicios de Linux directamente desde Windows sin tener que virtualizar nada más ni montar infraestructuras complicada 

![img](img/Logo_3.png)

# __¿Por que utilizar WSL2?__

Las características principales de WSL 2 son un mayor rendimiento (hasta 20 veces mejor que WSL 1 🤯) y un kernel de Linux 100% nativo, y otras características como:

* Llamadas del sistema totalmente compatibles
* Poco uso de memoria RAM
* Acceder a los archivos de la distro a través de la Red desde el explorador de Windows

Además debemos considerar tener un ambiente de desarrollo lo más cercano a lo que tendremos a los servidores en producción. Si comparamos porque utilizar contra GitBash la razón es sencilla, tenemos una alta gama de herramientas de desarrollo disponibles en WSL, además de que GitBash está muy limitado a funcionar adecuadamente para que utilicemos Git.

# __Requisitos de WSL2__
* Los requisitos del sistema para la utilización de WSL2 dependen del procesador que el ordenador tenga instalado: Para sistemas x64 se requiere como mínimo la versión 1903 con build 18362 o superior. Para sistemas ARM64 se requiere como mínimo la versión 2004 con build 19041 o superior.

## __Como saber si tego WSL1 ó WSL2__

* Para ver si la distribución de Linux está establecida en WSL 1 o WSL 2, use el comando wsl -l -v . Para cambiar de versión, use el comando: wsl --set-version < distro name>

 ![img](img/Logo_4.jpg)

### __Enlaces__
* [Para que sirve WSL2](https://www.softzone.es/windows/como-se-hace/subsistema-windows-linux/#:~:text=La%20finalidad%20principal%20de%20WSL,m%C3%A1s%20ni%20montar%20infraestructuras%20complicadas.)

* [Requisitos de WSL2](https://www.ionos.es/digitalguide/servidores/know-how/wsl2/#:~:text=Los%20requisitos%20del%20sistema%20para,con%20build%2019041%20o%20superior.)
