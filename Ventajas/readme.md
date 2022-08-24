# __Ventajas de utilizar WSL2__
WSL2 cuenta con un hipervisor nativo que permite ejecutar un Kernel real directamente en Windows. Con esto, se solucionan todos los problemas de rendimiento y se compatibilidad con servicios y programas, consiguiendo incluso una mejora de rendimiento de hasta un 500% al realizar determinadas tareas.

## __¿Que es mejor usar Windows ó Linux?__

Windows es muy estable y competente, además de estar ya consolidado en el mercado, siendo “estándar” para varias aplicaciones desarrolladas. Por otro lado, Linux es un sistema gratuito, personalizable y más seguro. Además, representa una gran cuota del mercado en lo que se refiere a servidores.

## __¿Como activar WSL2 en Windows?__
Accede a la consola avanzada Powershell en modo administrador para instalar la función ejecutando el comando «Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux». Cuando te lo pida reinicia el equipo.

## __WSl1 vs WSL2__
|     <text style = "display:block; text-align: Center">**CARACTERÍSTICA**</text>    |     **WSL 1** |     **WSL 2** |
|---|:---:|:---:|
|     Integración entre Windows y Linux |     :white_check_mark:    |     :white_check_mark:    |
|     Tiempos de arranque rápidos |     :white_check_mark:    |     :white_check_mark:    |
|     Huella de recurso pequeña en comparación con las máquinas virtuales tradicionales |     :white_check_mark:    |     :white_check_mark:    |
|     Se ejecuta con las versiones actuales de VMWare y VirtualBox |     :white_check_mark:    |     :white_check_mark:    |
|     VM administradas |     :x:    |     :white_check_mark:    |
|     Kernel de Linux completo |     :x:    |     :white_check_mark:    |
|     Compatibilidad completa con las llamadas del sistema |     :x:    |     :white_check_mark:    |
|     Rendimiento entre sistemas de archivos del sistema operativo    |     :white_check_mark:    |     :x:    |
