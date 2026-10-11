# Mes outils de classe

Page d'accueil qui regroupe tous mes outils pédagogiques, rangés par projet : https://anlito.github.io/

Elle est mise en ligne automatiquement par GitHub Pages à chaque envoi sur la branche `main`.

## Ajouter un nouvel outil

Dans `index.html` :
- outil d'un projet existant : copier un bloc `<article class="tool">…</article>` dans la `<section class="project">` du projet ;
- nouveau projet : copier une `<section class="project">` entière, lui donner une couleur (`--c-…` dans `:root` et les deux blocs sombres) et ajouter son lien dans `<nav class="jump">`.

Puis changer le nom, la description, le lien « Ouvrir l'outil », le lien de « Copier le lien », l'adresse affichée et les documents.
Outil réservé au professeur : classe `is-prof` sur l'article et badge `only-prof`. Accès professeur dans un outil élève : encart `<div class="prof">` (sans jamais écrire le code : la page est publique).
Mettre à jour les compteurs (« N projets · N outils » en haut, « N outils » du projet).

## Outils actuels

| Projet | Outil | Adresse |
|---|---|---|
| Concept Store | Concept Store 3D | https://anlito.github.io/concept-store-3d/ |
| Concept Store | Site vitrine | https://anlito.github.io/creation-site-vitrine/ |
| Concept Store | Concept Store · Professeur | https://anlito.github.io/concept-store-prof/ |
| Distributeur de céréales | Atelier de blocs (+ `prof.html`) | https://anlito.github.io/atelier-cereales/ |
| Théâtre d'ombre | Théâtre d'ombre augmenté | https://anlito.github.io/theatre-ombre/ |
| Toute l'année | Carnet de classe | https://anlito.github.io/gestion-de-classe-et-suivi-projet/ |
