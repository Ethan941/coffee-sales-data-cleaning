# ☕ Coffee Sales Data Cleaning

Projet de **Data Cleaning** et de **Data Quality** basé sur un dataset de ventes de café.

L’objectif est de transformer un dataset brut contenant des erreurs, des valeurs manquantes et des incohérences en un dataset propre, structuré et exploitable pour l’analyse ou la visualisation.

---

## 🎯 Objectif du projet

Les données brutes sont rarement exploitables directement.

Ce projet montre comment passer d’un dataset sale à un dataset propre :

```txt
Dataset brut
     ↓
Diagnostic qualité
     ↓
Nettoyage
     ↓
Transformation
     ↓
Dataset final exploitable
     ↓
Analyse / BI / Machine Learning
```

Le but est de démontrer une compétence essentielle en Data Engineering : la capacité à fiabiliser les données avant leur exploitation.

---

## 🧠 Problématique Data Engineering

Avant d’analyser ou de modéliser des données, il faut s’assurer qu’elles sont propres, cohérentes et structurées.

Ce projet répond à la problématique suivante :

> Comment nettoyer, corriger et structurer un dataset brut pour le rendre exploitable ?

---

## 🛠️ Technologies utilisées

- Python
- Pandas
- NumPy
- Jupyter Notebook
- CSV
- Data Cleaning
- Data Quality
- Data Transformation

---

## 📁 Structure du projet

```txt
coffee-sales-data-cleaning/
│
├── data/
│   ├── raw/
│   │   └── dirty_cafe_sales.csv
│   │
│   └── processed/
│       └── cleaned_cafe_sales.csv
│
├── notebooks/
│   └── data_cleaning.ipynb
│
├── reports/
│   └── rapport_nettoyage.pdf
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🔎 Étapes du projet

### 1. Diagnostic du dataset

La première étape consiste à comprendre la qualité du dataset.

Analyses réalisées :

- affichage des premières lignes ;
- analyse des colonnes ;
- vérification des types de données ;
- identification des valeurs manquantes ;
- identification des doublons ;
- repérage des valeurs incohérentes ;
- détection des formats incorrects.

---

### 2. Nettoyage des données

Le nettoyage permet de corriger les problèmes présents dans le dataset.

Actions réalisées :

- suppression des doublons ;
- correction des valeurs manquantes ;
- nettoyage des chaînes de caractères ;
- uniformisation des catégories ;
- correction des formats de dates ;
- conversion des types de données ;
- suppression ou correction des valeurs incohérentes.

---

### 3. Transformation des données

Une fois les données nettoyées, elles sont transformées pour être plus faciles à exploiter.

Transformations possibles :

- renommage des colonnes ;
- création de nouvelles colonnes ;
- standardisation des noms ;
- calcul de montants ;
- préparation du dataset pour analyse ;
- export du dataset final.

---

### 4. Export du dataset propre

Le dataset final est exporté dans un fichier CSV propre.

Ce fichier peut ensuite être utilisé pour :

- une analyse exploratoire ;
- un dashboard Power BI ;
- une base SQL ;
- un modèle de Machine Learning ;
- un rapport métier.

---

## 📊 Exemple de contrôles qualité

| Contrôle | Objectif |
|---|---|
| Valeurs manquantes | Identifier les colonnes incomplètes |
| Doublons | Éviter les lignes répétées |
| Types de données | Vérifier que les colonnes ont le bon format |
| Dates | Standardiser les formats |
| Catégories | Uniformiser les valeurs textuelles |
| Montants | Vérifier les incohérences numériques |

---

## 📈 Résultat attendu

À la fin du projet, le dataset final doit être :

- propre ;
- structuré ;
- sans doublons critiques ;
- avec des formats cohérents ;
- avec des types de données corrects ;
- exploitable pour l’analyse ;
- exploitable pour un dashboard ;
- exploitable pour une base de données.

---

## ⚙️ Installation

### 1. Cloner le repository

```bash
git clone https://github.com/Ethan941/coffee-sales-data-cleaning.git
cd coffee-sales-data-cleaning
```

Si le repository garde son ancien nom :

```bash
git clone https://github.com/Ethan941/data_refirment.git
cd data_refirment
```

### 2. Créer un environnement virtuel

```bash
python -m venv .venv
```

Sur macOS / Linux :

```bash
source .venv/bin/activate
```

Sur Windows :

```bash
.venv\Scripts\activate
```

### 3. Installer les dépendances

```bash
pip install -r requirements.txt
```

### 4. Lancer le notebook

```bash
jupyter notebook
```

Puis ouvrir :

```txt
notebooks/data_cleaning.ipynb
```

---

## ✅ Compétences démontrées

- Nettoyage de données
- Data Quality
- Analyse exploratoire
- Manipulation avec Pandas
- Transformation de données
- Gestion des valeurs manquantes
- Gestion des doublons
- Correction de formats
- Préparation de données pour l’analyse
- Structuration d’un projet Data Engineering

---

## 🚀 Améliorations possibles

- Renommer le repository en `coffee-sales-data-cleaning`
- Renommer le dossier `notbooks` en `notebooks`
- Ajouter un rapport qualité avant / après
- Ajouter des tests de validation
- Ajouter un script Python réutilisable
- Ajouter un fichier `main.py`
- Ajouter une étape SQL
- Créer un dashboard Power BI
- Ajouter des graphiques d’analyse
- Automatiser le pipeline de nettoyage

---

## 📌 Statut du projet

Projet de nettoyage de données en cours d’amélioration.

L’objectif est de le présenter comme un projet clair de **Data Engineering** orienté qualité et préparation des données.

---

## 👤 Auteur

**Ethan Pandor**  
Étudiant en Bachelor Data & IA à HETIC  
Recherche stage ou alternance en Data Engineering / Data Science
