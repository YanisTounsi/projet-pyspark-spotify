# 🎵 Projet PySpark — Analyse du catalogue Spotify

Projet universitaire **Master 2** — Introduction à PySpark.  
Analyse de 114 000 chansons du catalogue Spotify via Apache Spark en Python.

## 📊 Objectifs

1. Charger et nettoyer un dataset de 114 000 chansons
2. Explorer les caractéristiques musicales (features audio, popularité)
3. Appliquer des transformations avancées (joins, pivots, window functions)
4. Optimiser les performances (cache, broadcast join, explain)
5. Construire un modèle de clustering (K-Means)
6. Produire des visualisations et insights métier

## 🗂️ Dataset

- **Source** : Spotify Tracks Dataset (Kaggle, licence CC0)
- **Volume** : 114 000 chansons × 21 colonnes

## 🚀 Démarrage rapide

### Prérequis
- Python 3.10+
- Java 11
- PySpark 3.5.0

### Installation

```bash
conda create -n pyspark-projet python=3.10 openjdk=11 pyspark=3.5.0 \
    jupyter pandas matplotlib seaborn scikit-learn -c conda-forge -y
conda activate pyspark-projet
```

### Télécharger le dataset

Le dataset n'est pas inclus dans le repo. Il se télécharge automatiquement via la première cellule du notebook.

## 📁 Structure du projet

projet-pyspark-spotify/
├── data/                          # Dataset (ignoré par Git)
├── notebooks/
│   └── 01_setup_et_ingestion.ipynb
├── slides/                        # Slides de soutenance
├── .gitignore
└── README.md

## 👥 Auteurs

- **Yanis Tounsi**
- **Can Pekgoz**