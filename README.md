# Temporal-Series-electricity-forecast-
Projet 9 - "Prédisez la demande en électricité" 
Le but du projet est de prévoir la consommation électrique sur une année  

Jeu de données:  
* eCO2mix_RTE_energie_M.csv: Consommation électrique de la France de Janvier 2010 à Mai 2018  
* dju_chauffage.csv: Degrès Jour Unifiés pour le chauffage de Janvier 2010 à Mai 2018  
* dju_chauffage.csv: Degrès Jour Unifiés pour la climatisation de Janvier 2010 à Mai 2018   

A partir du jeu de données, le script va:  
-Préparer les données  
-Corriger l'effet de la température sur la consommation électrique par régression linéaire  
-Désaisonnaliser la consommation électrique par la méthode des moyennes mobiles
-Effectuer une prédiction de la consommation électrique pour la période de Juin 2018 à Juin 2019 avec un modèle dit de Holt-Winters  
-Effectuer une prédiction de la consommation électrique pour la période de Juin 2018 à Juin 2019 avec un modèle SARIMA 


    
Il s'agit d'un fichier jupyter notebook en Python
Le script va créer des dossiers pour stocker les graphiques  
