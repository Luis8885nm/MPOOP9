# Patrones de diseño
## Historia
### Los diseñadores de software  orientado a objetos querían reutilizar su código.
### Los patrones de diseño en sistemas orientados a objetos hace que estos sean más flexibles, elegantes y reutilizables, haciendo que se puedan aplicar como soluciones a problemas sin la necesidad de redescubrirlos


## ¿Qué es un patrón de diseño?

### Es una plantilla que puede aplicarse en muchas situaciones diferentes
### Los patrones de diseño orientados a objetos son descripciones de clases y objetos relacionados, los cuales están abstraídos para resolver un cierto problema de diseño general bajo cierto contexto
### Nomina, abstrae e identifica aspectos clave usados en una estructura de diseño general, de este modo será más fácil trabajar en proyectos, ya que siguiendo un patrón conservamos un orden y se evitan posibles errores o fallas dentro del mismo

### Elementos esenciales en un patrón de diseño:
#### Nombre
#### Problema
#### Solución
#### Consecuencias

## Tipos de Patrones de diseño

### Creacionales:
#### Abstraen el proceso de creación de objetos, ayudan a diseñar clases en forma independiente a como los objetos son creados, compuestos y representados
##### Factory
##### Abstract Factory
##### Builder
##### Prototype
##### Singleton

### Estructurales:
#### Tienen que ver con la forma en que las clases y los objetos son agrupados para formar grandes estructuras
#### Usan la herencia para formar interfaces o implementaciones. Los patrones estructurales de objeto describen formas de agrupar objetos para crear nuevas funcionalidades.
##### Decorator
##### Adapter
##### Facade
##### Proxy
##### Bridge
##### Virtual Proxy
##### Counting Proxy
##### Aggregate Enforcer (Supervisor Agregado)
##### Object Cache
##### Composite (Compuesto)
##### Flyweight (Peso mosca)

### De comportamiento:
#### Están relacionados con los algoritmos y con la asignación de responsabilidades entre los objetos
#### Estos no describen solo patrones de clases y de objetos, sino que describen los patrones de cómo estos se comunican.
##### Iterator
##### Visitor (Visitante)
##### Command (Comando)
##### Mediator
##### Chain of Responsibility (Cadena de responsabilidad)
##### Memento
##### Observer
##### Interpreter
##### State
##### Strategy
##### Null Object
##### Template Method
##### Object Authenticator (Objeto autenticador)
##### Common Attribute Registry -CAR-

## Clasificación de Patrones

### De diseño
#### Patrones de nivel de abstracción alto y nivel de granularidad  fino

### De arquitectura
#### Esquemas primarios en la organización de un sistema de software. 
#### Especifican una serie de subsistemas y sus responsabilidades respectivas, incluyendo tácticas y estrategias arquitectónicas para organizar las relaciones existentes entre ellos.

### Elementales (Idioms)
#### Son patrones directamente involucrados en la codificación, por lo tanto, son más simples y específicos al lenguaje.
#### Normalmente vienen incluidos como plantillas en los ambientes de desarrollo.

## Antipatrones

### Son la guía perfecta para un pésimo diseño de software
### Ejemplos de malas soluciones a problemas los cuales es importante conocerlos para evitarlos en futuros proyectos y poder identificarlos en el caso que se lleguen a presentar en el análisis de algún sistema.

## Modelo Vista Controlador (MVC)

### Consiste en tres tipos de objetos:

#### El Modelo es el objeto de aplicación.
#### la Vista es su representación en pantalla
#### El Controlador define el modo en que la interfaz reacciona a la entrada del usuario. 
#### MVC separa para incrementar la flexibilidad y reutilización.

## Síntesis en 3 Frases
### Utilizar patrones de diseño permite una mejor organización para comprender el software logrando que podamos comprenderlo y explicárselo a terceros
### Comprender lo que no es un patrón permite simplicidad y una disminución en los errores a la hora de diseñar uno
### Existen diverso tipos de patrones de diseño cuyo fin depende de lo que busque el cliente.