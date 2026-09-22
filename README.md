# HTTP Comprendre le HTTP

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

## BRUNO

J'ai installé Bruno "https://www.usebruno.com/" <br>
et j'ai mis la clé API donné dans le tp : "https://jsonplaceholder.typicode.com/posts" <br>
puis avec un **GET** pour récupérer les information du serveur ce qui m'a donné ceci : 
![alt text](assets/image-1.png)
Pour répondre aux questions suivante : 
- Comment est affichée la réponse ?
**La réponse s’affiche à droite de l’écran, dans la partie Response, ici au format JSON.**
- Comment sauvegarder la requête ?<br>
**On peut sauvegarder la requête avec Ctrl + S ou avec l’option d’enregistrement de Bruno. La requête est enregistrée dans la collection.**
- Comment organiser les requêtes (dossiers/collections) ?<br>
**Les requêtes peuvent être regroupées dans des collections puis rangées dans des dossiers pour mieux les organiser.**

## POSTMAN

J'ai utilisé POSTMAN sur navigateur "https://web.postman.co/"<br>
et j'ai mis la clé API donné dans le tp "https://jsonplaceholder.typicode.com/posts"<br>
puis avec un **GET** pour récupérer les informations du serveur ce qui m'a donné ceci : 
![alt text](assets/image.png)
Pour répondre aux questions suivante : 
- Comment est affichée la réponse ?<br>
**La réponse s’affiche dans la partie basse de Postman, dans l’onglet Body ici au format JSON.**
- Comment sauvegarder la requête ?
**On peut sauvegarder la requête en cliquant sur le bouton Save en haut à droite.**
- Comment organiser les requêtes (dossiers/collections) ?
**Les requêtes peuvent être rangées dans des Collections puis classées dans des dossiers à l’intérieur de ces collections.**

## INSOMNIA

J'ai installé INSOMNIA "https://app.insomnia.rest/" <br>
et j'ai mis la clé API donné dans le tp : "https://jsonplaceholder.typicode.com/posts" <br>
puis avec un **GET** pour récupérer les information du serveur ce qui m'a donné ceci : 
![alt text](assets/image-2.png)
Pour répondre aux questions suivante : 
- Comment est affichée la réponse ?<br>
**La réponse s’affiche à droite de l’écran, dans l’onglet Preview, ici au format JSON.**
- Comment sauvegarder la requête ?<br>
**Insomnia enregistre automatiquement les modifications de la requête.**
- Comment organiser les requêtes (dossiers/collections) ?<br>
**Les requêtes peuvent être regroupées dans des collections et rangées dans des dossiers pour mieux les organiser.**
