# Ejercicios estructura secuencial aplicando variables y tipos de datos


## Para esta guia podes optar por cualquier resolución
-------------------------------------------------------

#### A continuacion dejo resuelto el ejercicio 1 solo con javascript y html basico. Aplicar el mismo criterio para el resto de las actividades 
## Resolucion aplicando javascript
```js
let num1 = 10; 
let num2 = 20;

let suma = num1 + num2;
let prod = num1 * num2;

console.log('La suma es: ' + suma);
console.log('El producto es: ' + prod);
```

## Resolucion aplicando html, css y javascript
### Para realizar la práctica, se debe crear una carpeta por ejercicio, que contenga el html (index.html), el codigo javascript (main.js) y estilos (style.css)
#### A continuacion dejo resuelto el ejercicio 1 con html + css + js. Aplicar el mismo criterio para el resto de las actividades 

-----------------------------



```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Ejercicio 1</title>
</head>

<body>
    <h3 class="h3">SUMA y PRODUCTO</h3>
    <form action="#">
        <input type="text" id="num1" placeholder="Ingrese el numero 1" class="text">
        <br>
        <br>
        <input type="text" id="num2" placeholder="Ingrese el numero 2" class="text">
        <br>
        <br>
        <input id="button" type="submit" class="btn" Calcular>
    </form>

    <label id="suma" class="label"></label>
    <br>
    <label id="producto" class="label"></label>

    <script src="./main.js"></script>
</body>

</html>
```
```css
/*style.css*/
.text {
    background: transparent;
    border: 1px solid #0099CC;
    border-radius: 5px 5px 5px 5px;
    color: #393939;
    font-size: 12px;
    padding: 5px;
 }

 .btn {
    /* Color del texo */
    color: #0099CC;
    /* Eliminar color de fondo */
    background: transparent;
    /* Grosor del borde, estilo de línea y color */
    border: 2px solid #0099CC;
    /* Añadir esquinas curvadas */
    border-radius: 6px;

 }

 .btn:hover {
    /* Al poner el curso encima (hover) */
    background-color: #008CBA;
    color: white;
}

h3 {
    color: #6c2eb9;
    font-weight: normal;
    font-size: 20px;
    font-family: Arial;
    text-transform: uppercase;
  }
  
.label {
    color: #6c2eb9;
    font-weight: normal;
    font-size: 12px;
    font-family: Arial;
}  
```
```js
/*main.js*/
function suma(){
    //obtiene el valor del primer input y lo asigna a num1
    let num1 = document.querySelector('#num1').value;

    //obtiene el valor del segundo input y lo asigna a num2
    let num2 = document.querySelector('#num2').value;

    //Realiza los calculos
    //parseInt convierte texto a numero
    let sum = parseInt(num1)+parseInt(num2);
    let prod = parseInt(num1) * parseInt(num2);

    //selecciono los labels 
    let l1 = document.querySelector('#suma');
    let l2 = document.querySelector('#producto');

    //Muestro el resultado en los labels
    l1.innerHTML = 'La suma es: ' + sum;
    l2.innerHTML = 'El producto es: ' + prod;
   
}
//Escucho el evento click en el boton
let element = document.querySelector('#button');
element.addEventListener('click', suma);
```


1. Dados como datos dos números calcular su suma y su producto e informar los resultados.
2. Dados como datos cinco números obtener el promedio de los mismos e informar el  resultado.
3. Dados dos números enteros obtener su suma, resta, multiplicación y división.
4. Dadas las medidas de dos ángulos de un triángulo determinar la medida del tercero e informar el resultado.
5. Dado como dato el valor del lado de un cuadrado calcular su perímetro y su superficie, e informar los mismos con carteles aclaratorios.
6. Dado como dato el importe de una factura, calcular el valor correspondiente al IVA. (21% del valor de venta).
7. Calcular el sueldo de un operario conociendo la cantidad de horas que trabajó en el mes y el jornal horario.
8. Determinar el número de horas, minutos y segundos que hay en 6250 segundos.
9. Dado el importe bruto de una factura calcular el resultado de bonificarlo con un 4%. Al monto obtenido calcularle el IVA. Finalmente informar el importe bruto, el valor de la Bonificación  el importe bruto bonificado, el monto correspondiente al IVA y el importe neto resultante. 
10. Calcular cuántos pesos tiene un banco en monedas si dispone de N1 monedas de 1 peso, N2 de medio peso, N3 de un cuarto de peso, N4 de 10 centavos de peso y N5 de 5 centavos de peso.

