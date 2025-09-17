# MeRenta-Chatbot-Declaracion-de-la-Renta

![Logo del proyecto](Logo-MeRenta.jpg)

La declaración de la renta es un trámite anual que suele generar múltiples dudas y confusiones entre los contribuyentes. En este contexto surge la propuesta de crear MeRenta, un chatbot especializado en la declaración de la renta; capaz de responder preguntas frecuentes de manera inmediata. Su principal objetivo es ofrecer a los usuarios una herramienta sencilla y práctica que les ayude a comprender mejor los conceptos fiscales y los procedimientos básicos relacionados con este trámite. La interfaz conversacional permitirá una interacción encilla, incluso para personas con pocos conocimientos tecnológicos.

Para garantizar la calidad y la precisión de las respuestas, el sistema se implementará mediante un enfoque de Retrieval-Augmented Generation (RAG). Esta técnica combina la recuperación de información desde una base de conocimiento actualizada con la capacidad generativa de los modelos de lenguaje. De esta forma, el chatbot podrá ofrecer respuestas fundamentadas en documentos oficiales y normativas fiscales, evitando respuestas genéricas y proporcionando al usuario información contextualizada y verificada.

Asimismo, el motor principal del MeRenta se apoyará en un Large Language Model (LLM) encargado de interpretar las consultas y generar respuestas naturales en lenguaje humano. Con el fin de encontrar el modelo óptimo se llevará a cabo una comparación entre diferentes modelos ya entrenados disponibles en Hugging Face. Para el desarrollo e implementación del chatbot se empleará Python como lenguaje principal de programación, dado que ofrece una amplia variedad de librerías y frameworks orientados al procesamiento del lenguaje natural y la integración con modelos de inteligencia artificial. Además, el entorno de trabajo seleccionado será Google Colab, lo que permitirá aprovechar recursos de cómputo en la nube. 

Antes de ejecutar el código hay que tener en cuenta lo siguiente: 
1. Al tratarse de un repositorio público de GitHub, es necesario crear una clave para la API de Hugging Face.
2. Cambiar las direcciones a los repositorios locales personales para que el código pueda ejecutarse sin problema.

Ejecutar el código en el siguiente orden: 
1. Fase_1_limpieza_chunks.ipynb
2. Fase_2_embeddings_local.ipynb
3. Fase_3_interfaz.ipynb

