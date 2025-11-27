# 📁 Projet Data Science

Bienvenue sur ma page projet.  
Vous trouverez ici mon premier projet complet en modélisation et machine learning, que je continuerai à enrichir au fur et à mesure.

---

# 🔹 Prédiction d’Octroi de Prêt Bancaire  
**IAE Montpellier – 2025**

### 🎯 Objectif du projet
Construire un modèle de machine learning capable de prédire la probabilité qu’un prêt bancaire soit encaissé (remboursé) ou non.  
Ce modèle a pour objectif d’aider à la prise de décision en gestion du risque, un enjeu clé dans le secteur bancaire.

### 🗂️ Contexte
Les données fournies étaient **fortement déséquilibrées**, ce qui complexifie la modélisation.  
La priorité était donc d’améliorer le **rappel** (recall) sur la classe des défauts de paiement, critique pour la banque.

### 🛠️ Méthodologie
- Analyse exploratoire et nettoyage des données  
- Gestion du déséquilibre avec **SMOTE**  
- Encodage + standardisation  
- Construction d’un pipeline complet  
- Comparaison de plusieurs modèles :
  - Régression Logistique  
  - Random Forest  
  - Gradient Boosting  
- Optimisation d’hyperparamètres  
- Évaluation avec :
  - F1-score  
  - AUC-ROC  
  - Matrice de confusion  

### 📊 Résultats
- Le modèle **Gradient Boosting ** offre le meilleur compromis entre rappel et précision  
- Amélioration du score sur la classe minoritaire grâce à SMOTE  
- Visualisations : importance des variables, courbe ROC, matrices de confusion

---

# 🌐 Démo : Application Streamlit
Vous pouvez tester le modèle directement ici :

👉 **[🎛️ Lancer l’application Streamlit](https://predictionoctroipretbancaire.streamlit.app)**

L’application permet de saisir les caractéristiques d’un client et de prédire la probabilité d’encaissement du prêt ou de télécharger un fichier csv comportant les mêmes caractérisqtiques.

---

# 🔗 Liens associés
- 📦 **[Code source GitHub ](https://github.com/samiramamanesidi2050-lgtm/Prediction_octroi_pret_bancaire)** 
- 📄 **[Notebook d’analyse](https://github.com/samiramamanesidi2050-lgtm/Prediction_octroi_pret_bancaire/blob/main/prediction_octroi_pret_bancaire.ipynb)**  

---

Merci pour votre visite !  
D’autres projets seront ajoutés prochainement.
