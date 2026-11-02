Laboratorio de Seguridad - VirtualBox

1. Descripción

Este proyecto consiste en la creación y configuración de un entorno virtual de pruebas controlado utilizando Oracle VirtualBox y Windows 11.

El objetivo es aprender a configurar un entorno aislado para realizar futuras pruebas de seguridad informática.

2. Configuración de red

Modo seleccionado: Red Interna (Internal Network).

Se eligió el modo Red Interna porque permite aislar la máquina virtual de la red doméstica y de Internet, proporcionando un entorno controlado para realizar pruebas de seguridad. Las máquinas virtuales conectadas a la misma red interna pueden comunicarse entre sí.

No se utilizó el modo Puente (Bridged) porque conecta directamente la máquina virtual a la red física, exponiéndola a otros dispositivos de la red local y aumentando los posibles riesgos de seguridad.

Captura de configuración de red



3. Instantánea del sistema

Se creó una instantánea llamada Instalación Base Limpia, que permite recuperar el estado inicial del sistema operativo en caso de errores o modificaciones durante las pruebas.


4. Conclusión

Se logró configurar un entorno virtual de pruebas utilizando VirtualBox, aplicando conceptos de aislamiento de red y protección del estado inicial mediante instantáneas.

Este entorno permitirá realizar futuras prácticas de seguridad informática de manera controlada.
