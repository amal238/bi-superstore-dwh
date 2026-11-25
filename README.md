# Projet BI : Analyse des Ventes Superstore

Data Warehouse & analyse multidimensionnelle  
2ème LGL, 2025/2026, École Polytechnique de Sousse  
Enseignante : Dr-Ing. Nedya BOUFARES

## Contenu

- `superstore_2.py` : exploration des données, pipeline ETL, Data Warehouse SQLite, requêtes SQL et KPIs
- `Sample-Superstore.csv` : dataset Sample Superstore (Kaggle), 9 994 lignes × 21 colonnes
- `Rapport_BI_Superstore.pdf` : rapport du projet
- `Projet_BI_Superstore_2_.pdf` : présentation du projet

## Modèle en étoile

1 table de faits (`FACT_VENTES`) et 5 dimensions : `DIM_DATE`, `DIM_PRODUIT`, `DIM_CLIENT`, `DIM_GEOGRAPHIE`, `DIM_EXPEDITION`.

## Technologies

Python (pandas, matplotlib, seaborn), SQLite, Power BI

## Exécution

```bash
pip install pandas matplotlib seaborn
python superstore_2.py
```
