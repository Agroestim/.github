# Agroestim

## ¿Que es Agroestim?

**Agroestim** nacio como un proyecto de feria de ciencias al rededor del año 2016. Tenía como objetivo, permitir al usuario visualizar de forma grafica un conjunto de datos que pertenecian a diferentes estudios realizados de camapñas de multiples varientes del trigo.

El elemento principal de la aplicación fue un arbol de deciciones que permitia establecer, segun una serie de reglas y filtros, el rendimiento aproximado de una sola variedad de trigo. El nucleo del proyecto consistia en permitir a los productores de forma sencilla, acceder a un catalogo de variedades y determinar segun las condiciones de su estancia el rendimiento aproximado de su produccion.

Varios años despues de participar en la feria de ciencias, un grupo de estudiantes tomo la idea del proyecto y la llevo al mundo de las aplicaciones web y de esa forma, construir una aplicación web que contaba con las funcionalidades base del proyecto original, mejoras en la experiencia de usuario e interfaz.

### Desarrollo del proyecto

Durante el desarrollo de este nuevo proyecto mejorado, fuimos recibiendo el ascesoramiento con personas referentes del Instituto Nacional de Tecnologia Agropecuaria (INTA) el cual nos fue de punto de apoyo en los aspectos tecnicos acerca de la produccion agricola. En ese proceso, se fue descubirndo varios problemas que estaban ligados con nuestro cometido y son, hasta la actualidad un vector de ataque, los cuales estan directamente relacionados con nuestro cometido.

### Estructura del algoritmo

La estructura y funcionameinto del algoritmo de la aplicacion fue, en principio, una implementacion a mano alzada que determinaba en base a concideraciones personales, el rendimiento relativo de las variantes, y en base a ello, se exportaba una ecuación basica donde los valores incognita eran reemplazados por los valores que ingresaba el productor, estimando asi, de forma muy precaria, el rendimiento aproximado del una variante x.

### Implementacion de un estandar

Los problemas que se mencionan con anterioridad, tenia que ver con el principio de funcionamiento del algoritmo el cual no era correcto implementar de tal forma, es por ello que evaluando el proceso general implementado en la realizacion tanto de los estudios de las campañas como en los metodos utilizados para determinar los resultados de los estudios, se determinó que es necesario implementar una serie de medidas y operaciones estandarizadas que aseguren la correcta relacion entre lo probabilistico y lo real.

### En la actualidad

Actualmente se encuentra en desarrollo **Agrovar** la cual implementa varias soluciones a los anteriores problemas mediante una aplicación web multiplataforma la cual posee de una API privada exclusiva para el cliente web.
