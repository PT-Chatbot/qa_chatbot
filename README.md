# QA Chatbot

Este proyecto implementa un chatbot de preguntas y respuestas diseñado para asistir automáticamente a los usuarios en la Universidad del Caribe. Utiliza técnicas avanzadas de procesamiento de lenguaje natural, incluyendo el uso de embeddings para mejorar la comprensión y generación de respuestas.

## Langchain

Langchain es una poderosa biblioteca diseñada para transformar la interacción y el flujo de trabajo con modelos de lenguaje de aprendizaje automático. A continuación, se ofrece una visión general de los temas y cuadernos incluidos en este repositorio, destacando cómo cada uno aborda diferentes aspectos y funcionalidades de Langchain.

### Configuración inicial

Antes de empezar con los notebooks, es esencial establecer un archivo `config.py` en la carpeta correspondiente y colocar su clave API de OpenAI:

```python
OPENAI_API_KEY = 'your_api_key'
```

```python
SERPAPI_API_KEY = 'your_serpapi_api_key'
```

## Características

- **Procesamiento de Lenguaje Natural**: Capacidad para entender y procesar preguntas en lenguaje natural.
- **Respuestas Automatizadas**: Genera respuestas basadas en una amplia base de conocimientos.
- **Aprendizaje Continuo**: Se actualiza constantemente para mejorar su precisión y relevancia.

## Tecnologías Utilizadas

- Python
- Langchain
- OpenAI

## Instalación

Clonar este repositorio y instalar las dependencias:

```bash
git clone https://github.com/PT-Chatbot/qa_chatbot.git
cd qa_chatbot
pip install -r requirements.txt
```
