# Formation R pour les débutants

Bienvenue dans la formation sur le langage **R** ! Cette formation a pour objectif d'apprendre les bases de **R** et de permettre aux étudiants de développer des compétences solides pour l'analyse de données et la visualisation avec R.

## Description

Cette formation couvre les fondamentaux du langage R, y compris :

-   Les bases de R : variables, types de données, opérateurs, et structures de données.
-   Manipulation des données avec **dplyr**.
-   Visualisation des données avec **ggplot2**.
-   Statistiques descriptives.
-   Création de graphiques et d'analyses statistiques.
-   Gestion des données manquantes (NA).
-   Introduction à l'utilisation des packages R pour des analyses avancées.

## Objectifs de la formation

À la fin de cette formation, les participants seront capables de :

-   Utiliser R pour importer, nettoyer et transformer des données.
-   Appliquer des fonctions de base pour explorer des ensembles de données.
-   Créer des visualisations de données simples à l'aide de **ggplot2**.
-   Calculer des statistiques descriptives et interpréter les résultats.
-   Travailler efficacement avec des données manquantes (NA).
-   Appliquer des techniques de manipulation des données avec **dplyr**.

## Prérequis

-   Aucun prérequis n'est nécessaire pour cette formation, mais une connaissance de base en statistiques et en programmation est un plus.
-   Avoir **R** et **RStudio** installés sur votre machine.
-   Une connexion Internet est recommandée pour accéder aux ressources en ligne et aux packages.

## Installation

### Étape 1 : Installer R

Si vous n'avez pas encore installé R, vous pouvez télécharger et installer la dernière version de R depuis [le site officiel de CRAN](https://cran.r-project.org/).

### Étape 2 : Installer RStudio

Pour une meilleure expérience de programmation, nous vous recommandons d'utiliser **RStudio**, qui est un environnement de développement intégré (IDE) pour R. Téléchargez-le depuis [le site officiel de RStudio](https://www.rstudio.com/products/rstudio/download/).

### Étape 3 : Installation des packages nécessaires

Voici les packages utilisés dans cette formation :

``` r
install.packages(c("ggplot2", "dplyr", "tidyr", "data.table", "readr"))
```

### Étape 4 : Charger les packages

Dans votre session RStudio, utilisez `library()` pour charger les packages nécessaires.

``` r
library(ggplot2)
library(dplyr)
library(tidyr)
library(data.table)
library(readr)
```

## Contenu de la formation

1.  **Introduction à R et RStudio**

    -   Introduction au langage R
    -   Utilisation de RStudio : interfaces et fonctionnalités principales

2.  **Types de données et structures**

    -   Variables et types de données de base (numériques, logiques, caractères)
    -   Structures de données : vecteurs, matrices, listes, data frames, tibbles

3.  **Manipulation des données avec dplyr**

    -   Sélectionner, filtrer, trier les données
    -   Créer de nouvelles colonnes et modifier des colonnes existantes
    -   Groupement et agrégation de données

4.  **Visualisation des données avec ggplot2**

    -   Créer des graphiques simples : histogrammes, boîtes à moustaches, diagrammes de dispersion
    -   Personnaliser les graphiques : titres, étiquettes, couleurs

5.  **Statistiques descriptives**

    -   Calcul des mesures de tendance centrale (moyenne, médiane, mode)
    -   Calcul des mesures de dispersion (écart-type, variance, quantiles)

6.  **Gestion des données manquantes**

    -   Identifier et traiter les valeurs manquantes (NA)
    -   Remplacer ou supprimer des NA

## Télécharger et cloner le dépôt

Pour suivre cette formation, vous devez cloner le dépôt Git sur votre machine locale. Assurez-vous d'avoir **Git** installé sur votre ordinateur avant de procéder. Si vous n'avez pas encore Git, vous pouvez le télécharger ici : [Git - Download](https://git-scm.com/).

### Cloner le dépôt avec Git

1.  **Ouvrez votre terminal ou invite de commandes**.
2.  **Clonez le dépôt en exécutant la commande suivante** :

``` bash
git clone https://github.com/Badjodibe/Learn-R.git
cd Learn-R
ls
```
3. ** Si vous avez déjà le code et vous voulez le mettre à jour **
   
``` bash
git pull
```
## Support

Si vous avez des questions ou des problèmes, vous pouvez ouvrir une **issue** sur GitHub ou me contacter par email à [[badjodibe\@gmail.com](mailto:badjodibe@gmail.com){.email}].

------------------------------------------------------------------------

### Conclusion

j'espére que cette formation vous aidera à maîtriser les bases du langage R et à l'appliquer dans des analyses de données réelles. Bonne chance et amusez-vous bien dans votre apprentissage !

------------------------------------------------------------------------
