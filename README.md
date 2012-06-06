ciclami-android
===============

Android project for running [ciclami](http://colmarius.github.com/ciclami) hybrid app.

What it does?
-------------

Shows a map with a crosshair and a marker at the user's position. Allows you to take a photo and upload it to a couchdb instance with your current position and some description data.

Build
-----

    android update project -p . -t android-15

Run
---

With your emulator or Android phone connected run:

    ant debug install