# :IU
## _Automatización para las plataformas de la UDNC_

[![N|Gians96](https://firebasestorage.googleapis.com/v0/b/nube-tecnologica.appspot.com/o/Mesa%20de%20trabajo%201.png?alt=media&token=b272d29c-a2fc-4a7c-8653-7ad8488d1306)](https://github.com/gians96)

Son un conjunto de herramientas hecho en python para automatizar tareas repetitivas que vienen realizando en la organización de la UNDC.

## Sobre

- Creación de grupos de WhatsApp de manera masiva.
- Eliminación de usuarios que conforman el grupo de WhatsApp.
- Envío de comunicado masivo a grupos de WhatsApp.
- Llenado de Carga Lectiva, Carga no lectiva y Carga detalle lectiva masivamente.
- Extrae en listado en formato xls, de la carga lectiva, no lectiva, carga detalle lectiva y Link de Aula Virtual
- Crear Tag's en el Aula Virtual para unirse a los grupos de WhatsApp.
- Crea los links de descarga para los backup's de los cursos en el Aula Virtual


## Tecnologías

Se utiliza una serie de proyectos de código abierto para funcionar correctamente:

- Python3
- Anaconda
- Chrome Driver
- Jupyter


## Instalación

Requiere [Python](https://www.python.org/downloads/) v3+.
Requiere [Anaconda](https://www.anaconda.com/products/distribution) 
## Paquetes Anaconda
Necesitamos dos paquetes para poder correr el script, abrimos el terminal y ejecutamos los siguientes comandos:
```sh
conda install -c conda-forge webdriver-manager
conda install -c conda-forge selenium
```
## Para entrar al SIVIRENO
Tienes que modificar el archivos .env.example a .env  y poner tus credenciales en los parametros que se necesite.
```sh
EMAIL=<pepitogrillo@gians96.dev>
PASSWORD=<123456>
```
## Dev

¿Quieres colaborar? Genial!, claro si estas dentro de la organización y tengas acceso para ir contruyendo algo mejor en el Repositorio.
Puedes ir empezando a clonar:


```sh
git clone https://github.com/gians96/UNDC_AUTOMATIZACION.git
```


## License

FREE

**Free Software, Hell Yeah!**

[//]: # (Si tienes una referencia interesante para este proyecto lo puedes listar aqui. Thanks SO)

   [python]: <https://www.python.org/>
