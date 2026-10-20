# Mes outils de classe

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
| Théâtre d'ombre | Théâtre d'ombre augmenté | https://anlito.github.io/theatre-ombre/ |
| Théâtre d'ombre | Théâtre d'ombre · Professeur | https://anlito.github.io/theatre-ombre/professeur.html |
| Robot Rush | Robot Rush · Jouer (élèves, hébergé sur Render) | https://robot-rush.onrender.com/jouer |
| Robot Rush | Robot Rush · Professeur | https://robot-rush.onrender.com/admin |
| Labo Blocs | Labo Blocs · Parcours (choix du parcours) | https://anlito.github.io/labo-blocs/site/eleves.html |
| Labo Blocs | Labo Blocs · Professeur (accueil, éditeur, suivi) | https://anlito.github.io/labo-blocs/site/accueil.html |
| Toute l'année | Carnet de classe | https://anlito.github.io/gestion-de-classe-et-suivi-projet/ |
| Toute l'année | Sauvegarde du travail des élèves (Windows, à télécharger) | https://anlito.github.io/fichiers/sauvegarde-eleves/SauvegardeEleves.zip |
