# HoyoverseAvertidador — données publiques

Ce dépôt contient uniquement les snapshots JSON générés automatiquement par
les scrapers de **HoyoverseAvertidador**.

## Consommation

Le fichier [`manifest.json`](./manifest.json) décrit chaque snapshot publié :
chemin, taille, nombre d’éléments et empreinte SHA-256.

Les données sont accessibles sur la branche `main`, par exemple :

```text
https://raw.githubusercontent.com/Hugo-Gardes/HoyoverseAvertidador-data/main/data/genshin/events.json
```

## Garanties de publication

- tous les fichiers attendus doivent être présents et être du JSON valide ;
- une collection vide n’écrase jamais le dernier snapshot valide ;
- aucun fichier applicatif, secret ou identifiant d’administration n’est publié ;
- une exécution sans changement ne crée pas de commit inutile.

Les fichiers de ce dépôt sont générés. Toute correction durable doit être faite
dans le scraper du dépôt privé, puis republiée par l’automatisation.
