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
```

### Pour installer les dépendances des projets

```sh
npm install -g yarn pnpm # Installe les gestionnaires de paquets 
pnpm web:install # Installe les dépendances du projet web
pnpm turbobouffe:install # Installe les dépendances du projet turbobouffe
pnpm turbosecu:install # Installe les dépendances du projet turbosecu
```

## Travailler avec les sous-modules

Voici le lien de la documentation officielle de git pour travailler avec les sous-modules : https://git-scm.com/book/fr/v2/Utilitaires-Git-Sous-modules