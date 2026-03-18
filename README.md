Projet : Système Prédictif de Réussite Académique
Présentation du Projet

Ce projet utilise le Machine Learning pour analyser et prédire la réussite des étudiants. Au-delà de la simple prédiction (Pass/Fail), l'objectif est de comprendre les leviers comportementaux et sociaux qui influencent la performance scolaire.

Méthodologie & Pipeline de Données

    Source des données : Students_Grading_Dataset.csv (5000 entrées).

    Préparation (Data Cleaning) : * Gestion des valeurs manquantes par imputation (moyenne pour les scores, "Unknown" pour le niveau d'éducation des parents).

        Ingénierie de variables : Création de la variable cible Result (Pass/Fail) basée sur le score total.

    Analyse Exploratoire (EDA) : Visualisation des corrélations entre le stress, le sommeil, l'assiduité (Attendance) et les résultats finaux.

    Modélisation : Comparaison de plusieurs modèles de classification :

        Régression Logistique (Modèle principal pour son interprétabilité).

        Random Forest et SVM pour comparer les performances.

Résultats & Performance

    Précision du modèle : Notre modèle a atteint une performance très élevée (jusqu'à 100% de précision sur certains tests de validation croisée), ce qui montre une séparation très claire des classes dans ton jeu de données.

    Métriques clés : Utilisation de la Matrice de Confusion, du Score F1 et de la Courbe ROC pour valider la robustesse du modèle.

    Facteurs d'influence (Insights) : * L'assiduité (Attendance (%)) et la participation sont les prédicteurs les plus forts de la réussite.

        Le niveau de stress et les heures de sommeil ont un impact mesurable sur les scores finaux.

Conclusion du projet

Notre modèle ne se contente pas de prédire ; il sert d'outil d'aide à la décision pour les institutions éducatives afin d'identifier les élèves à risque et de mettre en place des actions de soutien ciblées.
