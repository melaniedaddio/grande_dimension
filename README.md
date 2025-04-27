# Prévision des Annulations de Réservations – Groupe INN Hotels

📌 **Description**  
Développement d'un modèle de machine learning pour prédire les annulations de réservations dans le groupe INN Hotels.  
L’objectif est d’optimiser le **F1-score** pour minimiser les erreurs de classification et améliorer la gestion des réservations.

---

📊 **Données**
- **Nombre d’observations** : 36 275
- **Nombre de variables** : 18
- **Variables influentes** :
  - Délai avant l’arrivée (`lead_time`)
  - Type de pension (`meal_plan`)
  - Segment de marché (`market_segment_type`)
- **Format des données** : CSV, avec des variables numériques et catégorielles

## Utilisation
Les principaux notebooks du projet :

## Résultats
- Comparaison de plusieurs modèles : Régression logistique, Forest, XGBoost.
- Optimisation des hyperparamètres  et sélection du meilleur modèle (XGBoost).
- Établissement du seuil optimal.

## Organisation du projet
```
annulation-reservations/
│── Projet_INNHotelsGroup.ipynb/               # Analyse Exploratoire, Traitement des données, Modélisation et Optimisation des hyper-paramètres
│── README.md                                  # Documentation
```
