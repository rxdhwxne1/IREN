# Projet IREN - Classification d'images de navires avec des réseaux de neurones convolutifs (CNN) - cursus EPITA

Ce projet est une solution de classification d'images de navires réalisée dans le cadre du projet IREN. Il consiste en la création d'un réseau de neurones convolutifs pour classer des images de navires en différentes catégories. Le projet inclut un notebook détaillé avec l'architecture et les choix d'optimisation du modèle, ainsi que des explications sur les étapes de prétraitement des données.

## Objectifs

Compétition : Concevoir un CNN de 0 pour atteindre une précision optimale.

## Architecture et approche

**Prétraitement des images**
Les images ont été normalisées avant d'être traitées par le CNN afin d'améliorer la performance du modèle. Des techniques de data augmentation ont également été utilisées pour augmenter la diversité des données d'entraînement.

**Architecture du modèle**
Le modèle est composé de plusieurs couches convolutionnelles suivies de couches de pooling et de couches entièrement connectées. Cela permet au réseau d'apprendre des caractéristiques pertinentes pour la classification des images de navires.

## Installation

Clonez ce dépôt :
```bash
git clone git@github.com:rxdhwxne1/IREN.git
cd IREN
```

Installez les dépendances :
```bash
pip install -r requirements.txt
```

## Utilisation

Ouvrez le notebook Jupyter IREN.ipynb pour explorer le code, les visualisations et les résultats du modèle.

## Auteur

NAMAOUI Radhwane