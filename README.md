 Projet Machine Learning – Qualité de l’Eau

## 🟢 Contexte
Ce projet vise à prédire la **potabilité de l’eau** à partir de paramètres physico-chimiques.  
La qualité de l’eau est un enjeu majeur pour la **santé publique et l’environnement**, particulièrement en Afrique.

## 📊 Dataset
- Contient des mesures comme : pH, dureté, solides dissous, conductivité, sulfate, etc.  
- La variable cible : `Potability` (1 = potable, 0 = non potable)  
- Valeurs manquantes remplacées par la moyenne.

## 🛠️ Méthodologie
1. Prétraitement des données (remplacement des valeurs manquantes)  
2. Division en **train (80%) / test (20%)**  
3. Modèles entraînés :
   - **Random Forest**
   - **Régression logistique**
4. Évaluation avec :
   - Accuracy
   - Matrice de confusion

## 📈 Résultats
- **Random Forest** : meilleur modèle (meilleure capacité à capturer les relations complexes)
- Accuracy : ~0.7 (exemple)
- Matrice de confusion : permet d’analyser les erreurs de classification

## 🔍 Interprétation
- Les paramètres les plus influents sur la potabilité de l’eau peuvent être identifiés grâce à Random Forest.  
- Ces informations peuvent guider **les ONG, entreprises et services de l’environnement** pour mieux gérer la qualité de l’eau.

## 💡 Conclusion
Ce projet montre que le **Machine Learning appliqué à l’environnement** est une méthode efficace pour :
- Surveiller la qualité de l’eau
- Prévenir les risques sanitaires
- Aider à la décision pour les acteurs de la santé et de l’agro-environnement.

## 📂 Fichiers inclus
- `water_potability.csv` : dataset  
- `notebook.ipynb` : notebook avec le code complet et visualisations

## ⚡ Usage
1. Cloner le dépôt :  
   ```bash
   git clone <URL_DU_REPO>
