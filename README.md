# Portfolio — Malick (BTS SIO, option SISR)

Portfolio statique en HTML/CSS/JS pur, prêt à être hébergé sur GitHub Pages.

## Structure

```
index.html          → toute la page (sections : accueil, qui suis-je, objectif,
                       compétences, langues, projets, formation, contact)
css/style.css        → styles
js/script.js         → menu mobile, année du footer, bouton retour en haut
assets/img/          → mets ta photo ici (ex: photo.jpg)
assets/cv/           → mets ton CV en PDF ici (ex: cv-malick.pdf)
```

## À compléter

Cherche les commentaires `<!-- TODO -->` dans `index.html` :
- Photo (section "Qui suis-je") → `assets/img/photo.jpg`, puis remplace le `<div class="photo-placeholder">` par `<img src="assets/img/photo.jpg" alt="Malick">`
- CV en PDF → `assets/cv/cv-malick.pdf` (le bouton "Télécharger mon CV" pointe déjà vers ce chemin)
- Tes infos perso (âge, établissement, ville, disponibilité)
- Tes objectifs pro (court/moyen/long terme)
- Niveaux de compétences et de langues (barres de progression, valeurs en %)
- Tes 3 projets (titre, description, technos, lien GitHub)
- Ta formation (dates, établissements)
- Tes liens de contact (email, LinkedIn, GitHub)

## Aperçu en local

Ouvre simplement `index.html` dans ton navigateur, ou lance un petit serveur local :

```bash
python -m http.server 8000
```

puis va sur `http://localhost:8000`.

## Déploiement sur GitHub Pages

1. Crée un dépôt GitHub (ex: `portfolio`).
2. Pousse ce projet dedans :
   ```bash
   git init
   git add .
   git commit -m "Premier commit du portfolio"
   git branch -M main
   git remote add origin https://github.com/TON-PSEUDO/portfolio.git
   git push -u origin main
   ```
3. Sur GitHub : `Settings` → `Pages` → `Source` → sélectionne la branche `main` et le dossier `/ (root)`.
4. Ton site sera disponible à `https://TON-PSEUDO.github.io/portfolio/` après quelques minutes.
