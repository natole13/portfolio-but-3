# Portfolio BUT3 — Anatole Lodier

Site statique. **Chaque fichier HTML est autonome** (CSS et JS intégrés dedans). Aucun dossier `assets`, aucun `.nojekyll` nécessaire.

## Mise en ligne (GitHub Pages)
1. Mets ces 6 fichiers à la **racine** du dépôt : `index.html`, `but1.html`, `but2.html`, `but3.html`, `bilan.html`, `contact.html`.
2. Settings → Pages → Source : Deploy from a branch → `main` / `(root)` → Save.
3. URL : https://natole13.github.io/portfolio-but-3/

## Pages
- index.html — Accueil
- but1.html / but2.html / but3.html — les trois années
- bilan.html — Montée en compétences sur 3 ans + projet
- contact.html — Contact + CV

## Pour modifier
Les pages sont générées depuis `content_but*.py` + `build.py` (`python3 build.py`). Les traces BUT3 affichent des noms de fichiers « à déposer » : ajoute tes PDF à la racine avec ces noms pour les activer.
