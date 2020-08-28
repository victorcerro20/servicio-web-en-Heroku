# Puesta en Producción de un modelo de aprendizaje automático con Flask y Heroku



La creación de un proyecto de aprendizaje automático en un jupyter notebook ejecutandose en local para unos datos de entrada controlados es una cosa, pero implementar el modelo como una aplicación web y su posterior puesta en producción como servicio para usuarios en la red es otra cosa muy distinta.

Para que un producto basado en el aprendizaje automático tenga éxito, es necesario crear servicios que otros equipos puedan usar o un producto donde los usuarios puedan interactuar. Para ello, el objetivo final es brindar el modelo como un servicio, basandose en un concepto llamado API. Una API es la forma en que los sistemas informáticos se comunican entre sí, actuando como un agente que lleva la información del usuario al servidor y luego nuevamente del servidor al usuario devolviendo la respuesta. Flask proporciona esa capacidad, actuando como una API entre su modelo y el archivo HTML.

Por otra parte utilizaremos Heroku como plataforma en la nube para crear nuestro servicio. Heroku es uno de los PaaS más utilizados en la actualidad en entornos empresariales por su fuerte enfoque en resolver el despliegue de una aplicación. Ademas te permite manejar los servidores y sus configuraciones, escalamiento y la administración. A Heroku solo le dices qué lenguaje de backend estás utilizando (Python, Java, PHP, NodeJS…) o qué base de datos vas a utilizar y te preocupas únicamente por el desarrollo de tu aplicación. Heroku es gratuito para aplicaciones de poco consumo y posteriormente hablaremos de como crear una cuenta gratuita para desplegar nuestro servicio.











puedan desplegar de forma exitosa este tipo de aplicaciones