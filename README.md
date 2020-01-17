# TelegramBotClientKaios
Aplicación para el sistema Kaios para mensajería de Telegram utilizando un Bot de Telegram

La principal limitación es que para poder mantener una conversación con alguien, primero debe empezar la conversación la persona con nuestro Bot y a partir de ese momento, ya podremos comunicarnos con esa persona mediante la aplicación en cualquier momento.

Para poder usar la aplicación se debe crear un bot de Telegram.
Para ello, debemos tener instalado la aplicación Telegram en un dispositivo y buscar el usuario: BotFather
Empezamos conversación indicando el texto siguiente:
/newbot
A partir de este momento, se empieza un proceso que te irá preguntando distintas cuestiones para poder crear el Bot.
Al final obtendremos un token.
Este token deberá de ser introducido en nuestra aplicación.
A partir de ese momento, ya podremos utilizar la aplicación.

La aplicación tiene una funcionalidad muy básica, pero puede enviar y recibir texto, puede recibir imágenes, videos, audios y gifs animados.

Para poder instalar la aplicación en un dispositivo con sistema Kaios, primero debemos activar el modo de desarrollo, con la combinación de teclas siguiente: **#**#33284#**#**

Después deberemos utilizar el aplicativo adb desde la línea de comandos y executar la siguiente instrucción:
adb forward tcp:6000 localfilesystem:/data/local/debugger-socket

Si todo ha ido bien, deberemos ir a una versión de Firefox que tenga habilitado el WebIDE para poder trabajar con nuestro dispositivo con Kaios.

Desde el WebIDE seleccionaremos la carpeta donde hemos descargado la aplicación y clicaremos el botón central de Play. Esto instalará y ejecutar la aplicación.

Ahora ya sólo queda que se configure el token del Bot de Telegram en la aplicación y ya podremos indicar a las personas que queramos cual es el nombre de nuestro Bot para que se puedan comunicar con nosotros.
