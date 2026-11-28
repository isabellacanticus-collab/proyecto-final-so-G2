# Ficha de verificación de versión · Grupo 02

## ¿Qué es esta ficha?
Antes de descargar una distribución hay que comprobar que su versión sirve para el proyecto. Esta ficha es la prueba de que lo comprobaron. Se llena una vez por cada distribución del grupo (la gráfica, la de consola y la imagen base del Dockerfile) y cada respuesta lleva el enlace de donde sacaron el dato.

**Distribuciones del grupo 02:** Linux Mint (gráfica), Rocky Linux (consola) y Debian (imagen base).

---

## Linux Mint (VM gráfica)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Linux Mint 22.3 (Zena) - Enero de 2026 | https://linuxmint.com/download_all.php |
| Hasta cuándo recibe actualizaciones de seguridad | Hasta 2029 (5 años de soporte LTS) | https://linuxmint.com/ |
| Requisitos de hardware y si funciona en VirtualBox | 2 GB RAM (recomendado 4 GB), 25 GB disco. Sí funciona en VirtualBox. | https://linuxmint.com/documentation.php |
| ¿El instalador permite particionado manual? | Sí. La opción se llama «Something else» (Algo más). | https://linuxmint-installation-guide.readthedocs.io/en/latest/install.html |
| Guía oficial para instalar Docker Engine en esa familia | Al estar basado en Ubuntu, se usa la guía de Ubuntu. | https://docs.docker.com/engine/install/ubuntu/ |
| Imagen base del Dockerfile para esa versión | No aplica (La imagen base será Debian). | https://hub.docker.com/_/debian |

*Nota del equipo:* A la VM le asignaremos 2 GB de RAM (el mínimo requerido por el proyecto para la VM gráfica).

---

## Rocky Linux (VM consola)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Rocky Linux 9.x (Verificar versión exacta en la página) | https://rockylinux.org/download |
| Hasta cuándo recibe actualizaciones de seguridad | Hasta mayo de 2032 (10 años de soporte) | https://wiki.rockylinux.org/ |
| Requisitos de hardware y si funciona en VirtualBox | Mínimo 2 GB RAM, 2 CPU y 25 GB disco. Sí funciona. | https://docs.rockylinux.org/ |
| ¿El instalador permite particionado manual? | Sí. La opción se llama «Custom» (Personalizada). | https://docs.stg.rockylinux.org/es/teams/testing/documentation/qa_test_cases/Testcase_Disk_Layouts/ |
| Guía oficial para instalar Docker Engine en esa familia | Rocky usa la guía de la familia CentOS/RHEL. | https://docs.docker.com/engine/install/centos/ |
| Imagen base del Dockerfile para esa versión | No aplica (La imagen base será Debian). | https://hub.docker.com/_/debian |

*Nota del equipo:* A la VM de consola le asignaremos los mínimos exigidos por el proyecto (1 GB RAM, 1 CPU, 25 GB disco).

---

## Debian (Imagen base del Dockerfile)

| Pregunta | Respuesta | Enlace donde lo comprobamos |
|---|---|---|
| Versión elegida y fecha de lanzamiento | Debian 12 (Bookworm) - Junio de 2023 | https://www.debian.org/releases/bookworm/ |
| Hasta cuándo recibe actualizaciones de seguridad | Soporte LTS hasta 2028 | https://wiki.debian.org/LTS |
| Requisitos de hardware y si funciona en VirtualBox | Mínimo 512 MB RAM (recomendado 2 GB), 1 GHz CPU. Funciona perfectamente en VirtualBox. | https://www.debian.org/releases/bookworm/amd64/install.es.html |
| ¿El instalador permite particionado manual? | Sí. La opción se llama «Manual». | https://www.debian.org/releases/bookworm/amd64/install.es.html |
| Guía oficial para instalar Docker Engine en esa familia | Guía oficial de Docker para Debian. | https://docs.docker.com/engine/install/debian/ |
| Imagen base del Dockerfile para esa versión | La imagen oficial existe en Docker Hub con la etiqueta `debian:bookworm`. | https://hub.docker.com/_/debian |
