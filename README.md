<a name="top"></a>

<div align="center">
    <h3 align="center">Cheat sheet sur le terminal linux</h3>
    <p align="center">
        <img src="images/terminal-seeklogo.com.svg" width="64"><br>
        <i>Le guide ultime pour manipuler le terminal</i>
    </p>
</div>

***
<br>
<details>
    <summary>Table des matières</summary>
    <ul>
        <li>
            <a href="#">Installation et paramétrage de ZSH</a>
            <ul>
                <li><a href="#">Installation sous Ubuntu</a></li>
                <li><a href="#">Paramétrage</a></li>
            </ul>
        </li>
        <li><a href="#contexte">Contexte</a></li>
        <li><a href="#contributeurs">Contributeurs</a></li>
        <li><a href="#contribuer">Contribuer</a></li>
    </ul>
</details>

## Consulter la documentation d'une commande

Chaque commande du terminal dispose d'une documentation détaillant sa finalité et ses paramètres. Cette documentation pouvant s'afficher sur plusieurs pages, utiliser les touches <kbd>FLECHE HAUT</kbd> et <kbd>FLECHE BAS</kbd> pour naviguer ligne par ligne, et les touches <kbd>PAGE HAUT</kbd> et <kbd>PAGE BAS</kbd> pour naviguer page par page.

Exemples :

    $ man ls

Affiche la documentation de la commande `ls`

    $ man mkdir

Affiche la documentation de la commande `mkdir`

## Navigation dans le système de fichiers

- `pwd` : Affiche le répertoire de travail actuel.
- `ls` : Liste les fichiers et répertoires dans le répertoire courant.
- `cd` : Change de répertoire (par exemple, `cd /chemin/vers/repertoire`).
- 
## Affichage du contenu de fichiers

- `cat` fichier : Affiche le contenu d'un fichier.
- `more` fichier ou less fichier : Permet de parcourir le contenu d'un fichier page par page.

## Commandes relatives au réseau

### Ping d'un hôte

    $ ping myserver.com

Ping le serveur `myserver.com` et affiche le résultat.

### Téléchargement d'un fichier

    $ curl -O https://www.myserver.com/video.mkv

Télécharge le fichier depuis l'URL `https://www.myserver.com/video.mkv` et l'enregistre dans le dossier courant sous le nom `video.mkv`

### Connexion à distance avec SSH

SSH (diminutif de "Secure Shell" ou"Secure Socket Shell") est un protocole réseau permettant d'accéder à des services réseaux de manière sécurisée à travers des réseaux non sécurisés.

Le serveur SSH écoute par défaut sur le port 22, mais un autre port peut-être utilisé.

Quelques commandes de base :

    $ ssh user@myserver.com

connecte au serveur `myserver.com` sur le port par défaut 22 en tant qu'utilisateur `user`

    $ ssh user@myserver.com -p 1234

connecte au serveur `myserver.com` sur le port 1234 en tant qu'utilisateur `user`

    $ ssh user@myserver.com 'ls -l'

connecte au serveur `myserver.com` sur le port par défaut en tant qu'utilisateur `user` et exécute `ls -l` à distance
 
## Raccourcis clavier

Voici quelques raccourcis claviers utiles pour utiliser le terminal avec efficacité :

* <kbd>CTRL+A</kbd> place le curseur en début de ligne
* <kbd>CTRL+E</kbd> place le curseur en fin de ligne
* <kbd>CTRL+K</kbd> efface les caractères après le curseur
* <kbd>CTRL+U</kbd> efface les caractères avant le curseur
* <kbd>CTRL+L</kbd> efface l'écran du terminal
* <kbd>CTRL+C</kbd> arrête l'exécution de la commande en cours
* <kbd>TAB</kbd> active l'auto-complétion sur les noms de fichiers et de dossiers
* <kbd>FLECHE HAUT</kbd> navigue dans l'historique des commandes saisies en partant de la plus récente à la plus ancienne
* <kbd>FLECHE BAS</kbd> navigue dans l'historique des commandes saisies en partant de la plus ancienne à la plus haute

## Installation et paramétrage de ZSH

Zsh est un interpréteur de commandes (shell), tout comme bash. Il fournit une interface entre l'utilisateur et le système. Il est indispensable d'avoir un interpréteur de commandes pour utiliser un système GNU/Linux (et même tous les autres systèmes). Le shell par défaut dans Ubuntu est bash, c'est un shell qui a bien des avantages (notamment pour les scripts), mais il est assez limité dans certaines fonctionnalités comme l'autocomplétion. Zsh est plutôt orienté pour l'interactivité avec l'utilisateur.

### Installation sous Ubuntu

```
$ sudo apt install zsh
```

### Paramétrage

Pour définir zsh comme shell par défaut, exécuter la commande suivante :

```
$ chsh
```

Pour définir le shell à utiliser, répondre `/bin/zsh`. Fermer puis ouvrir à nouveau un terminal pour être directement sous zsh.

## Contexte

Ce document a été rédigé dans le cadre d'un brief de groupe durant le SAS Développeur .Net par Simplon, en novembre 2023.

<p align="right">(<a href="#top">haut de page</a>)</p>

## Contributeurs

Ce document a été initialement rédigé par Aguit, Youssouf et Guillaume.

<p align="right">(<a href="#top">haut de page</a>)</p>

## Contribuer

Si vous avez une suggestion pour améliorer ce document, merci de forker ce repo et de créer une *pull request*. N'oubliez pas de donner une étoile à notre projet, merci 😁

* Forkez le projet
* Créez votre branche de feature (`git checkout -b feature/MyFeature`)
* Committez vos changements (`git commit -m 'Feature description'`)
* Pushez la branche (`git push origin feature/AmazingFeature`)
* Ouvrez une *pull request*

<p align="right">(<a href="#top">haut de page</a>)</p>