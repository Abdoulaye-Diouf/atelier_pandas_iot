# Atelier Pandas — Analyse de données IoT

Préparation, nettoyage et analyse de données de capteurs (température, humidité, pression, consommation énergétique) avant transmission à un système de Machine Learning, à l'aide de la bibliothèque Pandas.

## Contexte

Une entreprise dispose de plusieurs capteurs installés dans différents bâtiments. Avant d'être exploitées par un futur système de détection d'anomalies, ces données doivent être explorées, nettoyées et analysées.

## Structure du projet

```
.
├── data/
│   └── mesures_capteurs.csv
├── exports/
│   ├── donnees_nettoyees.csv
│   └── donnees_nettoyees.json
├── atelier_pandas_iot.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## Contenu de l'atelier

| Partie | Sujet |
|---|---|
| 1 | Series |
| 2 | DataFrame |
| 3 | Exploration |
| 4 | Sélection |
| 5 | Manipulation des colonnes |
| 6 | Filtrage |
| 7 | Tri |
| 8 | Analyse |
| 9 | Gestion des valeurs manquantes |
| 10 | Gestion des doublons |
| 11 | Statistiques descriptives |
| 12 | Exportation |
| 13 | BONUS : Analyse Temporelle & Détection Automatique des Anomalies

Chaque partie se termine par un tableau récapitulatif des fonctions utilisées, mis en perspective avec leurs alternatives.

## Installation

**1. Cloner le dépôt**
```bash
git clone <url-du-depot>
cd atelier_pandas_iot
```

**2. Créer et activer l'environnement virtuel**
```bash
python -m venv venv
```
- Windows : `venv\Scripts\Activate.ps1`
- macOS / Linux : `source venv/bin/activate`

**3. Installer les dépendances**
```bash
pip install -r requirements.txt
```

## Utilisation

Ouvrir `atelier_pandas_iot.ipynb` dans VS Code (extension Jupyter) ou Jupyter Notebook, puis exécuter les cellules dans l'ordre.

## Technologies

- Python 3
- Pandas
- NumPy
- Jupyter Notebook

## Auteur

Abdoulaye DIOUF
Projet réalisé dans le cadre d'un atelier de pratique Pandas.