# Generación de números aleatorios

¿Cómo es que nuestras computadoras generan números aleatorios, siendo máquinas completamente predecibles que solo siguen instrucciones?

La verdad es que no lo hacen. Lo que generan son números pseudo aleatorios gracias a algoritmos matemáticos cada vez más sofisticados para simular independencia.

En aprendizaje de máquinas, la aleatoriedad es un concepto muy importante que se debe considerar, por poner algunos ejemplos, en la generación de los datos, en la obtención de los conjuntos de entrenamiento y validación, así como en el establecimiento de un estado inicial en una red neuronal.

El notebook de este repositorio presenta, en la primera parte, un generador de congruencia lineal de números aleatorios con distribución uniforme. 
Se utilizan dos funciones con distintos parámetros, con la intención de dejar clara la importancia que tiene una buena elección de parámetros.
En la segunda parte se muestra la transformación de dos vectores independientes con distribución uniforme a otros dos, igualmente independientes uno del otro, pero con distribución gaussiana
