# platzi-projects

### Conceptos basicos 

 Una de las cosas mas esenciales es tener el conocimiento de que existen tres formas o herramientas que hacen funcionar al internte estas son : HTML, CSS y JavaScript 

### definiciones de HTML, CSS Y JS.

 HTML es el lenguaje donde se define la información o el contenido del documento.

 CSS es el lenguaje donde se especifica el diseño del documento, maneja todo lo relacionado con la parte visual. 

 JavaScript, es el lenguaje que hace que todo sea interactivo y que nos permite crear sitios web El formato de los archivos es .js. Además, es el lenguaje de programación que interpreta el navegador.

 Estos conceptos definen los sistios webs los  que ayudan y protagonizan un papel muy importante.



### variables y arreglos 

Cuando nos referimos al termino variable esto quiere decir que es un elemento que se emplea para almacenar y hacer referencia a otro valor.

Los arreglos son un conjunto de datos ordenados por posiciones y todos asociados en una sola variable.


### mi primer alerta

Es una de las cosas mas basixas en JS, alert es basicamente una funcion, se pone dentro de parentesis por el simple hecho de que las funciones funcionan con parametros y se le pone entre comillas porque es un *string*.

asi se hace una alerta *alert("Hola mama, estoy programando");*

### variables y operadores matematicos

la palabra clave *var* para declara variables, como sabemos con las variables se pueden hacer operaciones un claro ejemplo los podemos ver aqui:

si declaramos las varianles:

var x = 2;

var y = 1;

var z = x + y;

si llammamos la variable z no va a dar como resultado z=3, porque al sumar x + y = 3.

un ejemplo de una alerta con strings y variables es este:

alert("El valor de z es" + z)

En este ejemplo podemos ver domo se usas los operadores de concatenacion para unir datos tipos strings, como resultado esto nos dara *El valor de z es 3*

### obteniendo datos del usuario 

  * La consola nos sirve para saber el estado de las variables
 

* Cuando tienen un valor en comillas("") es un texto
 

* Puedes usar la función prompt para recibir datos del usuario.
 

* Concatenar es unir cadenas de texto a variables

### Flujo y condicionales 

Creemos primero para resolver los problemas, para esto debemos aprender a usar condicionales, para escribir una condicional se usa una palabra clave llamada if.
* if (planeta == 1)

{

// Código si la condición se cumple

}

else

{

// Código si la condición no se cumple

}

Si quisiéramos tener tener varias condiciones podemos escribir nuevas condiciones con la palabra reservada else if

if (planeta == 1)

{

// Código si la condición se cumple

}

else if (planeta == 2)

{

// Código si la segunda condición se cumple

}

else

{

// Código si las condiciones no se cumplen

}


### Definiendo nuestro lugar de trabajo web.

* navigator: El objeto que contiene las funciones del navegador, también te permite acceder también al sistema operativo como el gps, guardar datos en el disco duro, etc.

 

* window: El objeto que maneja cada una de las pestañas.

 

* document: El objeto que contiene todo lo que vemos dentro de nuestra página

 

En aplicaciones web tenemos un concepto llamado DOM (Document Object Model) es la forma en que internamente el navegador organiza todo el HTML dentro de una estructura de árbol

### Dibujando en el DOM

Es importante saber: 

* ID es el identificador con el que podemos encontrar etiquetas con JavaScript, los nombres siguen las mismas reglas que las variables
 

 * Puedes obtener un elemento con su id buscándolo con document.getElementById('nombre_id');

 ### Funciones en JS


 La funciones son una herramienta que nos permite escribir código que vamos a re-usar múltiples veces

 * Puedes escribir una función en JavaScript así:

 

function nombreFuncion(parametros) {

 //Código que ejecuta la función

}

### ciclos 

Los ciclos son piezas de código que se repiten hasta que se cumple una condición, existen varios ciclos 

* for 
* while 

### Eventos y Formularios en HTML y JavaScript conceptos.

Los eventos son funciones que suceden cuando algo ocurre,  sucesos cómo un click, pulsar una tecla, colocar el mouse sobre un botón, etc.

* Cuando queremos enviar información a un servidor podemos usar un formularios

* En JavaScript puedes agregar un manejador de eventos con element.addEventListener('event', function)

### Detectar eventos del teclado con JavaScript

Debemos recordar que :


* Un programador divide los grandes problemas en problemas más pequeños.

* Todo manejador de eventos devuelve un objeto con los detalles del evento.


### Funciones matemáticas y números aleatorios en JavaScript

Math.floor() devuelve el número entero por debajo de los decimales.

Math.ceil() devuelve el siguiente número entero arriba de los decimales

Math.random() devuelve un número aleatorio de 0 a 0.999..

### División, módulo y residuo en JavaScript

Para calcular el módulo puedes usar %
 

Los programas dividen los programas complejos en problemas pequeños
 

La operación lógica and (y) se escribe en JavaScript con &&

### Clases y Arrays en JavaScript

Los arrays se forman en Javascript a través de una clase, de la siguiente forma: var <nombre_array> = new Array(<longitud>); Vamos a realizar un ejemplo en el que crearemos un array de 3 posiciones y le asignaremos un valor a cada posición del array.

* clases son la definición de los objetos

### Implementación del Cajero Automático

* Los programadores dividen problemas grandes en varios pequeños.
 

* Prueba frecuentemente que el código escrito funciona

### Modelo Cliente/Servidor

Las tecnologías utilizadas en aplicaciones web son:

Bases de datos, MySQL es una base de datos relacionales y MongoDB es una base de datos no relacional

Backend, existen muchos lenguajes que puedes usar cómo Python, Ruby, JavaScript

Servidores, existen tecnologías como NGINX, Apache, Node

Frontend, son las tecnologías que corren en el navegador, HTML, CSS y JavaScript

A un grupo de tecnologías se les conoce como Stack

Cliente: Es el navegador que abre tu archivo HTML o JS

COMPLEMENTACION BASES DE DATOS:
-Backend (Servidor) -Frontend(Navegador)

BASES DE DATOS:
-MySQL (Mas común) -MongoDB

BACKEND COMPLEMENTADO:
-php -python -nodeJS
RECUERDA
El Backend actúa como contraseña de los datos de los demás usuarios, pero si el Frontend no tiene Backend los datos de los demas usuarios estarán expuestos a accederse.

FRONTEND:
-Html -CSS -JS

STACK LAMP (Grupo de tecnologías):
-Apache -MySQL -php

HEADERS HTTP: permiten al cliente y al servidor enviar información adicional junto a una petición o respuesta.

METODOS PARA CONECTAR HTML A JS (MC):
++(MC)- GET : Utiliza variables o etiquetas js en la

A un grupo de tecnologías se les conoce como Stack.

Recuerda:

Si tuvieras un código en el Frontend que se conectara a una base de datos, esta seria visible para todos.