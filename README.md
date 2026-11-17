# Predicting Six-Month Survival in Seriously Ill Hospitalized Adults

**Group members:** Betanya Binyam, Ryan Colavita, Heath Miller
**Course:** DS4021: Machine Learning

## Research question
Can machine learning models predict 6-month survival among seriously ill 
hospitalized adults using information available early in their hospital stay, 
and can they match or exceed physicians' own prognoses?

## Data
SUPPORT2 dataset from the UCI Machine Learning Repository
(https://archive.ics.uci.edu/dataset/880/support2).

- `Data/support2_train.csv`: 80% training set (7,284 patients)
- `Data/support2_reporting.csv`: 20% reporting set (1,821 patients).
  **Do not open or use until final evaluation.**

The split is stratified on the outcome (`died_6m`, death within 180 days of
study entry) with `random_state=42`. See `NOTEBOOKS/data_split.ipynb`.
