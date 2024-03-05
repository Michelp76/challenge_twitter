Tiré des articles : 
https://dev.to/ipscodingchallenge/part-1-creating-a-twitter-clone-with-graphql-knex-typescript-and-react-32i1

- Créer un fichier ".env.development" à la racine :
```
PORT=5432
DB_HOST = 'localhost'
DB_NAME = 'challenge_twitter'
DB_USER = 'postgres'
DB_PASSWORD = 'XXXXX'
JWT_SECRET = 'X?Zj>T6vNDr-oyLST>-?qXn<Ul@K>VY-3X0w,SL0hs$}Z{*cUc;F|/J>T)Jn8rzA'
DEBUG = 'true'
```
- Créer une base de données "challenge_twitter" avec pgAdmin
  
- Lancer dans un terminal :

```
knex migrate:latest
knex seed:run
```
 
- Enfin lancer :
```
yarn dev
```

- Se connecter sur http://localhost:4000/

- Optionnel (mais cool) : lancer le front ici : https://github.com/Michelp76/challenge_twitter_front
