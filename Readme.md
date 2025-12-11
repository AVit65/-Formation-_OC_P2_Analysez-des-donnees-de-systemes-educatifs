📊 **Projet**

Ce projet consiste à réaliser une analyse exploratoire d’un jeu de données sur l’éducation fourni par la Banque mondiale (EdStats All Indicator Query). L’objectif est d’évaluer la qualité et la pertinence de ces données et de déterminer si la start-up Academy proposant des contenus de formation en ligne pour un public lycéen et universitaire a intérêt à s'étendre à l'international.

🎓 **Compétences évaluées**
- Manipuler des données avec des librairies Python spécialisées
- Mettre en place un environnement Python
- Utiliser un notebook Jupyter pour faciliter la rédaction du code et la collaboration
- Effectuer une analyse univariée et des représentations graphiques avec une librairie
- Maîtriser les opérations fondamentales du langage Python pour la Data Science

📂 **Architecture du repository**

*Note*: les données ne sont pas inclues et doivent être téléchargés via le lien ci-dessous
```
OC_P2_Analysez-des-donnees-de-systemes-educatifs/
│
├── Data/
│   ├── EdStatsCountry.csv           # Informations générales sur les pays (codes, régions, niveau de revenu, etc.)
│   ├── EdStatsCountry-Series.csv    # Mapping entre les pays et les indicateurs éducatifs disponibles
│   ├── EdStatsData.csv              # Données principales : valeurs des indicateurs éducatifs par pays et par année
│   ├── EdStatsFootNote.csv          # Notes méthodologiques et commentaires associés à certaines données
│   ├── EdStatsSeries.csv            # Description des indicateurs (définition, source, unité de mesure)
│
├── Notebook/                         # Notebook d’analyse                            
├── Ouput/                                    
│   ├── Boxplot/                      # Distribution des indicateurs par régions 
│   ├── Classement/                   # Tableau contenant le classement des pays
│   ├── Corrélation/                  # Heatmap illustrant les corrélation entre indicateurs 
│   ├── Tab_evolution/                # Tableau contenant l'évlution des indicateurs entre 2000 et 2015 par régions
│   ├── Taux_valeurs_manquantes/      # Tableau contenant les taux de valeurs manquantes par indicateur 
├── Soutenance/                       # Présentation en pdf
├── README.md                         # Documentation générale du projet
├── Requirements                      # Liste des dépendances nécessaires

```

🗄️ **Données**

Les tables de données brutes listées ci-dessous et utilisées dans le notebook d’analyse peuvent être téléchargées sur le [site de la Banque mondiale](https://datacatalog.worldbank.org/dataset/education-statistics):
- EdStatsCountry
- EdStatsCountry-Series
- EdStatsData
- EdStatsFootNote
- EdStatsSeries

