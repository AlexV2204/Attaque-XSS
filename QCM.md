# [Basics] Injections SQL : découvrir (challenge)

## 1. Les SQLi représentent une menace pour les sites web statiques.
FAUX

## 2. Les SQLi peuvent être DOM-based, c'est-à-dire que l'attaque reste dans le navigateur et n'atteint jamais le serveur.
FAUX

## 3. "SELECT * FROM users WHERE email = ?" est une requête...
Paramétrée

## 4. Les frameworks d'Object Relational Mapping (ORM) utilisent majoritairement, sous leur capot...
Des requêtes SQL paramétrées

## 5. Les frameworks d'Object Relational Mapping (ORM) empêchent la création de requêtes dynamiques.
FAUX

## 6. Les attaques par SQLi représentent une menace uniquement pour les applications web codées en PHP.
FAUX

## 7. A priori, laquelle de ces requêtes représente une faille potentielle pour une SQLi ?
User.where("email = '" + email + "'")

## 8. Une requête paramétrée permet l'interprétation d'un input provenant de l'utilisateur en tant que...
Donnée

## 9. Le code String sql = "SELECT * FROM users WHERE email = '" + email + "'"; correspondra à une requête...
Dynamique


