# Que fait la commande git init ?

La commande git init initalise un repository git dans le dossier ou on a executer la commande, il créer un dossier caché .git qui contient tout les fichiers et dossiers necessaires pour le fonctionnement de git.

# Quelle est la différence entre git add et git commit ?

git add permet d'ajouter des fichiers dans la zone de staging (en gros de dire a git de mettre en attentes ces fichiers pour les prochains commits) et git commit permet de créer un commit avec les fichiers qui sont dans la zone de staging 
git add = ajouter des mot dans une lettre
git commit = envoyer la lettre

# Expliquez pourquoi il est important de bien rédiger les messages de commit.

Pour bien distingué les modifications apporté dans le commits, pour ne pas a regarder le code, l'analysé et comprendre ce qu'il fait, exemple avec un commit avec le nom "Changement couleur bouton connexion" on sait directement ce que fait le commit sans avoir a regarder le code.

# Quelle est la commande pour ajouter ce fichier au suivi ?

git add main.c

# Que représente chaque ligne dans le résultat de git log ?

Chaque ligne représente un commit, avec le hash du commit, l'auteur, la date et l'heure du commit et le message du commit.

# À quoi sert git diff ? 

git diff permet de voir les modifications apporté dans les fichiers qui ne sont pas encore dans la zone de staging (qui n'ont pas été encore git add) comparé a la derniere version commité.

# Pourquoi est-il utile d'avoir un fichier .gitignore ?

le fichier gitignore permet de que certains fichier ou extension de fichier soit ignoré automatiquement dans les commits, pour ne pas par exemple commit et push des fichier sensibles ou des fichier de configuration.

# Quelle est la différence entre un dépôt public et un dépôt privé ?

un depot public est visible par tous le monde et un depot privé est visible seulement par les personnes qui ont les droits d'accès.

# Expliquez à quoi sert la commande git remote add origin 

git remote add origin permet d'ajouter un remote a notre repository git, un remote est le lien vers le repository distant 

# Que signifie l'option -u dans la commande git push ?

l'option -u permet de dire a git de lier la branche local avec la branche distante, pour que les prochains git push et git pull soit plus simple et rapide.