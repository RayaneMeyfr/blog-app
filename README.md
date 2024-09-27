## Structure du Projet

1. Initialisation du dépôt Git :
    ```bash
    git init
    git add README.md
    git commit -m "First commit"
    git branch -M main
    git remote add origin https://github.com/RayaneMeyfr/blog-app.git
    git push origin main
    ```

### Gestion des articles

2. Création et gestion de la branche `Article` :
    ```bash
    git checkout -b Article
    git branch
    git add article.txt
    git commit -m "Ajout: Gestion des articles"
    git push origin Article
    ```

### Gestion des commentaires

3. Création et gestion de la branche `Comments` :
    ```bash
    git checkout main
    git checkout -b Comments
    git add comments.txt
    git commit -m "Ajout: Gestion des commentaires"
    git push origin Comments
    ```

### Gestion des utilisateurs

4. Création et gestion de la branche `Users` :
    ```bash
    git checkout main
    git checkout -b Users
    git add user.txt
    git commit -m "Ajout: Gestion des utilisateurs"
    git push origin Users
    ```

### Gestion des Pull Requests et merge

5. PR et merge des branches :
    - Création d'un PR pour la branche `Article`.
    - Commentaire du PR.
    - Confirmation du PR avec un merge sur la branche `main`.

    - Création d'un PR pour la branche `Comments`.
    - Commentaire du PR.
    - Confirmation du PR avec un merge sur la branche `main`.

    - Création d'un PR pour la branche `Users`.
    - Commentaire du PR.
    - Confirmation du PR avec un merge sur la branche `main`.

### Correction de bug sur les commentaires

6. Gestion du bug :
    ```bash
    git checkout main
    git pull origin
    git add bug_report.md
    git commit -m "bug:comments"
    git checkout -b FixBugComment
    git add comments.txt
    git commit -m "FIX: correction du bug dans comments"
    git push origin FixBugComment
    ```

### Mise à jour du `README`

7. Mise à jour de la documentation :
    ```bash
    git checkout main
    git add README.md
    git commit -m "Mise à jour de README"
    git push origin main
    ```
