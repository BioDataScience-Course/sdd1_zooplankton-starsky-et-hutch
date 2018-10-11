# Analyse d'image du zooplancton provenant de Tuléar (Madagascar)
## Engels Guyliann & Philippe Grosjean

## Objectif

- Organiser un projet en plusieurs sous-dossiers afin de décrire les données du jeu de données `zooplankton` 
- Créer un rapport d'analyse en R Markdown organisé en plusieurs sections afin de rapporter le fruit de vos recherches sur ces données.

## Partie 1

- Explorez les données provenant du jeu de données et proposez **au moins** 15 graphiques variés sur les données

- Rapportez le fruit de vos recherches dans un document structuré.

Pour importer ces données vous devez employer les instructions suivantes

```
# Importation du jeu de données
zooplankton <- read( file = "zooplankton", package = "data.io", lang = "fr")
```

## Partie 2

Après avoir étudié le jeu de données dans son ensemble, étudiez plus en précision les copépodes 

- Proposez  **au moins** 10 graphiques afin de les comparer. 

- Rapportez le fruit de vos recherches dans un document structuré.

Pour filter les données, vous devez employer les instructions suivantes
 
```
# Réduction du jeu de données zooplankton
zooplankton_sub <- filter(zooplankton, class %in% c("Poecilostomatoid", "Calanoid", "Cyclopoid", "Harpacticoid"))
```

