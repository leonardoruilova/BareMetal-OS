# BareMetal OS -- a 64-bit OS written in Assembly for x86-64 systems #

[![JPor favor unase a nuestro chat https://gitter.im/ReturnInfinity/BareMetal-OS](https://badges.gitter.im/ReturnInfinity/BareMetal-OS.svg)](https://gitter.im/ReturnInfinity/BareMetal-OS?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Copyright (C) 2007-2016 Return Infinity -- Por favor remitase a LICENSE.TXT. La traduccion es de licencia CC-BY-NC

BareMetal es un Sistema Operativo de 64-bit para computadores de CPU x86-64. El Sistema Operativo está programado en el lenguaje Assembly, sin embargo, el software puede ser programado en Ensamblado, C/C++ y Rust. Tres objetivos conducen el desarrollo de Baremetal OS:

* **Computacion de Alto Rendimiento** - (High Performance Computing) Baremetal OS es el fundamento de un cluster de HPC. La ejecucion de grandes cargas de trabajo (workloads) es perfecta para un Sistema Operativo monotareas.
* **Desarrollo de Aplicaciones Empotradas** - Baremetal OS es una excelente plataforma para aplicaciones empotradas a ejecutar en hardware x86-64.
* **Educacion** - Baremetal OS es un entorno ideal para el aprendizaje del Ensamblado para CPU x86-64, asi como tambien es adecuado para entender los fundamentos de los Sistemas Operativos.

BareMetal es un Sistema Operativo para procesadores de 64-bit, en modo protegido, para computadores x86-64. El codigo de Baremetal OS es el lenguaje Ensamblado y su proceso de boot puede ser desde un disco duro o desde la red. Puede usar Baremetal mediante una linea de comandos. En Baremetal existe soporte para [discos duros formateados en el sistema de ficheros BMFS](https://github.com/ReturnInfinity/BMFS) y es posible usar el parlante interno de su computador. Ud puede cargar programas externos y dar uso a mas de 60 llamadas a sistema. Es posible utilizar todos los CPU disponibles en su computador mediante BareMetal.

En este momento no existen planes para que BareMetal sea un sistema de proposito general como Microsoft Windows, Apple MacOS o GNU Linux; su desarrollo es tan 'lean' como nos es posible, si bien nuestro Sistema Operativo entrega cualidades de gran utilidad.

La documentacion de BareMetal se encuentra en el directorio docs/ e incluye instrucciones para su ejecucion, compilacion y para el desarrollo de su propio software.

La licencia de Baremetal esta en el documento LICENSE.TXT, donde estan detallados los derechos de redistribucion y modificacion. En el archivo CREDITS.TXT podra enterarse de han participado en nuestro proyecto.

Ian Seyler (ian.seyler@returninfinity.com)

Traduccion: Virgilio Leonardo Ruilova - Licencia : Creative Commons - By - NC
