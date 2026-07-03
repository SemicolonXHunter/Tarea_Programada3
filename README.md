# Tarea_Programada3
Tarea programada 3 del curso Python 2 (RPV) que está basada en la Tarea Programada 2

# Tarea Programada 2 - Procesamiento de Imágenes con Python

## Descripción

Este proyecto fue desarrollado en Python como parte de la Tarea Programada 2 del curso. Su objetivo es automatizar el procesamiento de imágenes mediante la aplicación de diferentes transformaciones y generar un reporte con la información de las imágenes procesadas.

El programa recorre automáticamente las imágenes ubicadas en una carpeta de entrada, realiza el procesamiento solicitado y almacena los resultados en una carpeta de salida, además de crear un archivo Excel con la información correspondiente.

---

## Funcionalidades

- Lectura automática de imágenes desde una carpeta.
- Redimensionamiento de imágenes manteniendo la relación de aspecto.
- Conversión de imágenes a escala de grises.
- Inserción de una marca de agua.
- Almacenamiento de las imágenes procesadas.
- Generación de un reporte en formato Excel con información del procesamiento.

---

## Estructura del proyecto

```
Tarea2_RPV/
│
├── entrada/                # Carpeta donde se colocan las imágenes originales
├── salida/                 # Carpeta donde se guardan las imágenes procesadas
├── source/                 # Archivos fuente de Sphinx
├── main.py                 # Programa principal
├── marca.png               # Imagen utilizada como marca de agua
├── requirements.txt        # Dependencias del proyecto
├── reporte_imagenes.xlsx   # Ejemplo de un reporte generado
├── Makefile
└── make.bat
```

---

## Requisitos

- Python 3.11 o superior
- pip

Bibliotecas utilizadas:

- Pillow
- XlsxWriter
- Sphinx (para la documentación)

---

## Instalación

Instalar las dependencias ejecutando:

```bash
pip install -r requirements.txt
```

---

## Ejecución

Para ejecutar el programa:

```bash
python main.py
```

El programa procesará todas las imágenes ubicadas en la carpeta `entrada` y guardará los resultados en la carpeta `salida`.

---

## Documentación

La documentación fue generada utilizando **Sphinx**.

Para construir nuevamente la documentación:

```bash
make html
```

En Windows:

```bash
make.bat html
```

Los archivos HTML generados se encuentran en:

```
build/html/index.html
```

---

## Tecnologías utilizadas

- Python 3.11
- Pillow
- XlsxWriter
- Sphinx
- Git
- GitHub

---

## Autor

**Ricardo Palacios**