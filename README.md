# Application pour compter les coureurs de course de vélo

## I. Introduction
- **Objectif**: Développer une application pour compter les coureurs de course de vélo par catégorie et nombre de tours, permettant une inscription en ligne avant la course et permettant pendant la course à l'utilisateur de modifier des numéros mal saisis, d'en ajouter ou d'en supprimer. L'application doit également permettre à l'utilisateur de définir les nombres de tours attribués pour chaque catégorie, d'identifier les coureurs de même catégorie ayant deux tours de retard et de fournir un classement par catégorie en fin de course.
- **Contexte**: Dans le secteur du cyclisme amateur des course de route, cyclo cross et VTT sont organisés chaque week end. Trois fédérations sont concernées: FSGT, FFC et Ufolep. Jusqu’à présent ces courses nécessitent de nombreux bénévoles pour prendre les inscriptions (souvent par courrier), organiser une liste de départ et au moment de la course, chronométrer et définir les classements par catégories. L’idée serait de simplifier le travail des bénévoles et d’accélérer le temps de traitement des informations. Certaines courses vont utiliser les puces pour le comptage mais cela reste minoritaire car extrêmement onéreux, coûteux en matériel et nécessite également la présence d’un expert indépendant pendant toute une journée.

## II. Fonctionnalités de l'application
1. Inscription des coureurs
- Permettre aux coureurs de s'inscrire en ligne avant la course, en fournissant leur nom, prénom, date de naissance, numéro de téléphone, adresse e-mail, catégorie de course et nombre de tours.
2. Paramétrage des courses
- Permettre à l'utilisateur de définir les nombres de tours attribués pour chaque catégorie.
3. Comptage pendant la course
- Pour les officiels de compter le nombre de coureurs passant par un point de contrôle en temps réel, par catégorie et par nombre de tours.
- Afficher le nombre total de coureurs ayant terminé la course par catégorie et par nombre de tours.
- Permettre à l'utilisateur de modifier des numéros mal saisis, d'en ajouter ou d'en supprimer pendant la course.
- Identifier les coureurs de même catégorie ayant deux tours de retard, dans ce cas leur course est terminée.
- Fournir un classement par catégorie en fin de course.

## III. Exigences fonctionnelles
- L'application doit être facile à utiliser et intuitive pour les organisateurs de la course et pour les coureurs.
- L'application doit pouvoir être utilisée hors ligne pour éviter les problèmes de connexion.
- L'application doit être capable de gérer un grand nombre de coureurs (jusqu'à 300) répartis en différentes catégories avec un nombre de tours spécifique pour chaque catégorie.
- L'application doit être capable de fournir un classement en fin de course et de stocker ces informations en base de données.
