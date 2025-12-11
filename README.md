# 🌟 Analyse Comparative de la Mortalité : Azerbaïdjan et Norvège (1990)

Ce projet de démographie présente une analyse descriptive et comparative des données de mortalité et de population pour l'**Azerbaïdjan** et la **Norvège** pour l'année 1990. L'objectif est d'évaluer les différences de mortalité entre les deux pays en éliminant l'effet de la **structure par âge** de leurs populations.

Le rapport complet est disponible ici : [Rapport.pdf](TP1_Michel.pdf)

---

## 🎯 Objectif
Comparer les profils de mortalité de l'Azerbaïdjan et de la Norvège en 1990 pour :

* Identifier les différences de mortalité entre les deux pays
* Éliminer l'effet de la structure par âge des populations
* Appliquer des méthodes de standardisation directe et indirecte
* Extraire des conclusions démographiques robustes et exploitables

---

## 📊 Données

* Période : Année 1990
* Pays analysés : Azerbaïdjan, Norvège
* Variables :
  * Effectifs de population par groupe d'âge
  * Nombre de décès par groupe d'âge
  * Taux de mortalité spécifiques
* Populations de référence : Combinée (AZ+NO), Monde, Europe

---

## 🛠️ Outils utilisés

* Python 3
* Pandas, NumPy
* Matplotlib, Seaborn
* Jupyter Notebook

---

## 📂 Structure du projet

Analyse-Mortalite-Azerbaidjan-Norvege-1990/
│
├── README.md                    # Ce fichier
├── TP1_Michel.pdf              # Rapport complet d'analyse
├── TP1_Epidé.ipynb            # Notebook avec tous les calculs
├── data/                       # Données sources
│   ├── Données.xlsx
└── images/                     # Visualisations

---

## 🔬 Méthodologie d'Analyse

L'analyse a suivi la démarche suivante pour comparer les deux pays :

1.  **Taux Bruts de Mortalité (TBM)** : Un indicateur initial, trompeur en raison de la structure par âge.
2.  **Taux de Mortalité Spécifiques par Âge (ASMR)** : Comparaison de la mortalité par groupe d'âge.
3.  **Standardisation Directe (TMS)** : Utilisation de populations de référence (Combinée, Monde, Europe) pour obtenir des taux standardisés.
4.  **Standardisation Indirecte (RSM)** : Calcul des Ratios Standardisés de Mortalité.

![Image du Diagramme du flux d'analyse](images/Diagramme.png)

---

## 💡 Résultats Clés

### 1. Structure par Âge
* La population norvégienne est plus **vieillissante** que celle de l'Azerbaïdjan, ce qui explique le TBM initialement plus élevé en Norvège.

### 2. Taux Spécifiques par Âge (ASMR)
* [cite_start]L'**Azerbaïdjan** présente une mortalité plus élevée que la Norvège pour la majorité des groupes d'âge[cite: 133].
* [cite_start]La Norvège ne dépasse l'Azerbaïdjan qu'aux âges très avancés (80 ans et plus)[cite: 134].

![Image des Taux de Mortalité Spécifiques par Âge - Global (1990)](images/asmr_global.png)

### 3. Taux Standardisés (TMS)
* [cite_start]Une fois l'effet de la structure par âge éliminé, la mortalité est **significativement plus élevée en Azerbaïdjan** qu'en Norvège[cite: 154, 171].

![Image des Taux de Mortalité Standardisés (Réf. Combinée)](images/tms_ref_combinee.png)

---

## 💻 Code Source et Fichiers

* **Code** : Le script Python/Jupyter Notebook utilisé pour le nettoyage des données, les calculs et la génération des graphiques se trouve dans [CodeSource.ipynb](TP1_Epidé.ipynb).
* **Fichiers Sources** : Les données originales et les références de population sont dans le dossier `data/`.

---

## 👤 Auteur

Michel TCHATCHOUA - [Lien vers mon profil GitHub](https://github.com/MichelTCHATCHOUA)
