¿Cuál es la diferencia entre un componente UI y un componente funcional en React?
R:
Componente UI: son componentes interactivos con el usuario como lo pueden ser barras de navegacion, listas, botones, entre otros.
Componentes funcionales: son los que se especializan en la logica, procesos funcionales, y matematicos.

¿Qué son las props en React y cuál es su propósito principal?
R: 
Son los argumentos que se le pasa a los componentes o funciones para que al momento de ser retornados devuelva los elementos con los que  trabajamos.

¿Qué son los children props en React y por qué no se recomienda su uso excesivo?
R//: los children prop son componentes que permiten pasar elementos o contenido entre etiquetas, ademas, generando elementos hijos en sus resultados; 
estos children props no se recomiendan usarlos de forma constante porque es complicada de leer su estructura, no es flexible a la hora de mantener la logica de programacion y tiene comportamientos inesperados a la hora de hacer actualizaciones o existan muchas condiciones. 

¿Qué es useState en React y para qué se utiliza principalmente?
R//: useState o variable de estado es un hook que nos permite utilizar variables que estan dentro de funciones afuera de las mismas para gestionar componentes funcionales antes de los hooks, su principal funcion es mantener valores actualizados a la hora de cambiarlos, esto tambien siendo aplicado a funciones con valores predefinidos.
