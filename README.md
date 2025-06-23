
# Atelier GitHub Actions : CI avec Node.js

## 🎯 Objectif
Découvrir GitHub Actions à travers un projet Node.js simple. À chaque `push`, on souhaite :
1. Installer les dépendances
2. Vérifier la syntaxe avec ESLint
3. Lancer les tests
4. Générer un build dans `dist/`
5. Uploader l'artefact
6. Afficher un message de succès

## 📦 Instructions

1. Cloner ce dépôt localement
2. Installer les dépendances :
   ```bash
   npm install
   ```
3. Configurer le fichier `.github/workflows/ci.yml`
4. Pousser les modifications sur GitHub pour déclencher le workflow

## 📝 Conseils
- Utiliser `actions/checkout`, `setup-node`, `upload-artifact`
- Vérifiez votre YAML avec [YAML Lint](http://www.yamllint.com/)

Bonne pratique ! 🚀
