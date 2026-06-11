# Comentarios resolución Tarea 02

En el segundo problema, empiezo con un rango de números (de 1 a 101, para que incluya al 100) y se indica en el código que en caso de (if) que el número, al dividirse por 10 resulte 0, imprimir Bip Bip y lo mismo, pero con elif, que simboliza una segunda condicional, indicando imprimir Bip para los números que divididos por 5 den 0. 
Esto es bastante simple gracias al operador que incluyeron las profesoras a modo de ayuda:  % permite obtener el resto de una división, así con el resultado en 0 sabemos cuáles son divisibles por 5 y por 0.  

Para el tercer problema, se empieza indicando las variables que se sumarán, definiendo que los puntajes son insertados y el mensaje que debe aparecer junto a la opción de escribir entre comillas. Luego, se define a “suma puntajes” como la adición de los números ingresados anteriormente y se condicionan las impresiones según los resultados de la suma con el mismo mecanismo del primer problema; if, elif y else para referirse al resto de opciones no incluidas en if ni elif. 

Por último, para el cuarto problema se necesitaba algo un poco más complejo pues, aunque se crucen varias variables y haya varias opciones de respuesta  

Se empieza con la definición de los datos que se necesitan ingresar para dar imprimir resultados; la edad, si le gusta la música y si le gusta bailar.  

En los dos últimos casos, se indica en el texto instructivo (sí/no) para unificar las opciones de respuesta.  El lower(), que fue parte de ayuda de Gemini, entendí que es para transformar los caracteres de la respuesta a minúsculas de forma que puede procesar uniformemente las variaciones posibles en el typeo de si o no. 

Luego, sabemos que un signo igual (=) sirve para asignar valores, pero dos (==) para comparar. Por ende, con la tercera parte se define que, si es que, en el cuadro de texto, hay un “sí”, esa respuesta equivale a que “Le gusta bailar” o “Le gusta música”. 

Con esa definición a partir de las respuestas de la primera parte, se puede usar “and” y “not” para relacionar las variables y asignar el texto a imprimir. 