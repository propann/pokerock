Dossier `docs/` pour un depot Web statique (GitHub Pages par exemple).
- Option A : publier directement le dossier `build/web` produit par GB Studio (index.html inclus) sur l hebergement de votre choix.
- Option B : copier le contenu de `build/web` dans `docs/` pour activer GitHub Pages sur le repo (branche main).

Rappel : les builds sont ignores par git (.gitignore), seul ce dossier vide est versionne pour preparer l hebergement.
