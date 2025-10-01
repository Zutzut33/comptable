# Comptable Pro

Site vitrine statique qui compare les principaux cabinets comptables en ligne. La page d'accueil affiche un hero condensé, le tableau comparatif et un menu inspiré d'envoi-de-fleurs.fr avec accès rapide aux fiches et au classement des prix. Chaque cabinet dispose d'une fiche individuelle sans colonne latérale mais avec CTA affilié et points clés synthétiques.

## Structure
- `index.html` : page d'accueil avec comparatif, méthodologie, FAQ et contact.
- `les-moins-chers.html` : classement des cabinets par prix décroissant.
- `cabinets/` : fiches détaillées (Indy, Dougs, Keobiz, L-expert-comptable.com, Livli, Clémentine).
- `styles.css` : feuille de style globale responsive inspirée des codes graphiques d'envoi-de-fleurs.fr.
- `assets/` : éléments graphiques.

## Prévisualisation locale
```bash
# depuis le dossier du projet
python -m http.server 8000
```
Puis ouvrez `http://localhost:8000/index.html` dans votre navigateur.

Le site est responsive et pensé pour une expérience mobile et desktop.
