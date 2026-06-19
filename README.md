# sentiment-analysis-apps
Développement d'un système automatisé d'analyse de sentiment (positif, négatif, neutre) basé sur le NLP pour analyser les avis utilisateurs d'applications mobiles (livraison, banques, télécoms).
# Fonctionnalités Principales
Scraping : Collecte automatisée de près de 30 000 avis sur le Google Play Store.
Data Wrangling : Nettoyage strict (déduplication, suppression des textes trop courts) et filtrage linguistique via langdetect.
Modélisation NLP : Comparaison de plusieurs algorithmes allant des baselines classiques (One-Hot, TF-IDF + SVM) jusqu'au fine-tuning de modèles de langage (CamemBERT).
# Technologies
Python (Pandas, NumPy, Scikit-learn)
PyTorch & Hugging Face (CamemBERT)
Google Play Scraper
# Structure du Projet

├── data/                  # Datasets bruts et nettoyés
├── figures/               # Graphiques et visualisations (EDA)
├── notebooks/             # Code source : Scraping, Preprocessing et Entraînement
├── README.md              # Description
└── Rapport_Projet.pdf     # Rapport complet et méthodologie détaillée
