WhiTTsper the Lora
============
<a href="https://github.com/ImPavloh/WhiTTsper-The-Lora" target="_blank"><img src="https://img.shields.io/github/stars/ImPavloh/WhiTTsper-The-Lora?style=social&label=Star&maxAge=2592000" alt="Test"></a> [![Live Demo](https://img.shields.io/badge/demo-online-green.svg)](https://colab.research.google.com/drive/11MHiNlhQ0ZSqKVl0Fniu085bkQRdJX9E?usp=sharing) <a href="https://github.com/ImPavloh/WhiTTsper-The-Lora/blob/master/LICENSE" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a> <a href="https://twitter.com/ImPavloh" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>


Demo que combina Whisper para el reconocimiento de voz y Google TTS para la síntesis de voz para interactuar junto Alpaca-LoRA.

![Chat Preview](https://i.imgur.com/qq6vS1E.png)

---

## Características
- Reconocimiento de voz (Whisper)
- Modelo de lenguaje basado en LLaMa 7B
- Síntesis de voz con Google Text-to-Speech
- Interfaz gráfica con gradio

## TODO
- Conversación seguida con contexto
- Agregar más modelos de lenguaje (ej. gpt-j-6B)
- Usar una IA avanzada para la síntesis de voz
- Optimizar y hacer el código compatible en distintas plataformas (ej. Windows, Linux, etc.)
- Modificar la interfaz gráfica añadiendo configuraciones extra (ej. idioma, vista previa, ajustar la temperatura para la generación de texto, etc.)

---

## Uso

Para utilizar la demo, es necesario tener acceso a un micrófono.
Al ejecutar todo el código, se abrirá una interfaz gráfica en la que se puede hablar en el micrófono y obtener una respuesta de la IA Alpaca-LoRA.

En la interfaz gráfica, se puede seleccionar el tamaño del modelo de Whisper a utilizar (tiny, base, small, medium, large). El tamaño del modelo afecta el tiempo de respuesta de la IA y la calidad de la respuesta generada.

---

## Apoya el proyecto

Tanto si utilizas este proyecto como si has aprendido algo de él o simplemente te gusta, considera la posibilidad de apoyarlo invitándome a un café, para que pueda dedicar más tiempo a proyectos de código abierto como éste :)

<a href="https://www.buymeacoffee.com/pavloh" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

---

## Créditos

Se utiliza como modelo de lenguaje [Alpaca-LoRA](https://github.com/tloen/alpaca-lora). El código utiliza la librería de Transformers de Hugging Face para el modelo. 
También se utiliza la tecnología de reconocimiento de voz [Whisper](https://github.com/openai/whisper) de OpenAI y la tecnología de síntesis de voz [Google Text-to-Speech](https://github.com/pndurette/gTTS).
La interfaz gráfica es creada utilizando la librería [Gradio](https://github.com/gradio-app/gradio).

---
## Licencia
>Puedes consultar la licencia completa [aquí](https://github.com/ImPavloh/WhiTTsper-The-Lora/blob/master/LICENSE)

Este proyecto está licenciado bajo los términos de la licencia **MIT**.
