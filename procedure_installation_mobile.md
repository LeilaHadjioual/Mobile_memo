## PROCEDURE INSTALLATION ANDROID, CORDOVA

- installation Android studio

    https://developer.android.com/studio/install.html​



- installation npm et node

vérifier si déjà installé : 

        git bash  
            node -v
            npm -v


- installer cordova
  
        npm install -g cordova

- modifier le path 

        ajouter en 1er
            C:\Users\leila.hadjioual\AppData\Roaming\npm

- vérifier l'installation, réouvrir un bash et taper

        cordova

- créer un projet, se placer dans le dossier où l'on veut créer le projet 

        cordova create nomprojet

*si message telemetry* : taper cordova telemetry on

- ajouter platform, se positionner dans le projet

        cordova platform add browser  

        cordova run browser

        cordova platform add android

        cordova run android

*si erreur build failed*

        ouvrir le projet sur android
        dans le terminal, vérfier l'erreur et cliquer sur le lien
        update ok


- installer java  

        Java Development Kit (JDK) 8 
        avant dernière version et windows 64


- ouvrir android   

        suivre indication dans event log

        cliquer sur lecture (haut droite)
        create new virtual device
        faire sélection : oreo

redémarrer le pc 

        echap
        f10
        advanced
        système options
        cocher virtualization technology
        virtualizaton technology for directed
        save
        save and exit

- modif path pour java 

        nouveau 
        JAVA-HOME
        C:\Program Files\Java\jdk1.8.0_161

- verifier installation JAVA et ANDROID SDK dans dossier appmobile -> bash

        cordova requirements

- verifier config sur android 

        files
        settings

- ouvrir android

                sélectionner le projet
                play haut droite
                choisir le virtual host
                le tél apparait

                


