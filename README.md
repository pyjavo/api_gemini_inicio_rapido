# Guía descafeinada de la guía de inicio rápido de Gemini 

En este repositorio hago un breve resumen del tutorial para iniciar con la API  de Gemini que ofrece Google.

## ¿Cómo correrlo localmente?

1. Comprobar que tienes Python instalado. Abre una terminal y escribe `python --version` o `python3 --version`. Para este proyecto necesitas tener python 3.
2. Crear un ambiente virtual de Python. Si no sabes, puedes [ver esta guía](https://micro.recursospython.com/recursos/como-crear-un-entorno-virtual-venv.html)
3. Activa el ambiente virtual
4. Una vez activado el ambiente virtual, instala las dependencias con el manejador de paquetes pip, de esta forma: `pip install -r requirements.txt`
5. Crea tu API key para Gemini en el [Ai studio de Google](https://aistudio.google.com/app/apikey)
6. Crea un archivo `.env` en este directorio (al mismo nivel del cuaderno de Jupyter) y escribe ahi tu API Key. De esta forma:

```
GOOGLE_API_KEY=Mi-llave-super-secreta-para-gemini
```

7. Luego, corre el cuaderno de jupyter con este comando `jupyter notebook` y empieza a jugar.

## Enlaces de referencia

- De la charla de febrero de GdG Barranquilla
  - https://ai.google.dev/
  - https://ai.google.dev/gemini-api/docs?hl=es-419
      - Guía para Python: https://ai.google.dev/gemini-api/docs/get-started/python
  - https://github.com/google-gemini/cookbook

#### Modelo de código abierto, Gemma
  - https://ai.google.dev/gemma?hl=es-419

