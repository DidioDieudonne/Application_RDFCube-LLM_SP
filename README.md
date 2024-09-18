#Application de Suivi des Performances Éducatives avec LLM et RDF Cube
Bienvenue dans notre projet qui combine des Modèles de Langage de Grande Taille (LLM) et des Cubes RDF pour offrir une solution innovante de suivi des performances éducatives. Ce projet permet de structurer des données éducatives et d'utiliser l'intelligence artificielle pour produire des analyses et des recommandations personnalisées en fonction des performances des étudiants.

Contexte du Projet
Dans le cadre de l'éducation, il est essentiel de suivre et d'évaluer les performances des étudiants pour identifier les domaines où des améliorations sont nécessaires. Ce projet se concentre sur l'utilisation de RDF Cube pour structurer les données éducatives et de LLM pour générer des réponses aux questions posées en langage naturel par les utilisateurs (enseignants, administrateurs).

Fonctionnalités Principales
Analyse des performances éducatives : Basée sur différents critères tels que les cours, la classe, ou l'année.
Recommandations personnalisées : Propose des actions ciblées pour améliorer les performances des étudiants ou des classes.
Interface utilisateur intuitive : Les utilisateurs peuvent poser des questions en langage naturel pour obtenir des réponses sous forme de statistiques, tendances ou recommandations.
Architecture du Système
L'application est constituée de trois principaux composants :

Interface Utilisateur (UI) : Permet aux utilisateurs de poser des questions et de visualiser les résultats.
Module LLM : Interprète les questions posées en langage naturel et génère des réponses pertinentes à partir des données RDF Cube.
Cubes RDF : Stocke et organise les données éducatives de manière multidimensionnelle, facilitant les requêtes complexes.
Installation et Configuration
Prérequis
Python 3.10 ou plus récent
Poetry pour la gestion des dépendances
Une clé API OpenAI pour interagir avec le modèle de langage.
Étapes d'Installation
Cloner le dépôt du projet :

bash
Copier le code
git clone https://github.com/votre-repo/education-llm-rdfcube.git
cd education-llm-rdfcube
Créer un environnement virtuel et l'activer :

bash
Copier le code
python -m venv .venv
source .venv/bin/activate
Installer les dépendances avec Poetry :

bash
Copier le code
poetry install --no-root
Configurer la clé API OpenAI :

Créez un fichier .env et ajoutez-y votre clé API OpenAI.
bash
Copier le code
OPENAI_API_KEY=votre_cle_api
Lancer l'application dans Visual Studio Code :

Ouvrez le projet dans VSCode avec l'extension Jupyter installée pour une interaction transparente avec les notebooks.
Exécution
Accédez au fichier main.ipynb dans VS Code pour commencer à poser des questions et interagir avec le système.
Contribution
Nous accueillons les contributions de la communauté. Si vous souhaitez proposer des améliorations ou corriger des bugs, vous pouvez :

Forker ce dépôt,
Créer une nouvelle branche,
Proposer une Pull Request.
Licence
Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus d'informations.

Auteurs
Dieudonné BYAOMBE MWINDULWA
Priscile EBWALLA EBWALETTE
Haback Marthe Désirée Olivia
David Lutala Lushuli
Encadré par : Dr. Tuong Nguyen
