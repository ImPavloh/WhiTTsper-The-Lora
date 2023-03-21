![Demo Preview](https://i.imgur.com/zO3x80I.jpg)

<div align="center">

<a href="https://github.com/ImPavloh/WhiTTsper-The-Lora" target="_blank"><img src="https://img.shields.io/github/stars/ImPavloh/WhiTTsper-The-Lora?style=social&label=Star&maxAge=2592000" alt="Test"></a>
[![Google Colab Demo](https://img.shields.io/badge/demo-online-green.svg)](https://colab.research.google.com/drive/11MHiNlhQ0ZSqKVl0Fniu085bkQRdJX9E?usp=sharing)
<a href="https://github.com/ImPavloh/WhiTTsper-The-Lora/blob/master/LICENSE" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://twitter.com/ImPavloh" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>

# WhiTTsper the Lora

Demo que combina Whisper para el reconocimiento de voz y Google TTS para la síntesis de voz para interactuar junto Alpaca-LoRA.


### Pruébalo desde **Google Colab**
<a href="https://colab.research.google.com/drive/11MHiNlhQ0ZSqKVl0Fniu085bkQRdJX9E?usp=sharing" target="_blank"><img src="https://i.imgur.com/0j68Rhz.png" alt="Test" width="150"></a>
</div>

## Características 📃

- Reconocimiento de voz mediante Whisper con elección de tamaño
- Modelo de lenguaje basado en LLaMa 7B configurable desde la interfaz
- Síntesis de voz con Google Text-to-Speech
- Interfaz gráfica mediante gradio
- Historial de conversaciones disponible
- Función de reinicio de conversación

## TODO 📑

- Incluir modelos de lenguaje adicionales, como gpt-j-6B
- Utilizar una inteligencia artificial avanzada para la síntesis de voz
- Optimizar el código y asegurar su compatibilidad en diferentes plataformas, incluyendo Windows, Linux, etc.
- Agregar configuraciones adicionales a la interfaz gráfica, como vista previa, soporte para adjuntar y reconocer imágenes*, etc.
- *Agregar generación de imágenes como una funcionalidad adicional mediante Stable Diffusion

---

## Uso 📒

Para utilizar la demo, es necesario tener acceso a un micrófono.
Al ejecutar todo el código, se abrirá una interfaz gráfica en la que se puede hablar en el micrófono y obtener una respuesta de la IA Alpaca-LoRA.

En la interfaz gráfica, se puede seleccionar el tamaño del modelo de Whisper a utilizar (tiny, base, small, medium, large). El tamaño del modelo afecta el tiempo de respuesta de la IA y la calidad de la respuesta generada. Se puede cambiar manualmente la temperatura del modelo Alpaca-Lora además de poder restablecer la conversación.

---

## Créditos 📜

Se utiliza como modelo de lenguaje [Alpaca-LoRA](https://github.com/tloen/alpaca-lora). Se emplea la librería de Transformers de Hugging Face para el modelo. 
También se usa la tecnología de reconocimiento de voz [Whisper](https://github.com/openai/whisper) de OpenAI y la tecnología de síntesis de voz [Google Text-to-Speech](https://github.com/pndurette/gTTS).
La interfaz gráfica es construida utilizando la librería [Gradio](https://github.com/gradio-app/gradio).

---

## Apoya el proyecto ☕

Si te gusta este proyecto o te ha ayudado en alguna forma, considera invitarme a un [café](https://www.buymeacoffee.com/pavloh) como forma de apoyo. De esta manera, podré dedicar más tiempo a proyectos de código abierto como éste y mejorarlos aún más :)

<a href="https://www.buymeacoffee.com/pavloh" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

---
## Licencia 📃
>Puedes consultar la licencia completa [aquí](https://github.com/ImPavloh/WhiTTsper-The-Lora/blob/master/LICENSE)

Este proyecto está licenciado bajo los términos de la licencia **MIT**.
