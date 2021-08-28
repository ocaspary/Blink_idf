## Projet *Blink_idf*

Projet à intégrer dans PlatformIO (extension dans VS Code).

![image](https://user-images.githubusercontent.com/44494044/131227814-46cd06f2-98c8-4b11-be6a-d62d68db73c9.png)

Le programme *main.c* est écrit uniquement en langage C : plus besoin d'inclure arduino.h.

Exécution de 2 tâches (hello_task et blinky) sur un microcontrôleur ESP32 NodeMCU version 30 broches avec le framework espidf.

Affichage d'Hello World dans le moniteur série et clignotement de la LED bleue intégrée au microcontrôleur.


**Paramètres lors de la création du projet avec PlatformIO :**

![image](https://user-images.githubusercontent.com/44494044/131227633-030858a1-daf3-4855-9517-3e5d42a1ed27.png)

*monitor_speed = 115200* peut être ajouté à la main dans le fichier platformio.ini s'il n'a pas été défini lors de la création du projet.
