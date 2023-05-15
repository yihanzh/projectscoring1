# Projet7-OpenClassrooms
Parcours Data Scientist - Projet 7: Implémentez un modèle de scoring

**Source de données : https://www.kaggle.com/c/home-credit-default-risk/data**

**Contexte:**

Nous sommes Data Scientist au sein d'une société financière **"Prêt à dépenser"**, qui propose des crédits à la consommation pour des personnes ayant peu ou pas du tout d'historique de prêt.
L’entreprise souhaite mettre en œuvre un **outil de “scoring crédit”** pour calculer la probabilité qu’un client rembourse son crédit, puis **classifie la demande en crédit accordé ou refusé**. Elle souhaite donc développer un **algorithme de classification** en s’appuyant sur des sources de données variées (données comportementales, données provenant d'autres institutions financières, etc.).

De plus, les chargés de relation client ont fait remonter le fait que les clients sont de plus en plus demandeurs de transparence vis-à-vis des décisions d’octroi de crédit. Cette demande de transparence des clients va tout à fait dans le sens des valeurs que l’entreprise veut incarner.
Prêt à dépenser décide donc de développer un **dashboard interactif** pour que les chargés de relation client puissent à la fois expliquer de façon la plus transparente possible les décisions d’octroi de crédit, mais également permettre à leurs clients de disposer de leurs informations personnelles et de les explorer facilement. 

**Notre mission :**

* Construire un modèle de scoring qui donnera une prédiction sur la probabilité de faillite d'un client de façon automatique.
* Construire un dashboard interactif à destination des gestionnaires de la relation client permettant d'interpréter les prédictions faites par le modèle, et d’améliorer la connaissance client des chargés de relation client.
* Mettre en production le modèle de scoring de prédiction à l’aide d’une API, ainsi que le dashboard interactif qui appelle l’API pour les prédictions.

**Description des dossiers et fichiers :**
* Dossier API : Dossier contenant les fichiers liés au focntionnement de l'API de prédiction.
    * 
* Dossier Dashboard : Dossier contenant les fichiers liés au fonctionnement du dashboard. 
    * Dashboard.py : Tableau de bord réalisé avec le framework Streamlit. Il comprend la partie interface utilisateur qui interagit avec l'API de rpédiction.
    * setup_streamlit.sh : fichier necessaire au lancement de streamlit. Précise l'option "headless" ainsi que le port d'écoute.
    * logo_pret_a_depenser.png : fichier image logo de la société "Prêt à dépenser"
* Dossier Data :
* Procfile :
* Requirements.txt : 
* runtime : 
