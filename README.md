
# Algoritmos de Optimización — Actividades y Seminario

Este repositorio contiene una serie de notebooks desarrollados como parte del curso de **Algoritmos de Optimización**, donde se aplican diversas técnicas como **divide y vencerás**, **programación dinámica**, **búsqueda local**, **fuerza bruta** entre otros para resolver problemas clásicos de optimización.

Además se ha añadido por cada notebook un espacio de **Práctica individual de material de clase** sugeridas para practicar más y mejorar las calificaciones.

---

## Contenido de los notebooks

### 1. Algoritmos_AG1_RogerRodriguez.ipynb
- **Tema**: 
	- Divide y vencerás
	- Algoritmo Voraz
    - Vuelta atrás 
    - Programación Dinámica 
- **Problemas trabajados**: Torres de Hanoi, Fibonacci, Fibonacci optimizado, devolución de cambio, N-Reinas
- **Práctica individual de material de clase**
	- Dado un conjunto de puntos se trata de encontrar los dos puntos más cercanos
	- Suponer en 1D, o sea, una lista de números: [3403, 4537, 9089, 9746, 7259, ... ]
    - Primer intento: Fuerza bruta 
    - Calcular la complejidad. ¿Se puede mejorar?
	- Segundo intento. Aplicar Divide y Vencerás
	- Calcular la complejidad. ¿Se puede mejorar?
	- Extender el algoritmo a 2D: [(1122, 6175), (135, 4076), (7296, 2741)…]
	- Extender el algoritmo a 3D.
	- Para generar conjuntos de datos aleatorios

---

### 2. Algoritmos_AG2_RogerRodriguez.ipynb
- **Tema**: 
	- Programación dinámica
	- Descenso del Gradiente
- **Problema trabajado**: Viaje por el río con costos entre embarcaderos, Problema de Asignación de Tareas
- **Práctica individual de material de clase**
	- Optimizar la función: f(x)=sin(1/2∗x2−1/4∗y2+3)∗cos(2∗x+1−ey)
	- Generar matrices con valores aleatorios de mayores dimensiones (5,6,7,…) y ejecutar ambos algoritmos.
	- ¿A partir de que dimensión el algoritmo por fuerza bruta deja de ser una opción?
    - ¿Hay algún valor de la dimensión a partir de la cual el algoritmo de ramificación y poda también deja de ser una opción válida?
	
---

### 3. Algoritmos_AG3_RogerRodriguez.ipynb
- **Tema**: Búsqueda local y metaheurísticas para problemas de optimización combinatoria
- **Problema trabajado**:Búsqueda Aleatoria, Búsqueda Local, Simulated Annealing
- **Práctica individual de material de clase**
	- Búsqueda local con Entornos variables: ¿Se puede mejorar con otros operadores de vecindad variables?
	- Búsqueda local con Entornos variables: ¿Se puede mejorar con otra elección no tan aleatoria( función genera_vecina_aleatorio() ) ?
	
---

### 4. Seminario_Algoritmos_RogerRodriguez.ipynb
- **Problema**: Combinar cifras y operaciones
- **Condiciones**: 
	- El problema consiste en analizar el siguiente problema y diseñar un algoritmo que lo resuelva
	- Disponemos de las 9 cifras del 1 al 9 (excluimos el 0) y de los 4 signos básicos de las operaciones fundamentales: suma(+), resta(-), multiplicación(*) y división(/).
	- Debemos combinarlos alternativamente sin repetir ninguno de ellos para obtener una cantidad dada. Un ejemplo sería para obtener el 4:4+2−6/3∗1=4 
- **Preguntas desarrolladas**: 
	- ¿Qué valor máximo y mínimo se pueden obtener según las condiciones del problema?
	- ¿Es posible encontrar todos los valores enteros posibles entre dicho mínimo y máximo?
	- ¿Cuántas posibilidades hay sin tener en cuenta las restricciones?
	- ¿Cuántas posibilidades hay teniendo en cuenta todas las restricciones?
	- ¿Cual es la estructura de datos que mejor se adapta al problema? Argumentalo.
	- ¿Cual es la función objetivo? ¿Es un problema de maximización o minimización?
	- Diseña un algoritmo para resolver el problema por fuerza bruta
	- Calcula la complejidad del algoritmo por fuerza bruta
	- Diseña un algoritmo que mejore la complejidad del algortimo por fuerza bruta. Argumenta porque crees que mejora el algoritmo por fuerza bruta
	- Calcula la complejidad del algoritmo
	- Según el problema (y tenga sentido), diseña un juego de datos de entrada aleatorios. Aplica el algoritmo al juego de datos generado
	- Enumera las referencias que has utilizado(si ha sido necesario) para llevar a cabo el trabajo
	- Describe brevemente las lineas de como crees que es posible avanzar en el estudio del problema. Ten en cuenta incluso posibles variaciones del problema y/o variaciones al alza del tamaño
	
---

## Autor

**Roger Hans Rodriguez Samanez**  
Maestría en Inteligencia Artificial – VIU  
GitHub: https://github.com/rrodriguezsamanez/03MIAR---Algoritmos-de-Optimizacion/

---

## Notas

- Los notebooks pueden abrirse en Google Colab para su correcta ejecución.
- Algunas imágenes están embebidas directamente en los notebooks.



