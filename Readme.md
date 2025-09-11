# 🏢 Prédiction d’énergie des bâtiments (ENB2012) – MLP From Scratch

## 🎯 Objectif
Ce projet a pour but de développer un réseau de neurones multicouche (**MLP**) pour prédire les besoins énergétiques de **chauffage** et de **refroidissement** des bâtiments résidentiels, à partir du dataset **ENB2012**.

L’originalité du projet réside dans le fait que :
- L’algorithme de type **MLP est implémenté from scratch** (initialisation, propagation avant, rétropropagation, mise à jour des poids).  
- Seul le calcul du **backpropagation** utilise des bibliothèques scientifiques (NumPy), mais toute la logique réseau est **codée à la main**.  

👉 Ce projet est donc une démarche **pédagogique** pour comprendre en profondeur le fonctionnement d’un réseau de neurones artificiel.

---

## 📊 Dataset
- **Source** : ENB2012 (Energy Efficiency Dataset)  
- **Nombre d’échantillons** : 768 bâtiments  
- **Variables d’entrée (X)** : 8 caractéristiques (surface, hauteur, orientation, vitrage, etc.)  
- **Variables de sortie (Y)** :  
  - **Y1** : Besoin en chauffage  
  - **Y2** : Besoin en refroidissement  

Le dataset nettoyé est fourni : `ENB2012_data_clean.csv`

---

## 🛠️ Contenu du projet
- `Notebook_Prediction_Energie_Batiments_VF.ipynb` → entraînement et tests du MLP from scratch  
- `ENB2012_data_clean.csv` → dataset nettoyé  
- `requirements.txt` → dépendances Python  
- `README.md` → documentation du projet  

---

## 🚀 Installation & Exécution
1. Cloner le projet :

git clone https://github.com/<ton-user>/<ton-repo>.git
cd <ton-repo>
Installer les dépendances :
pip install -r requirements.txt
Ouvrir le notebook :
jupyter notebook Notebook_Prediction_Energie_Batiments_VF.ipynb

## 📈 Résultats
Le modèle MLP from scratch a permis de prédire les besoins énergétiques avec une erreur moyenne inférieure à XX% (ajoute ton résultat exact si dispo).

Visualisation des courbes d’apprentissage (loss vs epochs).

## Technologies utilisées
Python, NumPy : implémentation réseau de neurones et calcul matriciel

Jupyter Notebook : expérimentation et visualisation

Matplotlib : visualisation des performances

## 📬 Contact
Projet académique réalisé par Khadija Mouhtaj.
N’hésitez pas à me contacter pour plus d’informations.

