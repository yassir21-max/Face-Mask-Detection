# Face-Mask-Detection

Détection de masques en temps réel à l'aide de Machine Learning et OpenCV

## À propos du projet
Ce projet utilise les algorithmes de classification, plus précisément SVM et Logistic Regression, pour différencier les images de personnes avec et sans masque. Ces algorithmes parvient à obtenir
une précision de **98,2% sur l'ensemble d'entraînement** et **98% sur l'ensemble de test**. Ensuite, les poids stockés  sont utilisés pour classer en masque ou sans masque, en temps réel, à l'aide d'OpenCV.
Avec la webcam capturant la vidéo, les images sont prétraitées et transmises au modèle pour accomplir cette tâche. Le modèle fonctionne efficacement sans délai apparent entre
port/retrait du masque et affichage du pronostic.


## Working 

### With Mask

![image](mask.png)

### No Mask

![image](nomask.png)




## Dataset

The data used can be downloaded through this [link](https://data-flair.training/blogs/download-face-mask-data/) or can be downloaded from this repository as well (folders 'test' and 
'train'). There are 1314 training images and 194 test images divided into two catgories, with and without mask.

## How to Use

To use this project on your system, follow these steps:

1.Clone this repository onto your system by typing the following command on your Command Prompt:

```
git clone https://github.com/Karan-Malik/FaceMaskDetector.git
```
followed by:

```
cd FaceMaskDetector
```

2. Download all libaries using::
```
pip install -r requirements.txt
```

3. Run facemask.py by typing the following command on your Command Prompt:
```
python facemask.py
```

#### The Project is now ready to use !!


