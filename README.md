# MedicalCostPrediction

Ce projet consiste à prédire les coûts médicaux pour les individus en fonction de diverses caractéristiques comme l'âge, le sexe, le nombre de dépendants, le tabagisme, l'index de masse corporelle (IMC), etc. L'objectif est de créer un modèle capable de prédire les coûts médicaux pour les utilisateurs à partir des informations fournies.

## Table des matières

1. [Contexte du projet](#contexte-du-projet)
2. [Technologies utilisées](#technologies-utilisées)
3. [Données](#données)
4. [Installation](#installation)

## Contexte du projet

L'augmentation des coûts des soins de santé est un défi majeur à l'échelle mondiale. La prédiction des coûts médicaux peut aider les compagnies d'assurance et les établissements de santé à mieux gérer les risques et à fournir des services plus adaptés aux besoins des patients. Ce projet se concentre sur la construction de modèles de prédiction des coûts médicaux en utilisant des techniques d'apprentissage automatique.

## Technologies utilisées

- **Python** : Langage principal utilisé pour le développement du modèle.
- **pandas** : Manipulation et analyse des données.
- **numpy** : Calcul scientifique et manipulation des tableaux.
- **scikit-learn** : Bibliothèque pour l'apprentissage automatique.
- **matplotlib** et **seaborn** : Visualisation des données et des résultats.
- **Jupyter Notebooks** : Environnement interactif pour le développement et l'analyse.

## Données

Les données utilisées dans ce projet proviennent de [Kaggle](https://www.kaggle.com/mirichoi0218/insurance), qui contient un ensemble d'informations sur les assurances médicales des individus, incluant :

- **Âge** : L'âge de l'individu.
- **Sexe** : Sexe de l'individu (male/female).
- **Nombre de dépendants** : Le nombre de personnes à charge.
- **Tabagisme** : Si l'individu fume ou non (yes/no).
- **Indice de Masse Corporelle (IMC)** : Un indice calculé pour déterminer si une personne est en surpoids, en sous-poids ou dans une fourchette de poids saine.
- **Région** : Région géographique (nord-ouest, nord-est, sud-est, sud-ouest).
- **Coût médical** : Le coût médical que l'individu a payé (la cible du modèle).

### Description des colonnes
| Colonne             | Description                             |
|---------------------|-----------------------------------------|
| age                 | L'âge de l'individu (int)               |
| sex                 | Sexe de l'individu (male/female)        |
| bmi                 | Indice de Masse Corporelle (float)      |
| children            | Nombre de dépendants (int)              |
| smoker              | Statut de tabagisme (yes/no)            |
| region              | Région géographique (categorical)       |
| charges             | Coût médical (cible, float)             |

## Installation

### Prérequis

Avant de commencer, assurez-vous d'avoir installé Python et pip. Vous pouvez télécharger Python ici : [Python Downloads](https://www.python.org/downloads/).

### Installation via pip

Clonez ce dépôt, puis installez les dépendances :

```bash
git clone https://github.com/DahliaNoir71/MedicalCostPrediction.git
cd MedicalCostPrediction
pip install -r requirements.txt
