
Pour installer youtube-dl pour Linux
================================== 
 déjà on se met à jour
 ````````````````````````````````````````````````````````````````````````````````````````
$ sudo apt-get update && sudo apt-get dist-upgrade && sudo apt-get dist-upgrade
````````````````````````````````````````````````````````````````````````````````````````
on installe python pip car c'est plus facile a mettre a jour même si  ça installe beaucoup de trucs
````````````````````````````````````````````````````````````````````````````````````````
$ sudo apt install python3-pip
````````````````````````````````````````````````````````````````````````````````````````

on install youtube-dl ou on upgrade

````````````````````````````````````````````````````````````````````````````````````````
$ sudo pip install --upgrade youtube_dl
````````````````````````````````````````````````````````````````````````````````````````


pour installer youtube-dl sur mac os 
=========================================
````````````````````````````````````````````````````````````````````````````````````````
$ brew install youtube-dl
````````````````````````````````````````````````````````````````````````````````````````

pour convertir en audio ou vidéo 
mais normalement ça s'installe car c'est une dépendance sinon
````````````````````````````````````````````````````````````````````````````````````````
$ brew ffmpeg  
````````````````````````````````````````````````````````````````````````````````````````

pour  utiliser youtube-dl
======================================
tu vas dans le dossier Video ou musique 
 et tu fait 
 

 affiches toutes les qualite dispo 
````````````````````````````````````````````````````````````````````````````````````````
$ youtube-dl -F lien-de-ta-video-youtube
````````````````````````````````````````````````````````````````````````````````````````


  on télécharge la vidéo du format n22 de la liste précédente
````````````````````````````````````````````````````````````````````````````````````````
$ youtube-dl -f 22 lien-de-ta-video-youtube
````````````````````````````````````````````````````````````````````````````````````````


 et la "la commande ultime" pour l'enregistre en mp3 320  pour les audiophiles en flac débrouiller vous 
````````````````````````````````````````````````````````````````````````````````````````
$   youtube-dl -x --audio-format mp3 --prefer-ffmpeg  https://youtu.be/5S30jAev2Ds       
````````````````````````````````````````````````````````````````````````````````````````





