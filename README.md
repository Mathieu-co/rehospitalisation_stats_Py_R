# Analyse de la réhospitalisation de 1 à 12 mois chez les patients IC - Projet Satelia

Ce projet vise à analyser les caractéristiques des patients insuffisants cardiaques suivis en télésurveillance via Satelia Cardio, et à évaluer l’impact de cette télésurveillance sur les réhospitalisations dans le mois suivant la sortie d’hospitalisation.

## 🎯 Objectifs

- Décrire la population de patients en post-hospitalisation
- Comparer les caractéristiques des patients réhospitalisés sous différentes temporalités avec ceux qui ne l'ont pas été
- Identifier les facteurs potentiels associés à une réhospitalisation précoce

## 📁 Contenu du projet

projet-rehospitalisation/
├── notebooks/
│ └── analyse_rehospitalisation.ipynb # Notebook Jupyter (code R)
├── data/ # Fichiers .xlsx (non versionnés)
├── output/ # Fichiers de résultats (Excel, Graphiques)
├── README.md # Présentation du projet (ce fichier)
├── .gitignore # Exclusion des fichiers sensibles


## 🧪 Technologies utilisées

- R (via Jupyter Notebook avec IRkernel)
- Packages : `dplyr`, `ggplot2`, `readxl`, `tableone`, `openxlsx`, `janitor`
- Python (Jupyter Notebook)
- Packages : 'scipy', 'pandas', 'statsmodels', 'sklearn', 'matplotlib'

## 🔐 Confidentialité

Les données patients (fichiers Excel) sont **exclues du dépôt GitHub** pour respecter la confidentialité (voir `.gitignore`).

## 🚀 Lancer l’analyse

1. Placer le fichier Excel anonymisé dans le dossier `data/`
2. Ouvrir le notebook Jupyter `analyse_rehospitalisation.ipynb`
3. Exécuter les cellules pour générer :
   - Le tableau descriptif (Table 1)
   - Les graphiques comparatifs
   - L’export Excel dans `output/`


