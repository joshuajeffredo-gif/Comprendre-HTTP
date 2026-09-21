# HTTP-AP1

Projet réalisé dans le cadre d'un exercice sur les requêtes HTTP.

## Objectif

Le projet prend la forme d'un jeu de piste permettant de découvrir progressivement le fonctionnement d'une API et des différentes méthodes HTTP.

Les requêtes sont enregistrées dans plusieurs fichiers `.yml`.

## Méthodes HTTP utilisées

Le projet permet de manipuler plusieurs méthodes :

* `GET` : récupérer des informations
* `POST` : envoyer ou créer des données
* `PUT` : modifier ou remplacer des données
* `DELETE` : supprimer une ressource
* `PATCH` : modifier une partie d'une ressource

## Contenu

Le jeu de piste est composé d'une introduction suivie de plusieurs étapes :

```text
Jeu de piste étape intro.yml
Jeu de piste étape 1.yml
Jeu de piste étape 2.yml
Jeu de piste étape 3.yml
Jeu de piste étape 4.yml
Jeu de piste étape 5.yml
Jeu de piste étape 6.yml
Jeu de piste étape 7.yml
opencollection.yml
```

Chaque fichier contient une requête HTTP permettant d'avancer dans le jeu de piste.

## Notions abordées

Au cours des différentes étapes, le projet utilise notamment :

* les paramètres d'URL
* les paramètres de requête
* les données JSON
* les headers HTTP
* le `Content-Type`
* les clés API
* les différentes méthodes HTTP

## API

Les exercices communiquent avec une API disponible sur le réseau local :

```text
172.16.3.254:8001
```

L'accès à cette API peut donc nécessiter d'être connecté au réseau prévu pour le TP.
Réalisé par Chatgpt avec le prompt suivant : "si je t'envoie tout ça est-ce que tu peux me faire un readme simple ?"
