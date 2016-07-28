Ejemplo de la Base de Datos en Tiempo Real de Firebase
=============================

El ejemplo demuestra cómo conectarse a la DB de Firebase para enviar y recibir datos de una sencilla aplicación de blogging social.
Va a interoperar con la misma DB del ejemplo de Android (en construcción).

Introducción
------------

- [Leer más sobre la DB de Firebase](https://firebase.google.com/docs/database/)

Comenzamos?
---------------

- Creá tu proyecto desde la [consola de administración de Firebase](https://console.firebase.google.com).
- Copiá el código de inicialización en el archivo index.html. Lo podés hacer clickeando el logo rojo de HTML
  en la esquina superior derecha de la página con el nombre "Add Firebase to your web app" ("Agregar Firebase a tu app web"). El código que aparece debe ubicarse dentro de la etiqueta `<head>` del `index.html`.
  ![imagen botón](https://raw.githubusercontent.com/ptf-houssay/firebase-database/master/img/pic1.png "Botón Web")
- Habilitá Google Auth en la solapa **Auth > SIGN IN METHOD** .
- Ejecutá `firebase serve` desde la línea de comandos de tu computadora (usando la herramienta [Firebase CLI](https://github.com/ptf-houssay/firebase-database#instalación)) para iniciar un server Firebase local.

Instalación
--------
Para usar Firebase CLI debemos instalarlo mediante npm
```bash
npm install -g firebase
```
Más tarde no serviran algunas funciones de "firebase-tools"
```bash
npm install -g firebase-tools
```
Soporte
-------

https://firebase.google.com/support/

Licencia
-------

© Google, 2016. Licencia de [Apache-2](../LICENSE). Traducido por PTF - Sede Houssay
