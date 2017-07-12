# Installation du projet Tp-Arbre-Tableau :


# Projet back-End

1. télécharger le projet seedBackEnd sur le dépôt ci-dessous et suivre les étapes d'installation de 
l'environnement :
    [seedBackEnd](https://github.com/gitProject01/seedBackEnd). 
 
   1. démarrer le serveur weblogic 12.1.3 
      - ouvrir une invite de commande
      - aller sur le dossier "votre_chemin_d'installation\Middleware\Oracle_Home\user_projects\domains\wl_server" 
      - executer le script bin/startWebLogic.cmd (pour Windows)
   
   2. ouvrir une invite de commande 
      
      - aller dans le dossier de téléchargement du projet backEnd
      - executer la commande suivante :
      
        mvn compile package pre-integration-test

    3. Tester le lancement du projet 
       - ouvrir un navigateur et taper l'url suivante :
       http://localhost:7001/seedbackend/index.xhtml 


# Projet front-End

1. télécharger le projet seedFrontEnd sur le dépôt ci-dessous et suivre les étapes d'installation de 
l'environnement :
    [seedFrontEnd](https://github.com/gitProject01/tp-arbre-tableau). 
 
   1. Lancer le projet seedFrontEnd
      - ouvrir une invite de commande
      - aller sur le dossier de téléchargement du projet seedFrontEnd
      - executer la commande suivante :
          npm start

   
   2. Tester le lancement du projet 
       - ouvrir un navigateur et taper l'url suivante :
       http://localhost:8000
        

