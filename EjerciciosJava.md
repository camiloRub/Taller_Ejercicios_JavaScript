# Taller de JavaScript

## Participantes

1. Esteban Bedoya
2. Camilo Rubiano 

## Ejercicios Pares

## Ejercicio #1

```javascript
var nombre = prompt("ingresar el nombre");
console.log("ahora estas en la matrix " + nombre);
```
![I1](https://github.com/camiloRub/Taller_Ejercicios_JavaScript/blob/main/Imagenes/Ejercicio1png.png)

## Ejercicio #3

```javascript
var numero1 = prompt("ingrese el primer numero: ");
var numero2 = prompt("ingrese el segundo numero: ");
var suma = Number(numero1)+ Number(numero2);
console.log("Suman: " + suma);
var numero3 = prompt("ingrese el tercer numero: ");
var multiplicacion = suma * Number(numero3);
console.log("Multiplicacion de la suma por el ultimos numero: " + multiplicacion);
```
![i1](https://github.com/camiloRub/Taller_Ejercicios_JavaScript/blob/main/Imagenes/Ejercicio3.png)

## Ejercicio #5

```javascript
var tempt = prompt("ingresar una temperatura en Farenheit: ")
var Celsius = (5/9) * (tempt-32)
console.log("En grados celsius es: "+ Celsius);

```
![i1](https://github.com/camiloRub/Taller_Ejercicios_JavaScript/blob/main/Imagenes/Ejercicio5.png)

## Ejercicio #7

```javascript
var numero1 = prompt("ingrese un numero: ");
console.log("Descontando el 15% queda: " + (numero1 - numero1 * 0.15)); 
```
![i1](https://github.com/camiloRub/Taller_Ejercicios_JavaScript/blob/main/Imagenes/Ejercicio7.png)

## Ejercicio #9

```javascript
var texto = prompt("ingresar un texto: ");
console.log("" + texto )
console.log("El caracter en primer lugar es :" + texto.charAt(0) )
console.log("ingrese un numero positivo menor a  " + texto.length );
var indice = prompt("");
console.log("" + indice);
var posicion = texto.charAt(indice);
console.log("El caracter en esa posicion es: " + posicion);
```
![i1](https://github.com/camiloRub/Taller_Ejercicios_JavaScript/blob/main/Imagenes/Ejercicio9.png)

## Ejercicio 11

```javascript
var fecha = Number(prompt("Ingrese la fecha en formato DDMMAAAA: "))
console.log(fecha)
var aaaa = Math.trunc(fecha % 10000)
fecha /= 10000
var mm = Math.trunc(fecha % 100)
fecha /= 100
var dd = Math.trunc(fecha)
console.log(dd + "/" + mm + "/" + aaaa)
```

## Ejercicio #13

```javascript
var edad = prompt("Tu edad: ");
console.log(""+edad);
var articulos = prompt("articulos comprados: ");
console.log(""+articulos);
var verdad = Boolean(edad>18 && articulos>1);
console.log(""+verdad);
```
![i1](https://github.com/camiloRub/Taller_Ejercicios_JavaScript/blob/main/Imagenes/ejercicio13.png)

## Ejercicio #15

```javascript
var palabra1 = prompt("Una palabra: ");
console.log(""+palabra1);
var palabra2 = prompt("Otra palabra: ");
console.log(""+palabra2);
var verdad = Boolean(palabra1<palabra2);
console.log(""+verdad);
```
![i1](https://github.com/camiloRub/Taller_Ejercicios_JavaScript/blob/main/Imagenes/Ejercicio15.png)

## Ejercicio #17

```javascript
var numero1 = prompt("Numero: ");
var valor = Math.abs(numero1);
console.log = (""+valor);
```
![i1](https://github.com/camiloRub/Taller_Ejercicios_JavaScript/blob/main/Imagenes/Ejercicio17.png)

## Ejercicio #19

```javascript
var letra = prompt ("Letra: ");
var vocal= ("aeiou");
if(vocal.indexOf(letra) != -1){
alert("vocal encontrada");
}else {
    alert("No se pudo procesar el dato");

} 
```
![i1](https://github.com/camiloRub/Taller_Ejercicios_JavaScript/blob/main/Imagenes/Ejercicio19.1.png)
![i1](https://github.com/camiloRub/Taller_Ejercicios_JavaScript/blob/main/Imagenes/Ejercicio19.2.png)

## Ejercicios Impares

## Ejercicio 2

```javascript
var primero = prompt("Primer número")
console.log(primero)
var segundo = prompt("Segundo número")
console.log(segundo)
var suma = Number(primero) + Number(segundo) 
console.log("La suma de ambos números: " + suma)
```

![ejercicio en consola](capturas/2.png)

## Ejercicio 4

```javascript
var km = prompt("Kilómetros recorridos: ")
console.log(km)
var lt = prompt("Litros de combustible gastados: ")
console.log(lt)
var consumo = Number(km) / Number(lt) 
console.log("El consumo por kilómetro es de: " + consumo)
```

![ejercicio en consola](capturas/4.png)

## Ejercicio 6

```javascript
var primero = Number(prompt("Primer número: "))
console.log(primero)
var segundo = Number(prompt("Segundo número: "))
console.log(segundo)
var tercero = Number(prompt("Tercero número: "))
console.log(tercero)
var promedio = (primero + segundo + tercero) / 3
console.log("El promedio de los números es: " + promedio)
```

![ejercicio en consola](capturas/6.png)

## Ejercicio 8

```javascript
var primera = prompt("Primera palabra")
console.log(primera)
var segunda = prompt("Segunda palabra")
console.log(segunda)
console.log(primera + " " + segunda)
```

![ejercicio en consola](capturas/8.png)

## Ejercicio 10

```javascript
var shows = Number(prompt("Shows vistos el último año: "))
console.log(shows)
var mas_de_3 = shows > 3
console.log(mas_de_3)
```

![ejercicio en consola](capturas/10.png)

## Ejercicio 11

```javascript
var fecha = Number(prompt("Ingrese la fecha en formato DDMMAAAA: "))
console.log(fecha)
var aaaa = Math.trunc(fecha % 10000)
fecha /= 10000
var mm = Math.trunc(fecha % 100)
fecha /= 100
var dd = Math.trunc(fecha)
console.log(dd + "/" + mm + "/" + aaaa)
```

![ejercicio en consola](capturas/12.png)

## Ejearcicio 12

```javascript
var num = Number(prompt("Ingrese un número: "))
console.log(num)
var numpar = (num % 2) == 0
console.log(numpar)
```

## Ejercicio 14

```javascript
var str = prompt("Ingrese una frase: ")
console.log(str)
var numpar = (str.length % 2) == 0
console.log(numpar)
```

![ejercicio en consola](capturas/14.png)

## Ejercicio 16

```javascript
var str1 = prompt("Ingrese el primer nombre: ")
console.log(str1)
var str2 = prompt("Ingrese el segundo nombre: ")
console.log(str2)
var primera = str1[0] == str2[0]
var ultima = str1[str1.length - 1] == str2[str2.length - 1]
var out = primera || segunda
console.log(out)
```

![ejercicio en consola](capturas/16.png)

## Ejercicio 18

```javascript
var num1 = Number(prompt("Ingrese un número: "))
console.log(num1)
var mayor = num1
var num2 = Number(prompt("Ingrese otro número: "))
console.log(num2)
if (num2 > num1)
    mayor = num2
console.log(mayor + " es mayor")
```

![ejercicio en consola](capturas/18.png)

## Ejercicio 20

```javascript
var num1 = Number(prompt("Ingrese un número: "))
console.log(num1)
var menor = num1
var num2 = Number(prompt("Ingrese otro número: "))
console.log(num2)
if (num2 < num1)
    menor = num2
var num3 = Number(prompt("Ingrese otro número: "))
console.log(num3)
if (num3 < num2)
    menor = num3
console.log(menor + " es menor")
```

![ejercicio en consola](capturas/20.png)
