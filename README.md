
### Despliegue local demo
Pasos
1. Asegurarse de tener docker y ngrok instalado. 
2. Correr ```docker compose up``` en el directorio del repositorio privado que aloja el código del bot, este código crea tres servicios y abre el puerto ```localhost:5010```
3. Correr ```.\ngrok http 5010```, esto abre el puerto ```5010``` y abre una dirección púlbica para el webhook.
4. Copiar la dirección https de ngrok a ```/static/js/constants.js``` agragando ```webhooks/rest/webhook```, a la variable ```rasa_server_url``` archivo  de este repositorio
5. Hacer ```commit``` a ese cambio y fusionarlo en la rama master
6. Esperar a que github reconstruya la página, esto se puede ver en la pestaña Actions




![ScreenShot](static/img/banner.png)


  ***An Open Source ChatBot widget easy to connect to RASA bot through [Rest](https://rasa.com/docs/rasa/user-guide/connectors/your-own-website/#rest-channels) Channel.***


![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)
[![forthebadge](https://forthebadge.com/images/badges/for-you.svg)](https://forthebadge.com)

[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-html.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com)

[![forthebadge](https://forthebadge.com/images/badges/built-with-swag.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](https://forthebadge.com)

[![forthebadge](https://forthebadge.com/images/badges/makes-people-smile.svg)](https://forthebadge.com)

## Features

- Text 
- Markdown
- Buttons
- Images
- Video 
- PDF Attachment
- Dropdown
- Quick replies
- Cards carousel
- Charts
- Collapsible
- Bot typing indicator
- Location access



## Instructions
- You can read the instructions here in [instructions.md](docs/instructions.md)

## Documentation
- Check out the documentation on how to send bot response from Rasa in [response.md](docs/responses.md)
- If you want to modify the UI elements, you can read on how to do here: [modifications.md](docs/modifications.md)

## Gallery:
- Check out the sample pics here [gallyery.md](docs/gallery.md)

## Sample Bots:
Below are the sample bot projects that were developed using Rasa and made to work with this widget
- [Restaurant Search Bot](https://github.com/JiteshGaikwad/Restaurant-Search-Bot.git)
- [HR Bot](https://github.com/JiteshGaikwad/HR_Bot)

## Library used:
- [Materialize CSS](https://materializecss.com) for CSS
- [Showdownjs](https://github.com/showdownjs/showdown) for Markdown suppport
- [Chart.js](https://www.chartjs.org/) for Charts

## Demo:

Check out the widget in action here [demo](https://www.youtube.com/watch?v=mnolLtOWykk)



