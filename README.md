# Prédiction du Diabète – Projet Data Science

## Description du projet
Ce projet a pour objectif de prédire si une patiente est atteinte de diabète à partir de mesures médicales.  
Le dataset provient du **National Institute of Diabetes and Digestive and Kidney Diseases** et est disponible au format CSV sur **Kaggle**.  

Tous les patients inclus sont des femmes d’au moins 21 ans et d’origine indienne Pima.

## Contenu du dataset
Le dataset contient plusieurs variables prédictives et une variable cible `Outcome` :

- **Pregnancies** : nombre de grossesses  
- **Glucose** : concentration de glucose dans le sang  
- **BloodPressure** : pression artérielle  
- **SkinThickness** : épaisseur du pli cutané  
- **Insulin** : taux d’insuline  
- **BMI** : indice de masse corporelle  
- **DiabetesPedigreeFunction** : score génétique  
- **Age** : âge de la patiente  
- **Outcome** : 0 si la patiente n’a pas de diabète, 1 si elle en a  

## Objectif
Créer un modèle de **classification binaire** capable de prédire la présence ou l’absence de diabète à partir des mesures médicales.

## Étapes du projet
1. **Présentation des données** : description et aperçu du dataset  
2. **Exploration et compréhension des données (EDA)** :  
   - Analyse des distributions des variables  
   - Visualisation des relations avec `pairplot` et heatmap  
   - Détection des valeurs manquantes et aberrantes  
3. **Préparation des données** et **Modélisation** :  
   - Gestion des valeurs manquantes ou aberrantes  
   - Normalisation ou standardisation si nécessaire  
   - Séparation en ensembles d’entraînement et de test
   - entraînement de modèles de classification k-nn
5. **Évaluation du modèle** : précision, rappel, F1-score, matrice de confusion, ROC-AUC  
 

## Technologies et bibliothèques
- **Python**  
- **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**  
- **Scikit-learn**  

## Licence
Le dataset est disponible publiquement sur Kaggle. Le code et le README sont libres d’usage

## Auteur

Rayan FRAJ
