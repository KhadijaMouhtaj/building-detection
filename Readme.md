# 🏢 Prédiction d’énergie des bâtiments (ENB2012) — MLP From Scratch

## 🎯 Objectif du projet
Ce projet a pour but de développer un **réseau de neurones multicouche (MLP)** pour prédire les **besoins énergétiques de chauffage et de refroidissement** des bâtiments résidentiels, à partir du dataset **ENB2012**.

L’originalité du projet réside dans le fait que :
- l’algorithme de type **MLP est implémenté **from scratch** (initialisation, propagation avant, rétropropagation, mise à jour des poids)  
- seul le calcul du backpropagation (BP) utilise les bibliothèques scientifiques, mais toute la logique réseau est codée à la main  

C’est donc une **démarche pédagogique**, pour comprendre en profondeur le fonctionnement d’un réseau de neurones artificiel.

---

## 📊 Dataset
Le dataset utilisé est **[ENB2012](https://archive.ics.uci.edu/ml/datasets/energy+efficiency)**, qui contient :
- 768 échantillons de bâtiments
- Variables d’entrée : 8 caractéristiques (surface, hauteur, orientation, vitrage, etc.)
- Variables de sortie : 
  - `Y1` : Besoin en chauffage  
  - `Y2` : Besoin en refroidissement  

Dans le repo, le dataset nettoyé est fourni :  
`ENB2012_data_clean.csv`

---

## 🛠️ Contenu du projet
- `Notebook_Prediction_Energie_Batiments_VF.ipynb` : notebook principal avec l’entraînement et les tests du MLP from scratch  
- `ENB2012_data_clean.csv` : dataset nettoyé  
- `README.md` : ce fichier de documentation  


## 🚀 Installation
Cloner le projet et installer les dépendances :
```bash
git clone https://github.com/<ton-user>/<ton-repo>.git
cd <ton-repo>
pip install -r requirements.txt

