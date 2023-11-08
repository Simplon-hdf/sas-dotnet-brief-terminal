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

## Utilitaires système

- `date` : Affiche la date et l'heure actuelles.
- `who` : Affiche les utilisateurs connectés.
- `df` : Affiche l'utilisation de l'espace disque.
- `du` : Affiche l'utilisation de l'espace disque pour un répertoire.
- `man commande` : Affiche le manuel d'utilisation d'une commande spécifique.
- `history` : Affiche l'historique des commandes précédemment exécutées.
- `clear` : Efface le contenu du terminal.

## Gestion des processus

- `ps` : Affiche les processus en cours d'exécution.
- `top` : Affiche une liste en temps réel des processus en cours d'exécution.
- `kill PID` : Arrête un processus en utilisant son ID de processus (PID).
- `Ctrl + C` : Interrompt un processus en cours d'exécution dans le terminal.
- `bg` : Exécute un processus en arrière-plan.
- `fg` : Fait revenir un processus en premier plan.

## Gestion des utilisateurs et des permissions

- `sudo commande` : Exécute une commande avec des privilèges d'administrateur.
- `useradd nom_utilisateur` : Crée un nouvel utilisateur.
- `passwd nom_utilisateur` : Modifie le mot de passe d'un utilisateur.
- `chmod permissions fichier` : Modifie les permissions d'accès à un fichier.
- `chown propriétaire:fichier` : Change le propriétaire d'un fichier.

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
