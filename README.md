# POKEROCK

## Pitch
Dossier officiel de cailloux de compagnie : vous signez, vous adoptez, vous polissez. Ton solennel, contenu absurde, service notarie des pierres domestiques.

## Comment lancer / editer
1. Installer GB Studio (>=3.x).
2. Ouvrir le projet `POKEROCK.gbsproj` dans GB Studio (nom du fichier accentue selon l OS, voir racine du repo).
3. Lancer "Play" pour tester directement depuis l editeur.

## Exporter en Web / ROM
- Web: Menu `Build` > `Build Web`. Par defaut GB Studio exporte dans `build/web` (index.html compris). Publier ce dossier ou recopier son contenu dans `docs/` si vous voulez GitHub Pages.
- ROM: Menu `Build` > `Build ROM`. GB Studio genere `build/rom/game.gb` (ou `.gbc`) et les assets associes.
- Nettoyage: les exports sont ignores par git via `.gitignore` pour garder le repo propre.

## Structure des dossiers
- `project/` : scenes, scripts, variables, ressources GB Studio.
- `assets/`, `plugins/`, `pokerock/`: elements fournis par GB Studio/jeu.
- `docs/` : vide par defaut, peut accueillir l export Web pour GitHub Pages.

## Roadmap courte
- Vertical slice jouable: titre -> Maitre Galet -> duel mineral -> retour map.
- Systeme cailloux: variables centralisees pour id/type/niveau/HP/XP/starter.
- Web: depot du build dans `build/web` puis eventuellement `docs/` pour Pages ou autre hebergement.
