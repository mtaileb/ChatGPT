
### Analyse de la consommation d'énergie mondiale

**Objectif :** Explorer et analyser les données de consommation d'énergie pour comprendre les tendances, les relations et formuler des recommandations stratégiques.

---

### Jeu de données

**Nom : Global Energy Consumption Dataset**  
- **Source :** Kaggle ([Global Energy Consumption Dataset](https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather))  
- **Taille :** Plusieurs centaines de milliers de lignes.  
- **Description :**  
  - Contient des informations sur la consommation d'énergie, la génération d'énergie, les prix, et des variables météorologiques.
  - Colonnes principales :  
    - `datetime`, `energy_consumption`, `energy_generation`, `wind_generation`, `solar_generation`, `price`, `temperature`, `humidity`, `country`.

---

### Instructions

#### 1. Chargement et exploration des données

1. Charger le fichier Zip et afficher les premières lignes pour examiner la structure des données.  
2. Identifier le nombre de lignes et de colonnes, et vérifier les types de données pour chaque colonne.  
3. Rechercher les valeurs manquantes et proposer une stratégie pour les traiter.  

---

#### 2. Nettoyage des données

4. Supprimer les doublons si présents dans la colonne `datetime`.  
5. Remplir les valeurs manquantes dans des colonnes critiques comme `energy_consumption` ou `temperature`.  
6. Vérifier et corriger les anomalies éventuelles dans les colonnes `price` ou `energy_generation` (par exemple, des valeurs négatives ou nulles).

---

#### 3. Analyse descriptive

7. Calculer la consommation totale et la génération totale d'énergie pour l'ensemble des pays.  
8. Analyser la répartition des sources d'énergie (`wind_generation`, `solar_generation`, etc.).  
9. Identifier les pays ayant les consommations d'énergie les plus élevées.  
10. Calculer la consommation moyenne d'énergie par pays et par mois.  
11. Calculer les prix moyens de l'énergie (`price`) par pays.  

---

#### 4. Analyse temporelle

12. Ajouter des colonnes pour `Year`, `Month`, et `Day` en se basant sur la colonne `datetime`.  
13. Analyser les tendances annuelles de consommation d'énergie.  
14. Identifier les mois avec les consommations d'énergie les plus élevées (par exemple, en hiver).  
15. Visualiser les variations de la génération solaire et éolienne au fil du temps.  
16. Analyser les variations des prix de l'énergie au fil des années.  

---

#### 5. Analyse géographique

17. Identifier les pays où la génération solaire ou éolienne est la plus importante.  
18. Analyser les pays où les prix de l'énergie sont les plus élevés.  
19. Visualiser la répartition géographique de la consommation d'énergie par pays.  
20. Créer une carte indiquant les pays qui utilisent majoritairement des énergies renouvelables.  

---

#### 6. Analyse des relations

21. Étudier la corrélation entre `temperature` et `energy_consumption`.  
22. Identifier si la génération d'énergie renouvelable (éolienne ou solaire) a un impact sur les prix de l'énergie.  
23. Analyser la relation entre `energy_generation` et `energy_consumption` (les pays génèrent-ils autant qu'ils consomment ?).  
24. Étudier l'impact de la météo (`temperature`, `humidity`) sur la consommation d'énergie.  

---

#### 7. Analyse avancée

25. Réaliser une segmentation des pays en fonction de leur dépendance énergétique (rapport entre consommation et génération).  
26. Calculer l'efficacité des énergies renouvelables par pays (`wind_generation` + `solar_generation` / `energy_generation`).  
27. Identifier les périodes où les prix de l'énergie sont les plus élevés et les comparer avec les tendances de consommation.  
28. Analyser les variations saisonnières de consommation pour les pays ayant des climats très différents.  

---

### Visualisations

29. Créer un heatmap pour montrer les corrélations entre `energy_consumption`, `energy_generation`, `price`, et les variables météorologiques.  
30. Afficher un histogramme des prix de l'énergie par pays.  
31. Créer un scatter plot pour visualiser la relation entre la consommation d'énergie et la température.  
32. Créer un graphique en ligne pour visualiser les variations de consommation d'énergie au fil des années.  
33. Réaliser un bar plot pour comparer la consommation d'énergie par source (`wind`, `solar`, etc.) dans les principaux pays.  

---

### Insights métier

34. Identifier les pays qui peuvent devenir des leaders dans les énergies renouvelables.  
35. Recommander des stratégies pour réduire les coûts de l'énergie dans les pays où les prix sont élevés.  
36. Analyser les pays qui dépendent fortement des importations d'énergie et recommander des solutions pour réduire leur dépendance.  
37. Proposer des recommandations pour optimiser la consommation d'énergie pendant les périodes de pointe (exemple : hiver).  
38. Identifier les opportunités pour développer davantage les énergies renouvelables dans les pays où leur part est faible.  

---

### Livrables attendus

1. Un notebook contenant toutes les analyses mentionnées ci-dessus.  
2. Des visualisations claires pour appuyer les analyses.  
3. Une présentation synthétique des principaux insights tirés des données, accompagnée de recommandations stratégiques.  
