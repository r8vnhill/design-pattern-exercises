# Ejercicios sobre patrones de diseño

![http://creativecommons.org/licenses/by/4.0/](https://i.creativecommons.org/l/by/4.0/88x31.png)

This work is licensed under a
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)

---

## Pizzería

Una pizzería necesita un sistema para gestionar sus pedidos y le pide a usted que la desarrolle.
La pizzería actualmente consta de 3 tipos de pizza: Margarita, Funghi y Carbonara. Cada una de ellas
tiene un precio base de $5000. Además, la pizzería ofrece la posibilidad de añadir ingredientes a 
las pizzas por un precio adicional de $300 por ingrediente. 
Los ingredientes que se pueden añadir son:

- Jamón
- Champiñones
- Aceitunas
- Anchoas
- Cebolla
- Pimiento
- Piña

1. Diseñe un diagrama de clases que permita modelar la _elaboración_ de pizzas, considerando que 
podrían necesitarse más tipos de pizza en el futuro.
2. Implemente la solución propuesta en el punto anterior.
3. La pizzería cuenta con tres formas de realizar los pedidos: en el local, por teléfono y por 
internet. Considerando que la pizzería debe poder manejar varios pedidos simultáneamente y que
cada pedido puede tener varios tipos de pizza, diseñe un diagrama de clases que permita modelar
una manera de recibir los pedidos y gestionarlos.
4. Implemente la solución propuesta en el punto anterior.

## Base de datos

El servicio médico legal le encarga el diseño de una base de datos centralizada para la 
gestión de los expedientes de alcoholemias. El sistema debe permitir registrar los datos de
los conductores, los datos de los vehículos, los datos de los agentes que realizan las 
pruebas y los datos de las pruebas realizadas.
Como la base de datos debe ser accesible desde todos los centros del país es importante 
asegurar que la base de datos sea única.

1. Diseñe un diagrama de clases que permita modelar la base de datos.
2. Implemente la solución propuesta en el punto anterior.
3. Inicialmente, se pide que la base de datos sea implementada con SQLite, pero en el futuro
se desea que la base de datos pueda cambiar de motor de base de datos sin que el resto del
sistema se vea afectado. Diseñe un diagrama de clases que permita modelar la base de datos
considerando que se desea que sea independiente del motor de base de datos.
4. Implemente la solución propuesta en el punto anterior.

## Algoritmos de ordenamiento

Una lista de números enteros se puede ordenar de diferentes maneras. En este ejercicio se
pide implementar los siguientes algoritmos de ordenamiento:

- QuickSort
- MergeSort
- BubbleSort

Para esto considere que tiene una clase abstracta `AbstractIntList` que representa una lista
de números.

1. Diseñe un diagrama de clases para modelar una solución que permita ordenar la lista usando
los algoritmos de ordenamiento propuestos. _Hint: Utilice herencia para modelar los algoritmos._
2. Implemente la solución propuesta en el punto anterior.

