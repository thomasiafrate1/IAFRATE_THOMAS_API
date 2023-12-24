# IAFRATE_THOMAS_API

## Présentation
IAFRATE_THOMAS_API est un projet PHP développé dans le cadre d'un exercice académique pour se familiariser avec le langage PHP et les opérations de base de données MySQL. Le projet permet de réaliser les opérations CRUD (Créer, Lire, Mettre à jour, Supprimer) sur une table MySQL via des requêtes URL.

## Fonctionnalités
Le projet permet de :
- Ajouter une ligne dans la table
- Modifier une ligne existante
- Supprimer une ligne
- Afficher les détails d'une ligne spécifique

## Sécurisation des Identifiants de Connexion
Les identifiants sont stockés séparément dans un dossier mdp qui n'est pas accessible publiquement.
Le dossier mdp contient un fichier creditials.json avec les informations de connexion.
Ces identifiants sont récupérés dans le code de manière sécurisée pour établir la connexion à la base de données.

## Utilisation
### Explication des URLs
#### "action" présent dans l'url correspond à l'action souhaité, il y en a 4 :
- ajouter
- modifier
- supprimer
- afficher

### Ajouter une ligne
Pour ajouter une ligne dans la table, utilisez l'URL suivante :
```http://localhost/IAFRATE_THOMAS_API/public/index.php?action=ajouter&nom=Iafrate&prenom=Thomas&age=19```

### Modifier une ligne
Pour modifier une ligne existante, utilisez l'URL suivante :
```http://localhost/IAFRATE_THOMAS_API/public/index.php?action=modifier&id=30&nom=Bourdi&prenom=Remi&age=20```

### Supprimer une ligne
Pour supprimer une ligne, utilisez l'URL suivante :
```http://localhost/IAFRATE_THOMAS_API/public/index.php?action=supprimer&id=30```

### Afficher une ligne
Pour afficher les détails d'une ligne, utilisez l'URL suivante :
```http://localhost/IAFRATE_THOMAS_API/public/index.php?action=a```

## Langage
PHP

## Auteur
Thomas Iafrate, étudiant en Bachelor 2 Informatique au Campus Ynov Aix-En-Provence.