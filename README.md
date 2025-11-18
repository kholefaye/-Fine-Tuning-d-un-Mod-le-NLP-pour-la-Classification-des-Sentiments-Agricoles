# -Fine-Tuning-d-un-Mod-le-NLP-pour-la-Classification-des-Sentiments-Agricoles
Ce projet consiste à générer des données textuelles synthétiques sur les dynamiques du marché agricole (hausse des prix, production, crise, exportations) et à fine-tuner un modèle NLP afin de classifier automatiquement les sentiments associés (positif, négatif, neutre).

##  Objectifs du projet
- Créer un dataset synthétique réaliste lié au secteur agricole  
- Entraîner un modèle NLP adapté aux machines à faible RAM  
- Évaluer la performance du modèle fine-tuné  
- Préparer une base réutilisable pour d’autres tâches agri-économiques  

##  Contenu du repository
- `dataset_agri_sentiment.csv` — Données synthétiques générées  
- `fine_tuning_sentiment.ipynb` — Notebook complet du fine-tuning  
- `model/` — Dossier du modèle fine-tuné (si ajouté)  
- `README.md` — Documentation du projet  

## Modèles utilisés
Pour être compatibles avec les machines à faible mémoire :
- **DistilBERT**  
- **BERT Mini / Tiny**  
- **ALBERT**  

Ces modèles sont légers, efficaces et parfaits pour le fine-tuning.

## Résultats attendus
Le modèle fine-tuné doit être capable de :
- reconnaître automatiquement le ton d'un texte agricole  
- aider à analyser les tendances du marché ou des rapports économiques  
- servir de base pour un futur projet de dashboard ou d’assistant IA agricole  


Khole Faye – Data Scientist / ML Researcher.
