# 📂 Explorador Inteligente de Archivos para Google Colab

Una herramienta interactiva construida con Python y `ipywidgets` para Google Colab que permite explorar, filtrar, ordenar, buscar y crear archivos directamente en una carpeta de **Google Drive** con un diseño moderno (*Dark Mode*).

---

## ✨ Características Principales

* **Filtros Avanzados:** Búsqueda global por palabras clave (normalizada sin acentos), filtrado por extensiones (`.json`, `.csv`, `.pdf`, `.txt`), rango de tamaño en KB y fechas de modificación.
* **Ordenamiento Inteligente:** Implementación híbrida de **Insertion Sort** (para listas pequeñas) y **Merge Sort** (para listas grandes), mostrando estadísticas en tiempo real de comparaciones y tiempo de ejecución.
* **Interfaz Moderna (UI/UX):** Estilo visual oscuro inspirado en plataformas web modernas, totalmente responsivo y adaptado para celdas de Google Colab.

---

## 🚀 ¿Cómo utilizarlo en Google Colab?

1. Abre un nuevo notebook en [Google Colab](https://colab.research.google.com/).
2. Copia y pega el código principal de la interfaz en una celda.
3. Ejecuta la celda. El sistema te pedirá autorizar el acceso a tu Google Drive para montar la unidad.

## 📁 Creación de archivos a utilizar
Para que la interfaz muestre resultados desde el inicio, puedes **crear archivos** de esta forma:

**Directamente de Google Colab:** Copia y pega el código de creacion de archivos en una celda, el cual creara los archivos compatibles (`.json`, `.csv`, `.pdf`, `.txt`).

### ⚙️ ¿Cómo cambiar la carpeta de Google Drive?

Por defecto, la aplicación busca o crea una carpeta llamada `InventarioColab` en tu unidad principal. Si deseas utilizar otra ruta personalizada, simplemente modifica la variable **`DIRECTORIO`** al inicio del script:

```python
# Cambia esta ruta por la de tu propia carpeta en Google Drive
DIRECTORIO = '/content/drive/My Drive/MiCarpetaPersonalizada/TuInventario'
```
🛠️ Requisitos y Dependencias
El script utiliza librerías nativas de Python y de Google Colab, por lo que no requiere instalaciones complejas externas:

os, time, unicodedata, datetime

ipywidgets

IPython.display

👨‍💻 Autor / Contribución
Desarrollado como proyecto optimizado para gestión de metadatos y análisis de algoritmos en entornos de Google Colab. ¡Siéntete libre de clonarlo y adaptarlo a tus necesidades!
