# Comptable Pro

Site vitrine statique qui compare les principaux cabinets comptables en ligne. La page d'accueil propose un hero introductif léger et un tableau comparatif directement accessible. Chaque cabinet dispose d'une fiche individuelle avec une colonne B dédiée aux appels à l'action.

## Structure
- `index.html` : page d'accueil avec comparatif, méthodologie, FAQ et contact.
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
