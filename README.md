# Traductor básico con servicios de Azure

Esta aplicación web proporciona un traductor básico que utiliza los servicios de Azure Cognitive Services para traducir texto de un idioma a otro. La aplicación está desarrollada utilizando HTML, CSS, Python y Flask.

## Funcionalidad

La aplicación ofrece las siguientes funcionalidades:

- **Interfaz de usuario amigable**: La interfaz de usuario permite al usuario ingresar un texto y seleccionar el idioma de origen y el idioma de destino para la traducción.
- **Traducción de texto**: La aplicación utiliza los servicios de Azure Cognitive Services para traducir el texto ingresado del idioma de origen al idioma de destino seleccionado.
- **Detección automática del idioma**: La aplicación detecta automáticamente el idioma de origen del texto ingresado y lo muestra al usuario.
- **Respuesta visual**: Una vez realizada la traducción, la aplicación muestra el texto traducido en un recuadro resaltado para una mejor visualización.

## Tecnologías utilizadas

- HTML: Para la estructura y el contenido de la página web.
- CSS: Para el diseño y la apariencia visual de la página.
- Python: Para el backend y la lógica de traducción utilizando los servicios de Azure Cognitive Services.
- Flask: Un framework de Python para el desarrollo de aplicaciones web.

## Configuración

Para ejecutar la aplicación, se requiere configurar los siguientes elementos:

- **Clave y región de Azure Cognitive Services**: La aplicación utiliza los servicios de traducción de Azure Cognitive Services. Se debe proporcionar la clave de servicio y la región correspondiente en el archivo `.env`.

## Ejecución

Para ejecutar la aplicación, siga estos pasos:

1. Asegúrese de tener Python instalado en su sistema.
2. Clonar o descargar el repositorio de la aplicación.
3. Desde la terminal, navegue hasta el directorio raíz de la aplicación.
4. Ejecute el siguiente comando para instalar las dependencias necesarias:
pip install -r requirements.txt
5. Configure las variables de entorno para la clave y región de Azure Cognitive Services en el archivo `.env`.
6. Ejecute la aplicación con el siguiente comando:
python app.py

7. Abra su navegador web y vaya a `http://localhost:5000` para acceder a la aplicación.

¡Listo! Ahora puede utilizar la aplicación para traducir texto de un idioma a otro utilizando los servicios de Azure Cognitive Services.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentra algún problema o tiene alguna mejora, puede abrir un problema o enviar una solicitud de extracción en el repositorio.

