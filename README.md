# 🧭 Modes de garde collectif à Nantes

Ce projet présente une **visualisation interactive** inspirée de Power BI, permettant d’explorer les données des **crèches et micro-quartiers** de la ville de **Nantes**.

👉 [**Voir la version en ligne**](https://n58s29.github.io/mode-garde-nantes/) *(GitHub Pages)*  
*(si le lien ne fonctionne pas encore, attendre quelques minutes après le dernier commit)*

---

## 📊 Description du projet

L’application affiche :
- Les **indicateurs clés** : nombre de crèches, nombre de places, densité par habitant…
- Une **répartition par type** (municipale, associative, micro-crèche…)
- Un **graphique des places par quartier**
- Un **tableau détaillé** des établissements
- (Optionnel) une **carte interactive Leaflet** pour la localisation

Les données sont extraites des fichiers JSON suivants :
- `DataCreches.json` → liste des crèches, avec adresse, quartier, type et nombre de places  
- `DataQuartier.json` → statistiques de population et superficie par micro-quartier

---

## 🗂️ Structure du projet

mode-garde-nantes/
├── index.html # Interface principale (version locale ou en ligne)
├── DataCreches.json # Données des structures d'accueil
├── DataQuartier.json # Données des quartiers de Nantes
├── geocode_creches.py # Script Python pour géocoder les adresses (optionnel)
└── README.md # Ce fichier
