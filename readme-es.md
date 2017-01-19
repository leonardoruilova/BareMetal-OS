# BareMetal OS -- a 64-bit OS written in Assembly for x86-64 systems #

[![Dialogue copn nosotros en el chat Gitter en https://gitter.im/ReturnInfinity/BareMetal-OS](https://badges.gitter.im/ReturnInfinity/BareMetal-OS.svg)](https://gitter.im/ReturnInfinity/BareMetal-OS?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Copyright (C) 2007-2016 Return Infinity -- Por favor revise el documento LICENSE.TXT

BareMetal es un sistema operativo de 64-bit para computadores de arquitectura x86-64. El sistema operativo esta programado en ensamblador, sin embargo es posible programar software en ensamblador, C/C++ y Rust. Existen tres focos para el desarrollo del sistema operativo:

* **Computacion de Alto Rendimiento** - Buscamos que Baremetal OS sea el fundamento de clusters para HPC. Nuestro sistema operativo es muy apropiado para altas cargas de trabajo, debido a que posee monotarea.
* **Aplicaciones empotradas** - Buscamos que Baremetal OS sea adecuado para aplicaciones empotradas que sean ejecutadas en hardware x86-64.
* **Educacion** - Buscamos que Baremetal OS sea adecuado para el aprendizaje y la experimentacion con ensamblado x86-64 y con la base de los sistemas operativos.

BareMetal es un sistema operativo de 64-bit en modo protegido para computadores compatibles con CPU x86-64, su codigo esta escrito en ensamblador y es posible el boot desde un disco duro y desde la red. Baremetal OS posee interfaz de linea de comandos y es posible acceder a discos duros [formatedos con BMFS](https://github.com/ReturnInfinity/BMFS), asi como es posible usar el parlante interno de su PC. It can load external programs and has over 60 system calls. BareMetal can also utilize all available CPU's in the computer it is run on.

At the moment there is no plan to build BareMetal into a general-purpose operating system like Windows, Mac OS X, or Linux; it is designed to be as lean as possible while still offering useful features.

The complete documentation for BareMetal, including instructions on running it, building it and writing your own programs for it can be found in the docs/ directory.

See LICENSE.TXT for redistribution/modification rights, and CREDITS.TXT for a list of people involved.

Ian Seyler (ian.seyler@returninfinity.com)
