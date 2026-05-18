# :brain: :robot: _Neural-EmoBot_  
(En desarrollo)

<!--  
### :file_folder: Estructura del código
```
📁 LLM-Chatbot
|
│── 📁 data
│   |── Manual de usuario.pdf                 # Archivos pdf para el RAG
│   └── Manual de usuario.pdf                 # Archivos pdf para el RAG
│
│── 📁 src
│   |── app.py        # Estructura principal del Streamlit y modelo LLM (Código principal)
│   └── rag.py        # Implementación del RAG (Módulo lógica de la técnica RAG)
|
│── .gitignore        # Archivos en .gitgnore
│── LICENSE           # Licensia MIT
│── README.md         # Archvio readme, descripción del proyecto
│── hello.py          # Archivo inicial al hacer uv init
│── pyproject.toml    # Apartado donde se encuentra la descripción del uv (versión python, librerías instaladas)
└── uv.lock           # Lista de versiones de paquetes y dependencias para que el entorno sea reproducido sin problemas.
```

### :: Pruebas de preguntas
> [!NOTE]
> La pregunta es para el libro "La vuelta al mundo en 80 días"
- Q1: Quien es el autor del libro?
- RM: El autor del libro "La vuelta al mundo en 80 días" es Jules Verne.

> [!NOTE]
> La pregunta es para el manual "Manual de Usuario.pdf"
- Q2: Cómo debería limpiar el módulo de base del equipo?
- RM: Para limpiar el módulo base, se debe:
  - Apagar el modulo base y desconectar cualquier conexión activa.
  - Desinfectar los módulos.
  - Limpiar con trapos secos o ligeramente húmedos cada componente del equipo.
  - Inspeccionar visualmente el instrumento y sus componentes para detectar daños o desgaste.


### :dart: Características
- Consulta inteligente de PDFs.
- Respuestas contextualizadas con Langchain, Ollama y técnicas RAG.
- Procesamiento interno de PDFs y generación de embeddings.
- Monitoreo y Trazabilidad con LangSmith del chatbot.
- Interfaz de usuario intuitiva con Streamlit.
- Configuración de parámetros para el modelo (temperature, top_p, etc).
- Si cuentas con modelos en Ollama, los extrae y te permite elegir con un selectbox, el modelo que gustes.

### :rocket: Tecnologías usadas
- Python
- uv
- Ollama
- Streamlit
- LangChain

### :framed_picture: Visualización de la aplicación

| App Streamlit | LangSmith |
|-----------| -------------|
| ![InterfazST](./data/Interfaz_ST.jpg) | ![LangSmith](./data/validacion_LangSmith.jpg) |

| App resultado |
|------------------|
| ![app](./data/interfaz_function.jpg) |

---
## :hammer_and_wrench: Configuración

### 1. Descargar Ollama y uv
- Ollama - [Download](https://ollama.com/)
- uv - [Terminal](https://docs.astral.sh/uv/#__tabbed_1_1)
> [!IMPORTANT]
> Para correr satisfactoriamente la aplicación y configuración debes contar con UV Python y Ollama (LLMs Open Source).

### 2. Instalar modelos de Ollama:
```bash
# Validar modelos de Ollama descargados
ollama list

# Descargar modelos qwen3
ollama run qwen3:latest
```

### 3. Clona el repositorio e instalar dependencias
```bash
git clone https://github.com/DonLuisM/LLM-Chatbot.git
cd LLM-Chatbot

uv sync
```

### 4. Ejecutar la app en Streamlit
```bash
uv run streamlit run .\src\app.py 
```

-->

### :scroll: Licencia
Licencia MIT – consulta el archivo [LICENSE](./LICENSE) para más detalles.

### :handshake: Contribuciones
Si deseas contribuir a este proyecto, siéntete libre de hacer un fork del repositorio y enviar un pull request. ¡Todas las contribuciones son bienvenidas!

### :busts_in_silhouette: Autor:
- [@DonLuisM](https://github.com/DonLuisM)
