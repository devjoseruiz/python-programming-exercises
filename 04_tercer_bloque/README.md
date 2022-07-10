# Ejercicios de programación en Python: manejo de excepciones

Para los siguientes ejercicios no habrá ya pistas de ningún tipo. Se asume que el alumno ha adquirido a estas alturas la madurez necesaria para deducir cómo resolver los problemas propuestos e investigar por sí mismo en internet cuando sea necesario.

## 1. Reggaeton Twitter Bot

La propuesta es programar un bot de Twitter que cada "X" horas genere aleatoriamente un verso reggaetonero y lo publique en forma de tweet. Para este proyecto se va a reutilizar el concepto del generador de canciones de reggaeton que se había desarrollado en una actividad anterior. Sin embargo, para esta ocasión se plantea un pequeño cambio: la tabla de palabras empleadas en la generación de canciones ya no se va a encontrar en una variable dentro del propio código, sino en un fichero en formato "JSON" al que el programa deberá acceder.

## 2. Cracker de ficheros ZIP

Se va a desarrollar una aplicación capaz de romper la contraseña de ficheros comprimidos en formato "ZIP", empleando un ataque de "fuerza bruta". Para hacer uso de esta técnica, se va a disponer de un fichero en formato "TXT" al cual se le conoce con el nombre de "diccionario", y que contiene un amplio conjunto de contraseñas (se pueden obtener algunos "diccionarios" [aquí](https://github.com/berzerk0/Probable-Wordlists)). De modo que el programa prueba una a una las contraseñas contenidas en el "diccionario", con la esperanza de que alguna pueda ser la correcta, para obtener acceso al contenido del fichero comprimido.

## 3. Acortador de URLs

Se propone desarrollar una aplicación que acorte las URLs dadas por el usuario. Por ejemplo, la dirección "https://www.reddit.com/r/Damnthatsinteresting/" podría convertirse en "https://bit.ly/3yUeWYk", haciéndola más fácil de compartir.

## 4. Lector de cuentos

La idea es desarrollar un programa de cuentacuentos para niños, el cual mediante el uso de tecnología Text to Speech, recite por voz algún cuento. Las historias estarían contenidas en ficheros "TXT" a los cuales acceda la aplicación para su lectura.

## 5. Notificaciones de Bitcoin

Se va a desarrollar una aplicación que consulte de forma periódica el precio del Bitcoin, para comprobar si hubo un cambio significativo, en cuyo caso ha de enviar una notificación a través de algún servicio como Telegram, WhatsApp, Twitter... a fin de que el usuario reciba el aviso.
