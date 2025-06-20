﻿# TP_Fashion
Ce projet a été réalisé dans le cadre du cours de Deep Learning à Polytech Lyon.
Il s'agit d'un travail pratique portant sur la classification d’images issues de la base de données FashionMNIST, une alternative à MNIST proposant des vêtements au lieu de chiffres manuscrits.

Objectif
L'objectif est de construire, entraîner et évaluer un modèle de réseau de neurones capable de reconnaître automatiquement le type de vêtement représenté sur une image en niveaux de gris (28x28 pixels).

## Contenu
Le notebook TP4_FashionMNIST.ipynb contient :

Le chargement et la visualisation des données FashionMNIST

La définition d’un modèle de réseau de neurones (avec PyTorch)

L’entraînement du modèle sur les données d’entraînement

L’évaluation sur les données de test

L’analyse de la performance avec matrice de confusion

## Résultats
Le modèle obtient une précision de test raisonnable compte tenu de sa simplicité. Une analyse par classe permet d’identifier les erreurs fréquentes (notamment entre classes visuellement proches comme « shirt » et « T-shirt »).
