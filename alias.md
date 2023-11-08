## Alias

Voici quelques alias utiles, ne pas oublier de 
    source ~/.bashrc

### Relatifs à git
    alias g='git'
    alias gs='git status'
    alias ga='git add'
    alias gc='git commit'
    alias gp='git push'

### Commandes générales

    alias c='clear'  # Efface l'écran du terminal
    alias h='history'  # Affiche l'historique des commandes
    alias g='git'  # Raccourci pour les commandes Git
    alias p='ping'  # Envoie des paquets vers une adresse IP ou un hôte (pratique pour tester sa connexion)
    alias psa='ps aux'  # Liste tous les processus actifs avec des informations détaillées
    alias d='df -h'  # Affiche l'utilisation de l'espace disque avec des valeurs lisibles
    alias duh='du -sh * | sort -h'  # Affiche la taille des répertoires et les trie par taille

### Management de paquets 

    alias update='sudo apt update'  # Met à jour les informations des paquets
    alias upgrade='sudo apt upgrade'  # Met à jour les paquets installés
    alias install='sudo apt install'  # Installe un nouveau paquet
    alias remove='sudo apt remove'  # Supprime un paquet

### Alias pour Docker

    alias d='docker'
    alias dps='docker ps'  # Liste les conteneurs en cours d'exécution
    alias dimages='docker images'  # Liste les images Docker
    alias  dlogs='docker logs'  # Affiche les journaux d'un conteneur
