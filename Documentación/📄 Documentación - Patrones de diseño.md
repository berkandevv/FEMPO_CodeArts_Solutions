![Image](https://github.com/user-attachments/assets/8993c470-ef5b-4d2c-9af4-7362a4e2a7d7)

# Patrones de Diseño

## Historia de los patrones de diseño

Los patrones de diseño no son conceptos complejos, sino soluciones recurrentes a problemas comunes en el diseño orientado a objetos. Surgen cuando una solución se repite en varios proyectos, lo que lleva a darle un nombre y explicarla detalladamente.

El concepto de patrones fue introducido por **Christopher Alexander** en *El lenguaje de patrones*, donde los patrones se usaban para diseñar entornos urbanos. Más tarde, **Erich Gamma**, **John Vlissides**, **Ralph Johnson** y **Richard Helm** aplicaron esta idea a la programación con su libro *Patrones de diseño* (1995), que presentó 23 patrones para problemas comunes en el diseño orientado a objetos. Este libro, conocido como el "**GoF**" (de la "gang of four"), se convirtió en un éxito.

Desde entonces, se han creado muchos otros patrones de diseño, y la metodología del patrón se ha extendido a otros campos de la programación.

---

## ¿Qué es un patrón de diseño?

Un patrón de diseño es una solución estándar a problemas comunes en el desarrollo de software. Se trata de un concepto general, no de un fragmento específico de código, y se personaliza para resolver problemas recurrentes en un programa. A diferencia de un algoritmo, que define pasos concretos para lograr un objetivo, un patrón describe una solución de alto nivel que puede adaptarse a diferentes contextos y programas.

Los patrones se describen formalmente e incluyen detalles como:

- **El propósito**: Explica brevemente el problema y la solución.
- **La motivación**: Explicación más detallada del problema y la solución.
- **La estructura de clases**: Muestra las partes del patrón y cómo se relacionan entre sí.
- **Ejemplo de código**: Facilita la comprensión de la idea detrás del patrón.

Además, algunos catálogos de patrones incluyen:

- **Aplicabilidad**: En qué situaciones es útil el patrón.
- **Pasos de implementación**: Guía para aplicar el patrón.
- **Relaciones con otros patrones**: Cómo se conecta con otros patrones de diseño.

---

## Clasificación de los patrones

Los patrones de diseño varían en complejidad, detalle y aplicabilidad. Se pueden comparar con la construcción de carreteras: algunos patrones son simples, como instalar semáforos, y otros más complejos, como crear un intercambiador con pasajes subterráneos.

- **Idioms**: Son los patrones más básicos y de bajo nivel, generalmente aplicables a un solo lenguaje de programación.
- **Patrones de arquitectura**: Son los patrones más universales y de alto nivel, útiles para diseñar la arquitectura de una aplicación completa y aplicables en diversos lenguajes.

Los patrones se clasifican según su propósito en tres grupos:

1. **Patrones creacionales**: Facilitan la creación de objetos, aumentando la flexibilidad y reutilización del código.
2. **Patrones estructurales**: Enseñan cómo organizar objetos y clases en estructuras más grandes sin perder flexibilidad ni eficiencia.
3. **Patrones de comportamiento**: Se enfocan en la comunicación efectiva y la asignación de responsabilidades entre objetos.

---

### Patrones Creacionales

---

Estos patrones se encargan de los mecanismos de creación de objetos, mejorando la flexibilidad y reutilización del código.

1. **Factory Method**: Define una interfaz para la creación de objetos en una superclase, permitiendo que las subclases cambien el tipo de objetos creados.
2. **Abstract Factory**: Permite la creación de familias de objetos relacionados sin especificar sus clases concretas.
3. **Builder**: Facilita la construcción de objetos complejos paso a paso, permitiendo la creación de distintos tipos de objetos con el mismo código.
4. **Prototype**: Permite la creación de nuevos objetos mediante la clonación de objetos existentes.
5. **Singleton**: Asegura que una clase tenga solo una instancia y proporciona un punto de acceso global a ella.

### Patrones Estructurales

---

Estos patrones tratan sobre la organización y ensamblaje de clases y objetos en estructuras más complejas.

1. **Adapter**: Permite que objetos con interfaces incompatibles colaboren.
2. **Bridge**: Separa la abstracción y la implementación de una clase, permitiendo que ambas evolucionen de forma independiente.
3. **Composite**: Permite componer objetos en estructuras de árbol y tratarlas como objetos individuales.
4. **Decorator**: Añade funcionalidades a un objeto colocando este objeto dentro de objetos decoradores.
5. **Facade**: Proporciona una interfaz simplificada a un conjunto de clases complejas.
6. **Flyweight**: Optimiza el uso de la memoria compartiendo partes comunes del estado entre objetos.
7. **Proxy**: Proporciona un sustituto o marcador de posición para otro objeto, controlando el acceso al objeto original.

### Patrones de Comportamiento

---

Se centran en cómo se comunican los objetos y en la asignación de responsabilidades entre ellos.

1. **Chain of Responsibility**: Permite pasar solicitudes a lo largo de una cadena de manejadores, donde cada uno decide si procesar la solicitud o pasarla al siguiente.
2. **Command**: Convierte una solicitud en un objeto que contiene toda la información de la misma, permitiendo la parametrización de métodos con diferentes solicitudes.
3. **Iterator**: Permite recorrer los elementos de una colección sin exponer su representación subyacente.
4. **Mediator**: Reduce las dependencias entre objetos, haciendo que colaboren solo a través de un objeto mediador.
5. **Memento**: Guarda y restaura el estado de un objeto sin revelar sus detalles de implementación.
6. **Observer**: Permite que un objeto notifique a otros objetos sobre eventos o cambios en su estado.
7. **State**: Cambia el comportamiento de un objeto según su estado interno, haciendo que parezca que cambia de clase.
8. **Strategy**: Define una familia de algoritmos y los hace intercambiables, permitiendo cambiar el algoritmo utilizado en tiempo de ejecución.
9. **Template Method**: Define el esqueleto de un algoritmo en una clase base, permitiendo que las subclases sobrescriban pasos sin modificar la estructura.
10. **Visitor**: Permite separar los algoritmos de los objetos sobre los que operan, haciendo que el algoritmo pueda añadirse sin modificar los objetos.
