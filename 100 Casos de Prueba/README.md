# 35. Search Insert Position 💻

![Version 1.0](https://img.shields.io/badge/version-1.0.-blue.svg) 

## Descripción Y Contexto 📑

Esta programa realizado genera 100 casos de prueba en total para el problema. Este busca tener una variedad equilibrada de casos de prueba, para así generar arreglos de diferentes longitudes con valores enteros aleatorios distintos y variedad de valores (números) objetivo. 

La primera mitad de los casos de prueba están entre valores (número) objetivo que se encuentran en el arreglo, mientras la otra mitad consiste en valores objetivo que no se encuentran en el arreglo.

Para cada uno de los casos de prueba, la aplicación genera un arreglo de longitud aleatoria con valores enteros aleatorios diferentes, luego lo ordena y selecciona un valor (número) objetivo aleatorio. Si el valor objetivo se encuentra en el arreglo, se lo pasa a la función searchInsert para que devuelva su índice. Por otro lado, si el valor objetivo no se encuentra en el arreglo, se genera un nuevo valor aleatorio hasta que no se encuentre en el arreglo y se lo pasa a la función searchInsert.

Cada caso de prueba se imprime en la consola como un arreglo, un valor objetivo y el resultado de la función searchInsert.


## Explicación del Código Main 📃

Debe escribir un algoritmo con una complejidad de tiempo de ejecución O(log n).

Ejemplo 1:

```bash
    $ Input: nums = [1,3,5,6], target = 5
    $ Output: 2
```
