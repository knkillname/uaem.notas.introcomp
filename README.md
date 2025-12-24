# 📚 uaem.notas.introcomp: Introducción a la Computación para Estudiantes de Ciencias

> *"La computación no trata sobre computadoras más que la astronomía trata sobre telescopios."*
>
> — Edsger Dijkstra.

Este repositorio nació como el material oficial del curso de primer semestre en la Licenciatura en Ciencias de la [Universidad Autónoma del Estado de Morelos](https://www.uaem.mx/) (UAEM). Aunque mi camino profesional me ha llevado de la academia a liderar equipos de ingeniería en la industria, he decidido mantener y expandir estas notas *por puro antojo* y por una convicción profunda: la teoría de la computación es el único conocimiento que no caduca, y Python es el mejor lenguaje para experimentar con ella.

¿Para quién es esto?

* **Estudiantes autodidactas** que buscan rigor sin la frialdad de un libro de texto. 🧠
* **Profesores** que necesiten una referencia de lo que se enseñó previamente en esta cátedra. 🏫
* **Hispanohablantes** que buscan material de calidad en su idioma (porque la ciencia no debería tener barreras lingüísticas). 🇲🇽🇪🇸
* **Mi hijo**, por si algún día decide que este laberinto de lógica es útil para su vida. ❤️

## 🌟 Contenido Detallado

Este repositorio alberga una variedad de materiales para facilitar tu aprendizaje en Introducción a la Computación:

* **📘 Cuadernos de Clase Principales:** El corazón del curso reside en la carpeta `cuadernos/`. Cada archivo `.ipynb` representa una clase, diseñado para ser interactivo y ejecutable directamente en Google Colab. Cubren desde la introducción hasta temas de cómputo científico.
* **📝 Guías de Prácticas:** En la carpeta `prácticas/`, encontrarás archivos `.md` con ejercicios y guías para aplicar los conocimientos adquiridos en los cuadernos.
* **📚 Recursos Adicionales:** La carpeta `recursos/` contiene material de apoyo crucial:
  * `temario.md`: El plan de estudios detallado del curso. 📜
  * `bibliografía.md`: Referencias y lecturas recomendadas para profundizar. 📖

## 🚀 ¿Cómo empezar?

1. **Accede a cualquier clase:**  
   * Haz clic en el cuaderno deseado (ej: `cuadernos/01.Introducción.ipynb`).
   * Presiona el botón ![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg) (que aparece al visualizar el cuaderno).
2. **Ejecuta el código:**  
   * Usa ⬆️ + ↩️ en tu teclado o el ícono ▶️ para correr celdas.
   * **¡Listo!** No necesitas instalar nada. ✨

## ❓ Preguntas Frecuentes

### 1. *\"¿Por qué debo aprender Python si quiero ser matemático puro?\"* 🤔  

* **Respuesta corta:** Porque hasta Grothendieck necesitaba herramientas. 🔧  
* **Respuesta larga:** La programación te permite:  
  * Simular conjeturas (ej: ¿Es cierta la conjetura de Collatz para $10^6$ números?). 💡
  * Visualizar espacios abstractos (ej: gráficas 4D proyectadas en 2D). 🖼️
  * *Bonus secreto:* Si te aburres, puedes programar un poema en código binario. 💻  

### 2. *"¿Me aprueba si solo veo los cuadernos desde Colab?"* 😇  

* **Respuesta corta:** No. 🚫  
* **Respuesta larga:** Nooooooooooooooooooooooooooooooooooooooooooooooooo.  
  * **Motivo:** Ver no es igual a hacer. ¡Ejecuta el código, modifícalo, *experimenta*!  

### 3. *\"¿Qué hago si mi código da error?\"* 🔥  

* **Paso 1:** No entres en pánico (es normal). 🧘
* **Paso 2:** Lee el mensaje de error (la parte roja *a veces* ayuda). 🔍
* **Paso 3:** Usa un asistente de IA (como Gemini, Deepseek, ChatGPT, etc.) para entender el error y obtener sugerencias de solución. 🤖

## 🗂️ Estructura del Repositorio

```plaintext
uaem.notas.introcomp/
├── 📁 .devcontainer/                      # Configuración Docker (opcional)
│   └── 📄 devcontainer.json
├── 📁 cuadernos/
│   ├── 📘 01.Introducción.ipynb           # ¡Empieza aquí!
│   ├── 📘 02.FundamentosPython.ipynb
│   ├── ...                                # (13 clases en total)
├── 📁 prácticas/
│   ├── 📄 1.JupyterNotebooks.md           # Guía de prácticas
│   ├── ...
├── 📁 recursos/
│   ├── 📄 temario.md                      # Temario del curso
│   ├── 📄 bibliografia.md                 # Lecturas recomendadas
│   └── ...
├── 📄 LICENSE                             # Licencia del proyecto
├── 📄 Pipfile                             # Dependencias del proyecto (Python 3.12)
├── 📄 Pipfile.lock                        # Dependencias exactas (generado por Pipenv)
└── 📄 README.md                           # Este archivo que estás leyendo
```

## ⚙️ Configuración Avanzada (solo si sabes lo que haces)

Esta sección es para aquellos que desean ejecutar los cuadernos de Jupyter en su propia máquina local en lugar de usar Google Colab. Esto ofrece más control sobre el entorno, pero requiere familiaridad con herramientas de desarrollo como la línea de comandos, Python y, opcionalmente, Docker.

### Opción 1: Usando Pipenv para un Entorno Virtual de Python

**¿Qué es Pipenv?** Pipenv es una herramienta que combina la gestión de paquetes (pip) con la gestión de entornos virtuales (venv). Crea un entorno aislado para tu proyecto, asegurando que las dependencias no entren en conflicto con otros proyectos de Python en tu sistema. Usaremos Python 3.12. 🐍

**Pasos:**

1. **Instala Pipenv:** Si aún no lo tienes, instálalo globalmente.

   ```bash
   pip install pipenv
   ```

   *Nota: Dependiendo de tu sistema, podrías necesitar `pip3` en lugar de `pip`, o bien, `sudo apt install pipenv` en sistemas basados en Debian/Ubuntu.* 🐧

2. **Instala las dependencias del proyecto:** Navega a la raíz de este repositorio en tu terminal y ejecuta:

   ```bash
   pipenv install --dev
   ```

   * `pipenv install` lee el archivo `Pipfile` para encontrar las dependencias necesarias (como Jupyter Lab, Pandas, etc.).
   * `--dev` asegura que también se instalen las dependencias de desarrollo, útiles para contribuir al proyecto.
   * Esto creará un `Pipfile.lock` (si no existe) que fija las versiones exactas de las dependencias, y un entorno virtual (generalmente dentro de `~/.local/share/virtualenvs/`).

3. **Activa el entorno virtual:** Para usar las dependencias instaladas, necesitas "entrar" en el entorno virtual:

   ```bash
   pipenv shell
   ```

   *Verás que el prompt de tu terminal cambia, indicando que estás dentro del entorno virtual del proyecto.* 💻➡️✨

4. **Inicia Jupyter Lab:** Una vez dentro del entorno, puedes iniciar el servidor de Jupyter:

   ```bash
   jupyter lab
   ```

   *Esto debería abrir automáticamente una pestaña en tu navegador web. Si no es así, busca en la salida de la terminal un mensaje similar a este:* 🌐

   ```plaintext
   Jupyter Server 2.xx is running at:
   http://localhost:8888/lab?token=abcdef1234567890abcdef1234567890abcdef12
   ```

   *Copia la URL (la que empieza con `http://localhost:8888/lab?token=...`) y pégala en tu navegador para acceder a Jupyter Lab. Luego podrás navegar a la carpeta `cuadernos/` y abrir cualquier `.ipynb`.*

5. **Para salir del entorno virtual:** Cuando termines, simplemente escribe `exit` en la terminal. 👋

### Opción 2: Usando DevContainer con VS Code y Docker

**¿Qué es un DevContainer?** Un "Development Container" (Contenedor de Desarrollo) es un entorno de desarrollo completo que se ejecuta dentro de un contenedor Docker. Esto significa que todas las herramientas, extensiones de VS Code, y dependencias del proyecto están preconfiguradas y aisladas del resto de tu sistema. Es ideal para la reproducibilidad y para evitar el clásico "funciona en mi máquina". 📦

**Requisitos Previos:**

* [Docker Desktop](https://www.docker.com/get-started) instalado y en ejecución.
* [Visual Studio Code](https://code.visualstudio.com/) instalado.
* La extensión "Dev Containers" de Microsoft instalada en VS Code (ID: `ms-vscode-remote.remote-containers`).

**Pasos:**

1. **Abre el Repositorio en VS Code:**
   * Clona este repositorio en tu máquina.
   * Abre la carpeta del repositorio con VS Code.

2. **Reabre en el Contenedor:**
   * VS Code debería detectar automáticamente el archivo `.devcontainer/devcontainer.json`.
   * Aparecerá una notificación en la esquina inferior derecha preguntando si deseas "Reopen in Container". Haz clic en ese botón.
   * Si no ves la notificación, puedes abrir la paleta de comandos (`Ctrl+Shift+P` o `Cmd+Shift+P`), escribir "Dev Containers: Reopen in Container" y seleccionarlo.

3. **¡El Entorno se Construirá Automáticamente!** 🐳
   * La primera vez, Docker descargará la imagen base especificada y construirá el contenedor. Esto puede tardar unos minutos.
   * Una vez listo, VS Code se recargará y estarás trabajando *dentro* del contenedor, que ya tendrá Python, Pipenv, Jupyter y las extensiones de VS Code necesarias preinstaladas y configuradas.
   * Puedes abrir una terminal integrada en VS Code y ejecutar `pipenv shell` seguido de `jupyter lab` como en la Opción 1, pero esta vez todo se ejecuta dentro del contenedor aislado.

Esta opción es excelente si ya usas Docker y VS Code, ya que simplifica enormemente la configuración y asegura que todos los colaboradores tengan un entorno idéntico.

## 📜 Licencia

Este material es libre bajo [Licencia MIT](LICENSE). Se permite:  

* Usar, modificar y compartir.  
* Hacer memes matemáticos (si son buenos, envíalos al profesor). 😎  

*¿List@ para dominar la computación como un verdadero computólogo?*  
**Haz clic en `cuadernos/01.Introducción.ipynb` y ¡comienza el viaje!** 🌌
