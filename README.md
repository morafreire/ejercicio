# Analizador de Conversaciones

## ¿Qué hace?

Este repositorio tiene como objetivo explorar y determinar el tópico de todas las conversaciones entre un cliente y un agente de contact center. Como la desgrabación de cada llamada no es clara, tanto por el formato como por su contenido, se tuvo que hacer una carga y limpieza de datos, y luego el procesamiento de cada conversación utilizando un modelo de LLM.

## Cómo Usarlo

1. Clonar este repo.
2. Abrir `ejercicio_tecnico.ipynb` en Jupyter Notebook o VS Code.
3. Establecer una clave API válida en `api_key`, ya que usamos la API de OpenAI y el modelo `gpt-3.5-turbo-1106` para analizar las conversaciones.
3. Ejecutar las celdas para ver qué hay dentro de las conversaciones (los comentarios en el código hacen que se entienda mejor el paso a paso).

## Contenido del Repo

- `corpus`: Carpeta con archivos CSV de las conversaciones.
- `ejercicio_tecnico.ipynb`: Notebook con el código.


