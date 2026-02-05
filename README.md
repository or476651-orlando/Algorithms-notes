# Notas del curso de Algoritmos
Hasta ahora, el curso va orientado al análisis de algoritmos (muchos de ellos de problemas combinatorios). En términos generales, se ha analizado la *complejidad* de algunos problemas famosos y se han definido términos de esencial relevancia (aunque de manera informal).
Hasta el momento, se han abordado problemas célebres que, en su solución y/o planteamiento se ha visto involucrada la **teoría de gráficas**, a saber:
## El problema de los emparejamientos
Dados dos conjuntos de hombres y mujeres de igual cardinalidad, teniendo cada persona una lista de personas del sexo opuesto preferidas para emparejarse, determinar si existe un emparejamiento en el que nadie se quede sin pareja. Este problema involucra determinar si la gráfica asociada al problema es **bipartita** o no.
## El problema de los salones
Este problema tiene como planteamiento determinar cuántas etiquetas necesito para etiquetar salones, definiéndolos como adyacentes si hay algún traslape de grupo de alumnos queriendo ocupar el mismo salón. Este problema involucra el **número cromático de la gráfica**, siendo una variante del problema de coloración de un mapa.
## El problema del camino del menor costo
Este problema consiste en, dadas n localidades, encontrar la vía de menor costo tal que se pueda llegar a todas las localidades, suponiendo que a cada par de localidades adyacentes le corresponde un costo monetario para construir su camino entre ellas. Este problema involucra encontrar el **árbol generador de la gráfica**.
## El problema de los vértices
Este problema es una variante del problema de los caminos de Euler. Aquí, en lugar de fijarnos en los puentes, nos fijamos en las localidades. Este problema involucra determinar si la gráfica asociada al problema es **hamiltoniana**.

## Conceptos de interés al momento
- Gráfica
- Grado de un vértice
- El número cromático de una gráfica $G$ ,   $\chi(G)$
- Problema
- Algoritmo
- Instancia de un problema
- Clase de complejidad

Estos son sólo algunos de los problemas clásicos. Existen muchos otros problemas, de distintas complejidades.
Cobra una especial relevancia la notación $O(_)$, la cual define lo siguiente: una función $f(n)$ es $O(g(n))$ si existe c>0 tal que
$$ |f(n)| \leq c|g(n)| $$
