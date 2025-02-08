
# 📚 uaem.notas.introcomp: Introducción a la Computación para Estudiantes de Ciencias

*¿Programar es como demostrar un teorema o más como hornear un pastel? ¿A qué sabe un código bien escrito? ¡Descúbrelo aquí!*  
Repositorio del curso de computación para primer semestre de la licenciatura en Ciencias de la [Universidad Autónoma del Estado de Morelos](https://www.uaem.mx/) del [Dr. Mario Abarca](https://www.knkillname.org/).  
**Nota:** Todo el material está diseñado para usarse en [Google Colab](https://colab.research.google.com). ¡Cero instalaciones requeridas! 🚀

---

## 🌟 Contenido

- **Cuadernos autocontenidos:** Cada clase es un archivo `.ipynb` listo para ejecutar en Colab.
- **Enlaces a recursos externos:** Tutoriales, artículos históricos y herramientas en la nube.
- **Configuraciones avanzadas (opcional):** Soporte para Pipenv y DevContainer (solo expertos).

---

## 🚀 ¿Cómo empezar?

### Para el 99% de los estudiantes (¡recomendado!)

1. **Accede a cualquier clase:**  
   - Haz clic en el cuaderno deseado (ej: `Clase1_Introducción.ipynb`).
   - Presiona el botón <img src="https://colab.research.google.com/assets/colab-badge.svg" width="80"> (arriba a la derecha).
2. **Ejecuta el código:**  
   - Usa `Ctrl + Enter` o `▶️` para correr celdas.
   - **¡Listo!** No necesitas instalar nada. ✨

### Para el 1% rebelde con Python 3.12 y Docker

#### Opción A: Pipenv

1. **Instala Pipenv:**

    ```bash
    pip install pipenv
    ```

2. **Instala dependencias y abre Jupyter Notebook:**

    ```bash
    pipenv install
    pipenv run jupyter notebook
    ```

#### Opción B: DevContainer (VS Code + Docker)

1. **Instala [Docker](https://www.docker.com/get-started) y [VS Code](https://code.visualstudio.com/):**
2. **Abre el repositorio en VS Code y haz clic en "Reopen in Container".**

---

## ❓ Preguntas Frecuentes

### 1. *"¿Por qué debo aprender Python si quiero ser matemático puro?"* 🤔  

- **Respuesta corta:** Porque hasta Grothendieck necesitaba herramientas. 🔧  
- **Respuesta larga:** La programación te permite:  
  - Simular conjeturas (ej: ¿Es cierta la conjetura de Collatz para 10^6 números?).  
  - Visualizar espacios abstractos (ej: gráficas 4D proyectadas en 2D).  
  - *Bonus secreto:* Si te aburres, puedes programar un poema en código binario. 💻  

### 2. *"¿Me aprueba si solo veo los cuadernos desde Colab?"* 😇  

- **Respuesta corta:** No. 🚫  
- **Respuesta larga:** Nooooooooooooooooooooooooooooooooooooooooooooooooo.  
  - **Motivo:** Ver no es igual a hacer. ¡Ejecuta el código, modifícalo, *experimenta*!  

### 3. *"¿Qué hago si mi código da error?"* 🔥  

- **Paso 1:** No entres en pánico (es normal).  
- **Paso 2:** Lee el mensaje de error (la parte roja *a veces* ayuda).  
- **Paso 3:** Usa ChatGPT para traducir el error a español y pide ayuda en el foro.  

---

## 🗂️ Estructura del Repositorio

```plaintext
uaem.notas.introcomp/
├── 📁 cuadernos/
│   ├── 📘 1.Introducción.ipynb            # ¡Empieza aquí!
│   ├── 📘 2-3.Fundamentos_Python.ipynb
│   ├── ...                                # Para cuando termines el curso habrá 15 clases
├── 📁 prácticas/
│   ├── 📄 1.JupyterNotebooks.md           # Guía de prácticas
│   ├── ...
├── 📁 recursos/
│   ├── 📄 temario.md                      # Temario del curso
│   ├── 📄 rubricas.md                     # Rúbricas de evaluación
│   └── ...
├── 📄 Pipfile                             # Para Pipenv (Python 3.12)
├── 📁 .devcontainer/                      # Configuración Docker (opcional)
│   └── 📄 devcontainer.json
└── 📄 README.md                           # Este archivo
```

---

## ⚙️ Configuración Avanzada (solo si sabes lo que haces)

### Pipenv (Python 3.12)

```bash
pipenv install --ignore-pipfile  # Instala dependencias
pipenv shell                      # Activa el entorno
jupyter notebook                  # Abre Jupyter local
```

### DevContainer en VS Code

1. Instala [Docker](https://www.docker.com/) y [VS Code](https://code.visualstudio.com/).  
2. Abre el repositorio en VS Code y haz clic en **"Reopen in Container"**.  
3. ¡El entorno se construirá automáticamente! 🐳  

---

## 📜 Licencia

Este material es libre bajo [Licencia MIT](LICENSE). Se permite:  

- Usar, modificar y compartir.  
- Hacer memes matemáticos (si son buenos, envíalos al profesor). 😎  

---

*¿List@ para dominar la computación como un verdadero computólogo?*  
**Haz clic en `Clase1_Introducción.ipynb` y ¡comienza el viaje!** 🌌
