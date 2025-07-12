# Monitor de Sistema con Django y Psutil

Presentado por los estudiantes:
Nombre: Denilson Josue Galo Osorto  Numero de cuenta: 201810110446
Nombre: Rigoberto Maradiaga Rodriguez Numero de cuenta: 202310110266


## Descripción del Proyecto

Este proyecto es una aplicación web desarrollada con *Django* que ofrece una visión en tiempo real del estado de un sistema. Utiliza la potente librería de Python *psutil* para recopilar métricas clave como el uso del CPU, la memoria RAM, el espacio en disco, y detalles del sistema operativo. La interfaz web, diseñada para ser clara y estructurada, permite la actualización manual de los datos o, si se configura, una actualización automática.

El objetivo principal es proporcionar una herramienta sencilla pero efectiva para supervisar los recursos vitales de una máquina a través de un navegador web.

## Características Principales

* *Uso del CPU:* Muestra el porcentaje de uso actual del procesador, así como el número de núcleos físicos y lógicos.
* *Uso de Memoria RAM:* Detalla la cantidad total, utilizada y libre de memoria RAM, además de su porcentaje de uso.
* *Almacenamiento en Disco:* Proporciona información sobre el espacio total, usado y libre en la partición principal del disco, junto con el porcentaje de ocupación.
* *Información del Sistema Operativo:* Presenta el nombre del sistema operativo, su versión, la arquitectura del sistema y el hostname de la máquina.
* *Interfaz Web Intuitiva:* Datos mostrados de forma clara en "tarjetas" individuales para fácil lectura.
* *Actualización de Datos:* Opción de actualización manual con un botón o actualización automática configurable (mediante JavaScript).
* *Manejo de Errores:* La aplicación está diseñada para manejar gracefulmente situaciones donde psutil no pueda obtener ciertos datos, mostrando mensajes de error sin interrumpir la ejecución.

## Tecnologías Utilizadas

* *Python 3.x:* Lenguaje de programación principal.
* *Django 4.x+:* Framework web para el desarrollo de la aplicación.
* *psutil 5.x+:* Librería externa de Python para acceder a la información del sistema.
* *HTML5 / CSS3:* Para la estructura y estilos de la interfaz de usuario.
* *JavaScript:* Para funcionalidades interactivas (como la actualización automática opcional).

## Cómo Ejecutar el Proyecto Localmente

Sigue estos pasos detallados para poner en marcha el monitor de sistema en tu entorno de desarrollo.

### 1. Clona el Repositorio (Si Aplica)

Si este proyecto se encuentra en un repositorio Git (por ejemplo, GitHub, GitLab, Bitbucket), el primer paso es clonarlo a tu máquina local:


```bash
git clone <URL_DE_TU_REPOSITORIO>
cd monitor