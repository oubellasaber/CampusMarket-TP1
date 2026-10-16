# CampusMarket-TP1
TP1 - Lancement, analyse et planification du projet CampusMarket (ENSIASD - Génie Logiciel)

## Contenu
- `rapport-tp1-campusmarket/main.tex` : fichier source LaTeX
- `rapport-tp1-campusmarket/sections/` : chapitres
- `rapport-tp1-campusmarket/includes/` : variables/packages/config
- `rapport-tp1-campusmarket/CampusMarket_TP1.pdf` : rapport final
- `rapport-tp1-campusmarket/images/` : ressources

## Configuration à modifier
Éditer `rapport-tp1-campusmarket/includes/variables.tex` selon ton équipe.

## Compilation
Compiler avec XeLaTeX (2 fois) :
```bash
cd rapport-tp1-campusmarket
xelatex main.tex
xelatex main.tex
```

Prérequis : MiKTeX/TeXLive avec fontspec, polyglossia, pgfgantt, tcolorbox, tikz, etc.
