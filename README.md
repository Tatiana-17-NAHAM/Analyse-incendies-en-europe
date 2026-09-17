![Statut](https://img.shields.io/badge/🔥_Projet-Actif-EA4C4C.svg)
![Auteur](https://img.shields.io/badge/Auteur-Tatiana%20SANGUEAL%20NAHAM-blue)

# 🗺️ Sommaire

- [📁 Données utilisées](#-données-utilisées)
- [🎯 Objectifs](#-objectifs)
- [🛠️ Technologies utilisées](#-technologies-utilisées)
- [📊 Principales visualisations](#-principales-visualisations)
- [📈 Résultats clés](#-résultats-clés)
- [🧾 Conclusion](#-conclusion)
- [👩‍💻 Réalisé par](Tatiana SANGUEAL NAHAM)
- 🔗 ([https://www.linkedin.com/in/ton-lien-linkedin](https://www.linkedin.com/in/tatiana-sangu%C3%A9al-naham-050170178/))


# Analyse-incendies en Europe
Analyse des données d'incendies en Europe (2006-2025) avec Python — Visualisation, modélisation et interprétation.

Ce projet explore les incendies forestiers en Europe entre 2006 et 2025, en mettant en lumière l'évolution de la surface brûlée, le nombre d'incendies et leur corrélation.  
Il utilise des données réelles et propose des visualisations interactives pour dégager des tendances.
#   📁 Données utilisées

- Source : [EFFIS – European Forest Fire Information System](https://effis.jrc.ec.europa.eu/)
- Données annuelles de 2006 à 2025
- Colonnes : `Year`, `BurnedArea` (en hectares), `"NumberOfFires` (nombre d'incendies)
# 🎯 Objectifs

- Nettoyer et structurer les données brutes
- Visualiser l'évolution de la surface brûlée et du nombre d'incendies
- Mesurer la corrélation entre nombre d'incendies et surface brûlée
- Modéliser la tendance par régression linéaire
- Interpréter les résultats et identifier des pistes d'approfondissement
  
# 🛠️ Technologies utilisées

- `Python`
-  Pandas, Matplotlib, Seaborn, Scikit-learn, SciPy
- [📘 Voir le notebook Jupyter](./Analyse%20incendies%20en%20europe%20%282006-2025%29%20%282%29.ipynb)






 # 📊 Principales visualisations

 # 🔥 Surface totale brûlée en Europe (2006–2025)

![Surface brûlée](surface_brulee_europe_2006_2025.png)

*Tendance de la surface brûlée par an, avec la droite de régression linéaire : hausse globale sur la période, malgré une forte variabilité d'une année à l'autre.*

# 🔄 Corrélation entre nombre d'incendies et surface

![Corrélation](correlation_incendies_surface_2006_2025.png)

Coefficient de corrélation de Pearson : **r = 0,89** (corrélation forte et significative).

# 📊 Nombre d'incendies de forêt par an

![Nombre d'incendies](nb_incendies_europe_2006_2025.png)

# ⚖️ Surface brûlée moyenne par incendie

![Ratio ha/incendie](nb_feux_par_1000ha_2006_2025.png)

# 📈 Évolution de la surface brûlée (tendance / régression linéaire)

![Évolution](evolution_surface_brulee_2006_2025.png)

# 🚀 Résultats clés

- Tendance haussière de la surface brûlée sur la période, confirmée par régression linéaire (scikit-learn)
- Corrélation forte entre nombre d'incendies et surface brûlée (r = 0,89)
- Les années 2019 et 2022 se distinguent par des incendies individuellement plus destructeurs (ratio ha/incendie élevé), pas seulement plus nombreux

# 🎨 Galerie des visualisations

![Surface vs incendies](surface_vs_incendies_2006_2025.png)

# 🧠 À retenir

La hausse de la surface brûlée ne s'explique pas uniquement par un nombre croissant d'incendies : certaines années présentent des incendies individuellement plus intenses, cohérent avec un rôle probable des conditions climatiques (sécheresse, vagues de chaleur).

# 🧾 Conclusion

Cette analyse met en évidence une tendance haussière et une forte variabilité interannuelle des incendies en France sur la période 2006–2025. Des travaux complémentaires croisant ces données avec des indicateurs climatiques permettraient de mieux isoler l'effet du changement climatique de la variabilité naturelle.

📓 [Voir le notebook complet](./Analyse%20incendies%20en%20europe%20%282006-2025%29%20%282%29.ipynb)


🧑‍💻 *Projet réalisé par Tatiana SANGUEAL NAHAM*  
🔗 [LinkedIn]([https://www.linkedin.com/in/ton-lien-linkedin](https://www.linkedin.com/in/tatiana-sangu%C3%A9al-naham-050170178/))


