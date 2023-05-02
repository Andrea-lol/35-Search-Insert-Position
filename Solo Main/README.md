# 35. Search Insert Position 💻

![Version 1.0](https://img.shields.io/badge/version-1.0.-blue.svg) 

## Descripción Y Contexto 📑

Esta aplicación contiene el main y la función searchInsert. 

- El main se encarga de recibir la entrada dada por el usuario para el tamaño de la matriz y los valores de la matriz en orden ascendente, y recibe el valor (número) objetivo, para así llamar a la función searchInsert para encontrar el índice del objetivo (ingresaro por el usuario) en la matriz. Finalmente imprimiendo el en la consola.

- La función searchInsert por su parte, es la implementación de la búsqueda binaria para encontrar el índice del objetivo (número que el usuario busca) en la matriz.Por lo que, este toma un arreglo de enteros (numbers) y un entero (target). Declara dos índices, left (inicialmente es 0) y right (es el último elemento del arreglo (numbers.length - 1)), los cuales representan los límites del subarreglo en el que se buscará el objetivo.  Luego, se realiza un bucle while donde se comparan los valores del objetivo y el elemento del medio de la matriz (middle). Si este valor (numbers[middle]) es igual al objetivo, devuelve middle. Pero si numbers[middle] es menor que el objetivo, significa que el objetivo debe estar en el lado derecho de la matriz, por lo que se actualiza el índice left a middle + 1. De lo contrario, el objetivo debe estar en el lado izquierdo de la matriz, por lo que se actualiza el índice right a middle - 1. Si finalmente no se encuentra el objetivo en la matriz, el bucle while termina y se devuelve left, que es el índice donde se puede insertar el objetivo en la matriz para mantenerla ordenada.



## Nota 🔖

Para el código se utilizaron variables en inglés ya que el LeetCode pedía que fuese así para que funcionara, pero el texto de las entradas se encuentra en español para mayor comodidad, además como dije en la parte superior se ha utilizado NetBeans 12.6 para realizarlo. Si se requiere más información puede dirigirse al documento PDF.

## LeetCode
**[35. Search Insert Position]** de la **[LeetCode]**

[35. Search Insert Position]: https://leetcode.com/problems/search-insert-position/description/
[LeetCode]: https://leetcode.com
