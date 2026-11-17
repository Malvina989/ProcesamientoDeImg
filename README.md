# Procesamiento De Imágenes
Proyecto desarrollado en el marco de la asignatura **Programación Python Avanzada** de la UPSO

# 📸 FotoApp – Procesamiento de imágenes con Python

## 📌 Descripción

FotoApp es una aplicación desarrollada en Python que permite realizar diferentes operaciones de procesamiento de imágenes mediante las bibliotecas Pillow, OpenCV, NumPy y Matplotlib.

El proyecto ofrece un menú interactivo desde el cual el usuario puede cargar una imagen, adaptarla a distintos formatos para redes sociales, ajustar el contraste, aplicar filtros y generar bocetos mediante técnicas de detección de bordes.

## 🎯 Funcionalidades

La aplicación cuenta con las siguientes opciones:

1. **Carga y redimensionado de imágenes**
   - Permite ingresar la ruta de una imagen.
   - Adapta sus dimensiones a distintos formatos sin deformarla.
   - Plataformas disponibles: YouTube, Instagram, Twitter y Facebook.

2. **Ajuste de contraste**
   - Ecualiza el histograma de la imagen.
   - Muestra una comparación entre la imagen original y la procesada.

3. **Aplicación de filtros**
   - Permite seleccionar entre 9 filtros de Pillow:
     - Blur
     - Contour
     - Detail
     - Edge Enhance
     - Edge Enhance More
     - Emboss
     - Find Edges
     - Sharpen
     - Smooth

4. **Generación de bocetos y detección de bordes**
   - Aplica umbralización binaria.
   - Utiliza el detector de bordes Canny.
   - Muestra una comparación de los resultados.

5. **Menú interactivo**
   - Permite acceder a las diferentes funcionalidades.
   - Valida las opciones ingresadas.
   - Controla los errores cuando se intenta procesar una imagen sin haberla cargado previamente.

## 🛠️ Tecnologías y bibliotecas

- Python 3
- Pillow
- OpenCV
- NumPy
- Matplotlib

## 📂 Estructura del proyecto

```text
FotoApp/
│
├── fotoapp.py
├── fotoapp_testdev.ipynb
├── README.md
└── imagenes/
    └── (imágenes de prueba)
```

## ⚙️ Instalación

Clonar el repositorio:

```bash
git clone URL_DE_TU_REPOSITORIO
```

Ingresar a la carpeta:

```bash
cd FotoApp
```

Instalar las dependencias:

```bash
pip install pillow opencv-python numpy matplotlib requests
```

## ▶️ Ejecución

Para ejecutar la aplicación desde Python:

```bash
python fotoapp.py
```

También se puede importar el módulo y ejecutar el menú:

```python
import fotoapp

fotoapp.ejecutar_menu()
```

Una vez iniciado el menú, seleccionar la opción deseada e ingresar la ruta de la imagen cuando corresponda.

## 🔀 Diagrama de flujo del menú

<img width="1303" height="929" alt="image" src="https://github.com/user-attachments/assets/5b2a2eab-1f6a-4d0c-84ef-9c95a2dbf5f1" />

## 📌 Consideraciones

- Es necesario cargar una imagen antes de utilizar las opciones de procesamiento.
- Las rutas de las imágenes deben corresponder a archivos existentes.
- Los resultados se guardan en el directorio de ejecución o en la carpeta de salida configurada.
- El proyecto fue desarrollado con fines educativos, aplicando conceptos de procesamiento digital de imágenes y programación modular en Python.

## 👩‍💻 Malvina Christiansen | Ramón Daniel Alberto Rodríguez


