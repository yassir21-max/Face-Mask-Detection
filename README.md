# Face-Mask-Detection

Détection de masques en temps réel à l'aide de Machine Learning/ Deep Learning et OpenCV

## À propos du projet
### 1ère manière : Machine Learning "les fichiers ipynb"
Ce projet utilise les algorithmes de classification, plus précisément SVM et Logistic Regression, pour différencier les images de personnes avec et sans masque. Ces algorithmes parvient à obtenir
une précision de **98,2% sur l'ensemble d'entraînement** et **98% sur l'ensemble de test**. Ensuite, les poids stockés  sont utilisés pour classer en masque ou sans masque, en temps réel, à l'aide d'OpenCV.
Avec la webcam capturant la vidéo, les images sont prétraitées et transmises au modèle pour accomplir cette tâche. Le modèle fonctionne efficacement sans délai apparent entre
port/retrait du masque et affichage du pronostic.
### 2ère manière : Deep Learning ( CNN ) "facemask.py"

## Working 

### With Mask
![mask2](https://user-images.githubusercontent.com/83836471/140391943-8983febb-f618-4db9-9ca2-3d547fce7350.PNG)


### No Mask

![nomask](https://user-images.githubusercontent.com/83836471/140391957-1caba983-13c8-4eac-89fe-c1ccca4c34a3.PNG)





## Dataset

The data used 
'train'). There are 1314 training images and 194 test images divided into two catgories, with and without mask.

