fi.js
=====

Framework JavaScript para ficción interactiva / JavaScript framework for interactive fiction

<a href="http://baltasarq.github.io/fi-js/">Web</a>

Construcción (*build*)
----------------------

El directorio `lib/` es el que contiene el motor y un ejemplo. Todos los trabajos de ficción interactiva tendrán un archivo `index.html`, `fi.js` y `verbs.js` que son el propio motor, y un último archivo **JavaScript** (en el ejemplo, `vampiro.js`), que es el juego en sí, definiendo las localidades, objetos, personajes, etc. Finalmente, por convención en el directorio `res/` están los recursos que precise el juego.

*The `lib/` directory is the one containing the engine and a given example. Any interactive fiction pieces will have to provide the same files as provided there, i.e., `index.html`, `fi.js` and `verbs.js` being the engine itself, and also another **JavaScript** file (`vampiro.js`, in the example), being the game's definitions, such as rooms, objects, characters, etc. Finally, the resources for the game are by convention inside the `res/` subdirectory.*
