# CNN-pour-la-Reconnaissance-d-Objets-en-Couleur-avec-le-Dataset-CIFAR-10
![ảnh](https://github.com/user-attachments/assets/e562f5c1-6ecc-433d-a879-ec11491fbcd9)

Ce projet démontre l'application des réseaux de neurones convolutifs (CNN) pour la tâche de reconnaissance d'objets en couleur en utilisant le dataset CIFAR-10. Le dataset CIFAR-10 se compose de 60 000 images couleur de 32x32 pixels réparties en 10 classes différentes. L'objectif de ce projet est de construire, entraîner et évaluer un modèle CNN capable de classer ces images dans leurs catégories respectives.
## Structure du projet
https://github.com/DeoMuunduku/CNN-pour-la-Reconnaissance-d-Objets-en-Couleur-avec-le-Dataset-CIFAR-10/blob/main/cvcvcv.png
Le projet est organisé en plusieurs sections :

Configuration de l'environnement :

Installation des bibliothèques et des dépendances nécessaires.
Téléchargement et prétraitement du dataset CIFAR-10.
Préparation des données :

Transformation des données pour la normalisation et l'augmentation des données.
Chargement des datasets d'entraînement et de validation.
Architecture du modèle :
 
Définition de l'architecture du modèle CNN avec PyTorch.
Spécification des couches, des fonctions d'activation et des taux de dropout.
Entraînement du modèle :

Configuration de la boucle d'entraînement, incluant la fonction de perte et l'optimiseur.
Entraînement du modèle sur le dataset d'entraînement CIFAR-10.
Surveillance des progrès de l'entraînement avec des métriques appropriées.
Évaluation du modèle :

Évaluation du modèle entraîné sur le dataset de validation.
Calcul et affichage des métriques de précision et de perte.
Génération et visualisation de la matrice de confusion.
Résultats et analyse :

Discussion des performances du modèle.
Mise en avant des améliorations potentielles ou des travaux futurs.
Démarrage
Prérequis
Python 3.5 ou supérieur
PyTorch
torchvision
numpy
matplotlib
