# Atelier – Identifier et Valoriser ses Compétences

Ce dossier est prêt à être **poussé sur GitHub** et publié via **GitHub Pages**.

## Contenu
- `index.html` — votre atelier (copie de `atelier_competences.html`) afin qu'il s'ouvre par défaut sur GitHub Pages.
- `atelier_competences.html` — le fichier original.
- `images/` — placez **toutes les images** référencées par la page ici (voir `images/README.txt`).
- `.nojekyll` — désactive le traitement Jekyll côté GitHub Pages (optionnel mais recommandé).

## Étapes rapides (terminal)
```bash
# 1) Créez un dépôt vide sur GitHub (web) — notez l'URL comme https://github.com/VOTRE_PSEUDO/atelier-competences-site.git
# 2) En local, placez-vous dans ce dossier :
cd atelier-competences-site

# 3) Initialisez Git et validez
git init
git add .
git commit -m "Publication initiale de l'atelier"

# 4) Liez à GitHub et poussez
git branch -M main
git remote add origin https://github.com/VOTRE_PSEUDO/atelier-competences-site.git
git push -u origin main
```

## Activer GitHub Pages
1. Ouvrez **Settings → Pages** dans votre dépôt GitHub.
2. **Source** : choisissez la branche `main` et le dossier `/ (root)`.
3. Enregistrez. L'URL de votre site sera affichée (ex: `https://votre_pseudo.github.io/atelier-competences-site/`).

## Images manquantes ?
Le fichier `images/README.txt` liste les images attendues (détectées dans le HTML). Copiez ces fichiers dans `images/` avant de pousser.

---

💡 Astuce : si vous préférez renommer le dépôt (par ex. `atelier-competences`), pensez à mettre à jour l'URL du `remote` avant le `push`.
