# SoloLearn

### Descripción genera

Complete los espacios en blanco para generar "JS is cool!" a la consola:
console
.
log
("¡JS es genial!");

Declare a variable called x, assign the value 42 to it and output it to the console.
x = 45;

console.log(x);

¿Cuál es el resultado de este código? // x = 8; x = 2; // x = 3; console.log (x);
2

Reorganizar para formar un código JavaScript válido que declare una variable y la envíe a la consola.

<scrpt>
nombre = "James"
console.log (nombre); 
</script>

### Conceptos básicos


¿Cuáles de estos nombres son aceptables para las variables de JavaScript?

primer numero 
_modulo

Complete los tipos de datos de los datos que se muestran a continuación en el campo de comentarios:
12 // número

"algún texto" // 
string


cierto // 
boolean
¿Cuál es el resultado de la expresión var1 && var2, si var1 = true y var2 = false?

falso

### Condicionales y bucles

¿Cuál es el resultado de este código? var x = 0; mientras (x <6) {x ++; } document.write (x);

6
Complete las palabras clave correctas para probar las condiciones:
switch
(día de la semana) {

  caso 1:

  caso 2:

  caso 3:

  caso 4:

  caso 5:

    document.write ("Días laborables");

    
break
;

  caso 6:

    document.write ("sábado");

    
break
;

  defecto:

    document.write ("Hoy es domingo");

    rotura;

}

Complete las palabras clave correctas para componer un bucle:
do
 {

   document.write (i);

    i ++;

}

while
 (i <10);

### Funciones

¿El siguiente código dará como resultado qué valor? prueba de función (número) {while (número <5) {número ++; } número de retorno; } alerta (prueba (2));
5

¿Cuál es el resultado de la siguiente expresión? función multNmbrs (a, b) {var c = a * b; } multNmbrs (2, 6);

Nada

Complete los nombres correspondientes para los cuadros de diálogo integrados:
prompt
 es para obtener información del usuario;

alert
 es para mostrar un mensaje en un cuadro;

Complete los espacios en blanco para calcular el máximo de los parámetros:
function max (a, b) {

  
if
(a> = b)

    regreso 
a
;

  
else


    volver b;

}


¿Cuál es la sintaxis correcta para hacer referencia a un script externo llamado "script.js"?

***<script src ="script.js">***

¿Qué alerta se mostrará en la pantalla? 

función test (a, b) {if (a> b) {return a * b; } else {return b / a; }} alerta (prueba (5, 15));

3

### OBJETO

Las propiedades de un objeto son similares a las variables; los métodos son similares a:

funciones


¿Cuál es el resultado de la siguiente expresión? var myString = "abcdef"; document.write (myString.length);
6

Complete la expresión para crear un constructor de objetos, teniendo en cuenta que "altura" y "peso" son propiedades y "calcular" es un método para el objeto dado:
function mathCalc (altura, peso) {

  this.height = 
height
;

  this.weight = 
weight
;

  this.sampleCalc = 
calculate
;

}

### Objetos centrales

Dada la matriz a continuación, complete la expresión para recibir una alerta con "manzana".
var fruit = new Array ("pera", "naranja",

"manzana", "pomelo");



alerta (frutas
[2]
);

¿Cuál es el resultado de la siguiente expresión? alerta (Math.sqrt (36));
6

Complete los espacios en blanco para mostrar los minutos actuales:
var fecha = nueva fecha ();

alerta(
date
.
get
Minutos());

¿Cuál es el resultado de este código? var arr = new Array ("a", "b", "c"); alerta (arr [1]);
b

Arrastre y suelte las opciones siguientes para recibir una alerta con el valor de la constante PI.
alert (math.PI);

### DOM y eventos

Complete los espacios en blanco para cambiar el contenido de todas las etiquetas de párrafo de la página a "SoloLearn".
var arr = 
document
.

  getElementsByTagName ("
p
");

para (var x = 0; x <longitud de arr.; x ++) 

{

   arr [
x
] .innerHTML = "SoloLearn";

}

¿Cuál es el resultado de este código?

 <div id = "prueba"> <p> algo de texto </p> </div> <script> var el = document.getElementById ("prueba"); alert (el.hasChildNodes ()); </script>
cierto


Arrastre y suelte las opciones siguientes para cambiar el color del párrafo con id = "p2" a rojo.
<script>


var d = document.


  getElementById ("p2");
b.style .color = "red";


</script>


¿Puede manejar varios eventos en el mismo elemento HTML?
sí

Complete los espacios en blanco para alertar un mensaje cuando se hace clic en el botón.

<button 
="msg()">Click me</button>

<script>

 msg() {

  alert("Hi!");

}

</script>

Complete los espacios en blanco para alertar un mensaje cuando se hace clic en el botón.
<div 
onmouseover
="alert('Hi!');">

  put the mouse pointer over me

</div>



