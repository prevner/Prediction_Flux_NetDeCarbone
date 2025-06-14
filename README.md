# 🌱 Prédiction du CO₂ échangé par les écosystèmes (NEE) avec LSTM

## 🎯 Objectif

Ce projet utilise un modèle de Deep Learning (LSTM) pour prédire le **Net Ecosystem Exchange (NEE_VUT_REF)**, un indicateur clé des flux de CO₂ dans les écosystèmes terrestres, à partir de conditions météorologiques passées issues du jeu de données [FLUXNET2015](https://fluxnet.org/data/fluxnet2015-dataset/).

[![Ouvrir dans Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prevner/Prediction_Flux_NetDeCarbone/blob/main/Prediction_Flux_NetDeCarbone.ipynb)


---

## 🌍 Contexte environnemental

Le **NEE (Net Ecosystem Exchange)** permet de mesurer si un écosystème **absorbe** (puits de carbone) ou **émet** (source de carbone) du CO₂.

👉 En modélisant cette variable, ce projet vise à :
- Comprendre l’influence du climat (température, humidité, rayonnement…) sur le cycle du carbone.
- Contribuer à la modélisation des effets du changement climatique.
- Prédire les dynamiques de carbone dans divers biomes (forêts, prairies…).

---

## 🔧 Pipeline du projet

Le modèle suit les étapes suivantes :

1. **Chargement des données** FLUXNET2015 journalières (température, humidité, radiations…).
2. **Prétraitement** et création de séquences temporelles de 30 jours.
3. **Entraînement** d’un modèle LSTM pour prédire le `NEE_VUT_REF` du jour suivant.
4. **Évaluation** des performances avec :
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Square Error)
   - R² Score
5. **Visualisation** des prédictions vs valeurs réelles.

---

## 📁 Données utilisées

- 📊 Source : [FLUXNET2015 Dataset](https://fluxnet.org/data/fluxnet2015-dataset/)
- 📍 Exemple de site : US-Ha1 (Harvard Forest)

---

## 🚀 Exécution rapide dans Google Colab

Cliquez sur le badge ci-dessous pour lancer le notebook dans un nouvel onglet :

[![Ouvrir dans Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prevner/Prediction_Flux_NetDeCarbone/blob/main/Prediction_Flux_NetDeCarbone.ipynb)


---

## 📌 À venir

- Intégration multi-sites FLUXNET.
- Optimisation du modèle (hyperparamètres).
- Comparaison avec d'autres architectures (GRU, Transformer…).

---

## 👤 Auteur

- Dixy Prevner M'POUTOU
- [GitHub](https://github.com/prevner)

