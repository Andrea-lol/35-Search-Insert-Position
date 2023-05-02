# 35. Search Insert Position 💻

![Version 1.0](https://img.shields.io/badge/version-1.0.-blue.svg) 

## Descripción Y Contexto 📑

Esta programa realizado genera 100 casos de prueba en total para el problema. Este busca tener una variedad equilibrada de casos de prueba, para así generar arreglos de diferentes longitudes con valores enteros aleatorios distintos y variedad de valores (números) objetivo. 

La primera mitad de los casos de prueba están entre valores (número) objetivo que se encuentran en el arreglo, mientras la otra mitad consiste en valores objetivo que no se encuentran en el arreglo.

Para cada uno de los casos de prueba, la aplicación genera un arreglo de longitud aleatoria con valores enteros aleatorios diferentes, luego lo ordena y selecciona un valor (número) objetivo aleatorio. Si el valor objetivo se encuentra en el arreglo, se lo pasa a la función searchInsert para que devuelva su índice. Por otro lado, si el valor objetivo no se encuentra en el arreglo, se genera un nuevo valor aleatorio hasta que no se encuentre en el arreglo y se lo pasa a la función searchInsert.

Cada caso de prueba se imprime en la consola como un arreglo, un valor objetivo y el resultado de la función searchInsert.


## Explicación del Código Main 📃

Este código se realizó en la versión 12.6 de NetBeans IDE

![Imagen de Evidencia](https://github.com/Andrea-lol/35-Search-Insert-Position/blob/main/100%20Casos%20de%20Prueba/img/Evidencia4.png "Esta es una imagen de muestra.")

#### 1. La primera parte del código consiste en generar casos de prueba en donde el valor (número) objetivo se encuentra en el arreglo, para ello:

```bash
    1.1. Define el número total de casos de prueba en la variable numTestCases.
```
```bash
    1.2. Usa un bucle for para generar numTestCases/2 casos de prueba, es decir, la mitad de los casos de prueba estarán ahí.
```
```bash
    1.3. Para cada caso se genera un tamaño aleatorio para el arreglo utilizando rand.nextInt(100) + 1, donde el tamaño será entre 1 y 100.
```
```bash
    1.4. Crea un arreglo de tamaño aleatorio y lo llena con números enteros aleatorios entre -100 y 99 utilizando el bucle for.
```
```bash
    1.5. Se ordena el arreglo en orden ascendente utilizando Arrays.sort().
```
```bash
    1.6. Elige el valor (número) objetivo aleatorio dentro del arreglo utilizando nums[rand.nextInt(size)].
```
```bash
    1.7. Llama a la función searchInsert que contiene nums y target) y se imprime el arreglo, el valor (número) objetivo y el resultado de la búsqueda.
```


#### 2. La segunda parte del código abarca y genera casos de prueba donde el valor (número) objetivo que no están en el arreglo, para ello:

```bash
    2.1. Como se dijo en la primera parte, se usa otro bucle for para generar numTestCases/2 casos de prueba, es decir, la mitad de los casos de prueba estarán ahí.
```
```bash
    2.2. El proceso es similar al primer bucle for, solo que esta vez genera un valor (número) objetivo aleatorio que no está presente en el arreglo. Esto se hace utilizando un bucle while que genera un valor aleatorio y verifica si ya está presente en el arreglo utilizando Arrays.binarySearch(). Si el valor ya está en el arreglo, se genera otro valor aleatorio y se repite el proceso hasta que se encuentra un valor que no está en el arreglo.
```
```bash
    2.3. Llama a la función searchInsert que contiene nums y target) y se imprime el arreglo, el valor (número) objetivo y el resultado de la búsqueda.
```

## Nota 🔖

Para el código se utilizaron variables en inglés ya que el LeetCode pedía que fuese así para que funcionara, además como dije en la parte superior se ha utiliz+o el NetBeans 12.6 para realizarlo. Si se requiere más información puede dirigirse al documento PDF.

## LeetCode
**[35. Search Insert Position]** de la **[LeetCode]**

[35. Search Insert Position]: https://leetcode.com/problems/search-insert-position/description/
[LeetCode]: https://leetcode.com
