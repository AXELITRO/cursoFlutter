
# Tipos de variables en Dart

### Variables con inferencia de tipos
Para la mayoria de varables en dart se utilizan diferentes tipos de variables, pero algo a resaltar es que podemos tener una variable con inferencia de tipos

**Dart**
```Dart
    var nombre = "Hola mundo";
    var entero = 10;
    var active = true;
    var caracter = 'e';
    var decimal = 20.5;
    
```
### Variables de tipado Explicito
En Dart Tambien podemos encontrar como en otros lenguajes de programacion las variables de Tipado Explicito, estas variables son declaradas con su tipo desde el inicio, a comparacion de las variables de tipo `var` estas solo aceptan valores del tipo antes declarado

**Dart**
``` Dart
    String nombre = 'Hola mundo';
    int entero = 10;
    bool active = true;
    String caracter = 'e';
    double decimal = 20.5;
```
**Dart**
```Dart
    print('Hola mundo');
```

## Concatenacion de variables en dart

En dart no se utiliza el simbolo `+` como en java u otros lenguajes, en el caso de C++ que para concatenar texto con numeros u otras variables se utilizan los simbolos `<<`, en dart para concatenar variables lo que se hace es colocar el simbolo `$` por ejemplo:

```Dart
    int edad = 20;
    print('Mi edad es: $edad');
```
La salida de esta impresion es:

Mi edad es: 20

## Condicionales
Dentro de dart se utilizan los condicionales `if`,`else`,`switch`
estos se utilizan para crear condiciones dentro del codigo que se deben cumplir para la logica del programa, la estructura de estos es igual que en los demas lenaguajes de programacion

## if else
```Dart
var edad = 18;
if (edad >= 18) {
  print('Mayor de edad');
} else {
  print('Menor de edad');
}
```
## Switch
```Dart
    switch{
        case 1:
        //Aqui va  el contenido de el ciclo
        break;
        //Aqui va  el contenido de el ciclo
        case 2:
        //Aqui va  el contenido de el ciclo
        break;
        //Aqui va  el contenido de el ciclo
        case 3:
        //Aqui va  el contenido de el ciclo
        break;
    }
```


## Ciclos

Dentro de dart se utilizan los ciclos que se utilizan en diferentes lenguajes `for`,`while`,`do while` y la estructura de cada uno de estos es igual que en otros lenguajes

## Ciclo for
```Dart
    for(int i =1; i<10;i++){
        //Aqui va  el contenido de el ciclo
    }
```
## Ciclo while
```Dart
    while (i<10){
        i++
        //Aqui va  el contenido de el ciclo
    }
```
## Ciclo do while
```Dart
    do{
        //Aqui va  el contenido de el ciclo
    }while(i<10)
```

