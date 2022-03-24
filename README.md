# SUTOM

Cette version du sutom est une instance personelle du sutome originel, un petit jeu de lettres en ligne (et en français) basé sur Wordle. Le jeu se trouve à l'adresse https://sutom.nocle.fr

## Développement

### Avec npm

Pour pouvoir travailler en local, il faut commencer par installer ce qu'il faut à node :

```sh
npm i
```

Puis, on lance le serveur :

```sh
npm run start:dev
```

### Accès au site

Une fois démarré, le site sera dispo sur http://localhost:4000 et le typescript va se recompiler tout seul à chaque modification de fichier.

## Déployer en production

### Avec npm

Pour déployer en production, on installe les dépendances :

```sh
npm install --production
```

Puis on lance le serveur :

```sh
npm start
```
