## Tipo de Datos en JavaScript

### 1 Numericos

number -(2^53 − 1) and (2^53 − 1)
```js
let velocidad = 98.5;
console.log(typeof velocidad);
```
### 2 String
```js
let userName = 'Sergio';
console.log(typeof userName);
```
### 3 Boolean
```js
let isActive = true;
console.log(typeof isActive);
```
### undefined, una variable cuyo valor aun no ha sido definido
```js
let nombre;
console.log(typeof nombre);
```
### null, el valor de nada 
```js
let edad = null;
console.log(typeof edad);
```
### BigInt (numeros muy grandes)
```js
let z = 3n ** 55n;
console.log(typeof z);
```
### Symbol--representa un identificador unico
```js
let clave = Symbol('Sym');
console.log(typeof clave);
```

### 4 array (matrices)
```js
let autos = ['Ford Mustang', 500, true];
console.log(typeof (autos));
```
### 5 object
```js
let auto = { modelo: 'Ford Mustang', potencia: 300, velocidad: 200 };
console.log(typeof auto);
```

### Copiado por referencia
```js
let x = [2, 4];

let y = x;

y.push(5);

console.log(x);
console.log(y);
```



