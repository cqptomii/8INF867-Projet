# Sujet TP 8INF867 - Fondamentaux de l'apprentissage automatique


## Idée 1: 

Prédire le temps d'un coureur sur une course à partir des caractéristiques de la course (distance, dénivelé), du coureur (âge, genre) et de son historique de résultats.

Objectifs détaillé:

à partir des données suivantes:

- Caractéristiques de la course et du coureur
- Historique des résultats du coureur
- Historique des résultats de la courses dans le passée (Optionel)

Prédire son temps moyen sur cette même course.

### Jeux de données utilisable

Dataset containing races from 2020 to 2029
- "https://zenodo.org/records/4671018" / "https://github.com/amurgo/TrailRunningRaces"

The Big dataset of ultra marathon running
- https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running

## Idée 2:

Prédire l’efficacité énergétique d’un coureur à partir de sa pose 3D, quelles déformations de la foulée annoncent sa dégradation, et que gagne-t-on par rapport à une montre seule ?


### Données
- Capture vidéo de la foulée d'un coureur
  - Extraction de la pose à l'aide de SAM3 Body
- Extraction des données à l'aide de capteur (Montre connecté)
  - Nombre de pas par minutes
  - Temps d'impact au sol
  - Fréquence cardiaque
  - Watt dépensé
  - Calories dépensé
 



