# Classification d’Images avec Fashion MNIST – CNN en Keras

Ce projet illustre l'utilisation d'un réseau de neurones convolutif (CNN) pour classer des images de vêtements provenant du dataset **Fashion MNIST**. Le projet est développé avec **Python** et **Keras (TensorFlow backend)**.

## 📊 Dataset

- **Fashion MNIST** est un ensemble de données composé de 70 000 images en niveaux de gris (28x28 pixels) représentant des articles de mode répartis en 10 catégories.
- Source : [Fashion MNIST – Zalando Research](https://github.com/zalandoresearch/fashion-mnist)

## 🧠 Objectif

Construire un modèle de deep learning capable de prédire la catégorie d’un vêtement à partir de son image.

---

## 📌 Étapes du Projet

### 1. Importer les Bibliothèques Nécessaires
Chargement des modules nécessaires : `numpy`, `matplotlib`, `tensorflow.keras`, etc.

### 2. Charger et Visualiser les Données
Utilisation de `tensorflow.keras.datasets.fashion_mnist` pour charger les données, suivie d'une visualisation avec `matplotlib`.

### 3. Prétraiter les Données
- Normalisation des pixels entre 0 et 1
- Reshape des images pour qu'elles aient une forme compatible avec les CNN

### 4. Créer le Modèle CNN avec Keras
Architecture typique :
- Couches `Conv2D` + `MaxPooling2D`
- `Flatten` et `Dense` en sortie avec `softmax`

### 5. Compiler et Entraîner le Modèle
Utilisation de l’optimiseur `Adam`, fonction de perte `sparse_categorical_crossentropy` et métrique `accuracy`.

### 6. Évaluer le Modèle
Évaluation sur l’ensemble de test et affichage de la précision.

### 7. Faire des Prédictions
Génération des prédictions et affichage de quelques résultats.

---

## 📁 Arborescence du Projet
├── fashion_mnist_cnn.ipynb
├── README.md
└── requirements.txt




