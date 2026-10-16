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

## Prérequis
MiKTeX (Windows) ou TeX Live (Linux/macOS).  
Compilateur **XeLaTeX** (obligatoire à cause de fontspec).  
Un éditeur : TeXstudio, VS Code + LaTeX Workshop, ou le terminal.  
Sur MiKTeX, les packages manquants (tcolorbox, listings, ...) sont téléchargés automatiquement au premier lancement (connexion Internet requise).

## Compilation
Compilez 2 à 3 fois (le sommaire et les renvois ont besoin de plusieurs passes) :

```bash
cd rapport-tp1-campusmarket
xelatex -interaction=nonstopmode main.tex
xelatex -interaction=nonstopmode main.tex
xelatex -interaction=nonstopmode main.tex
```

Ou avec `latexmk` :

```bash
latexmk -xelatex main.tex
```
