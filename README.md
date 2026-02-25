# 📊 Projet Big Data 

**PIGIER BÉNIN | Master Intelligence Artiffielle et Big data **

> Projet d'examen réalisé dans le cadre du module *Projet Big Data*, sous la direction du Dr. BABATOUNDE Moctard Olouladé.

---

## 📁 Contenu du dépôt

```
📦 Projet_Big_Data/
├── 📓 projet1_enquete_marche.ipynb     → Analyse de l'enquête de marché (pandas, scikit-learn)
├── 📓 projet2_spark_retail.ipynb       → Analyse Big Data avec Apache Spark
├── 📊 enquête.xlsx                     → Données de l'enquête (123 répondants, 29 variables)
├── 📄 retailsale.csv                   → Données retail (1 033 434 transactions)
└── 📝 README.md                        → Ce fichier
```

---

## 🎯 Présentation des deux projets

### Projet 1 — Analyse d'une enquête de marché

Une entreprise locale souhaite lancer une activité de vente de plats jetables. Une enquête terrain a été conduite auprès de **123 professionnels** de la restauration au Bénin.

**Ce qui a été réalisé :**
- Nettoyage et harmonisation des données (valeurs manquantes, encodage)
- Analyse exploratoire : types d'activité, usages actuels, préférences produit
- Analyse de la sensibilité au prix et de l'intention d'achat
- Segmentation clients par K-Means (3 segments identifiés)
- Recommandations stratégiques sur le produit, le prix et la logistique

**Stack technique :** `pandas` · `numpy` · `matplotlib` · `seaborn` · `scikit-learn`

---

### Projet 2 — Analyse Big Data des ventes retail avec Apache Spark

Analyse d'un jeu de données de ventes en détail contenant **plus d'un million de transactions** (1 033 434 lignes) issues de 107 magasins et 324 produits, sur la période janvier–mars 2017.

**Ce qui a été réalisé :**
- Chargement et prétraitement avec Apache Spark 4.0
- Analyse exploratoire : performances par produit, par magasin, temporelle
- Étude de l'impact des promotions sur les ventes
- Modélisation prédictive : Régression Linéaire vs Random Forest
- Recommandations opérationnelles (prix, stock, promotions)

**Stack technique :** `PySpark 4.0` · `pandas` · `matplotlib` · `seaborn` · `Spark MLlib`

---

## ▶️ Comment exécuter les notebooks

### Option 1 — Google Colab *(recommandé)*

1. Ouvrir [Google Colab](https://colab.research.google.com)
2. Importer le notebook souhaité via *Fichier → Importer le notebook*
3. Uploader le fichier de données correspondant quand le notebook le demande
4. Exécuter les cellules dans l'ordre (`Ctrl + F9` pour tout exécuter)

> ⚠️ Pour le Projet 2, Colab installe automatiquement PySpark via `!pip install pyspark`. Prévoir quelques minutes pour l'installation.

### Option 2 — En local

```bash
# 1. Cloner le dépôt
git clone https://github.com/Anjorin007/Projet_Big_Data.git
cd Projet_Big_Data

# 2. Installer les dépendances
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
pip install pyspark  # pour le Projet 2 uniquement

# 3. Lancer Jupyter
jupyter notebook
```

---

## 📌 Résultats clés

| Projet | Insight principal |
|--------|------------------|
| Projet 1 | 100 % des répondants utilisent déjà des emballages jetables — marché mature et réceptif |
| Projet 1 | 98,4 % d'intention d'achat positive — fort potentiel de lancement |
| Projet 2 | Les promotions n'améliorent **pas** les ventes moyennes (0,545 avec promo vs 0,599 sans) |
| Projet 2 | Le prix est la variable la plus influente sur les ventes (importance : 33,7 %) |
| Projet 2 | Régression linéaire : RMSE = 2,50 — R² = 0,173 (meilleur modèle) |

---

## 👤 Auteur

**DRAMANE Hamzath**
Master Intelligence Articifielle et Big data — PIGIER BÉNIN
Promotion 2025–2026

---

## 📧 Enseignant

**Dr. BABATOUNDE Moctard Olouladé**
b.oloulade@outlook.com | b.oloulade@whut.edu.cn
