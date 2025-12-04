# PSET - Project SETter

[![Static Badge](https://img.shields.io/badge/Licence-MIT-blue?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLXphei0tPgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgaGVpZ2h0PSIxNjYiIHdpZHRoPSIzMjEiPgo8ZyBzdHJva2Utd2lkdGg9IjM1IiBzdHJva2U9IiNBMzFGMzQiPgo8cGF0aCBkPSJtMTcuNSwwdjE2Nm01Ny0xNjZ2MTEzbTU3LTExM3YxNjZtNTctMTY2djMzbTU4LDIwdjExMyIvPgo8cGF0aCBkPSJtMTg4LjUsNTN2MTEzIiBzdHJva2U9IiM4QThCOEMiLz4KPHBhdGggZD0ibTIyOSwxNi41aDkyIiBzdHJva2Utd2lkdGg9IjMzIi8+CjwvZz4KPC9zdmc+Cg==)](https://choosealicense.com/licenses/mit/)
[![Static Badge](https://img.shields.io/badge/-Bash-darkgreen?logo=gnubash)](https://www.gnu.org/software/bash/bash.html)

## Sommaire
1. Sommaire
2. Présentation
3. Installation
4. Ligne de conduite

   
>[!Note]
>PSET est toujours en cours de développement; il n'a été testé que localement sur un Mac. Comportement inattendu à prévoir lors du test sur une autre architecture

## Présentation

> Commande permettant d'utiliser rapidement un template de projet

**PSET** est un outil en ligne de commande proposant l’initialisation rapide de projets.  
Il permet de créer, en une seule commande, une structure de projet complète dans le répertoire courant. Par exemple, pour un projet Python, l’outil génère un dossier contenant tous les éléments essentiels : environnement virtuel, dépôt Git initialisé, fichier .gitignore et requirements.txt...  
Actuellement, l’application ne prend en charge que l’initialisation de projets Python. Une extension modulaire pour supporter d’autres langages est en cours de développement.

## Installation

## Installation
##### Téléchargement
###### Par SSH
```
git clone git@github.com:cos-imo/pset.git
```
###### Par HTTPS
```
git clone https://github.com/cos-imo/pset.git
```

##### Installation
>[!Warning]
>PSET repose sur [gum](https://github.com/charmbracelet/gum). Il est donc nécessaire d'installer ce dernier préalablement à toute installation/utilisation de PSET.

Il est conseillé de se référer à la documentation de Gum pour installation, celui-ci devrait cependant pouvoir s'installer sans autre forme de procès à l'aide du gestionnaire de paquets par défaut du système d'exploitation (`apt install gum` pour les distributions *Debian*, `pacman -S gum` pour *Arch*, `brew install gum` pour *Mac*)  
Une fois l'installation effectuée, pset peut être lancé depuis la ligne de commande:  
```
pset [OPTIONS]
```



## Ligne de conduite
Bien que la consistance doive être privilégiée, le code se devra de respecter un maximum le [styleguide de ysap](https://style.ysap.sh)
