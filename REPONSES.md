# Fichier de réponse aux questions

## Sur <http://localhost:8080/api-docs>, lister les routes qui sont **déjà** implémentées et celles qui ne le sont pas encore

Les routes déjà implémentées sont :


## Donner la commande `httpie` correspondant à la commande `curl` [donnée par la doc](http://localhost:8080/api-docs/#/shortener/post_) pour la route `POST`

**TODO** réponse.

## Donner le _secret_ de la route qui n'est pas documentée sur <http://localhost:8080/api-docs/>.

**TODO** réponse.

## Démarrer l'application en mode _production_ avec `npm run prod` puis en mode _développement_ avec `npm run dev`. Donner les principales différences entre les deux modes

**TODO** réponse.

## Donner le script `npm` qui permet de formatter automatiquement tous les fichiers `.mjs`

**TODO** réponse.

## Les réponses HTTP contiennent une en-tête `X-Powered-By`. Donner la configuration Express à modifier pour qu'elle n'apparaisse plus

**TODO** réponse.

## Créer un nouveau `middleware` (niveau application) qui ajoute un header `X-API-version` avec la version de l'application. Donner le code

**TODO** réponse.

## Trouver un middleware Express qui permet de répondre aux requêtes `favicon.ico` avec `static/logo_univ_16.png`. Donner le code

**TODO** réponse.

## Donner les liens vers la documentation du driver SQLite utilisé dans l'application

**TODO** réponse.

## Indiquer à quels moments la connexion à la base de données est ouverte est quand elle est fermée

**TODO** réponse.

## Avec un navigateur **en mode privé** visiter une première fois <http://localhost:8080/>, puis une deuxième. Ensuite rechargez avec `Ctrl+Shift+R`. Conlure sur la gestion du cache par Express

**TODO** réponse.

## Ouvrir deux instances de l'application, une sur le port 8080 avec `npm run dev` et une autre sur le port 8081 avec la commande `cross-env PORT=8081 NODE_ENV=development npx nodemon server.mjs`. Créer un lien sur la première instance <http://localhost:8080/> et ensuite un autre sur la seconde instante <http://localhost:8081/>. Les liens de l'un doivent être visibles avec l'autre. Expliquer pourquoi

**TODO** réponse.

## Si on enregistre 1000 lien par heure, au bout de combien de temps aura t'on 1% de chance d'avoir une collision, c'est-à-dire deux liens différents avec le même raccourci ? Utiliser pour cela <https://zelark.github.io/nano-id-cc/>

**TODO** réponse.

## Pour chacune des fonctions présentes dans `database/database.mjs`, indiquer quelle fonction l'utilise dans le code du routeur

**TODO** réponse.

## La route `/error` fait planter le serveur au lieu de provoquer une erreur 500 comme indiqué dans la documentation. Trouver quel est le handler qui fait crasher le serveur et expliquer pourquoi

**TODO** réponse.

## Corriger le point précédent pour que le comportement soit conforme à la documentation. Donner le code

**TODO** réponse.
