
1. **Création d'une API CRUD avec Node.js et MySQL** :
   - configuration d'une API simple en Node.js pour gérer les utilisateurs avec un champ `nom`.
   - utilisation **MySQL** pour la base de données, en créant une table `users` pour stocker les utilisateurs.
   - mis en place les routes suivantes : 
     - `POST /users` pour créer un utilisateur.
     - `GET /users` pour lister tous les utilisateurs.
     - `GET /users/:id` pour récupérer un utilisateur spécifique.
     - `PUT /users/:id` pour mettre à jour un utilisateur.
     - `DELETE /users/:id` pour supprimer un utilisateur.

2. **Test de l'API avec Postman** :
   - utilisation **Postman** pour tester toutes les routes de l'API et vous assurer que tout fonctionnait correctement (création, lecture, mise à jour, suppression).

3. **Création d'une interface web (One Page)** :
   - Conception **One Page** en HTML, CSS et JavaScript pour interagir avec l'API.
   - Integration  d'un formulaire pour créer un utilisateur et une section pour afficher, mettre à jour et supprimer des utilisateurs.
   - Le site utilise `fetch` pour envoyer des requêtes HTTP à l'API et met à jour la page en temps réel sans avoir besoin de la recharger.

Cela couvre tout le travail accompli aujourd'hui pour créer et tester une API CRUD, ainsi que pour concevoir une interface utilisateur permettant d'interagir avec cette API.