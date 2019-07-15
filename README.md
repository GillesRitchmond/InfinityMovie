# InfinityMovie
InfinityMovie est une application qui permet aux utilisateurs de parcourir des films à partir de [l'API de base de données de films] (http://docs.themoviedb.apiary.io/#).



## InfinityMovie Part 1

### Histoires d'utilisateurs

#### REQUIS (10pts)
- [x] (10pts) L'utilisateur peut voir une liste des films (titre, image de l'affiche et aperçu) en cours de lecture dans les cinémas à partir de l'API Movie Database.

#### PRIME
- [x] (2pts) Les vues doivent être réactives pour le mode paysage / portrait.
   - [x] (1pt) En mode portrait, l'image affiche, le titre et la présentation du film sont affichés.
   - [x] (1pt) En mode paysage, la disposition modifiée en rotation doit utiliser l'image de fond et afficher le titre et la présentation du film à droite de celle-ci.

- [x] (2pts) Affiche un joli graphique [espace réservé] par défaut (https://guides.codepath.org/android/Displaying-Images-with-the-Glide-Library#advanced-usage) pour chaque image lors du chargement.
- [x] (2pts) Amélioration de l'interface utilisateur en expérimentant le style et la coloration.
- [] (2pts) Pour les films populaires (c’est-à-dire un film dont le nombre d’élèves est supérieur à 5 étoiles), l’image de fond complète est affichée. Sinon, une image d'affiche, le titre du film et une vue d'ensemble sont répertoriés. Utilisez Heterogenous RecyclerViews et utilisez différents fichiers de mise en page ViewHolder pour les films populaires et les moins populaires.

### App Walklever GIF 
<img src = "https://github.com/GillesRitchmond/InfinityMovie/blob/master/gif_movies.gif" width = 250> <br>
### Remarques
Décrivez les difficultés rencontrées lors de la création de l'application.

### Bibliothèques Open-Source utilisée

- [Android Async HTTP] (https://github.com/loopj/android-async-http) - Requêtes HTTP asynchrones simples avec analyse JSON
- [Glide] (https://github.com/bumptech/glide) - Bibliothèque de chargement et de mise en mémoire d'images pour Androids
