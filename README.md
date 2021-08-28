## Projet *Blink_idf*

Projet à intégrer dans PlatformIO (extension dans VS Code).

Le programme *main.c* est écrit uniquement en langage C : plus besoin d'inclure arduino.h.

![image](https://user-images.githubusercontent.com/44494044/131227924-e424af5d-355e-4490-bf4c-9c22d487667d.png)


Exécution de 2 tâches (hello_task et blinky) sur un microcontrôleur ESP32 NodeMCU version 30 broches avec le framework espidf.

Affichage d'Hello World dans le moniteur série et clignotement de la LED bleue intégrée au microcontrôleur.

**Paramètres lors de la création du projet avec PlatformIO :**

![image](https://user-images.githubusercontent.com/44494044/131227633-030858a1-daf3-4855-9517-3e5d42a1ed27.png)

L'option *monitor_speed = 115200* peut être ajoutée à la main dans le fichier platformio.ini si elle n'a pas été définie lors de la création du projet.


**Platformio.ini :**

![image](https://user-images.githubusercontent.com/44494044/131227846-5ba6e002-d5cc-4edc-b426-2daec7a958f7.png)

**Cloner le projet**

PIO Home -> Clone Git Project (pour obtenir le champ de saisie suivant en haut de la fenêtre) :

![image](https://user-images.githubusercontent.com/44494044/131229949-8a67e6da-9903-46fd-8846-f2b82a28f332.png)

Entrez l'URL du projet : https://github.com/ocaspary/Blink_idf

Sélectionnez le répertoire dans lequel il sera cloné, en général : Documents > PlatformIO > Projects.

