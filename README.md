# Index

* [Planification](#Planification)
* [Design](#Design)
* [Testing](#testing)
* [Bug management](#bugs)

# Contrasenyes_segures

App designed to manage passwords using local SQL storage, GOOGLE cloud functions to use TextToSpeech and biometric authentication.

<a name="Planification"></a>
## Planification
Tasks:
<p align="center">
<img src="img/Panificacio_Gantt.png" width="800" height="500">
</p>

Used Trello to manage tasks:
<p align="center">
<img src="img/Trello.PNG" width="800" height="400">
</p>

Postman to test http requests:
<p align="center">
<img src="img/postmanGC.png" width="600" height="400">
</p>

<a name="Design"></a>
## Design
Diagram:
<p align="center">
<img src="img/TFG_flujo.jpg" width="600" height="600">
</p>

Cryptography:
Decided to use the AES algorithm due to the necesity to use the same key to encrypt and to decrypt
<p align="center">
<img src="img/aes.png" width="600" height="400">
</p>

<a name="Testing"></a>
## Testing
Junit used to Unit test the cryptography module:
A mock Object for Base64 library was needed.
<p align="center">
<img src="img/UTest.PNG" width="600" height="300">
</p>

Exploratory Testing made as follows:
<p align="center">
<img src="img/Exploratory.PNG" width="400" height="400">
</p>

<a name="bugs"></a>
## Bug management
Bugs have been managed using the next structure:
<p align="center">
<img src="img/BugsTa.PNG" width="600" height="400">
</p>
