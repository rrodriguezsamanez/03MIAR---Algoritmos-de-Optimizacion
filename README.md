# Construcción del contenido del README.md
readme_content = """
# Algoritmos de Optimización — Actividades y Seminario

Este repositorio contiene una serie de notebooks desarrollados como parte del curso de **Algoritmos de Optimización**, donde se aplican diversas técnicas como **divide y vencerás**, **programación dinámica**, **búsqueda local**, y **fuerza bruta** para resolver problemas clásicos de optimización.

---

## Contenido de los notebooks

### 1. Algoritmos_AG1_RogerRodriguez.ipynb
- **Tema**: 
	- Divide y vencerás
	- Algoritmo Voraz
    - Backtracking 
    - Programación Dinámica 
- **Problema trabajado**: Torres de Hanoi, Fibonacci, Fibonacci optimizado, devolución de cambio, N-Reinas
- **Descripción**: Se implementa la solución recursiva al clásico problema de las Torres de Hanoi, explicando el principio de descomposición en subproblemas y su posterior resolución.
- **Ejercicios de la práctica individual de material de clase**

---

### 2. Algoritmos_AG2_RogerRodriguez.ipynb
- **Tema**: Programación dinámica
- **Problema trabajado**: Viaje por el río con costos entre embarcaderos
- **Descripción**: Se analiza cómo reducir los costos de un trayecto fluvial utilizando subproblemas almacenados y el principio de optimalidad de Bellman. Se incluye una matriz de costos y solución recursiva con memoización.

---

### 3. Algoritmos_AG3_RogerRodriguez.ipynb
- **Tema**: Metaheurísticas y búsqueda local
- **Contenido**: Aplicación de algoritmos como recocido simulado o búsqueda 3-opt a problemas combinatorios (probablemente TSP). Se enfoca en explorar el espacio de soluciones para encontrar rutas de costo mínimo.

---

### 4. Seminario_Algoritmos_RogerRodriguez.ipynb
- **Tema**: Fuerza bruta y espacio de búsqueda
- **Problema trabajado**: Combinación de cifras y operaciones para alcanzar valores enteros
- **Descripción**: Utiliza la función `eval()` para construir y evaluar expresiones numéricas generadas con los dígitos del 1 al 9 y operadores aritméticos, con el fin de hallar el máximo y mínimo valor posible bajo ciertas restricciones.

---

## Autor

**Roger Hans Rodriguez Samanez**  
Maestría en Inteligencia Artificial – VIU  
GitHub: https://github.com/rrodriguezsamanez/03MIAR---Algoritmos-de-Optimizacion/

---

## Notas

- Los notebooks pueden abrirse en Google Colab para su correcta ejecución.
- Algunas imágenes están embebidas directamente en los notebooks.
"""

# Guardar el README.md
readme_path = "/mnt/data/README.md"
with open(readme_path, "w", encoding="utf-8") as f:
    f.write(readme_content)

readme_path
