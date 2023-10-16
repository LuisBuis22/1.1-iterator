# Patrón de diseño: Iterator
---
El patrón de diseño Iterator consiste en recorrer una estructura de datos sin que sea necesario conocer su estructura interna

Iterator es un patron de dieseño de comportamiento muy útil cuando tratamos con estructuras de datos complejas ya que nos permite recorrer todos sus elementos por medio de un iterador.

Un iterador es un objeto que sigue una ruta establecida y da acceso a elementos de datos de una colección y devuelve un valor al terminar.

El patrón de dieseño Iterator tiene los siguientes elementos:

- Client --> Actor que utiliza el patrón Iterator
- Aggregate --> Define la estructura de las clases que pueden ser iteradas
- Concrete Aggregate --> Contiene la estructura de datos que deseamos iterar
- Iterator --> Define la estructura de los iteradores a través de métodos.
- Concrete Iterator --> Implementar un iterador concreto
---
El patrón de diseño iterator se utiliza cuando la colección en la que se trabaja tiene una estructura de datos compleja a nivel interno y se quiere ocultar su complejidad a los clientes.

De esta manera, se encapsula los detalles de la colección en una estructura de datos compleja y se le proporcioa al cliente varios métodos simples que le permiten acceder a los elementos de la colección.

Al mismo tiempo, se utiliza para reducir la duplicación en el código de recorrido a lo largo de tu aplicación.