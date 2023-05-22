# Application pour compter les coureurs de course de vélo

## I. Introduction

- **Contexte**: Dans le secteur du cyclisme amateur des course de route, cyclo cross et VTT sont organisés chaque week end. Trois fédérations sont concernées: FSGT, FFC et Ufolep. Jusqu’à présent ces courses nécessitent de nombreux bénévoles pour prendre les inscriptions (souvent par courrier), organiser une liste de départ et au moment de la course, chronométrer et définir les classements par catégories. L’idée serait de simplifier le travail des bénévoles et d’accélérer le temps de traitement des informations. Certaines courses vont utiliser les puces pour le comptage mais cela reste minoritaire car extrêmement onéreux, coûteux en matériel et nécessite également la présence d’un expert indépendant pendant toute une journée.

- **Objectif**: 
``` 
Développer une application à destination des officiel amateurs cyclistes pour classer les coureurs d'une course de vélo en fonction de leur catégorie.
Cette application devra pouvoir importer un fichier Excel des inscris au préalable
```

L'application doit également permettre à l'utilisateur de définir les nombres de tours attribués pour chaque catégorie, 
d'identifier les coureurs de même catégorie ayant deux tours de  retard et de fournir un classement par catégorie 
en fin de course. Certaines catégories ont 4 tours alors que d'autres 2 voir l'exemple ci-dessous 


## II. Fonctionnalités de l'application
### 1. Inscription des coureurs
- Permettre aux officiels de télécharger la liste des engagés réalisée sur Excel, et aussi de pouvoir modifier cette liste,
ajout suppression de coureurs : pour permettre aux retardataires non inscris le jour de la course de pouvoir quand même récupérer un dossard
- Permettre de paramètrer la course: modification des catégories, application d'un certain nombre de tour par catégorie
Liste actuelle 
![IMG_20230518_093031](https://github.com/rmaupoux/applivelo/assets/118294447/9af3e363-e6e8-4fe5-8279-c515757c05d7)


### 2. Comptage pendant la course
- A partir de la liste obtenue à l'étape 1 l'appli devra permettre aux officiels de rentrer les numéros de dossard des coureurs passant par un point de contrôle.
- Afficher le nombre total de coureurs ayant terminé la course par catégorie et par nombre de tours.
- Permettre à l'utilisateur de modifier des numéros mal saisis, d'en ajouter ou d'en supprimer pendant la course. (En option)
- Identifier les coureurs de même catégorie ayant deux tours de retard, dans ce cas leur course est terminée. 
- Fournir un classement par catégorie en fin de course.
- Un temps final devra être fourni pour chaque coureur, avec une imprécision de quelques secondes admissible.
- Renvoyer un document Excel avec le classement (En option)

## III. Exigences fonctionnelles
- L'application doit être facile à utiliser et intuitive pour les organisateurs de la course et pour les coureurs.
- L'application doit pouvoir être utilisée hors ligne pour éviter les problèmes de connexion.
- L'application doit être capable de gérer un grand nombre de coureurs (jusqu'à 300) répartis en différentes catégories avec un nombre de tours spécifique pour chaque catégorie.
- L'application doit être capable de fournir un classement en fin de course et de stocker ces informations en base de données.

![applivelo](https://github.com/rmaupoux/applivelo/assets/118294447/8e5533af-a5ea-4cdc-adb5-1391e6e44b78)

## Exemple de course : 4ème étape du VTT Tour 2023 Dimanche 14 mai 2023
4 tours (H. Espoirs, Séniors et Vétérans), 3 tours (Dames : Juniores, Séniores et
Vétéranes A ; Hommes : Juniors, Masters 1 et Masters 2 + Tandems) , 2 tours
(Cadets G et F + Féminines Vétéranes B) ou 1 tour (Minimes G et F) selon les âges
### Détail sur les catégories

Hommes : Minimes (2009-2010), Cadets (2007-2008), Juniors (2005-2006), Espoirs
(2001-2004), Séniors (1984-2000), Vétérans (1974-1983), Masters 1 (1964-1973),
Masters 2 (1963 et avant).
Dames : Minimes, Cadettes, Juniores (id. que G.), Séniores (incluant les Espoires :
1984-2004), Vétéranes A (1974-1983) et Vétéranes B (1973 et avant).
Tandems (mixtes ou non)


