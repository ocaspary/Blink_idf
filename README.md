## Projet *Blink_idf*

Projet à intégrer dans PlatformIO (extension dans VS Code).

Le programme *main.c* est écrit uniquement en langage C : plus besoin d'inclure arduino.h.

![image](https://user-images.githubusercontent.com/44494044/131230429-904f7c90-a9e1-443c-88d6-fd75c4e99875.png)


Exécution de 2 tâches (hello_task et blinky) sur un microcontrôleur ESP32 NodeMCU avec le framework espidf.

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

Puis *Upload* pour compiler et téléverser le programme, en cliquant sur la flèche du menu (en bas de la fenêtre) :

![image](https://user-images.githubusercontent.com/44494044/131230518-43410dd1-ea22-48a4-9c4a-24593b87f42c.png)

Après, ouvrez le Terminal en cliquant sur l'icône "prise" du menu pour afficher *Hello World!*

![image](https://user-images.githubusercontent.com/44494044/131230571-4d7ce6bf-1982-4b4c-ad54-7df898b80991.png)

L'affichage est le suivant (en plus du clignotement de la led bleue sur l'ESP32) :

![image](https://user-images.githubusercontent.com/44494044/131230591-98daff29-eccb-4e35-a0b2-66a6885fb1f5.png)

Remarque : la détection du port USB sur lequel est branché l'ESP32 est automatique. Vous pouvez le connaître avec PIO Home -> Devices :

![image](https://user-images.githubusercontent.com/44494044/131230390-c58fbc0b-05f0-4fdf-9576-06bff2af0f05.png)

