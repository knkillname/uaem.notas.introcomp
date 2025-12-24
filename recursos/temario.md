# Temario

Como se menciona en el prólogo, este curso fue impartido en sesiones maratónicas de 5 horas cada una, con un total de 13 clases.
Si eres un profesor o estudiante interesado en replicar este curso, puedes adaptar el contenido a un formato más tradicional de clases semanales.
A continuación se presenta un temario detallado de las 13 clases, incluyendo los temas tratados.

## Clase 1: Introducción a la Ciencia de la Computación

* **Contenido:**
  * Definición y alcance de la Ciencia de la Computación.
  * Breve historia de la computación: desde las primeras ideas de cálculo (huesos de Ishango, ábaco) y la máquina analítica de Babbage, hasta la computación moderna (Turing, Von Neumann), la era personal y la computación en la nube.
  * Concepto de algoritmo y su expresión.
  * Arquitectura de Von Neumann: Introducción mediante la "computadora del hombre pequeño" (LMC).
  * Sistemas de numeración posicionales (decimal, binario, hexadecimal).
* **Herramientas:** Introducción a Jupyter Notebooks (Práctica 1).

## Clase 2: Fundamentos de Programación en Python

* **Contenido:**
  * La REPL de Python y su uso interactivo.
  * Variables, identificadores y tipos de datos básicos (enteros, flotantes, cadenas, booleanos).
  * Operaciones aritméticas y expresiones; orden de evaluación.
  * Funciones aritméticas integradas (`round`, `abs`).
  * Manejo de cadenas de texto: creación, concatenación, repetición, longitud.
  * Introducción a módulos de la Biblioteca Estándar: `math` (pi, e, sin), `random`, `statistics`.
  * Definición y llamada de funciones personalizadas.
* **Práctica:** Cifrado César (Práctica 2), enfocada en manipulación de cadenas y funciones.

## Clase 3: Lógica Booleana y Estructuras Condicionales

* **Contenido:**
  * Lógica booleana: valores `True` y `False`, proposiciones, operadores de comparación.
  * Operadores booleanos (`and`, `or`, `not`); tablas de verdad.
  * Otros operadores lógicos (XOR, implicación) y leyes del álgebra booleana (De Morgan).
  * Estructuras de control condicional: `if`, `elif`, `else`.
  * Anidamiento de condicionales y aplicaciones en la toma de decisiones.
  * Introducción preliminar a las funciones recursivas (ej. factorial como ejemplo).

## Clase 4: Recursividad a Profundidad

* **Contenido:**
  * Relación entre la inducción matemática y la recursividad.
  * Estructura de una función recursiva: caso base y paso recursivo.
  * La pila de llamadas (`call stack`): cómo gestiona Python las llamadas recursivas (`inspect.stack`, `RecursionError`).
  * Visualización de la recursión: árboles de llamadas.
  * Estudio de caso: Las Torres de Hanói.
* **Práctica:** Potenciación modular recursiva (Práctica 3).

## Clase 5: Iteración: Ciclos y Generadores

* **Contenido:**
  * El ciclo `while`: sintaxis y ejemplos (raíz cuadrada por método babilónico, conjetura de Collatz).
  * La instrucción `break` para terminar ciclos.
  * Iterables e iteradores: `iter()`, `next()`, manejo de `StopIteration` con `try-except`.
  * Generadores: la palabra clave `yield` para producir secuencias de valores de forma perezosa.
  * El ciclo `for`: iteración sobre secuencias e iterables.
  * La función `range()` para generar secuencias numéricas.
* **Práctica:** Verificación de un Sudoku (Práctica 4), aplicando iteración y manejo de listas anidadas.

## Clase 6: Estructuras de Datos Fundamentales

* **Contenido:**
  * Listas:
    * Repaso de operaciones básicas.
    * Comprensión de listas para creación y filtrado.
    * Listas anidadas (ej. representación de matrices o tableros).
    * Uso de listas como pilas (operaciones `append` y `pop`).
  * Conjuntos (`set`):
    * Creación, operaciones de conjuntos (unión, intersección, etc.).
    * Comprensión de conjuntos.
    * Aplicaciones: eliminación de duplicados, verificación de pertenencia.
  * Diccionarios (`dict`):
    * Pares clave-valor, acceso, iteración.
    * Comprensión de diccionarios.
    * Manejo de datos estructurados y anidados.
  * Tuplas: como colecciones inmutables.
  * Concepto de mutabilidad e inmutabilidad; la función `hash`.

## Clase 7: Manejo Avanzado de Texto y Archivos

* **Contenido:**
  * Cadenas de texto (`str`):
    * Propiedades (inmutabilidad), alfabetos (ASCII, Unicode).
    * Operaciones, indexación, rebanado (slicing).
    * Métodos comunes de cadenas (`lower`, `upper`, `strip`, `replace`, `split`, `join`, `find`, etc.).
    * Interpolación y formato de cadenas: `str.format()`, f-strings y mini-lenguaje de formato.
  * Expresiones Regulares:
    * Introducción al módulo `re`.
    * Sintaxis básica y patrones comunes para búsqueda y manipulación de texto.
  * Manejo de Archivos:
    * Conceptos de sistema de archivos.
    * Uso de `pathlib` para manipulación de rutas.
    * Lectura y escritura de archivos de texto (uso de `with open(...)`).
    * Trabajo con formatos de datos: JSON (módulo `json`) y CSV (módulo `csv`).
* **Práctica:** Mini-motor de recomendaciones (Práctica 5), utilizando diccionarios y conjuntos para modelar preferencias de usuarios.

## Clase 8: Programación Orientada a Objetos (OOP)

* **Contenido:**
  * Conceptos fundamentales: clases, objetos, atributos y métodos.
  * El método constructor (`__init__`) y el parámetro `self`.
  * Principios de OOP:
    * Encapsulación (atributos privados con `__`).
    * Herencia (clases base y derivadas, `super()`).
    * Polimorfismo.
  * Métodos especiales (dunder methods): `__str__`, `__repr__`, `__len__`, `__add__`, `__divmod__`, etc., para personalizar el comportamiento de los objetos.
  * Clases Base Abstractas (ABCs) del módulo `collections.abc`.
  * Ejemplos prácticos: `datetime.datetime`, `fractions.Fraction`, clase `Polinomio`.
* **Práctica:** Analizador de chat de WhatsApp (Práctica 6), modelando mensajes y conversaciones con clases.

## Clase 9: Introducción a la Algoritmia y Análisis de Complejidad

* **Contenido:**
  * Definición de problemas computacionales: entradas, salidas y la relación entre ellas.
  * Ejemplos de problemas computacionales clásicos (búsqueda, ordenamiento, suma de subconjunto, 8 reinas).
  * Concepto de algoritmo como solución a un problema computacional.
  * Análisis de algoritmos:
    * Complejidad temporal: peor caso, mejor caso, caso promedio.
    * Conteo de operaciones.
    * Crecimiento asintótico y Notación O-grande ($O$) para describir la eficiencia.

## Clase 10: Diseño de Algoritmos

* **Contenido:**
  * Estrategias de diseño de algoritmos:
    * **Fuerza Bruta:** Exploración exhaustiva (ej. problema de la mochila).
    * **Vuelta Atrás (Backtracking):** Construcción incremental y poda (ej. problema de las 8 reinas).
    * **Algoritmos Voraces (Greedy):** Decisiones óptimas locales (ej. Árbol de Expansión Mínima - Algoritmo de Prim, introducción a montículos).
    * **Programación Dinámica:** Subproblemas superpuestos y subestructura óptima, memoización (ej. Fibonacci, problema de la mochila 0/1).
  * Relación entre técnicas de diseño y estructuras de datos.
* **Práctica:** El Poder de los Montículos (Práctica 7), implementando un heap.

## Clase 11: Fundamentos de Cómputo Científico: NumPy y Matplotlib

* **Objetivo:** Introducir las bibliotecas esenciales para cómputo numérico y visualización.
* **Contenido:**
  * **NumPy**
    * Arrays N-dimensionales: creación (`array`, `zeros`, `ones`, `arange`, `linspace`).
    * Operaciones vectorizadas y broadcasting básico.
    * Indexación y slicing avanzado.
    * Funciones universales (`ufuncs`) comunes: `sin`, `cos`, `exp`, `sqrt`, etc.
  * **Matplotlib**
    * Creación de gráficas 2D básicas: `plot()`.
    * Personalización: etiquetas (`xlabel`, `ylabel`), títulos (`title`), leyendas (`legend`).
    * Múltiples figuras y subplots básicos.
    * Ejemplos de visualización de funciones y datos generados con NumPy.

## Clase 12: Manipulación de Datos con Pandas y Vistazo a SciPy

* **Objetivo:** Introducir la manipulación de datos estructurados y funciones científicas avanzadas.
* **Contenido:**
  * **Pandas**
    * Estructuras de datos: Series y DataFrames.
    * Creación de DataFrames desde diccionarios o arrays de NumPy.
    * Selección y filtrado de datos (indexación basada en etiquetas y posiciones, condiciones booleanas).
    * Lectura/escritura de archivos CSV.
    * Operaciones básicas y estadísticas descriptivas (`describe`, `mean`, `sum`, `groupby` básico).
  * **SciPy**
    * Introducción general a SciPy y sus principales módulos.
    * Ejemplos prácticos seleccionados de `scipy.stats` (e.g., distribuciones, test de hipótesis simple) o `scipy.optimize` (e.g., ajuste de curvas básico, minimización de funciones).
* **Práctica:** Análisis de Datos Científicos (Práctica 8) integrando Numpy, Pandas, SciPy, Matplotlib y SymPy.

## Clase 13: Taller de Proyecto Final y Repaso General

* **Objetivo:** Brindar apoyo para el proyecto final y preparar a los estudiantes para el examen general.
* **Contenido:**
  * **Taller de Proyecto Final**
    * Sesión de trabajo práctico donde los estudiantes avanzan en sus proyectos.
    * Asesoría individualizada y resolución de dudas por parte del profesor.
  * **Repaso General**
    * Revisión de los conceptos clave de las Clases 1-10.
    * Resolución de dudas y ejemplos tipo examen.
    * Última ronda de preguntas.
