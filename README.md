# API Request to Claude

Coleccion de notebooks para practicar integracion con modelos de lenguaje y tecnicas de prompt engineering, desde solicitudes basicas hasta control de salida estructurada.

## Contenido

- `001_requests.ipynb`: primeras solicitudes a la API.
- `002_multichat.ipynb`: manejo de conversaciones con multiples turnos.
- `003_ChatBot-exercise.ipynb`: ejercicio de chatbot.
- `004_SystemPrompts.ipynb`: uso de system prompts.
- `005_SystemPrompts-FlexibleChat.ipynb`: prompts de sistema en chats flexibles.
- `006_SystemPrompts-Exercise.ipynb`: ejercicio de system prompts.
- `007_Temperature.ipynb`: impacto de la temperatura en respuestas.
- `008_StreamEvents.ipynb`: streaming de eventos/respuestas.
- `009_ControllingOutput-Exercise.ipynb`: ejercicio para controlar formato de salida.
- `009_ControllingOutput-StructuredData.ipynb`: salida estructurada (JSON/datos).

## Requisitos

- Python 3.10 o superior.
- Jupyter Notebook o VS Code con extensiones de Python/Jupyter.
- Variables de entorno configuradas en `.env`.

## Uso rapido

1. Crea y activa un entorno virtual.
2. Instala dependencias necesarias para tus notebooks.
3. Configura tus claves en `.env`.
4. Abre los notebooks en orden numerico.

## Recomendaciones

- No subas secretos ni claves API. Este repositorio ya ignora `.env`.
- Ejecuta cada notebook de arriba hacia abajo para evitar errores de estado.
- Si modificas un notebook, intenta mantener una salida limpia antes de commitear.

## Orden sugerido de aprendizaje

`001` -> `002` -> `003` -> `004` -> `005` -> `006` -> `007` -> `008` -> `009`

## Licencia

Uso educativo/personal.
