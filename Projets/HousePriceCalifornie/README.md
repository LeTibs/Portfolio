# 🏠 House Price - Prédiction des prix immobiliers en Californie

🔎 **Objectif :** Prédire le prix des maisons en Californie à partir de caractéristiques comme la surface, le nombre de chambres, la localisation, etc.

📊 **Données :**
- 📥 Source : [Kaggle - California Housing Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
- 🏡 Features : Nombre de chambres, population, latitude, longitude, etc.
- 🎯 Variable cible : `median_house_value` (Prix médian des maisons)

🛠️ **Technos utilisées :**
- Python, Pandas, Scikit-Learn
- Matplotlib, Seaborn pour la visualisation
- Régression linéaire, Random Forest, XGBoost

📈 **Résultats obtenus :**
- 🔍 Score RMSE : **O,84**
- 🏆 Meilleur modèle : **XGBRegressor**

---

## 🔄 Workflow du projet
1. **Chargement des données** → Importation et nettoyage
2. **Analyse exploratoire** → Visualisation des tendances
3. **Feature Engineering** → Sélection et transformation des variables
4. **Modélisation** → Entraînement du modèle de machine learning
5. **Évaluation** → Calcul des scores et validation

---

## 🚀 Installation et exécution du projet
```bash
# Cloner le repo
git clone https://github.com/LeTibs/portfolio-github.git
cd portfolio-github/projets/HousePriceCalifornie

# Installer les dépendances
pip install -r requirements.txt

# Lancer le notebook
jupyter notebook

