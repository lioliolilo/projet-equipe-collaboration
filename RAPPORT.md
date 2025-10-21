# Rapport de laboratoire Git - Équipe Adam Agha, Siyuan Zhao, Lucas Zijie Qin et Gabriel Poirier

## 1. Membres de l'équipe
- Membre 1 : Adam Agha - Chef d'équipe
- Membre 2 : Siyuan Zhao - Développeur
- Membre 3 : Zijie Lucas Qin - Testeur
- Membre 3 : Gabriel Poirier - Testeur

## 2. Résumé des parties complétées

### Partie 1 : Configuration initiale
Nous avons initialisé un git local dans un nouveau dossier, ajouté un fichier README.md puis on a commit ce fichier. Dans la section suivante, nous avons créé un nouveau dépôt GitHub. Enfin, nous avons connecté notre git local au dépôt GitHub.

Membre 2: j'ai mon compte GitHub personnel. 

### Partie 2 : Ajout des collaborateurs
Pour inviter quelqu'un à collaborer sur votre dépôt GitHub, accédez aux paramètres, puis à la section « Collaborateurs », vous pouvez inviter des personnes en utilisant leur nom d'utilisateur. Pour cloner un dépôt, dans VS Code, utilisez la commande « git clone » suivie du lien HTTPS du dépôt. Vous serez alors invité à choisir l'emplacement de sauvegarde.

Membre 2: J'ai reçu une invitation via les notifications GitHub pour collaborer au dépôt. Je l'ai acceptée, puis j'ai utilisé la commande `git clone` avec l'URL HTTPS du dépôt pour en obtenir une copie locale sur mon ordinateur.

### Partie 3 : Première collaboration
Membre 2: J'ai d'abord utilisé `git pull` pour m'assurer d'avoir la version la plus récente du projet. J'ai ensuite créé mon fichier personnel `membre2.txt`. Ensuite, j'ai utilisé `git add membre2.txt`, `git commit -m "Ajout des informations du membre 2"` et `git push` pour envoyer mon fichier sur GitHub.

### Partie 4 : Résolution de conflits
Membre 2: J'ai modifié le fichier `README.md` sans faire de `git pull`. Lorsque j'ai tenté de `git push`, Git a rejeté mon envoi car Membre 1 avait déjà modifié le même fichier. J'ai alors fait `git pull`, ce qui a donné un conflit de fusion. J'ai ouvert `README.md` dans VS Code, identifié les marqueurs de conflit, puis j'ai modifié manuellement le fichier pour combiner les deux versions. Pour finir, je les ai envoyé sur GitHub.

### Partie 5 : Collaboration HTML
Membre 2: J'ai commencé par un `git pull` pour récupérer le fichier `index.html` de base. J'ai ensuite ajouté la section `<section id="apropos">` dans le fichier HTML, puis j'ai push mes modifications. Plus tard, j'ai modifié le titre `<h1>` et l'ai push, ce qui a causé un conflit pour Membre 3.

### Partie 6 : Utilisation des branches
[Décrivez la création et la fusion de la branche]

### Partie 7 : Situations réalistes
Membre 2: 
1.  **Situation 1 :** J'ai modifié `membre2.txt` en même temps que le Membre 1 modifiait `membre1.txt`. Comme nous travaillions sur des fichiers différents, il n'y a pas eu de conflit.
2.  **Situation 2 :** J'ai modifié `README.md` après le Membre 1 sans `pull`, mon `push` a échoué, et j'ai dû faire `git pull` et résoudre un conflit avant de pouvoir "pusher".

## 3. Captures d'écran

### Étape 1.1 - Initialisation du dépôt
![Description](chemin/vers/capture1.png)

### Étape 1.2 - Création du compte GitHub
![Description](chemin/vers/capture2.png)

[Continuez pour toutes les étapes...]

## 4. Difficultés rencontrées

### Difficulté 1
- **Problème** : [Décrivez le problème rencontré]
- **Solution** : [Expliquez comment vous l'avez résolu]

### Difficulté 2
- **Problème** : [Décrivez le problème]
- **Solution** : [Expliquez la solution trouvée]

## 5. Apprentissages

### Ce que nous avons appris sur Git
- [Apprentissage 1 : par exemple, l'importance de faire git pull régulièrement]
- [Apprentissage 2 : par exemple, comment résoudre un conflit]
- [Apprentissage 3 : par exemple, l'utilité des branches]

### Ce que nous avons appris sur le travail d'équipe
- [Apprentissage 1 : par exemple, l'importance de la communication]
- [Apprentissage 2 : par exemple, comment coordonner le travail]

## 6. Conclusion
[Rédigez une courte conclusion (5-10 lignes) sur votre expérience globale du laboratoire]