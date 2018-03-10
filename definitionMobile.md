## MOBILE
----
**Xcode**   
IDE : (environnement de développement) logiciel qui rassemble un certain nombre d’outils permettant de développer d’autres logiciels.   
environnement de développement pour IOS qui peut utiliser le langage Objective-C  

**Android studio**   
IDE  
environnement de développement pour Android qui utilise le langage Java  

**Eclipse**   
IDE  
environnement de développement pour Android qui utilise le langage Java  
 
**Objective-C**   
langage de programmation sous IOS   

**Java**   
langage de programmation sous Android  

**API**   
Application Programming Interface   
interface pour les applications   

**Dépendance**   
le fait d'avoir besoin d'un logiciel donné pour en utiliser un autre   

**AppStores : Play et itunes**   
magasin d’applications sur appareils mobiles fonctionnant sous IOS  

**Task runner** : automatisateur de tâches  
effectue des tâches pour nous  
ex : création ou la suppression de dossiers ou de fichiers, création de serveur local permettant de tester sur de multiples périphériques en même temps   

*ex de task runner*: gulp (besoin de node.js : environnement JS), grunt  

**NPM**  
gestionnaire de paquets de node.js  
gère les dépendances d’une application  

**SDK**   
software Development Kit : ensemble d’outils d’aide à la programmation pour concevoir des logiciels, jeux, app mobiles… (ex : apache cordova)  

**React**  
bibliothèque de JS, facilite la création d’application web monopage.   
Gère que l’interface de l’app (idem vue dans MVC). Peut être utiliser avec une autre bibliothèque ou autre framework comme angularJS  

**vueJS**   
librairie qui permet de créer des interfaces web interactives en se reposant sur le principe des composants webs.(framework JS)  

**Angular**   
framework JS libre, permet de développer des pages web.   
Placé coté client  
Angular apporte aux applications web côté client les services traditionnellement apportés côté serveur, comme les contrôleurs de vues. En conséquence, une bonne partie du fardeau supporté par le back-end est supprimée, ce qui conduit à des applications web beaucoup plus légères côté serveur.   
permet de mieux organiser votre code Javascript   
permet de créer de l’HTML interactif   

**Ionic**  
framework   
permet de créer un code multisupport en utilisant des outils Web comme HTML, CSS, JavaScript, afin de générer des applications iOS, Android, Chrome, Windows Phone et bien d'autres.
2 versions :  

    -*1ère* : intègre AngularJS 1.x, ce qui veut dire qu'il est équipé d'un moteur javascript qui interprète le code javascript écrit par le programmeur.  

    -*2ème* : intègre Angular 23 qui est équipé d'un moteur de conversion TypeScript vers JavaScript, permettant au programmeur d'écrire son code en TypeScript. Cela permet aux programmeurs de mieux comprendre le code fait par quelqu'un d'autre.  

La performance d’Ionic 2 est nettement améliorée. Les applications sont beaucoup plus fluides que celles compilées par Ionic 1  

**Cordova**   
framework open-source développé par la fondation Apache . Il permet de créer des applications pour différentes plateformes (Android, Firefox OS, iOS, Ubuntu, Windows 8...) en HTML, CSS et JavaScript.  
Les applications qui en résultent sont hybrides, ce qui signifie qu'elles ne sont ni vraiment natives, ni purement basées sur les langages HTML, CSS et JavaScript  

**PhoneGap**  
framework open-source qui permet de créer des applications mobiles avec des technologies web classiques, de la même manière qu’un site web : Pages HTML, CSS, JavaScript   
on peut développer des app sans connaître java ou C  

**Single page app**   
application web monopage, app web accessible via une page web unique. Le but est d’éviter le chargement d’une nouvelle page à chaque action. (reconstruit la même page html en fonction des actions de l'user)

    2 méthodes :  
	    - l’ensemble des éléments de l’app est chargé dans un fichier unique(html)  
	    - les ressources nécessaires sont récupérées et affichées dynamiquement en fonction des actions de l’utilisateur  

**App native**  
développer avec des langages propres à chaque système d’exploitation. 

    C pour IOS  - IDE : XCODE  
    Java pour Android – android studio ou eclipse  
    C # pour Windows Phone – visual studio  

application qui a été conçue spécifiquement pour un système d’exploitation (OS) avec un langage et une/des technologie(s) appropriés.   
Pour développer une application mobile qui exploite les fonctionnalités natives du terminal (géolocalisation, contact, médias, appareil photo…) il faut “communiquer avec le SDK natif” via le code source. C’est-à-dire programmer des « ponts » qui vont aller chercher des morceaux de codes du SDK du système d’exploitation visé. Ces derniers vont permettre d’“appeler” des fonctionnalités natives pour les intégrer dans l’application mobile.  

*Développement natif* : Il est spécifique au système d’exploitation souhaité : pour développer une application iOS il faudra utiliser le langage Objective C, pour Android Java et pour Windows Phone le langage C#.   

**App native générée**  
app mobile qui n’a pas été développée avec la technologie et le langage natifs à son système d’exploitation mais via une technologie cross-platform : xamarin , titanium  

*inconvénient* :

    - diagnostic des bugs et maintenance plus délicats à cause des différentes étapes de compilation, de la structure plus complexe et moins native du code source et de la techno cross platform.

*Avantages* :

    - vise 2 systèmes d’exploitations
    - idéal pour un projet qui a besoin de puissance et performance liées au antif, sur les techno hybride ne peuvent pas apporter

**App hybride**  
développement avec un seul code, compiler sur les différentes plateformes. Ex :Titanium permet d’écrire une app avec JS et leur API.  
développée à partir de langages web (html, css, JS, …) mais s’appuie aussi sur des technologies natives mobiles  pour utiliser certaines fonctionnalités du smartphone.(elle est téléchargée depuis les magasins d’applications et installée sur le mobile contrairement à la web app qui n’est consultable que depuis un navigateur.   

*Ex de développement app hybride* : phoneGap, Rho Mobile ou apache cordova. 

*Avantages* :  

	    - gain de temps si projet pas complexe et pas de dev de plugins spécifiques.  
	    - coût moins importants car compétence web plus répandues que compétences mobiles.
	    -téléchargeable

*inconvénients* :   

	    - code source mélangé et compilation en plusieurs étapes, ce qui peut fragiliser le fonctionnement de l’app et rendre maintenance longue et complexe.  
	    - tout n’est pas réalisable en terme de fonctionnalité, vérifier la compatibilité du projet avec les techno hybrides.  
	    - contenus lourds impactent sur la performance  
	    - mode hors ligne est limité et délicat à concevoir  
	    - dépend d’un logiciel tiers (cordova et dc de sa compatibilité avec les nouvelles versions d’OS

**WebApp**  
L’application web n’est autre chose qu’un site web parfaitement adaptable à la taille et les caractéristiques de l’écran des appareils mobiles, de sorte qu’elle ressemble à l’application native.
c'est la version mobile d'un site web  
Il s’agit d’un logiciel applicatif pouvant être exécuté soit :  

	– depuis un navigateur Web (webapp desktop). Ils se présentent comme un logiciel de bureau, par exemple : les messageries web ou Pixlr  
	– depuis un smartphone (webapp mobile)   

C’est un logiciel applicatif hébergé sur un serveur et accessible depuis un navigateur Internet. Elle a une ergonomie et des fonctionnalités spécifiques adaptées aux contraintes des terminaux mobiles et ne peut pas fonctionner sans connexion Internet.  
Son avantage est sa compatibilité multi plateformes. Hébergée sur un serveur, elle peut afficher son contenu sur plusieurs systèmes d’exploitation et plusieurs navigateurs. Il est également possible de concevoir une webapp responsive design pour la rendre compatible à toutes les tailles d’écran.  

**application mobile**  
c’est un logiciel développé pour une système d’exploitation mobile(IOS, Android, Windows phone, …).  
elle doit être téléchargée depuis un magasin d’app mobiles (store) puis installée. l’app mobile peut fonctionner hors ligne et de baser sur les fonctionnalités natives du terminal (app photo, géolocalisation..).    

**Compilateur**  
transforme le code source en code binaire pour être plus simple à lire « human readable ».
(langage d’entrée → modification grâce au compilateur -> langage final compréhensible )

    ios : fichier    .ipa  
    android : fichier      .apk  
    windows phone : fichier      .appx  
ce fichier doit être téléchargé , installé puis exécuter sur le terminale pour fonctionner. En compilant les librairies appelées du SDK natif en même temps que le code source, le code binaire obtenu peut ainsi communiquer avec le système d’exploitation du terminal et exploiter ses fonctionnalités natives 

**RESTFUL**   
Representational State Transfer   
fait appel à des requêtes HTTP pour obtenir (GET), placer (PUT), publier (POST) et supprimer (DELETE) des données.   
permet une meilleure intégration car imite le style de communication du web (échange entre client et serveur)