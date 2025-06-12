# Rúbrica de Evaluación del Proyecto Final  

- Total de puntos: 120
- Mínimo para aprobar: 100 puntos

## 1. Estructura y Presentación (15 puntos)

1. [ ] **El cuaderno incluye una sección de introducción** que explica el tema elegido y su relevancia en física/matemáticas computacionales. *(5 puntos)*  
2. [ ] **Las celdas de código y Markdown están organizadas secuencialmente**, con explicaciones lógicas y formato profesional (títulos, subtítulos, listas). *(4 puntos)*  
3. [ ] **Se muestran gráficos incrustados** (ej. Matplotlib) o **fórmulas matemáticas en LaTeX** dentro del cuaderno. *(6 puntos)*  

---

## 2. Contenido del Curso (70 puntos)

### Fundamentos de Python y Jupyter (10 puntos)

4. [ ] **El código utiliza variables de al menos tres tipos** (entero, flotante, cadena, booleano) y funciones integradas como `round` o `math.sqrt`. *(3 puntos)*  
5. [ ] **Se definen al menos dos funciones personalizadas** con parámetros y retorno de valores. *(4 puntos)*  
6. [ ] **Se aplican operaciones de cadenas** como concatenación, formato con f-strings o métodos como `split`/`join`. *(3 puntos)*  

### Lógica, Recursividad e Iteración (15 puntos)

7. [ ] **Se implementan estructuras condicionales** (`if-elif-else`) con al menos dos condiciones anidadas. *(5 puntos)*  
8. [ ] **Se utiliza un ciclo `for` o `while`** para resolver un problema (ej. iterar sobre una lista o calcular una serie numérica). *(5 puntos)*  
9. [ ] **Incluye una función recursiva** correctamente implementada (ej. factorial, Fibonacci o Torres de Hanói). *(5 puntos)*  

### Estructuras de Datos (10 puntos)

10. [ ] **Se manipulan listas, diccionarios o conjuntos** para almacenar o procesar datos (ej. filtrar elementos, contar frecuencias). *(5 puntos)*  
11. [ ] **Se aplica comprensión de listas/conjuntos/diccionarios** o se trabaja con listas anidadas (ej. matriz 2D). *(5 puntos)*  

### Manejo de Texto y Archivos (8 puntos)

12. [ ] **Se lee o escribe un archivo externo** (CSV, JSON o texto) usando `with open()` o `pathlib`. *(4 puntos)*  
13. [ ] **Se usan expresiones regulares** (módulo `re`) o métodos avanzados de cadenas como `strip`, `replace` o `find`. *(4 puntos)*  

### Programación Orientada a Objetos (12 puntos)

14. [ ] **Se define una clase con el método `__init__`** y al menos dos atributos. *(6 puntos)*  
15. [ ] **Se implementa un principio de POO**: encapsulación (atributos privados con `__`), herencia (clase derivada) o polimorfismo. *(6 puntos)*  

### Algoritmia (10 puntos)

16. [ ] **Se implementa un algoritmo clásico** como búsqueda binaria, ordenamiento burbuja o backtracking (ej. problema de las 8 reinas). *(6 puntos)*  
17. [ ] **Se incluye un análisis de complejidad** (notación O-grande) o comentarios sobre la eficiencia del algoritmo. *(4 puntos)*  

### Bibliotecas Científicas (15 puntos)

18. [ ] **Se usan arrays de NumPy** para cálculos numéricos (ej. operaciones vectorizadas, creación con `zeros`/`arange`). *(5 puntos)*  
19. [ ] **Se genera al menos una gráfica 2D con Matplotlib** (ej. línea, dispersión, histograma) con ejes etiquetados y título. *(5 puntos)*  
20. [ ] **Se manipulan datos con Pandas** (ej. creación de DataFrame, filtrado con condiciones o uso de `groupby`). *(5 puntos)*  

---

## 3. Calidad Técnica y Originalidad (20 puntos)

21. [ ] **El código incluye comentarios explicativos** y las celdas de Markdown detallan el propósito de cada sección. *(7 puntos)*  
22. [ ] **El tema es original** y aplica conceptos de física/matemáticas computacionales (ej. simulación de partículas, optimización matemática). *(8 puntos)*  
23. [ ] **Los resultados son reproducibles**: los datos están incluidos o accesibles, y el código ejecuta sin errores al reiniciar el kernel. *(5 puntos)*  

---

## 4. Entrega y Cumplimiento (15 puntos)

24. [ ] **El cuaderno se ejecuta completamente sin errores** después de reiniciar el kernel. *(6 puntos)*  
25. [ ] **Tiene al menos 10 celdas de código relevantes** (excluyendo celdas vacías o de prueba). *(5 puntos)*  
26. [ ] **Se citan al menos dos referencias externas** (artículos, libros o tutoriales) relacionadas con el tema. *(4 puntos)*  

## Ideas de Proyecto Final

## 1. **Clase POO para el Grupo Simétrico y descomposición en ciclos**  

- **Complejidad:** 🔴  
- **Descripción:**  
  Implementar una clase para representar permutaciones y descomponerlas en ciclos disjuntos. Requiere dominio de álgebra abstracta, diseño de métodos para operaciones grupales (composición, inversa) y validación de propiedades matemáticas.  

## 2. **Programación lineal y algoritmo Simplex**  

- **Complejidad:** 🔴  
- **Descripción:**  
  Crear un solver básico para problemas de optimización lineal. Involucra manipulación de tablas Simplex, pivotes y manejo de restricciones. Reto técnico: evitar ciclos infinitos y garantizar convergencia.  

## 3. **Test de primalidad de Miller-Rabin**  

- **Complejidad:** 🟡  
- **Descripción:**  
  Implementar un test probabilístico para detectar primos usando aritmética modular y exponenciación rápida. Ideal para aplicar recursividad y manejar números grandes.  

## 4. **Triangulación de Delaunay**  

- **Complejidad:** 🔴  
- **Descripción:**  
  Generar una triangulación de un conjunto de puntos que maximice los ángulos mínimos. Complejidad alta por la necesidad de algoritmos geométricos (ej. "divide y vencerás") y validación de la propiedad de Delaunay.  

## 5. **Algoritmo de las K-medias**  

- **Complejidad:** 🟡  
- **Descripción:**  
  Clustering de datos usando un enfoque iterativo. Requiere cálculo de centroides, métricas de distancia (Euclidiana) y visualización de resultados con Matplotlib.  

## 6. **Algoritmo PageRank**  

- **Complejidad:** 🟡  
- **Descripción:**  
  Simular el algoritmo de ranking de páginas web usando matrices de transición y cálculos de autovalores. Uso de NumPy para álgebra lineal y Pandas para manejar grafos grandes.  

## 7. **Análisis de una red social (Facebook)**  

- **Complejidad:** 🟢/🟡  
- **Descripción:**  
  Analizar métricas de redes (grado, betweenness, clustering) con NetworkX. Carga de datos desde CSV/JSON, visualización de grafos y detección de comunidades.  

## 8. **Simulación de ondas en una cuerda con PDEs**  

- **Complejidad:** 🔴  
- **Descripción:**  
  Resolver la ecuación de onda unidimensional usando métodos numéricos (diferencias finitas). Requiere POO para modelar la cuerda, NumPy para cálculos matriciales y Matplotlib para animar la propagación de ondas.  

## 9. **Algoritmo genético para optimizar rutas de entrega**  

- **Complejidad:** 🟡  
- **Descripción:**  
  Implementar operadores de selección, cruza y mutación para minimizar distancias. Incluye visualización de rutas óptimas, uso de Pandas para datos de ubicaciones y análisis de convergencia del algoritmo.  

## 10. **Predicción de series temporales en mercados financieros**  

- **Complejidad:** 🟡  
- **Descripción:**  
  Aplicar modelos ARIMA o suavizado exponencial con `statsmodels` y Pandas. Generar gráficos interactivos con Matplotlib, validar predicciones y documentar métricas de error (MAE, RMSE).  
