## polymer2-workshop

### Javascript

### Polymer 2

1. Imaginemos que se tiene un arreglo de objetos llamado personas y que cada uno de los objetos tiene 3 propiedades: nombre, apellidoPat y edad, ¿Qué pasará al ejecutar el código siguiente?

```html
<template is = "dom-repeat" items = "personas" as = "persona">
    <template is = "dom-if" if = "[[!_greaterThan(persona.edad, 18)]]">
        <p> [[persona.nombre]] [[persona.apellidoPat]] => [[persona.edad] ]</p>
    </template>
</template>
```

Ahora el código para la función _greaterThan es:
```javascript
_greaterThan(edad, value) {
    return edad > value;
}
```    
Seleccione una:

a. Se muestra un listado de todos los elementos de "personas", donde la edad es mayor a 18.

b. Muestra una lista de todos los elementos de "personas".
c. No es la forma correcta de iterar "personas", por ese motivo no muestra nada. 

d. Muestra una lista con todos los elementos de "personas", donde la edad no es mayor a 18.


2. 

### Programación Orientada a objetos 