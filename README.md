# Tarea-1-Programaci-n-Avanzada

# Paradigmas de Programación y Complejidad Computacional

## ¿Qué es un paradigma de programación?

Un **paradigma de programación** es una forma de enfocar y formular problemas de programación. Un ejemplo son los **paradigmas imperativos**, los cuales consisten básicamente en una secuencia de pasos que van cambiando el estado del programa. Dentro de este tipo de paradigmas se encuentran:

- **Programación procedimental**
- **Programación orientada a objetos**
- **Procesamiento paralelo**

## ¿En qué se basa la programación orientada a objetos?

La **programación orientada a objetos (POO)** se basa en la creación de clases, las cuales definen objetos. Los objetos de cada clase tienen atributos y funcionalidades asociadas. Una de las características principales de este paradigma es el énfasis en los datos y la capacidad de herencia entre objetos.

## ¿Cuál es la diferencia entre recursividad e iteración, y cómo se relaciona esto con la notación Big O?

- **Iteración**: Consiste en repetir un procedimiento varias veces mediante ciclos como `for` o `while`.
- **Recursividad**: Se refiere a una función que se llama a sí misma, ya sea directa o indirectamente.

En cuanto a la complejidad computacional:

- **Iteración** suele tener una complejidad de **O(n)**, donde el número de repeticiones es proporcional a la entrada.
- **Recursividad** puede tener diferentes complejidades según el caso, ya que depende de la estructura y si utiliza espacio adicional en memoria o no.

## Diferencia de rendimiento entre O(1) y O(n)

- **O(1)**: Representa una complejidad de tiempo constante, es decir, el algoritmo tarda el mismo tiempo sin importar el tamaño de la entrada.
- **O(n)**: Representa una complejidad lineal, lo que significa que el tiempo de ejecución es proporcional al tamaño de la entrada.

Por lo tanto, **O(1)** es mucho más eficiente que **O(n)**, especialmente cuando el tamaño de entrada crece.

## ¿Cómo se calcula el orden en un programa que funciona por etapas?

Depende de cómo esté compuesto el programa:

- Si las etapas están organizadas en **serie**, la complejidad del programa es la suma de las complejidades de cada etapa.
- Si las etapas están **anidadas**, la complejidad total es el producto de las complejidades de cada etapa.

## ¿Cómo se puede determinar la complejidad temporal de un algoritmo recursivo?

La complejidad de un algoritmo recursivo se determina estableciendo una **relación de recurrencia**. Esto depende de cuántas veces se llama la función a sí misma y cuántos subproblemas se generan en cada llamada recursiva.
