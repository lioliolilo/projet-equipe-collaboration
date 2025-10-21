# Rapport de laboratoire Git - Équipe Adam Agha, Siyuan Zhao, Lucas Zijie Qin et Gabriel Poirier

## 1. Membres de l'équipe
- Membre 1 : Adam Agha - Chef d'équipe
- Membre 2 : Siyuan Zhao - Développeur
- Membre 3 : Zijie Lucas Qin - Testeur
- Membre 3 : Gabriel Poirier - Testeur

## 2. Résumé des parties complétées

### Partie 1 : Configuration initiale
Membre 1: Nous avons initialisé un git local dans un nouveau dossier, ajouté un fichier README.md puis on a commit ce fichier. Dans la section suivante, nous avons créé un nouveau dépôt GitHub. Enfin, nous avons connecté notre git local au dépôt GitHub.

Membre 2: j'ai mon compte GitHub personnel. 

### Partie 2 : Ajout des collaborateurs
Membre 1: Pour inviter quelqu'un à collaborer sur votre dépôt GitHub, accédez aux paramètres, puis à la section « Collaborateurs », vous pouvez inviter des personnes en utilisant leur nom d'utilisateur. Pour cloner un dépôt, dans VS Code, utilisez la commande « git clone » suivie du lien HTTPS du dépôt. Vous serez alors invité à choisir l'emplacement de sauvegarde.

Membre 2: J'ai reçu une invitation via les notifications GitHub pour collaborer au dépôt. Je l'ai acceptée, puis j'ai utilisé la commande `git clone` avec l'URL HTTPS du dépôt pour en obtenir une copie locale sur mon ordinateur.

### Partie 3 : Première collaboration
Membre 1: Nous avons créé nos fichiers individuels en récupérant d'abord les modifications les plus récentes dans le dépôt GitHub à l'aide de « git pull », puis en créant un nouveau fichier dans VS Code. Nous avons ensuite dû préparer la modification, la valider et la « push » vers le dépôt.

Membre 2: J'ai d'abord utilisé `git pull` pour m'assurer d'avoir la version la plus récente du projet. J'ai ensuite créé mon fichier personnel `membre2.txt`. Ensuite, j'ai utilisé `git add membre2.txt`, `git commit -m "Ajout des informations du membre 2"` et `git push` pour envoyer mon fichier sur GitHub.

### Partie 4 : Résolution de conflits
Membre 1: J'ai créé un nouveau fichier index.html dans VS Code et y ai ajouté du contenu. J'ai ensuite mis en scène la modification, je l'ai validée puis je l'ai « push » vers le dépôt GitHub.

Membre 2: J'ai modifié le fichier `README.md` sans faire de `git pull`. Lorsque j'ai tenté de `git push`, Git a rejeté mon envoi car Membre 1 avait déjà modifié le même fichier. J'ai alors fait `git pull`, ce qui a donné un conflit de fusion. J'ai ouvert `README.md` dans VS Code, identifié les marqueurs de conflit, puis j'ai modifié manuellement le fichier pour combiner les deux versions. Pour finir, je les ai envoyé sur GitHub.

### Partie 5 : Collaboration HTML
Membre 2: J'ai commencé par un `git pull` pour récupérer le fichier `index.html` de base. J'ai ensuite ajouté la section `<section id="apropos">` dans le fichier HTML, puis j'ai push mes modifications. Plus tard, j'ai modifié le titre `<h1>` et l'ai push, ce qui a causé un conflit pour Membre 3.

### Partie 6 : Utilisation des branches
Nous devons utiliser la commande « git checkout » pour créer une nouvelle branche. Cela nous permettra d'effectuer des modifications en dehors de la branche principale, puis, à la fin, on peut supprimer la nouvelle branche ou fusionner les deux. Pour les fusionner, nous avons d'abord utilisé la commande « git checkout main » pour revenir à la branche principale, puis la commande « git merge » suivie du nom de la nouvelle branche.

### Partie 7 : Situations réalistes
Membre 2: 
1.  **Situation 1 :** J'ai modifié `membre2.txt` en même temps que le Membre 1 modifiait `membre1.txt`. Comme nous travaillions sur des fichiers différents, il n'y a pas eu de conflit.
2.  **Situation 2 :** J'ai modifié `README.md` après le Membre 1 sans `pull`, mon `push` a échoué, et j'ai dû faire `git pull` et résoudre un conflit avant de pouvoir "pusher".
3.  **Situation 3 :**
4.  **Situation 4 :** Nous avons tous testé les trois formats différents de « git log ». D'abord, « git log » affiche tous les commits et leurs informations. Ensuite, nous avons utilisé « git log --oneline », qui condense tout en une seule ligne pour une meilleure lisibilité. Enfin, nous avons utilisé « git log --oneline --graph --all », qui inclut les commits et leurs informations, ainsi que les branches que nous avons créées.

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
- Apprentissage 1 : L'importance de faire un git pull régulièrement avant de commencer à travailler pour éviter les conflits. Cela permet de synchroniser son travail avec celui des autres membres de l'équipe.
- Apprentissage 2 : Comment résoudre un conflit de fusion. En cas de modifications concurrentes sur le même fichier, Git vous aide à identifier et résoudre les conflits manuellement.
- Apprentissage 3 : L'utilité des branches pour travailler sur des fonctionnalités séparées sans perturber le code principal. Les branches permettent de gérer les différentes parties d'un projet sans interférence directe.

### Ce que nous avons appris sur le travail d'équipe
- Apprentissage 1 : L'importance de la communication pour éviter les conflits, en particulier lorsque plusieurs membres travaillent sur les mêmes fichiers. Cela permet d'être sûr que les modifications sont bien synchronisées.
- Apprentissage 2 : Comment coordonner le travail entre les membres de l'équipe en utilisant Git et GitHub. L'utilisation des branches, des commits et des pulls facilite le travail collaboratif en permettant à chacun de contribuer sans perturber les autres.

## 6. Conclusion
Ce laboratoire Git nous a permis de comprendre l'importance d'une gestion efficace du code en équipe. Grâce à des exercices pratiques sur GitHub, nous avons appris à configurer un dépôt, inviter des collaborateurs, résoudre des conflits, et utiliser des branches pour travailler en parallèle. L'une des leçons clés de cette expérience a été l'importance de toujours effectuer un git pull avant de commencer à travailler, afin d'éviter les conflits. De plus, nous avons découvert la puissance des branches pour gérer différentes fonctionnalités sans interférer avec la branche principale. Enfin, la gestion des conflits de fusion nous a permis de comprendre la complexité d'un travail collaboratif et l'importance de la communication au sein de l'équipe pour résoudre ces situations. Cette expérience nous a non seulement renforcés sur nos compétences techniques mais aussi sur notre capacité à travailler efficacement en équipe.