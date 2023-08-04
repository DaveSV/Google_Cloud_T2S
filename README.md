# Google_Cloud_T2S

Descripción de proyecto
Python Client for Google Cloud Text-to-Speech API

Text-to-Speech API te permite convertir palabras y oraciones en datos de audio codificados en Base64 de voz humana natural. Luego, puedes convertir los datos de audio en archivos de audio reproducibles, como MP3, mediante la decodificación de los datos codificados en Base64. La API de Text-to-Speech acepta entradas como texto sin procesar o lenguaje de marcado de síntesis de voz (SSML).

Este código toma como base el provisto por Google (https://github.com/GoogleCloudPlatform/python-docs-samples/blob/HEAD/texttospeech/snippets/synthesize_text.py) con las siguientes mejoras:

- Incorpora el archivo JSON con las credenciales de la cuenta de servicio de Google Cloud Platform como una variable de entorno. Obviamente, por razones de seguridad, en el repositorio no se adjuntan estas credenciales.
- Sustituye el texto que va como argumento en el comando por un archivo de texto, asì el código lee el contenido del archivo en lugar de usar el texto directamente desde la línea de comandos. 
