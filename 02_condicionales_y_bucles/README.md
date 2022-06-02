# Ejercicios de programación en Python: condicionales y bucles

## 1. Adivina el número

En este sencillo juego, la máquina pensará en un número que tendremos que adivinar, poniendo a prueba nuestra capacidad para leer la mente. En cada intento nos dará una pista: si el número es mayor o menor. Finalmente, cuando acertemos, nos dirá en cuántos intentos lo hicimos.

La aplicación tendrá el siguiente comportamiento:

- Mostrará por pantalla las reglas del juego.

- El programa generará un número aleatorio comprendido entre 1 y 100.

- Se pedirá al usuario que intente adivinar el número. Se recogerá la entrada de dicho número por teclado.

- El programa incrementará en +1 el número de intentos.

- Si el número introducido es mayor al que generó el programa, se mostrará un mensaje que diga "Fallaste: el número que he pensado es menor"; si es menor, se mostrará un mensaje que diga "Fallaste: el número que he pensado es mayor".

- Mientras no se acierte el número, el programa seguirá repitiendo el proceso.

- Si el número introducido es igual al que generó el programa, se mostrará un mensaje que diga "Enhorabuena: lo has adivinado".

- Finalmente, se mostrará el número de intentos que hizo el usuario.

> Pista: en este ejercicio tendréis que usar condicionales y bucles. Además, como ya sabéis, para generar un número aleatorio podéis recurrir a las funciones del módulo "random".

## 2. Piedra - Papel - Tijeras

Vamos a desarrollar el clásico juego de "Piedra - Papel - Tijeras". La aplicación tendrá el siguiente comportamiento:

- Mostrará por pantalla las reglas del juego.

- Se preguntará al usuario cuántas rondas quiere jugar.

- El programa generará aleatoriamente la mano que va a sacar (piedra, papel o tijeras).

- Se pedirá al usuario que elija la mano que va a sacar.

- El programa averiguará qué mano gana a cual, y sumará +1 a la puntuación del ganador.

- Se mostrará por pantalla la puntuación del jugador y la máquina.

- El proceso se repetirá hasta completar todas las rondas.

- Finalmente, se mostrará por pantalla quién fue el ganador, o si hubo empate.

## 3. Generador de canciones de reggaeton

Existe una leyenda infame que dice que se pueden crear canciones de reggaeton simplemente usando una tabla, en la cual hay combinaciones de palabras "sabrosas". Seleccionando estas palabras de la tabla al azar, es posible formar el estribillo y las estrofas para componer un temazo latino.

Vamos a dar el pelotazo desarrollando un programa capaz de generar letras de canciones de manera automatizada. Para ello, usaremos la mencionada tabla:

<div>
    <table>
        <tr>
            <th>
                A
            </th>
            <th>
                B
            </th>
            <th>
                C
            </th>
            <th>
                D
            </th>
            <th>
                E
            </th>
            <th>
                F
            </th>
        </tr>
        <tr>
            <td>
                Mami
            </td>
            <td>
                Yo quiero
            </td>
            <td>
                Encendelte
            </td>
            <td>
                Suave
            </td>
            <td>
                Hasta que salga el sol
            </td>
            <td>
                Sin paral
            </td>
        </tr>
        <tr>
            <td>
                Bebé
            </td>
            <td>
                Yo puedo
            </td>
            <td>
                Amalte
            </td>
            <td>
                Lento
            </td>
            <td>
                Toda la noche
            </td>
            <td>
                Sin compromiso
            </td>
        </tr>
        <tr>
            <td>
                Prinsesa
            </td>
            <td>
                Yo vine a
            </td>
            <td>
                Perrialte
            </td>
            <td>
                Rápido
            </td>
            <td>
                Hasta el amanesel
            </td>
            <td>
                Feis to feis
            </td>
        </tr>
        <tr>
            <td>
                Mamasita
            </td>
            <td>
                Voy a
            </td>
            <td>
                Jugal
            </td>
            <td>
                Fuelte
            </td>
            <td>
                Todo el día
            </td>
            <td>
                Sin miedo
            </td>
        </tr>
    </table>
</div>

La aplicación tendrá el siguiente comportamiento:

- Generará dos versos usando todas las columnas de la tabla.

- Generará un estribillo usando las columnas de la tabla desde la "B" hasta la "D".

- El programa mostrará por pantalla los versos y luego el estribillo.

> Pista: usa listas para almacenar las palabras de cada columna. Accede a los índices de manera aleatoria para ir armando cada verso de la canción.

> Ejemplo:
> 
> Mami yo vine a jugal lento hasta que salga el sol sin paral.
> 
> Prinsesa yo quiero amalte suave toda la noche sin compromiso.
> 
> Yo puedo encendelte rápido.
> 
> Yo vine a perrialte fuelte.

> Recursos:
> 
> - [Cómo componer reggaeton en tan solo 30 segundos](https://www.youtube.com/watch?v=6iOlB0QLy84).

## 4. Aventura basada en texto

Vamos a desarrollar un juego siguiendo un concepto similar al de Visual Novel, pero sin la parte visual (de momento).

En este ejercicio habrá libertad casi total. Será una aventura basada en texto. La historia puede ser todo lo larga o corta que queráis hacerla. Solo tened en cuenta que deberían darse ramificaciones en la narrativa, tomas de decisiones, así como disponer de al menos un par de finales alternativos.

> Ejemplos:
> 
> - [Off Day](https://viv-url.itch.io/off-day).
> 
> - [Silver Thread](https://puchidesign.itch.io/silver-thread).
> 
> - [Posey Picks Bus Stop](https://derekachoy.itch.io/posey-picks-bus-stop).

## 5. Pomodoro (temporizador)

La Técnica Pomodoro es un método de administración del tiempo para incrementar la productividad. Se usa un temporizador para dividir el tiempo en intervalos llamados "pomodoros" y "descansos". La duración de cada "intervalo" suele ser de 25 minutos para los pomodoros y 5 minutos para los descansos.

Vamos a desarrollar una aplicación de temporizador Pomodoro. La aplicación tendrá el siguiente comportamiento:

- Mostrará una breve explicación del método Pomodoro por pantalla.

- Se pedirá al usuario que introduzca el número de intervalos que quiere gestionar.

- Mostrará una notificación advirtiendo que se inicia un nuevo pomodoro.

- El programa mostrará una notificación pasados 25 minutos para avisar de que transcurrió un pomodoro.

- Mostrará una notificación advirtiendo que toca hacer un descanso.

- Después de un pomodoro, el programa mostrará una notificación pasados 5 minutos para avisar de que transcurrió el descanso.

- El proceso se repetirá tantas veces como intervalos haya pedido el usuario.

> Pista: tendréis que usar la función "sleep" del módulo "time" para el temporizador.
> 
> Para la notificación, dependiendo de cuál sea vuestro sistema operativo, debéis usar la función "system" del módulo "os" para generar la notificación en la bandeja del sistema.

> Recursos:
> 
> - [Notificaciones en Mac OS y Linux con Python](https://www.pythongasm.com/desktop-notifications-with-python/).
> 
> - [Notificaciones en Windows con Python](https://stackoverflow.com/questions/29014944/send-a-message-box-to-a-list-of-remote-pc).

## 6. Tres en raya

Vamos a desarrollar un clásico juego del tres en raya que permita al usuario jugar contra la máquina. Este proyecto nos permitirá aprender a implementar tableros de juegos de mesa. Para el caso que nos ocupa, haremos un tablero que posea unas dimensiones de 3x3 casillas.

La aplicación tendrá el siguiente comportamiento:

- El usuario jugará con el símbolo "X", por lo tanto la máquina tendrá el "O".

- La máquina empieza la partida.

- La máquina coloca ficha en alguna posición libre del tablero, de forma aleatoria.

- Se comprueba si la máquina ha hecho tres en raya. En caso afirmativo, termina el juego mostrando un mensaje que diga que el usuario ha perdido. En caso negativo, continúa el juego.

- A continuación, se le pregunta al usuario en qué fila quiere colocar su ficha. La posición no puede ser menor a 1 ni mayor a 3. Si se incumplen las condiciones, se volverá a pedir el dato.

- A continuación, se le pregunta al usuario en qué columna quiere colocar su ficha. La posición no puede ser menor a 1 ni mayor a 3. Si se incumplen las condiciones, se volverá a pedir el dato.

- Se comprueba si la posición "X, Y" determinada por el usuario está libre o no. En caso de estar libre, se coloca la ficha. En caso de estar ya ocupada, se vuelve a pedir posición de fila y columna.

- Se comprueba si el usuario ha hecho tres en raya. En caso afirmativo, termina el juego mostrando un mensaje que diga que el usuario ha ganado. En caso negativo, continúa el juego.

- Se repite el proceso hasta que haya un ganador.

> Pista: para implementar un tablero tendréis que usar una "lista de listas", o lo que se conoce también como "array bidimensional".

## 7. Super Simon

Vamos a desarrollar un juego de memoria en el que tendremos que repetir secuencias, al estilo del clásico Super Simon, de Hasbro. Solo que, en vez de colores, el usuario deberá memorizar series de números.

La aplicación tendrá el siguiente comportamiento:

- Se generará un número aleatorio, entre 1 y 9, el cual se añadirá a una lista.

- Se mostrará la lista por pantalla.

- El usuario dispondrá de un tiempo de 3 segundos para memorizar la serie antes de que desaparezca.

- El programa pedirá al usuario que introduzca los elementos de la serie separados por coma.

- A continuación, se comparará si la serie introducida por el usuario es la misma que la serie generada por la máquina. Si no es igual, se muestra un mensaje diciendo que el usuario ha perdido. En caso contrario, se incrementa el contador de aciertos.

- El proceso se repite hasta que el usuario pierda.

- Finalmente, se muestra cuántas rondas aguantó el usuario.

> Pista: tendréis que usar la función "sleep" del módulo "time" y la función "system" del módulo "os" para hacer que la serie mostrada desaparezca a los 3 segundos.

> Recursos:
> 
> - [Cómo limpiar la consola en Python](https://www.tutorialspoint.com/how-to-clear-python-shell).

## 8. Generador de contraseñas

La seguridad informática es una materia de gran importancia hoy en día. La información que almacenamos es muy valiosa, y siempre hay piratas al acecho con fines maliciosos, tratando de dar algún golpe. En muchos casos, lo único que separa a los malhechores de su objetivo es tan solo una contraseña. Por eso resulta vital que las contraseñas que usemos sean siempre seguras y variadas.

Para hacer posible mantener altos nuestros estándares de seguridad, vamos a desarrollar un generador de contraseñas seguras. La aplicación tendrá el siguiente comportamiento:

- Se preguntará al usuario cuántos números debería contener la contraseña. El número introducido no puede ser menor a 1. Se volverá a pedir el dato mientras se incumpla la condición.

- Se preguntará al usuario cuántos símbolos debería contener la contraseña. El número introducido no puede ser menor a 1. Se volverá a pedir el dato mientras se incumpla la condición.

- Se preguntará al usuario cuántas mayúsculas debería contener la contraseña. El número introducido no puede ser menor a 1. Se volverá a pedir el dato mientras se incumpla la condición.

- Se preguntará al usuario cuántas minúsculas debería contener la contraseña. El número introducido no puede ser menor a 1. Se volverá a pedir el dato mientras se incumpla la condición.

- Si la suma de los datos anteriores es menor a 12, se le mostrará al usuario un mensaje diciendo que la longitud de la contraseña es insegura, explicando que el total de caracteres debe ser mayor a 12. Se volverán a pedir todos los datos al usuario mientras se incumpla la condición.

- El programa generará la contraseña.

- Finalmente, se mostrará por pantalla la contraseña generada.

> Pista: una de las muchas formas de realizar el proyecto sería añadir a una variable un bloque de X números aleatorios, otro bloque de X símbolos aleatorios, otro bloque de X mayúsculas y otro de X minúsculas aleatorias, según lo solicitado por el usuario. Finalmente, se aplica la función "shuffle" al conjunto para desordenarlo, creando así una contraseña totalmente aleatoria.

## 9. Traductor a Pig Latin

Vamos a desarrollar un traductor a Pig Latin. El Pig Latin es un "lenguaje" de broma utilizado como idioma secreto en niños de países de habla inglesa.

Sus reglas son simples:

- Si la palabra empieza en vocal, se deberá agregar "way" al final de la misma. Ejemplo: "animal" => "animal" + "way" => "animalway".

- Si la palabra comienza en consonante, se quita la primera letra y se añade al final de la palabra. Finalmente, se agrega "ay" a la misma. Ejemplo: "sandía" => "andía" + "s" + "ay" => "andíasay".

La aplicación tendrá el siguiente comportamiento:

- Pedirá al usuario que introduzca cualquier palabra o frase.

- El programa partirá el texto en palabras separadas y las almacenará en una lista.

- Recorriendo los elementos de la lista, el programa "traducirá" una a una las palabras a Pig Latin, aplicando las reglas antes descritas.

- Terminado el proceso de traducción, se volverán a unir las palabras en un string.

- Finalmente, se mostrará el resultado de la traducción por pantalla.

> Ejemplo:
> 
> "Confía en el tiempo, que suele dar dulces salidas a muchas amargas dificultades".
> 
> Se traduce a:
> 
> "Onfíacay enway elway iempotay, ueqay uelesay arday ulcesday alidassay away uchasmay amargasway ificultadesday".

## 10. Idle Hero

Desde hace años están muy de moda los videojuegos del género "idle". Básicamente, son "juegos" en los que no juegas a nada en absoluto. Algo inaudito, sin duda. ¿Pero quiénes somos nosotros para juzgar al cliente? Obedeciendo la demanda del mercado, vamos a desarrollar un juego tipo "idle" RPG en el que un héroe avance por el mundo derrotando enemigos, encontrando items y subiendo niveles, siendo guiado mediante eventos aleatorios. Hay libertad total para escoger la temática del mundo del juego.

La aplicación tendrá el siguiente comportamiento:

- Mostrará por pantalla un mensaje introductorio.

- Pedirá al usuario que introduzca un nombre y una clase para el personaje.

- Comienza el viaje.

- Se muestra el número de días que el héroe lleva en la aventura (empezando en 1).

- El héroe se encuentra con algún tipo de evento aleatorio (explorar una mazmorra, luchar contra un enemigo, ir a cumplir una "quest", etc.).

- Transcurrido un tiempo en segundos, el héroe completa el evento exitosamente, recibiendo una recompensa aleatoria en oro y puntos de experiencia. Además, existe la posibilidad de que reciba o no un item aleatorio (armas, piezas de armadura, pociones, grimorios, etc.).

- Cuando la experiencia del personaje supere el valor de 100, se incrementará su nivel en +1 y el contador de experiencia se reiniciará a 0 (cero). Además, los "stats" del héroe aumentarán de forma aleatoria.

- Si hubo subida de nivel, se mostrarán los nuevos "stats" del personaje.

- Al final de la jornada, se descontará una cantidad aleatoria de oro a los fondos del héroe, para representar los costes de la vida (comida, alojamiento, ropa, etc.).

- Se incrementa en +1 el número de días en la aventura.

- Se repite el proceso indefinidamente.

> Pista: este proyecto involucra la suma y culminación de todos los conocimientos que habéis adquirido hasta ahora.

> Ejemplos:
> 
> - [Idle Quest](https://play.google.com/store/apps/details?id=com.topcog.idlequest.android).
> 
> - [The Idle RPG](https://www.youtube.com/watch?v=VzzfyukYCuo).
