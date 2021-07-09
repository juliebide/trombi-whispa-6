# Trombinoscope Whispa 6.0

1- Créer le fork du projet
2- Cloner le fork du projet

`git clone <url de son lien>`
3- Ajouter des informations

- Ouvrir Visual Studio Code
- Modifier le contenu du fichier `index.html`
- Sauvagerde des modifications 

```bash
trompi-whispa-6>git add index.html
trompi-whispa-6>git commit -m "message en fonction de la modification effectuée"
```

4- Récupération des modifications du projet initial
- Ajout le dépôt distant du projet initial avec le nom `upstream`

```bash
trompi-whispa-6>git remote add upstream https://github.com/dehboris/trombi-whispa-6.git
```

- Recupération des modifications
```bash
trompi-whispa-6>git fetch upstream 
trompi-whispa-6>git merge upstream/main
```

- Résoudre les conflits si il y en a et effectuer les sauvegardes

- Envoyer les modfications vers son dépôt personnel

```bash
trompi-whispa-6>git push origin
```

- Créer une demande de fusion (Pull Request)

