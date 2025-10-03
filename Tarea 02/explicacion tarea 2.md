# Explicacion decisiones Tarea N2 - Felipe Guajardo
## Ejercecicio 1
Aqui se le da una orden al programa para que imprima determinados numeros, donde el numero inicial se escribe bajo num inicial y el final num final (pero se le agrega un +1 porque parte de cero en el conteo de la lista), entonces se usa la opcion range, porque estamos hablando de un rango de tal numero hasta el otro (inicial y final), y eso se conoce como lista, y se programa para que lo imprima (print).

## Ejercicio 2
En esta situacion se repite lo mismo que la anterior, por ende se repite lo del rango, pero no se quiere imprimir todos los numeros, sino que hay un condicional que es que sean divisibles por 6 y que ademas el resto sea 0.

Entonces, se copia lo mismo que el anterior, y se agrega "for" porque de esa lista queremos que solo se impriman ciertos numeros, entonces es la seleccion en si que se denomina (i), y posterior de a eso se entrega la condicion de tal seleccion (por eso usamos if), y como queremos el resto de tal division usamos "%" (que significa que tenga un resto del numero 6 en este caso) igual a 0 (== 0 ).

## Ejercicio 3
En este ejercicio se nos pide que el usuario ingrese dos numeros, realizar una suma y a partir de ese resultado dar por salida una respuesta clasificatoria (si el numero resultantes es menor a 200, mayor a 200 o mayor a 250)

Entonces, primero se escribe print con el mensaje que queremos entregar, que es que se ingresen los numeros, y para que el usuario pueda escribirlos se agrega un input, porque se trata de una entrada, el usuario esta dando informacion para realizar una operacion.

Luego, se ejecuta la suma bajo "sum", y para no escribir constantemente num1+num2, se iguala esa suma a otro nombre que es "X", siendo un nuevo valor.

Entonces dependiendo del resultado de la suma se agregan los condicionales y por eso se trabaja con if (si ... ) y elif que serian como un "or" en ingles. Bueno y en cada condicion se agrega la clausula de si es menor o mayor a tal cifra, y si es asi se debe imprimir tal mensaje (print). Pero para que no haya errores, se agregaron las clausulas de si X es igual a 200 o igual a 250, porque son resultados posibles y en el enunciado nunca se habla menor o igual - mayor o igual, entonces se consideraron esas dos soluciones posibles.

## Ejercicio 4
Aqui nos piden identificar la edad que ingrese el usuario (la misma logica del input en el ejercicio anterior, porque se requiere el usuario entregue los valores). Entonces dependiendo de la edad se clasifica si es mayor de edad y el gusto musical.

En caso de que el numero sea menor a 18 (menor de edad) se da la respuesta a "No eres mayor de edad".

El resto de los numeros siempre van a ser mayores de edad, y para hacerlo mas entretenido se hizo una clasificacion por rango de edades. De 18-28 les gusta la musica urbana, de 28-25 les gusta la alternativa y asi como sale en el ejercicio.

Use la misma logica de clausulas bajo if y elif que en el ejercicio anterior, pero tambien se pudo haber desarrollado de otra forma que seria bajo rangos como el uso de (xx:xx), donde las xx son laas edad, y asi ahorrarse los ">=" y los "and". Asi tambien se puso haber utilizado la palabra range (x , y).