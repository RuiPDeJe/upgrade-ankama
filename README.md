# upgrade-ankama
Installer ou mettre à jour l'ankama launcher sur les distributions linux

Optimisé pour ubuntu
Script en bash

Ce script installe le launcher officiel depuis le site ankama.
Il le déplace ensuite dans /bin/, d'où la nécessité d'être administrateur.
Par la suite, il modifie les permissions du programme afin qu'il puisse être exécuté par les utilisateurs.

# Lancer le script
( Assurez-vous d'être dans le même répertoire que le fichier pour exécuter ces commandes )
Pour lancer le script, assurez-vous de le rendre exécutable par le biais de la commande :
    - $sudo chmod u+rx upgrade-ankama
Ensuite, toujours depuis le terminal, effectuer la commande suivante pour l'exécuter :
    - $bash upgrade-ankama

Le script se chargera du reste
