# Projet d'Épidémiologie  
## Analyse de la Corrélation entre Consommation d'Alcool et Résultats Scolaires  

Ce projet vise à étudier la **corrélation entre la consommation d'alcool** et les **résultats en mathématiques** chez des élèves âgés de **15 à 22 ans**. L'objectif final est de **prédire leur note finale (G3)** en fonction de cette consommation.  

---

## Étapes du Projet  

### 1️⃣ **Qualification du Jeu de Données et Analyse Statistique Descriptive**  
- 🔎 **Exploration** du jeu de données pour évaluer sa qualité.  
- 📊 **Analyse descriptive** afin de mieux comprendre les tendances générales.  

### 2️⃣ **Visualisations**  
   -  Création de graphiques illustrant :  
   - La **répartition des notes**.  
   - La **consommation d'alcool**.  

### 3️⃣ **Analyse Factorielle des Correspondances Multiples (AFCM)**  
- Étude des liens entre les **variables catégorielles** pour identifier des associations pertinentes.  

### 4️⃣ **Modélisation par Régression Linéaire**  
   - Mise en place d'une **régression linéaire** pour prédire les notes finales en fonction de :  
   - La consommation d'alcool.  
   - Les absences.  
   - Les sorties.  

### 5️⃣ **Méthodes de Clustering (Non Supervisées)**  
   - Application de plusieurs algorithmes de clustering pour identifier des groupes d'élèves partageant des comportements similaires :  
   - **K-means**  
   - **Clustering hiérarchique**  
   - **GMM (Gaussian Mixture Models)**  

### 6️⃣ **Approches Supervisées**  
- Pour améliorer les prédictions des notes finales (G3), plusieurs modèles ont été testés :  
   -  **Random Forest**  
   -  **Réseau de Neurones**  
   -  **Deep Learning**  

⚠️ **Remarque importante :** Bien que ces méthodes offrent des capacités prédictives avancées, elles ne se sont pas révélées beaucoup plus efficaces en raison de la petite taille de l'échantillon. 
---

## Analyse des Résultats Graphiques  

###  **Distribution des notes finales (G3)**  
- La distribution est assez variée, avec une concentration notable autour des **notes moyennes** (entre 10 et 15). Il existe quelques élèves ayant des notes très faibles (proches de 0) ou très élevées (proches de 20), indiquant une disparité importante dans les performances académiques.  

###  **Impact de la consommation d'alcool en semaine (Dalc) sur les notes finales**  
- On observe une tendance selon laquelle les élèves consommant plus d'alcool en semaine ont tendance à obtenir des notes **légèrement plus faibles**. Toutefois, cette différence n'est pas extrêmement marquée, ce qui pourrait indiquer que d'autres variables influencent davantage les résultats scolaires.  

###  **Impact de la consommation d'alcool le week-end (Walc) sur les notes finales**  
- De manière similaire à la consommation en semaine, les élèves ayant une consommation d'alcool élevée le week-end semblent présenter des notes **légèrement inférieures**. Cependant, la variabilité reste importante, et la consommation d'alcool seule ne semble pas être un facteur déterminant unique.  

###  **Corrélation entre les absences et les notes finales**  
- Une tendance plus nette se dégage ici : les élèves ayant un grand nombre d'**absences** ont généralement des **notes plus faibles**. Ce résultat est logique et met en évidence l'importance de l'**assiduité scolaire** dans la réussite académique.  

---

##  Conclusion  
Les graphiques montrent que la **consommation d'alcool** a un impact **négatif modéré** sur les résultats scolaires, mais ce n'est pas le facteur prédominant. En revanche, le **nombre d'absences** semble être un facteur plus fortement corrélé aux performances académiques. Ces observations justifient l'exploration de modèles prédictifs complexes pour évaluer les interactions entre plusieurs variables.
