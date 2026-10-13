Intel GPU VRAM Unlocker

«Proyecto educativo para explorar y gestionar la configuración del controlador Intel i915 en Linux.»

Descripción

Intel GPU VRAM Unlocker es un proyecto de código abierto cuyo objetivo es facilitar el estudio de la configuración del controlador i915 para GPUs Intel integradas en Linux.

El proyecto proporciona scripts y documentación para inspeccionar la configuración del sistema, realizar copias de seguridad y aplicar parámetros del controlador cuando sean compatibles con la versión del kernel instalada.

«Importante: Las GPU Intel integradas utilizan memoria compartida (UMA). La cantidad de memoria disponible depende del hardware, del BIOS/UEFI y del controlador del kernel. Este proyecto no garantiza aumentar la VRAM en todos los equipos.»

---

Objetivos

- Aprender el funcionamiento del controlador Intel i915.
- Automatizar tareas de configuración mediante Bash.
- Facilitar la creación de copias de seguridad antes de modificar el sistema.
- Documentar los cambios realizados.
- Proporcionar scripts para diferentes distribuciones Linux.

---

Distribuciones compatibles

- Debian
- Ubuntu
- Linux Mint
- Pop!_OS
- Arch Linux
- Manjaro
- EndeavourOS
- Fedora
- CentOS Stream
- RHEL

---

Estructura del proyecto

intel-gpu-vram-unlocker/
│
├── config/
├── docs/
├── images/
├── scripts/
│
├── LICENSE
└── README.md

---

Estado del proyecto

🚧 En desarrollo.

Actualmente se está implementando:

- Estructura del repositorio.
- Scripts para Debian, Arch y Fedora.
- Documentación.
- Verificación del controlador i915.

---

Licencia

Este proyecto está distribuido bajo la licencia MIT.

---

Autor

Rodrigo Soliz

Proyecto desarrollado con fines educativos y de investigación.