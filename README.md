# Energy-conso-analysis

Ce projet vise à analyser les tendances mondiales de la consommation énergétique et à explorer son impact sur les facteurs économiques et démographiques. En combinant des données sur la consommation d'énergie, le PIB, la population, et les types de logements, ce projet cherche à comprendre comment ces éléments interagissent et influencent la demande énergétique à l’échelle mondiale.

source des données:

Récupérer des données sur la consommation d’énergie, le PIB, la population et les types de logements à partir de sources fiables comme l'Agence Internationale de l'Énergie (AIE), la Banque Mondiale, et les Nations Unies.

Analyse des relations :

Implémenter des modèles de machine learning pour prédire la consommation énergétique future, en utilisant des algorithmes comme Random Forest ou XGBoost.

Technologies Utilisées :
- Python (pandas, numpy, sqlalchemy, requests)
- PostgreSQL pour la gestion de la base de données
- Streamlit pour la création du tableau de bord interactif
- Matplotlib, Seaborn, et Plotly pour la visualisation des données
- Machine Learning : Random Forest, XGBoost pour les prévisions


Structure du Repository :
- /data : Contient les fichiers de données brutes et nettoyées.
- /notebooks : Jupyter Notebooks avec les étapes d'analyse et les visualisations.
- /src : Scripts Python pour la collecte des données, le nettoyage, et la connexion à la base de données.
- /dashboard : Code du tableau de bord interactif Streamlit.

Pour commencer :
Cloner ce repository.

Créer et activer un environnement virtuel :
- python -m venv venv
- source venv/bin/activate  # Sur macOS/Linux
- venv\Scripts\activate     # Sur Windows

Installer les dépendances :
- pip install -r requirements.txt

Lancer le tableau de bord avec Streamlit :
- streamlit run dashboard/app.py

Ce projet est conçu pour aider les décideurs, les chercheurs et les entreprises à mieux comprendre l'impact économique de la consommation énergétique et à élaborer des stratégies basées sur des données fiables et des prévisions éclairées.

