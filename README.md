<!-- badges: start -->
![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
<!-- badges: end -->



# Fichiers & dossiers utiles pour une étude clinique simple.


L'idée est de copier (ou cloner) ce dossier & on est prêt à travailler.

Les modèles Quarto ont une page de garde générée par [Quarto Title Page](https://nmfs-opensci.github.io/quarto_titlepages/03-titlepage-themes.html). Ils comportent une page `generique.tex` avec les informations légales (en cours d'écriture) & les noms des divers intervenants. Un glossaire est généré comportant une page pour les acronymes & une page de définitions. La bibliographie est générée avec le format `jama.csl`, les références sont dans le fichier `stat.bib`.

## Dossiers

Deux dossiers sont créés dont le nom suffit à leur description :

**Docs** Pour y mettre toute la doc du projet.

**datas** pour les datas avec un sous dossier `réserve` qui contient le fichier brut fournit par l'investigateur qu'on ne modifie **jamais**.

## Fichiers

**\_quarto.xml** est le fichier de configuration de Quarto utilisé pour toutes les pages. Il comporte aussi les info de mise en page $\LaTeX$ (police, glossaire, couleur etc.). Vu que ce fichier est sensé me servir en priorité le logo & le code couleur sont ceux de mon hôpital mais c’est facile à modifier. 

**base.qmd** Un fichier Quarto quasi vide pour commencer un nouveau document qui me sert principalement pour des essais. 

**generique2.tex** Le modèle de page pour les noms des intervenants, les infos légales etc.

**jama.csl** Le style de la bibliographie.

**novo_usrc.png** Le logo de mon établissement.


**plan_analyse.qmd** Un squelette (très vide) pour le PAS (Plan d'Analyse Statistique).

**rapport_pdf.qmd** Un squelette pour un rapport d'analyse statistique d'une étude clinique simple.

**stat.bib** La bibliographie (format Bib$\LaTeX$)
