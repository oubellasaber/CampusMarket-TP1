# CampusMarket-TP1

TP1 - Lancement, analyse et planification du projet CampusMarket (ENSIASD - Génie Logiciel)

## Contenu du dépôt

- apport-tp1-campusmarket/main.tex : Fichier source LaTeX du rapport
- apport-tp1-campusmarket/sections/ : Chapitres du rapport (01 à 10)
- apport-tp1-campusmarket/includes/ : Fichiers inclus (variables, packages, config)
- apport-tp1-campusmarket/images/ : Logos et images utilisés
- apport-tp1-campusmarket/CampusMarket_TP1.pdf : Rapport final compilé (à déposer)

## Pour configurer ce projet sur ton PC

Clone ce dépôt :

`ash
git clone https://github.com/oubellasaber/CampusMarket-TP1.git
cd CampusMarket-TP1
`

## Modifier les informations de l'équipe

Ouvre le fichier apport-tp1-campusmarket/includes/variables.tex et modifie les infos selon ton équipe (noms, prénoms, rôles...).

## Compiler le rapport

Il faut compiler avec **XeLaTeX** (2 fois pour le sommaire/tableaux).

`ash
cd rapport-tp1-campusmarket
xelatex main.tex
xelatex main.tex
`

### Prérequis

- [MiKTeX](https://miktex.org/) ou [TeX Live](https://tug.org/texlive/)
- Paquets requis : ontspec, polyglossia, pgfgantt, 	colorbox, 	ikz, ooktabs, longtable, 	abularx, pdflscape

Bonne chance pour ton TP !
