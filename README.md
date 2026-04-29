# Instrucciones de Ejecución - Mi API FastAPI

Este proyecto es una API básica construida con FastAPI. A continuación se detallan los pasos para configurar y ejecutar el proyecto localmente.

## Requisitos Previos

*   Python 3.7 o superior instalado.
*   Pip (administrador de paquetes de Python).

## Configuración del Proyecto

1.  **Clonar o acceder a la carpeta del proyecto:**
    Asegúrate de estar en la raíz del proyecto `mi-api-fastapi-python`.

2.  **Crear un entorno virtual (opcional pero recomendado):**
    Si aún no tienes uno, puedes crearlo con:
    ```bash
    python -m venv venv
    ```

3.  **Activar el entorno virtual:**
    *   **En Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
    *   **En macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```

4.  **Instalar las dependencias:**
    Ejecuta el siguiente comando para instalar FastAPI y Uvicorn:
    ```bash
    pip install -r requirements.txt
    ```

## Ejecución de la API

Para iniciar el servidor de desarrollo, ejecuta:

```bash
uvicorn main:app --reload
```

*   `main`: se refiere al archivo `main.py`.
*   `app`: se refiere a la instancia de `FastAPI()` creada dentro de `main.py`.
*   `--reload`: permite que el servidor se reinicie automáticamente al detectar cambios en el código.

## Acceso a la API

Una vez que el servidor esté corriendo (usualmente en `http://127.0.0.1:8000`):

*   **Ruta raíz:** [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
*   **Documentación Interactiva (Swagger UI):** [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)
*   **Documentación Alternativa (Redoc):** [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc)

---
Desarrollado para la Actividad 1-T4 - ADSO.
