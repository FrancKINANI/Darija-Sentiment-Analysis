# Darija-Sentiment-Analysis
Entraînement d’un modèle Naive Bayes pour classer 500+ tweets marocains (positif/négatif).

├── data/                  # Dataset (fichier CSV ou lien vers Kaggle)
├── models/                # Modèle sauvegardé (.pkl ou .h5)
├── notebooks/             # Jupyter Notebook ou script Python
├── requirements.txt       # Librairies Python
└── README.md              # Documentation en français

# Analyse de Sentiment de Tweets en Darija  
## Objectif  
Classifier des tweets marocains en positif/négatif avec scikit-learn.  
## Résultats  
- Précision de 82% sur 500 tweets.  
- Matrice de confusion et métriques (précision, rappel).  
## Utilisation  
```bash  
pip install -r requirements.txt  
python train.py  
