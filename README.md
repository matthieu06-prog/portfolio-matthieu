# portfolio-matthieu
Mon Portfolio Data Science

Bienvenue sur mon Portfolio Technique

Passionné par la data science, l'analyse de données, le machine learning et la modélisation mathématique. Vous trouverez ici un aperçu de mes principaux travaux, des modèles prédictifs complexes aux analyses géopolitiques et industrielles menées à partir de données réelles.

---

## Boîte à outils & Compétences

* **Languages & Modélisation :** Python, R, SQL, LaTeX, Java
* **Data Science & Machine Learning :** Scikit-Learn, Random Forest, Decision Trees, Logistic Regression, Clusturing (K-Means, CHD), ACP (Analyse en Composantes Principales), Pandas, NumPy
* **Visualisation & Business Intelligence :** Power BI, Streamlit

---

## Projets Majeurs

###  1. Classification Binaire de Pulsars (Dataset NASA HTRU2)
* **Objectif :** Automatiser la reconnaissance de pulsars (étoiles à neutrons en rotation rapide) au milieu d'un dataset fortement déséquilibré (90,8% de non-pulsars vs 9,2% de pulsars réels) mesurant des signaux et ondes cosmiques.
* **Stack Technique :** Python, Scikit-Learn (Random Forest, Decision Tree, Logistic Regression).
* **Méthodologie & Analyse :** Identification des critères les plus discriminants (notamment la variable `kurtosis_profile` et la `skewness` du signal). 
* **Résultats :** Excellentes performances globales avec des scores d'AUC supérieurs à 0,96 pour l'ensemble des modèles testés (Arbre de décision : 0,971 ; Régression logistique : 0,969). La Forêt Aléatoire est retenue comme modèle final pour sa capacité à maximiser la sensibilité globale.

###  2. Analyse des Conflits Armés Mondiaux par Clustering (UCDP GED Dataset)
* **Objectif :** Déterminer si les conflits mondiaux se regroupent naturellement selon la nature de la violence et leur intensité, de manière totalement agnostique à leur localisation géographique.
* **Stack Technique :** Python, K-Means, CHD (Classification Hiérarchique Descendante), ACP (Analyse en Composantes Principales).
* **Méthodologie & Analyse :** Prétraitement et feature engineering sur 385 918 événements et 49 variables (suppression des bruits, transformation logarithmique des mortalités, création d’un ratio de victimes civiles et standardisation). Réduction de dimension via une ACP (7 composantes majeures).
* **Résultats :** Convergence des algorithmes K-Means et CHD vers 6 profils / clusters de conflits hautement cohérents (validés par scores de silhouette et lisibilité géopolitique). L'étude prouve de manière mathématique que la nature d'un conflit et son intensité structurent les groupes bien plus que la simple proximité géographique.

###  3. Maintenance Prédictive par IA : Jumeau Numérique (Dataset NASA)
* **Objectif :** Prédire et détecter les défaillances critiques sur des composants industriels (roulements à billes) avant la rupture, en s'appuyant sur l'analyse vibratoire.
* **Stack Technique :** SolidWorks (Modélisation CAO / Jumeau numérique), Python / IA, MathJax (Formalisation des matrices vibratoires).
* **Méthodologie :** Fusion des dimensions géométriques exactes issues d'une modélisation CAO (SolidWorks) définissant la signature vibratoire théorique d'une pièce avec les données de capteurs réels de pannes (Dataset de la NASA).
* **Résultats :** Déploiement d'un modèle de classification atteignant **98,2% de Précision** et **96,5% de Rappel (Recall)** sur la matrice de confusion. Ce taux de rappel très élevé assure qu’aucune panne réelle n'échappe au système de maintenance prédictive.

###  4. Pivot Énergétique et Souveraineté de l'Union Européenne
* **Objectif :** Modéliser et évaluer l’impact macroéconomique du remplacement historique des flux de gaz russes (gazoducs) par le Gaz Naturel Liquéfié (GNL) américain sur le marché boursier européen (TTF).
* **Stack Technique :** Langage R (Calculs de corrélations), Power BI (Business Intelligence & Tableaux de bord), LaTeX.
* **Méthodologie :** Analyse de séries temporelles de flux énergétiques (2018-2026) et modélisation algorithmique des dépendances fournisseurs.
* **Résultats :** Formalisation mathématique d'un Taux de Remplacement Réel ($T_r \approx 0,48$) et d'un Indice de Dépendance critique envers le partenaire américain s’élevant à $88,24\%$. Conception d'un dashboard Power BI dynamique permettant le pilotage stratégique des indicateurs de souveraineté en période de forte volatilité des prix (pic historique à 130 €/MWh).
