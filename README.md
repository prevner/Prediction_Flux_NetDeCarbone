# 🎯 Objectif du projet

Utiliser un modèle de deep learning (ici un LSTM) pour prédire le comportement du CO₂ net échangé par les écosystèmes terrestres (le NEE_VUT_REF) à partir de conditions météorologiques passées avec les données du
[dataset  FLUXNET2015](https://fluxnet.org/data/fluxnet2015-dataset/)
# Contexte environnemental :
Le NEE (Net Ecosystem Exchange) est un indicateur essentiel pour évaluer si un écosystème absorbe ou émet du CO₂.

En le modélisant, ce projet aide à :

* Comprendre l’impact du climat (température, humidité, rayonnement, etc.) sur le cycle du carbone.

* Contribuer à la modélisation des changements climatiques.

* Prédire la dynamique du carbone dans différents biomes (forêt, prairie, etc.).

# 🔍 Ce que fait concrètement ton pipeline :
Prend les données journalières FLUXNET2015 (température, humidité, rayonnement, etc.).

* Crée des séquences temporelles de 30 jours d’entrée.

* Utilise un modèle LSTM pour prédire le NEE_VUT_REF du jour suivant.

* Évalue les performances (MAE, RMSE, R²).

* Visualise les prédictions vs la vérité.
