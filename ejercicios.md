# Ejercicios

## Lambda
### Ejercicio 1:
Función lambda que almacena en la variable (val) resta la lógica para realizar una resta. Realiza a-b.

### Ejercicio 2:
Crea la variable hola que contiene un println en el que se imprime hola mundo.

### Ejercicio 3: 
Crea un listOf de números y una mostrarLista. Esta debe debe de hacer un toString de la lista que recibe e imprimirla.

### Ejercicio 4: 
Crea la variable pares, que recibe una lista de entrada y la recorre usando un foreach. Si el número es par, lo imprime.

### Ejercicio 5:
Crea la variable obtenerPares, en este caso devuelve cómo resultado una lista de números pares. Para ello el programa usa una MutableList. Esa lista se debe guardar en otra variable y la podremos imprimir.

    val resultado = obtenerPares(numeros)
    mostrarLista(resultado)

### Ejercicio 6: 
Modifica la función del ejercicio 5 para que use filter.

## Funciones de extensión
### Ejercicio 1: 
La función de extensión toInt que viene por defecto en los String transforma un texto a número.
    val texto1 = "4"
    val texto2 = "6"
    val sumados = texto1.toInt() +5
    print(sumados)

Crea una funcion de extension escrito(). Que hace que si el número es "1" devuelva "uno" y si el número es "2" devuelva "dos".

### Ejercicio 2:
Con un valor Int, creale la funcion es par, esta devuelve "SI" o "NO"

### Ejercico 3: 
En una lista de Int crea la función multiplicar, que realiza una multiplicación entre todos los números.

recorre la lista usando for (elemento in this)

### Ejercicio 4:
Crea la función sumarVal(val:Int) que se hace sobre una lista de Int (List<Int>).

A todos los números se le s suma val.

### Ejercicio 5:
Crea la función listar, para una lista de String. Esta función imprime sus valores enumerados. Así que si la lista es: tomates, patatas y queso, el resultado esperado es:
1. tomates
2: patatas
3: queso

### Ejercicio 6:
Crea la función primera mayus para un String se le transforme la primera letra en mayúsculas.

Haz que primera mayus también funcione en una lista de Strings.

Ejercicio 7:
Modifica la función listar y combínala con primeraMayus para que la primera letra de cada uno de sus valores de la lista sea mayúsculas.
