# Fake News Detection

## Description
Cette application web permet de détecter automatiquement les fausses nouvelles à partir d'un article de presse.  
Elle classifie le texte saisi en **FAKE** ou **REAL** grâce à un modèle de Machine Learning entraîné sur plus de 40 000 articles.

<!-- Ici, insère les captures d'écran -->
<img width="938" height="475" alt="s1" src="https://github.com/user-attachments/assets/0f7912d4-7d5f-40d1-813a-d3e6f1e8f0a9" />
<img width="940" height="480" alt="s2" src="https://github.com/user-attachments/assets/1a122ce9-8965-48a3-85f9-77482e187e71" />


## Fonctionnalités principales
- Saisie d'un article de presse en texte libre.
- Classification automatique en FAKE ou REAL.
- Résultat affiché en rouge si FAKE, en vert si REAL.
- Interface simple et responsive.

## Technologies utilisées
- Python / Flask
- scikit-learn (PassiveAggressiveClassifier)
- TF-IDF Vectorizer
- HTML / CSS

## Installation et lancement

1. Cloner le repository :
```bash
   git clone https://github.com/AbdelouahadOudraia/Detection-Fake-News-ML.git
```

2. Installer les dependances :
```bash
   pip install Flask scikit-learn pandas numpy
```

3. Lancer l'application :
```bash
   python Fake_News_Det.py
```

4. Ouvrir dans le navigateur :
```
   http://127.0.0.1:5000
```
