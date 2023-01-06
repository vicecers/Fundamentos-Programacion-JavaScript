## Concepto de variable

Las variables son espacios de memoria en donde podemos guardar los datos que generamos al momento de ejecutar el programa. 
Se llaman así por el simple hecho de que pueden variar de acuerdo con lo que el usuario ingrese cada vez que ejecute el programa. 
Hay que tener en cuenta que en lenguajes de programación como "C", deben ser declaradas antes de utilizarlas. 


### A. Uso de ***var*** ***let*** y ***const***

```js
// 1. var y let se pueden declarar sin iniciar;
 var nombre;
 let precio;
 console.log(nombre);
 console.log(precio);
```
```js
// 2. var se puede re declarar
 var nombre = 'Felix';
 console.log(nombre);
 var nombre = 'Jane';
 console.log(nombre);
```
```js
// 3. let no se puede declarar de nuevo;
let precio = 15.40;
//let perro = 5.20; da error
console.log(precio);
precio = 20.52;
console.log(precio);
```
```js
// 4 const no se puede declarar sin iniciar
// const direccion; //da error
const direccion = 'avenida Paseos';
console.log(direccion);
```
```js

//5 const no se puede reasignar
// direccion = 'avenida Principal'; //da error
// console.log(direccion);
```
```js
//6 scope (alcance)
// var es visible en la funcion donde se declaro o global
//let y const son visibles en el bloque donde se declararon o globales
```

###  B. Reglas para nombrar Variables
```js
//1. No se puede usar palabras reservadas (function, var, for, while, etc.)

//2. No pueden empezar con un dígito

// let 2x = 6;
```
```js
    //3. Pueden empezar con una letra, guión bajo o $ 
    let $car = 'ford mustang';
    console.log($car);
```
```js
   //4. Para nombres complejos se usa notación de camello:
   // let userName = 'Juan';
```
### C.  Tipo de Datos en JavaScript



