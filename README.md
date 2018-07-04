# Space Invaders
Implementación del juego Space Invaders usando patrones de diseños, en el lenguaje de programación C++. Para este proyecto se utilizó la librería Allegro con el fin de facilitar algunas funciones del mismo. 

# Patrones de Diseño
* Un patrón de diseño es una solución general repetible a un problema común en el diseño de software.
* Es una descripción o plantilla de cómo resolver un problema que se puede utilizar en diferentes situaciones.


## Facade
#### Intención: 
* Proporcionar una interfaz unificada para un conjunto de interfaces en un subsistema. Facade define una interfaz de nivel superior que hace que el subsistema se más fácil de usar.
* Envuelve un subsistema complicado con una interfaz más simple.
#### Problema:
* El cliente necesita una interfaz simplicada para la funcionalidad general del subsistema complejo.
#### Diagrama:
![facade1](https://user-images.githubusercontent.com/38145376/42285314-d45ac424-7f74-11e8-9d61-f386dd1bdcfc.png)




## Bridge
#### Intención:
* Separa una abstracción de su implementación para que ambas puedan variar de forma independiente.
* Publicar una interfaz en una jerarquía de herencia y separar la implementación en su propia jerarquía de herencia.
#### Problema:
* Hay un problema de bloqueo en el enlace en tiempo de compilación entre la interfaz y la impleentación. La abstracción y la implementación no se pueden extender o componer independientemente.
#### Diagrama:


## Abstract Factory
#### Intención:
* Proporcionar una interfaz para crear familias de objetos relacionados o dependientes sin especificar sus clases concretas.
* Encapsulación, muchas posibles "plataformas" y la construcción de un conjunto de "productos".
#### Problema: 
* Si una aplicación debe ser portátil, debe encapsular las dependencias de la plataforma. Con demasiada frecuencia, esta encapsulación no está diseñada de antemano, y muchas declaraciones de "ifdef" comienzan a definirse demasiadas veces en todo el código.
#### Diagrama:
