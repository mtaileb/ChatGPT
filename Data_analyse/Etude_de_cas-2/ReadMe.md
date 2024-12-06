
### Analyse des ventes d'une entreprise internationale de grande distribution

**Objectif :** Mener une analyse approfondie des données de vente pour identifier des tendances, des relations, et formuler des recommandations stratégiques.

---

### Actions d'analyse

#### Chargement et exploration des données

1. Charger le fichier Sample_Superstore.zip (contenant le CSV) et afficher les premières lignes pour examiner la structure des données.
2. Identifier le nombre de lignes et de colonnes du dataset.
3. Vérifier les types de données pour chaque colonne et corriger les incohérences éventuelles.
4. Rechercher les valeurs manquantes et proposer une stratégie pour les traiter.

---

#### Nettoyage des données

5. Supprimer les doublons dans les colonnes comme `Order ID` et `Customer ID`.
6. Corriger les valeurs mal orthographiées dans les colonnes `Region` ou `Category` si nécessaire.
7. Remplir les valeurs manquantes dans les colonnes critiques comme `Profit` ou `Discount`.

---

#### Analyse descriptive

8. Calculer les ventes totales (`Sales`), le profit total (`Profit`), et la quantité totale de produits vendus (`Quantity`).
9. Identifier les produits les plus vendus et les moins vendus.
10. Analyser les catégories (`Category`) et sous-catégories (`Sub-Category`) pour déterminer lesquelles génèrent le plus de ventes et de profits.
11. Identifier les clients qui réalisent les dépenses les plus élevées.
12. Calculer le ratio moyen de profit par vente (`Profit` / `Sales`) pour évaluer la rentabilité.

---

#### Analyse temporelle

13. Ajouter des colonnes `Year` et `Month` en se basant sur la colonne `Order Date` pour faciliter l’analyse temporelle.
14. Analyser les ventes totales par année et par mois.
15. Identifier les périodes où les ventes et les profits sont les plus élevés.
16. Visualiser les tendances temporelles des ventes et des profits.

---

#### Analyse géographique

17. Identifier les États (`State`) avec les ventes et les profits les plus élevés.
18. Calculer la moyenne des ventes par région (`Region`) pour déterminer les régions les plus performantes.
19. Visualiser les ventes et les profits par région sous forme de carte.

---

#### Analyse des relations

20. Étudier la corrélation entre les variables numériques comme `Sales`, `Profit`, `Discount`, et `Quantity`.
21. Identifier l’impact des remises (`Discount`) sur les profits.
22. Analyser si les produits avec une quantité élevée (`Quantity`) ont un impact sur la rentabilité.

---

#### Analyse des segments et clients

23. Identifier les segments de clients (`Segment`) qui génèrent le plus de profits.
24. Analyser le comportement des clients par région en termes de ventes et de profits.
25. Réaliser une segmentation des clients en fonction de leurs dépenses totales.

---

### Livrables attendus

1. Un notebook contenant toutes les analyses ci-dessus.  
2. Des visualisations claires et informatives (histogrammes, cartes, scatter plots, heatmaps).  
3. Une synthèse des insights tirés des données et des recommandations pour améliorer les performances de l'entreprise.  
