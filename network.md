# Commandes relatives au réseau

## Ping d'un hôte

    $ ping myserver.com

Ping le serveur `myserver.com` et affiche le résultat.

## Téléchargement d'un fichier

    $ curl -o https://www.myserver.com/video.mkv
    $ wget -O https://www.myserver.com/video.mkv

Télécharge le fichier depuis l'URL `https://www.myserver.com/video.mkv` et l'enregistre dans le dossier courant sous le nom `video.mkv`

## Afficher les informations sur le réseau

    $ ifconfig

Cette commande liste les interfaces réseaux et permet d'obtenir l'IP et la MAC liée à chacune d'entre

## Afficher le nom d'hôte associé à une IP

    $ host domain.com

## Effectuer un DNS Lookup

    $ dig domain.com
    $ nslookup domain.com

## Afficher la liste des ports TCP ouverts

    $ netstat -at

## Afficher la route menant à une destination

    $ traceroute -T 1.2.3.4
    $ tracepath 1.2.3.4

## Afficher le WHOIS d'un domaine

    $ whois domain.com

## Afficher les ports ouverts sur un hôte

    $ nmap domain.com

## Connexion à distance avec SSH

SSH (diminutif de "Secure Shell" ou"Secure Socket Shell") est un protocole réseau permettant d'accéder à des services réseaux de manière sécurisée à travers des réseaux non sécurisés.

Le serveur SSH écoute par défaut sur le port 22, mais un autre port peut-être utilisé.

Quelques commandes de base :

    $ ssh user@myserver.com

connecte au serveur `myserver.com` sur le port par défaut 22 en tant qu'utilisateur `user`

    $ ssh user@myserver.com -p 1234

connecte au serveur `myserver.com` sur le port 1234 en tant qu'utilisateur `user`

    $ ssh user@myserver.com 'ls -l'

connecte au serveur `myserver.com` sur le port par défaut en tant qu'utilisateur `user` et exécute `ls -l` à distance