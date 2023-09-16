# UA Monorepo

Monorepo reprenant tous les projets de l'UTT Arena.

## Quick start

```sh
# Clone le dépôt. On te recommande de cloner le dépôt en ssh
# (vérifie que tu as une clé ssh et qu'elle est liée à ton compte github)
git clone --recurse-submodules git@github.com:ungdev/UA

# OU

git clone git@github.com:ungdev/UA
git submodule init
git submodule update

# Pour installer les dépendances des projets il faut ensuite parcourir les sous-modules et installer leurs dépendances comme expliqué dans la doc ou dans le readme de chaque projet.
```

## Travailler avec les sous-modules

Voici le lien de la documentation officielle de git pour travailler avec les sous-modules : https://git-scm.com/book/fr/v2/Utilitaires-Git-Sous-modules