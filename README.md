# Prévision des Annulations de Réservations – Groupe INN Hotels

📌 **Description**  
Développement d'un modèle de machine learning pour prédire les annulations de réservations dans le groupe INN Hotels.  
L’objectif est d’optimiser le **F1-score** pour minimiser les erreurs de classification et améliorer la gestion des réservations.

---

📊 **Données**
- **Nombre d’observations** : 36 275
- **Nombre de variables** : 18
- **Variables influentes** :
  - `lead_time` : Délai avant l’arrivée
  - `meal_plan` : Type de pension
  - `market_segment_type` : Segment de marché
- **Format des données** : Fichier CSV contenant des variables numériques et catégorielles

---

⚙️ **Utilisation**
Les principaux notebooks du projet :
- Analyse exploratoire des données
- Traitement des données (encodage, gestion des valeurs manquantes)
- Modélisation avec plusieurs algorithmes
- Optimisation des hyperparamètres pour améliorer les performances

---

📈 **Résultats**
- 📊 Comparaison de plusieurs modèles : **Régression logistique**, **Random Forest**, **XGBoost**
- 🏆 Sélection du meilleur modèle : **XGBoost** après optimisation des hyperparamètres
- 🎯 Définition du **seuil de classification optimal** pour maximiser le F1-score

