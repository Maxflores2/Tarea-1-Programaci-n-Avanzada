# Tarea-1-Programaci-n-Avanzada

# Paradigmas de Programación y Complejidad Computacional

## ¿Qué es un paradigma de programación?

Es una forma de enfocar y formular problemas de programación. Un ejemplo de los paradigmas de programación son los imperativos, los cuales son básicamente una secuencia de pasos que van cambiando el estado del programa. Dentro de este tipo de paradigmas están la procedimental, orientada a objetos y procesamiento paralelo.

## ¿En qué se basa la programación orientada a objetos?

Este tipo de programación se basa en la creación de una clase, la cual tiene objetos definidos. Los objetos de cada clase tienen atributos y funcionalidades asociadas. Una característica es la capacidad del énfasis en los datos y la herencia que se pueden tener entre objetos.

## ¿Cuál es la diferencia entre recursividad e iteración, y cómo se relaciona esto con la notación big 𝑂?

La iteración se basa en realizar el mismo procedimiento varias veces ocupando ciclos for o bucles while. En cambio, la recursividad consiste en llamar a sí misma la función, ya sea directamente o indirectamente. En términos de la complejidad con la notación big O, la iteratividad en la mayoría de los casos tiene complejidad O(n), en cambio la recursividad puede tener distintas complejidades según la forma en que esté planteada y si ocupa espacios en la memoria o no.

## Explicar la diferencia de rendimiento entre 𝑂(1) y 𝑂(𝑛)

La complejidad O(1) corresponde a un tiempo constante de ejecución del algoritmo sin importar la entrada que tenga. El caso de O(n) es un tiempo de ejecución lineal, es decir, el tiempo de ejecución es proporcional al tamaño de la entrada al algoritmo. Por lo tanto, O(1) es mucho más eficiente que O(n) para cualquier tamaño de entrada.

## ¿Cómo se calcula el orden en un programa que funciona por etapas?

Depende de cómo esté compuesto el programa por etapas, esto podría ser en serie o anidado de alguna manera. En el caso de que esté compuesto por etapas en serie, la complejidad big O del algoritmo corresponde a la suma de las complejidades de cada etapa. En el caso de las etapas anidadas, para obtener la complejidad big O del algoritmo completo se debe hacer la multiplicación de complejidades de cada etapa.

## ¿Cómo se puede determinar la complejidad temporal de un algoritmo recursivo?

Se puede establecer una relación de recurrencia, la cual depende de la cantidad de veces que se llama a sí misma la función y de la cantidad de subproblemas que se tienen en total.
