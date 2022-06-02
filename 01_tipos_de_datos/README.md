# Ejercicios de programación en Python: tipos de datos

## 1. Lanzador de dados

Vamos a desarrollar una aplicación que nos permita generar tiradas de dados. Queremos que sirva para todo tipo de situaciones (juegos de tablero, de roleplay, de azar, etc.), por lo que se tirarán dos dados, los cuales pueden tener cualquier número de caras que nos pida el usuario.

La aplicación tendrá el siguiente comportamiento:

- Pedirá al usuario que introduzca el número de caras que tendrán los dados.
  
- A continuación, el programa generará dos números aleatorios (uno por cada dado).
  
- Cada número estará comprendido entre 1 y "X", siendo "X" el número de caras que haya especificado el usuario.
  
- Finalmente, se mostrará el número que ha salido en cada dado.
  

> Pista: tendréis que importar un módulo llamado "random".

## 2. Inversor de textos

Vamos a desarrollar una aplicación muy simple que da la vuelta a los textos.

La aplicación tendrá el siguiente comportamiento:

- Pedirá al usuario que introduzca cualquier palabra o frase.
  
- A continuación, el programa le dará la vuelta al texto.
  
- Finalmente, se mostrará el resultado.
  

> Ejemplo: "mi mamá me mima" => "amim em ámam im".

## 3. Contador de letras y palabras

Vamos a desarrollar una aplicación que cuenta el número de letras y palabras que contiene un texto. Puede ser muy útil, por ejemplo, para comprobar si nos estamos pasando el límite de caracteres de un post de Instagram; o si estamos cumpliendo el mínimo de palabras que el profesor de lengua quiere que tenga nuestro comentario del libro que nos mandó leer en vacaciones.

La aplicación tendrá el siguiente comportamiento:

- Pedirá al usuario que introduzca cualquier palabra o frase.
  
- El programa contará cuántas letras contiene el texto.
  
- El programa contará cuántas palabras contiene el texto.
  
- Finalmente, se mostrará el total de letras y el total de palabras.
  

## 4. Traductor a "lenguaje inclusive"

En el pasado todos hemos intentado comunicarnos con feministas y "aliades", sin éxito. Estamos tan oprimidos con la heteronorma y la masculinidad tóxica que nos hemos vuelto incapaces de hablar sin ofender a otras personas. Realmente el problema lo tenemos nosotros... o lo teníamos, hasta hoy. En este proyecto vamos a desarrollar un traductor que convierta cualquier texto a lenguaje inclusivo. Estamos por romper las barreras del lenguaje patriarcal. Que tiemble la RAE.

La aplicación tendrá el siguiente comportamiento:

- Pedirá al usuario que introduzca cualquier palabra o frase.
  
- El programa sustituirá todas las letras "a" y todas las letras "o" por la letra "e".
  
- Finalmente, se mostrará el resultado.
  

> Ejemplo: "Por fin, ¡mi novio me ha pedido matrimonio!" => "Per fin, ¡mi nevie me he pedide metrimenie!" (sida).

## 5. Tu puta madre

Hay un juego que hace la gente en Twitter que consiste en tomar nombres de películas, canciones, libros, videojuegos... y cambiarles alguna parte del final por "tu puta madre". Es muy popular y los resultados son bastante cómicos.

Algunos ejemplos:

- Alicia en el País de las Maravillas => Alicia en el País de tu puta madre.
  
- En busca de la felicidad => En busca de tu puta madre.
  
- El Señor de los Anillos => El Señor de tu puta madre.
  
- El Club de la Lucha => El Club de tu puta madre.
  
- Viaje al centro de la Tierra => Viaje al centro de tu puta madre.
  

Vamos a desarrollar una aplicación que replique este mismo juego. Tendrá el siguiente comportamiento:

- Pedirá al usuario que introduzca el título de una película, serie, libro o canción, etc.
  
- El programa buscará en la cadena el lugar donde aparezca la palabra "de".
  
- El programa sustituirá el texto que haya a continuación de la palabra "de" por "tu puta madre".
  
- Finalmente, se mostrará el resultado.
  

## 6. Generador de Lorem Ipsum

El Lorem Ipsum es un texto que se usa como "placeholder" en muchos ámbitos. Entre otras cosas, se usa para dotar de contenido (temporal, de prueba) a páginas web en desarrollo. Se recomienda investigar un poco acerca del Lorem Ipsum, su historia y sus orígenes para entender mejor el contexto.

Vamos a desarrollar una aplicación que nos genere un párrafo de texto pseudo aleatorio, de una longitud determinada por el usuario, en base a un texto introducido por el mismo, para poder usar el resultado como "placeholder" cuando nos sea necesario.

La aplicación tendrá el siguiente comportamiento:

- Pedirá al usuario que introduzca un texto de muestra.
  
- Pedirá al usuario que introduzca el número de repeticiones que quiere.
  
- El programa hará que el texto quede "remezclado" o desordenado.
  
- Finalmente, mostrará el resultado multiplicado "X" veces, donde "X" es el número de repeticiones que ha determinado el usuario.
  

> Pista: tendréis que importar el módulo "random" y usar la función "shuffle". Además, deberéis aplicar casting para convertir entre tipos de datos.

## 7. La hora de tu muerte

Hay una película americana de terror llamada "La Hora de tu Muerte" o "Countdown", en la cual una aplicación maldita muestra cuál va a ser la hora de su muerte a la gente que se registra en la misma. Si los usuarios intentan cambiar su destino, palman de una forma horrible.

Inspirándonos en esta película, vamos a hacer una aplicación similar, que nos muestre el momento en el que supuestamente nos tendremos que mudar al otro barrio.

La aplicación tendrá el siguiente comportamiento:

- Generará una fecha aleatoria, siempre en el futuro. La fecha estará comprendida en un rango de entre mínimo 1'00 hora en el futuro hasta un máximo de 80 años.
  
- Finalmente, se mostrará la fecha en la que el usuario va a morir.
  

> Ejemplo: 15/04/2030 18:40.

> Pistas:
> 
> - Hay varias formas de hacer este proyecto.
>   
> - Una manera relativamente fácil es trabajar con los "timestamp". Requiere un poco de investigación por vuestra parte.
>   
> - Podéis generar un "timestamp" como un número entero aleatorio, comprendido entre el "timestamp" del momento actual, con una adición de 3600 segundos (1'00 hora) y el "timestamp" de dentro de 80 años.
>   
> - Después, podéis convertirlo a fecha usando la función "datetime.fromtimestamp()" del módulo "datetime". Con eso ya tendríais el momento de la muerte.
>   

## 8. Encriptador de mensajes secretos

¿Te imaginas poder comunicarte con alguien en chats grupales de tal forma que solo tú y esa persona privilegiada os podáis entender? En este proyecto crearemos una aplicación de cifrado con su complemento para descifrar. Por un lado tendremos la aplicación que cifra, y por el otro la que descifra. La idea es que podamos tomar un mensaje de texto y encriptarlo antes de, por ejemplo, enviarlo por WhatsApp. El mensaje que enviemos será ininteligible. Pero al otro lado, el receptor podrá desencriptarlo con la aplicación de descifrado y ver el contenido oculto.

Vamos a desarrollar una aplicación de cifrado de mensajes. Tendrá el siguiente comportamiento:

- Pedirá al usuario que introduzca el mensaje a cifrar.
  
- El programa cifrará el mensaje.
  
- Finalmente, se mostrará el mensaje ya cifrado, para que el usuario pueda copiarlo y enviarlo por chat.
  

> Pista: tendréis que importar el módulo llamado "base64" y usar la función "b64encode()".

## 9. Desencriptador de mensajes secretos

Vamos a desarrollar la otra parte del proyecto, que es la aplicación de descifrado de mensajes.

La aplicación tendrá el siguiente comportamiento:

- Pedirá al usuario que introduzca el mensaje a descifrar.
  
- El programa descifrará el mensaje.
  
- Finalmente, se mostrará el mensaje ya descifrado.
  

> Pista: de manera similar a la parte de cifrado, tendréis que importar el módulo llamado "base64", pero en este caso usaréis la función "b64decode()".

## 10. Pokédex

¿Así que quieres ser un maestro Pokémon? El profesor Oak nos ha mandado los planos del último modelo de Pokédex, que tiene acceso a una base de datos de todos los Pokémon conocidos en el mundo (1ª generación). Podemos hacer consultas sobre un Pokémon y la Pokédex nos devolverá los datos sobre el mismo. ¿Ya tienes ganas de probarla? Pues primero toca programarla.

Vamos a desarrollar una aplicación de Pokédex. Copia el siguiente fragmento a tu proyecto, no te preocupes por lo que hace el código ~~solo es un virus que te saca los leuros del banco~~. Digamos que es la forma en la que la Pokédex se conecta a Internet para obtener la información de los Pokémon.

```python
import requests, json

url = "https://raw.githubusercontent.com/" + \
      "Biuni/PokemonGO-Pokedex/master/pokedex.json"
response = requests.get(url)
pokedex_data = json.loads(response.text)["pokemon"]
```

En la variable "pokedex_data" se encuentra almacenada la información de los 151 Pokémon de la 1ª generación. Es un dato de tipo "list", que contiene elementos de tipo "dict". Es decir, es una lista de 151 elementos, y cada elemento es de tipo diccionario. Ahora bien, cada elemento de diccionario contiene pares de "clave/valor" con la información de un Pokémon, similar a esto:

- "name": "Bulbasaur"
  
- "height": "0.71 m"
  
- "weight": "6.9 kg"
  

Para entender mejor la estructura de los datos, se recomienda entrar directamente a la URL provista en la variable "url" y examinar el contenido.

El comportamiento de la aplicación será el siguiente:

- Pedirá al usuario que introduzca el número de ID del Pokémon que quiere consultar.
  
- El programa buscará al Pokémon en la lista.
  
- Finalmente, mostrará los datos del Pokémon.
  

> Pista: recuerda que en las listas se busca por índice, y el primer índice es siempre el número 0 (cero).
