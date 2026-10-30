# Mes outils de classe

<!-- suivi-maintenance:debut -->
## État du projet et améliorations documentées — 28 octobre 2026

- Rubrique 6e SEGPA : la course de voitures à ballon est en ligne (fiche élèves mise à jour, fiche « Voiture à ballon · Professeur » ajoutée avec la course et les gabarits). Compteurs : 11 projets · 24 outils.
- Une rubrique 6e SEGPA a été ajoutée (couleur `--c-segpa`) : fiche élèves (`segpa/`, le portail des projets SEGPA, sans lien professeur) et fiche professeur (`segpa/professeur.html`, page non liée depuis l'écran des élèves). Menu et compteurs mis à jour (11 projets · 23 outils). Premier projet : « Je démonte un objet technique » (taille-crayon).

- Une rubrique mBot Challenge · 3e a été ajoutée (couleur `--c-mbot`) : fiche élèves (`mbot-challenge/`, avec les fiches à imprimer) et fiche professeur (`prof.html`, avec `regie.html` et les fiches en documents). Menu et compteurs mis à jour (10 projets · 21 outils).

- Une rubrique Escape Lab · 3e a été ajoutée (couleur `--c-escape`) : fiche élèves (`site/`) et fiche professeur (`site/?prof`, avec `prof.html` et `regie.html` en documents). Menu et compteurs mis à jour (9 projets · 19 outils).

- Une rubrique Simon Rétro Game · 5e et 4e a été ajoutée (couleur `--c-simon`) : deux fiches distinctes, accès élèves (avec le tutoriel de câblage) et accès professeur (`prof.html`, avec le mode d’emploi). Menu et compteurs mis à jour (8 projets · 17 outils).
- Une rubrique Labyrinthe robotisé · 5e et 4e a été ajoutée au portail, avec deux fiches distinctes : accès élèves et accès professeur.
- Le menu, les filtres et les compteurs ont été adaptés. L’affichage sur ordinateur et téléphone ainsi que les liens ont été vérifiés lors de cette amélioration.
- Les fiches du portail sont dans index.html. Les fichiers proposés au téléchargement depuis fichiers/ restent à synchroniser avec leurs projets d’origine lorsque ces fichiers changent.

### Référence locale et maintenance

Dossier de travail de référence : **Documents/anlito.github.io**. Dépôt : [Anlito/anlito.github.io](https://github.com/Anlito/anlito.github.io). La branche principale est **main**. Les copies temporaires d’un chat ou les worktrees servent au travail intermédiaire ; elles ne remplacent pas ce dossier.

À chaque intervention :

1. Vérifier les modifications locales et la version publiée avant de commencer ; sauvegarder le travail non enregistré.
2. Décrire dans ce README les améliorations, les vérifications, les limites et les opérations restantes.
3. Publier les changements autorisés, puis synchroniser le dossier local de référence avec le même commit.
4. Contrôler le commit local, le commit distant et les fichiers restants avant d’annoncer que le projet est à jour. Signaler explicitement tout décalage ou travail conservé hors publication.

Cette règle permet de reprendre le projet dans un autre outil local sans perdre les dernières améliorations. Une publication du site ne met pas automatiquement à jour les dossiers du PC.

<!-- suivi-maintenance:fin -->

Page d'accueil qui regroupe tous mes outils pédagogiques, rangés par projet : https://anlito.github.io/

La plupart des outils sont sur GitHub Pages (`anlito.github.io/…`). Robot Rush a besoin d'un serveur : il est hébergé sur Render (`robot-rush.onrender.com`).

Elle est mise en ligne automatiquement par GitHub Pages à chaque envoi sur la branche `main`.

## Ajouter un nouvel outil

Dans `index.html` :
- outil d'un projet existant : copier un bloc `<article class="tool">…</article>` dans la `<section class="project">` du projet ;
- nouveau projet : copier une `<section class="project">` entière, lui donner une couleur (`--c-…` dans `:root` et les deux blocs sombres) et ajouter son lien dans `<nav class="jump">`.

Puis changer le nom, la description, le lien « Ouvrir l'outil », le lien de « Copier le lien », l'adresse affichée et les documents.
Chaque fiche commence par un bandeau `<div class="who">` (« Pour les élèves » ou « Pour le professeur ») : copier celui d'une fiche du même type. Outil réservé au professeur : classe `is-prof` sur l'article (fond grisé, bandeau sombre, masqué par le filtre « Élèves »). Accès professeur dans un outil élève : encart `<div class="prof">` (sans jamais écrire le code : la page est publique).
Mettre à jour les compteurs (« N projets · N outils » en haut, « N outils » du projet).

## Fichiers à télécharger

Le dossier `fichiers/` contient des copies de fichiers d'autres dépôts, proposés en téléchargement sur la page
(un lien `download` ne marche que pour un fichier du même site) :

| Fichier | Copie de |
|---|---|
| `fichiers/robot-rush/MODELE-QUESTIONS-IA.md` | `Anlito/robot-rush` : `outils-salle/MODELE-QUESTIONS-IA.md` |
| `fichiers/robot-rush/exemple-questions-robot-rush.json` | `Anlito/robot-rush` : `outils-salle/exemple-questions-robot-rush.json` |
| `fichiers/sauvegarde-eleves/SauvegardeEleves.zip` | Outil Windows (pas de dépôt à part) : le dossier `SauvegardeEleves` zippé |
| `fichiers/sauvegarde-eleves/mode-d-emploi.txt` | `Mode d'emploi.txt` du zip ci-dessus |

Quand l'original change, recopier le fichier ici.

## Outils actuels

| Projet | Outil | Adresse |
|---|---|---|
| Concept Store | Concept Store 3D | https://anlito.github.io/concept-store-3d/ |
| Concept Store | Site vitrine | https://anlito.github.io/creation-site-vitrine/ |
| Concept Store | Concept Store · Professeur | https://anlito.github.io/concept-store-prof/ |
| Distributeur de céréales | Atelier de blocs | https://anlito.github.io/atelier-cereales/ |
| Distributeur de céréales | Distributeur de céréales · Professeur | https://anlito.github.io/atelier-cereales/prof.html |
| Labyrinthe robotisé | Labyrinthe robotisé · Élèves | https://anlito.github.io/labyrinthe-robotise/ |
| Labyrinthe robotisé | Labyrinthe robotisé · Professeur | https://anlito.github.io/labyrinthe-robotise/prof.html |
| Simon Rétro Game | Simon Rétro Game · Élèves | https://anlito.github.io/simon-retro-game/ |
| Simon Rétro Game | Simon Rétro Game · Professeur | https://anlito.github.io/simon-retro-game/prof.html |
| Escape Lab | Escape Lab · Élèves | https://anlito.github.io/escape-lab/site/ |
| Escape Lab | Escape Lab · Professeur (suivi, pilotage, évaluation ; fiches et synchronisation dans prof.html ; regie.html) | https://anlito.github.io/escape-lab/site/?prof |
| mBot Challenge | mBot Challenge · Élèves (fiches à imprimer : fiches.html) | https://anlito.github.io/mbot-challenge/ |
| mBot Challenge | mBot Challenge · Professeur (régie du tournoi : regie.html, écran projeté) | https://anlito.github.io/mbot-challenge/prof.html |
| Théâtre d'ombre | Théâtre d'ombre augmenté | https://anlito.github.io/theatre-ombre/ |
| Théâtre d'ombre | Théâtre d'ombre · Professeur | https://anlito.github.io/theatre-ombre/prof.html |
| 6e SEGPA | 6e SEGPA · Élèves (taille-crayon ; voiture à ballon et stop motion à venir) | https://anlito.github.io/segpa/ |
| 6e SEGPA | 6e SEGPA · Professeur (suivi, évaluation, exports) | https://anlito.github.io/segpa/professeur.html |
| Robot Rush | Robot Rush · Jouer (élèves, hébergé sur Render) | https://robot-rush.onrender.com/jouer |
| Robot Rush | Robot Rush · Professeur | https://robot-rush.onrender.com/admin |
| Labo Blocs | Labo Blocs · Parcours (choix du parcours) | https://anlito.github.io/labo-blocs/site/eleves.html |
| Labo Blocs | Labo Blocs · Professeur (accueil, éditeur, suivi) | https://anlito.github.io/labo-blocs/site/accueil.html |
| Toute l'année | Carnet de classe | https://anlito.github.io/gestion-de-classe-et-suivi-projet/ |
| Toute l'année | Sauvegarde du travail des élèves (Windows, à télécharger) | https://anlito.github.io/fichiers/sauvegarde-eleves/SauvegardeEleves.zip |
