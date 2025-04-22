**Nom :** Lucas Leprevost  
**Groupe :** Groupe 6  
**Année :** BUT1  

**IUT Le Havre - Cours GIT**

---

### Compte-rendu TP1 – Introduction à Git (en local)

Dans ce TP, on apprend à travailler avec Git, un outil très utilisé en développement pour **gérer l’historique des fichiers dans un projet**. Ce TP est une introduction aux commandes de base de Git en **local**, sans utiliser GitHub.

#### Objectifs :
- Comprendre ce qu’est un dépôt Git
- Apprendre à suivre les modifications d’un projet
- Savoir enregistrer les versions d’un fichier avec des messages clairs
- Gérer les fichiers ignorés avec `.gitignore`

---

### Étapes réalisées :

1. **Initialisation du projet**
   - Création d’un dossier `tp1`
   - Utilisation de la commande `git init` pour créer un dépôt Git local

2. **Ajout d’un fichier à suivre**
   - On a créé un fichier `Cryptomonnaie.java` et un fichier `README.md`
   - Git ne suit pas les fichiers automatiquement : on a utilisé `git add` pour les suivre

3. **Création d’un commit**
   - On a enregistré une version du projet avec `git commit -m "Premier commit"`
   - Un commit correspond à une "photo" de l’état du projet à un moment donné, avec un message explicatif

4. **Visualisation de l’historique**
   - La commande `git log` nous permet de voir la liste des commits effectués

5. **Modification d’un fichier**
   - On a modifié le fichier `Cryptomonnaie.java` (par exemple : ajout d’un constructeur)
   - Puis on a refait `git add` et `git commit` pour enregistrer les changements

6. **Gestion des fichiers à ignorer**
   - On a créé un fichier `.gitignore` pour ne pas suivre certains fichiers (ex : fichiers temporaires)

---

### Ce que j’ai retenu :
Ce TP m’a permis de découvrir les bases de Git en local. J’ai compris que Git permet :
- de suivre toutes les versions d’un fichier
- de revenir en arrière si besoin
- de mieux organiser mon travail

C’est un outil indispensable pour les projets de développement, même si on travaille seul.

---

### Quelques commandes utiles vues dans le TP :
```bash
git init           # Crée un nouveau dépôt Git
git status         # Montre les fichiers modifiés ou suivis
git add fichier    # Ajoute un fichier pour le prochain commit
git commit -m ""   # Enregistre un nouveau commit avec un message
git log            # Affiche l’historique des commits
