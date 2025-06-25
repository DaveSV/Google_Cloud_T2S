# Google_Cloud_T2S

Descripción de proyecto
Python Client for Google Cloud Text-to-Speech API

Text-to-Speech API te permite convertir palabras y oraciones en datos de audio codificados en Base64 de voz humana natural. Luego, puedes convertir los datos de audio en archivos de audio reproducibles, como MP3, mediante la decodificación de los datos codificados en Base64. La API de Text-to-Speech acepta entradas como texto sin procesar o lenguaje de marcado de síntesis de voz (SSML).

Este código toma como base el provisto por Google (https://github.com/GoogleCloudPlatform/python-docs-samples/blob/HEAD/texttospeech/snippets/synthesize_text.py) con las siguientes mejoras:

- Incorpora el archivo JSON con las credenciales de la cuenta de servicio de Google Cloud Platform como una variable de entorno. Obviamente, por razones de seguridad, en el repositorio no se adjuntan estas credenciales.
- Sustituye el texto que va como argumento en el comando por un archivo de texto, asì el código lee el contenido del archivo en lugar de usar el texto directamente desde la línea de comandos.

  ![tetxt2audio1](https://github.com/user-attachments/assets/97efcd60-958d-4aca-afd9-124213a953a4)


Este código utiliza la biblioteca "google-cloud-texttospeech 2.14.1" (Google Cloud Texttospeech API client library). Mas información sore este recurso en https://pypi.org/project/google-cloud-texttospeech/

Idiomas y voces compatibles

Text-to-Speech proporciona las siguientes voces. La lista incluye las voces Neural2, Studio, Standard y WaveNet. Las voces Studio, Neural2 y WaveNet son voces de mejor calidad y con precios diferentes. El listado en https://cloud.google.com/text-to-speech/docs/voices?hl=es

![tetxt2audio2](https://github.com/user-attachments/assets/552b11e5-5612-4b90-8e08-817198d3b3a8)


Revisa la calculadora de precios (https://cloud.google.com/products/calculator?hl=es) para verificar el costo de tu proyecto consumiendo esta API. Recuerda que Google Cloud tiene una base de consumo gratuito en muchos de sus servicios.
