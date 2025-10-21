# 📊 Suivi de la Population Mondiale

Dashboard R Flexdashboard pour analyser les tendances démographiques mondiales.

## 🎯 Fonctionnalités

- **Indicateurs démographiques** : Population, croissance, espérance de vie, âge médian
- **Analyses temporelles** : Natalité, mortalité, fertilité
- **Cartes interactives** : Flux migratoires mondiaux
- **Filtres dynamiques** : Par année, région et pays
- **Export de données** : Téléchargement CSV

## 🚀 Installation

```r
# Installer les packages
packages <- c("flexdashboard", "shiny", "dplyr", "plotly", "highcharter", 
              "DT", "readxl", "leaflet", "rnaturalearth", "sf", "countrycode")
install.packages(packages)
```

## 💻 Utilisation

1. Cloner le repo
2. Placer le fichier `data.xlsx` avec une feuille "Reel"
3. Mettre à jour le chemin dans le code
4. Ouvrir le `.Rmd` dans RStudio et cliquer sur "Knit"

## 📊 Format des données

Le fichier Excel doit contenir :
- Year, Type, Region
- Total Population, Male/Female Population
- Life Expectancy, Fertility Rate
- Migration data etc....

## 👨‍💻 Auteur

**Klaus KUEKOU**
***Statistical Analyst***
***www.linkedin.com/in/klaus-kuekou-217bba173**
***kfkwconcept@gmail.com**
***+33 758 716 650***
