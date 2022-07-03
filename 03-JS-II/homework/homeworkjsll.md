Bucle "for"
// El bucle "for" nos sirve para repetir un mismo código muchas veces, esto dependiendo de las variables y la condición.
Este es el tipo de bucle más común que se utiliza.
Sintaxis:
for(var i = 0; i <= 5; i++) {
    código a ejecutar..
}
Ejemplo: Queremos indicar que en nuestro array, se muestren los números del 0 hasta el 5.
const array = [];
for(var i = 0; i <= 5; i++) {
    array.push(i)
}
indicaremos la palabra clave for().
Como vemos en el ejemplo, dentro de los paréntesis debemos nombrar una variable cuyo valor será el punto de partida de nuestro bucle. Iniciamos con i = 0.
Luego le indicaremos cuál será el punto en el que termina o cuantas veces debe de repetir el código, mientras que la condición sea verdadera. En este caso se repetirá mientras i sea menor o igual a 5, Sí la condición es falsa no se ejecutará el código.
Después debemos de indicar de que manera se irá incrementando con i++ o i-- (Esto es muy importante!).
Seguido de esto vienen dos corchetes dentro de los cuales irá el código a ejecutar. Como se muestra en el ejemplo..
Así se mostraría en la consola: 
[0,1,2,3,4,5].

                                                -------------------------------



* `&&`, `||`, `!`
// Son tipos de operadores logicos, los cuales son:
AND - &&
OR - ||
NOT - !

AND - && :
Sirve para comprobar más de una cosa a la vez.
Nos permite evaluar dos condiciones y nos darán un valor de verdadero o falso.
Para que se cumpla el &&, tienen que ser los dos verdaderos, si uno de los dos no se cumple dará un valor de false.
Se debe escribir de esta manera &&.

Sintaxis: function opAnd(val) {
    if(val >= 20 && val <= 50) {
        return true;
    }else {
        return false;
    }
}

OR - ||.
Es lo mismo que el operador AND solo cambia que si cualquiera de las dos expresiones es verdadera, este devolverá un valor de true.
Este debe de escribir de esta manera ||.
Sintaxis: function opOR(val) {
    if(val < 10 || val > 5) {
        return true;
    }else {
        return false;
    }
}
Si val está entre  5 y 10 devolverá true. En caso de que no sea así, devolverá false.

NOT - !.
Este cambiara el valor de false a true y viceversa.
Se escribe con el signo !.