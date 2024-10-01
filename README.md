# Projet DU Sorbonne - Data Science & Data Analytics

Ce dépôt regroupe les projets réalisés dans le cadre de mon **DU Sorbonne en Data Science et Data Analytics**. Chaque sous-module correspond à un projet ou à une partie spécifique du cursus.

## Structure du projet

Ce dépôt utilise des **sous-modules Git** pour organiser les différents projets de manière modulaire. Chaque projet a son propre dépôt et est lié à ce dépôt principal.

### Sous-modules inclus dans ce dépôt :

1. [DU Data Management](https://github.com/Jorissalmon/DU_Data_Management.git)
2. [DU NLP (Natural Language Processing)](https://github.com/Jorissalmon/DU_nlp.git)
3. [DU Statistiques](https://github.com/Jorissalmon/DU_Statistiques.git)
4. [DU Machine Learning Ops](https://github.com/Jorissalmon/DU_Ml_Ops.git)
5. [DU Machine Learning](https://github.com/Jorissalmon/DU_Machine_Learning.git)
6. [DU NEO4J](https://github.com/Jorissalmon/DU_NEO4J.git)
7. [DU Python](https://github.com/Jorissalmon/DU_Python.git)
8. [DU Spark](https://github.com/Jorissalmon/DU_Spark.git)
9. [DU SQL](https://github.com/Jorissalmon/DU_SQL.git)

### Comment cloner ce dépôt avec les sous-modules

Pour cloner ce dépôt avec tous les sous-modules, exécutez la commande suivante :
git clone --recurse-submodules https://github.com/Jorissalmon/DU-Sorbonne-Project.git

##### Ajout submodule
git submodule add https://github.com/Jorissalmon/DU_Nouveau_Projet.git DU_Nouveau_Projet  
git add .  
git commit -m "Ajout du nouveau projet DU_Nouveau_Projet"  
git push origin main
