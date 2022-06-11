# JavaScriptEngineCourse

V8 es un motor que nace a partir de google para mejorar el desempennio de google maps.

Actualmente V8 corre en la mayoria de los navegadores como lo son google, edge y firefox.

Hoisting solo sucede con variables y funciones

Que es el onjeto global?

    -El navegador automaticamente  crea un objeto que se llama window que es practicamente la pantalla con todas las API que el navegador necesita

Que es this?

    this una variable que se refiere a window window == this

Que  es hoisting?

    Es el proceso de JavaScript para asignar un valor undefined a una variable que fue llamada pero nunca declarada.
    En el caso de funciones estas si las ejecuta ya que JavaScriot identifica que es una funcion y que esta declarada despues.

Por buenas practicas para evitar errores se recomienda primero declarar las variables y funciones y despues mandarlas a llamar.

Parsing es la accion de acomodar el codigo con sus respectivos operadores, variable y funciones para que el motor lo pueda interpretar de mejor manera

Abstract Syntax Tree es un grafico que representa un programa

Memory Heap
Funciona como una repiza donde se va guardando el valor de las variables, este almacenamiento no se hace de manera ordenada en la memoria si no de una forma indeterminada

Call Stack
Es la forma en que JavaScript va ejecutando el codigo de forma ordenanda.

Garbage Collection
Cuando se declara una variable con un tamannio mayor y le asignamos un valor menor JavaScript desecha ese valor.

Stack Overflow
Google Chrome integro una funcion para evitar que la pila de ejecucion se sature cuando se satura la operacion de ejecuciones se produce el stack overflow

JavasScript Runtime
Al tener funciones con diferentes tiempos de ejecucion nuestra aplicacion se puede ver lenta ya que algunas tareas toman mas tiempo en ejecurtarse que otras.

Asincronia
Es la forma de ejecutar diferentes procesos a la vez un ejemplo es que mientras el motor de JavaScript esta ejecutando el codigo propio este le pasa al navegador funciones que este puede ejecutar paralelamente.

La funciones que puede ejecutar el navegador dependen unicamente de este y estas funciones ya estan pre definidas un ejemplo seria la funcion setTimeout

Lo que aprendimos en este curso fue:
    -que es el JavaScript Engine
    -que es y como funciona el V8
    -Que es el entorno y objeto global
    -hoiting y como evitarlo
    -Como funciona el JIT Compiler
    -Sincronia y Asincronia de JavaScript

JavaScript fue creado por Brandan Eich en 1995 y nace a partir de la necesidad de darle dinamismo a las paginas web que existian en ese entonces en un principio lo llamo Mocha pero en el mismo annio se mejor y se le dio el nombre de LiveScrip
