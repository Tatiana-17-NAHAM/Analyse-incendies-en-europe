![Statut](https://img.shields.io/badge/🔥_Projet-Actif-EA4C4C.svg)

# Analyse-incendies en Europe
Analyse des données d'incendies en Europe (2006-2025) avec Python — Visualisation, modélisation et interprétation.

Ce projet explore les incendies forestiers en Europe entre 2006 et 2025, en mettant en lumière l'évolution de la surface brûlée, le nombre d'incendies et leur corrélation.  
Il utilise des données réelles et propose des visualisations interactives pour dégager des tendances.
#   📁 Données utilisées

- Source : [EFFIS – European Forest Fire Information System](https://effis.jrc.ec.europa.eu/)
- Données annuelles de 2006 à 2025
- Colonnes : `Year`, `BurnedArea` (en hectares), `"NumberOfFires` (nombre d'incendies)
# 🎯 Objectifs

- Étudier l’évolution des incendies en Europe entre 2006 et 2025
- Visualiser la surface totale brûlée et le nombre d’incendies
- Analyser les ratios récents (2021–2025) d'incendies par surface
- Interpréter les anomalies : baisse en 2022, hausse en 2024/2025
- Identifier les liens entre fréquence et intensité des feux
  
# 🛠️ Technologies utilisées

- `Python`
- `Pandas`, `Matplotlib`, `Seaborn`
- Optionnel : `Scikit-learn` pour régression simple

 # 📊 Principales visualisations

- **Courbe de la surface brûlée par an**  
- **Barplot du nombre d’incendies**
- **Corrélation entre feux et hectares brûlés**
- **Indicateur d’intensité : Feux pour 1 000 ha

# 🚀 Résultats clés

- 📉 **2022** : Faible nombre d’incendies mais grande surface brûlée  
  → Incendies probablement plus vastes et moins maîtrisés

- 📈 **2024 & 2025** : Hausse du nombre d’incendies pour une surface globalement stable  
  → Feux plus fréquents mais peut-être mieux contenus

- ⚖️ **2021** : Ratio stable (~7 incendies pour 1 000 ha)  
  → Sert de référence pour les comparaisons

- 🔁 Corrélation modérée entre **nombre de feux** et **surface brûlée**  
  → Plus d’incendies ne signifie pas toujours plus de surface touchée

- 📊 **Modélisation par régression linéaire** :
  - Mise en évidence d’une tendance linéaire dans l’évolution des surfaces brûlées
  - **🔥 Prédiction surface brûlée en 2025 : 30 158 hectares*
