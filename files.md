## Navigation dans le système de fichiers

- `pwd` : Affiche le répertoire de travail actuel.
- `ls` : Liste les fichiers et répertoires dans le répertoire courant.
- `cd` : Change de répertoire (par exemple, `cd /chemin/vers/repertoire`).

## Manipulation de fichiers et de répertoires

- `touch fichier` : Crée un nouveau fichier vide.
- `mkdir dossier` : Crée un nouveau répertoire.
- `cp source destination` : Copie des fichiers ou des répertoires.
- `mv source destination` : Déplace ou renomme des fichiers ou des répertoires.
- `rm fichier` : Supprime un fichier (avec précaution).
- `rm -r dossier` : Supprime un répertoire et son contenu (avec précaution).
- 
## Affichage du contenu de fichiers

- `cat` fichier : Affiche le contenu d'un fichier.
- `more` fichier ou less fichier : Permet de parcourir le contenu d'un fichier page par page.

## Éditeurs de fichiers

### Nano

- `Ouvrir un fichier :` `nano nom_du_fichier`
- `Enregistrer :` `Ctrl` + `O`, puis appuyez sur `Enter`
- `Quitter :` `Ctrl` + `X`

### Vim

- `Ouvrir un fichier :` `vim nom_du_fichier`
- `Enregistrer :` En mode normal, tapez `:w`
- `Quitter :` En mode normal, tapez `:q`

### Emacs

- `Ouvrir un fichier :` `emacs nom_du_fichier`
- `Enregistrer :` En mode normal, tapez `Ctrl` + `X`, puis `Ctrl` + `S`
- `Quitter :` En mode normal, tapez `Ctrl` + `X`, puis `Ctrl` + `C`

### Ed

- `Ouvrir un fichier :` `ed nom_du_fichier`
- `Enregistrer :` En mode normal, tapez `w`
- `Quitter :` En mode normal, tapez `q`

## Recherche de fichiers

- `find chemin -name nom_fichier` : Recherche un fichier par nom.
- `locate nom_fichier` : Recherche un fichier en utilisant une base de données pré-indexée.
- `grep motif fichier` : Recherche un motif dans un fichier ou des fichiers.

## Compression et décompression

- `tar -cvzf fichier.tar.gz dossier` : Compresse un répertoire dans un fichier tar.gz.
- `tar -xvzf fichier.tar.gz` : Décompresse un fichier tar.gz.
- `zip -r nom_archive.zip dossier` : Crée une archive ZIP à partir d'un répertoire.
