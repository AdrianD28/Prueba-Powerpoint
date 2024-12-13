# Proyecto PowerPoint Automático

Este proyecto es una aplicación de Python que crea y modifica presentaciones de PowerPoint automáticamente. Utiliza la biblioteca `python-pptx` para generar diapositivas y actualizar el contenido de manera programática.

## Características

- **Creación de Presentaciones**: Genera un archivo PowerPoint con una diapositiva inicial.
- **Modificación de Contenido**: Cambia el texto de la diapositiva de "Hola" a "Gracias" y lo centra en la diapositiva.

## Requisitos

- Python 3.x
- `python-pptx` (instalable a través de pip)

## Instalación

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/AdrianD28/Prueba-Powerpoint.git
   ```

2. Crea un entorno virtual (opcional pero recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows usa `venv\Scripts\activate`   ```

3. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt   ```

## Uso

1. Ejecuta el script principal para crear y modificar la presentación:
   ```bash
   python app/main.py   ```

2. Verifica que el archivo `trial.pptx` se haya creado y modificado correctamente en el directorio raíz del proyecto.

## Pruebas

Para ejecutar las pruebas y verificar que todo funciona correctamente, usa:
