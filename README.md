# 📊 Impact de la croissance démographique sur la croissance économique en France (1960–2023)

![GitHub last commit](https://img.shields.io/github/last-commit/username/repo?style=flat-square&color=blue)
![Status](https://img.shields.io/badge/Statut-Terminé-brightgreen?style=flat-square)
![Made with](https://img.shields.io/badge/Réalisé%20avec-Python%20%26%20Excel-orange?style=flat-square)
![License](https://img.shields.io/badge/License-Académique-blueviolet?style=flat-square)

---

## 📑 Table des matières
- [🎯 Objectif](#-objectif)
- [📂 Sources de données](#-sources-de-données)
- [🛠️ Méthodologie](#️-méthodologie)
- [📈 Résultats clés](#-résultats-clés)
- [✅ Conclusion](#-conclusion)
- [📚 Références](#-références)

---

## 🎯 Objectif

Évaluer si la **croissance démographique favorise la croissance économique en France** et identifier les **principaux déterminants du PIB par habitant** sur la période 1960–2023.

---

## 📂 Sources de données

- **Base Excel** : `data_base.xlsx`  
- **Notebook Python** : `Projet_THE_Ange & Roumbo_Philippe.ipynb`  
- **Rapport complet** : `Rapport_Projet_THE.pdf`  
- **Données officielles** : INSEE, Banque mondiale, OCDE, Eurostat, PNUD  

---

## 🛠️ Méthodologie

1. **Analyse exploratoire des données (EDA)**  
   - Statistiques descriptives du PIB/habitant, de l’inflation, de l’épargne, du solde commercial.  
   - Mise en contexte historique : chocs pétroliers, crise des subprimes, Covid-19.  
   - Corrélations clés (par exemple, PIB/FBCF = 82 %).  

2. **Modèle de régression linéaire**  
   - R² ajusté = 81 %  
   - Résidus approximativement normaux, présence de multicolinéarité.  
   - Variables significatives :  
     - FBCF (+), Épargne (+)  
     - Croissance démographique (–), Emploi (–), Impôts (–).  

3. **Modélisation en séries temporelles (SARIMAX)**  
   - Modèle final : **SARIMAX(1,0,3)** avec FBCF et épargne en variables exogènes.  
   - Meilleure gestion des chocs que la régression linéaire.  
   - Performance : R² ≈ 81 % (train), 54 % (test).  

---

## 📈 Résultats clés

- 📉 **Croissance démographique** : effet négatif ou non significatif sur le PIB par habitant.  
- 📊 **FBCF (investissement)** : principal moteur de la croissance.  
- 💰 **Épargne** : effet positif mais modéré.  
- ⚖️ **Impôts & emploi** : effets négatifs, suggérant des rigidités structurelles.  
- 🔄 **Chocs économiques** : impact important, partiellement absorbé par la dynamique SARIMAX.  

---

## ✅ Conclusion

La croissance démographique **n’apparaît pas comme un déterminant central de la croissance économique en France**.  
Ce sont plutôt **l’investissement, l’épargne et l’innovation** qui constituent les principaux moteurs de la croissance à long terme.

Les politiques publiques devraient donc prioriser :  
- 🚀 Le soutien à l’investissement productif,  
- 📈 La promotion de l’innovation et de la compétitivité,  
- 🌍 Une intégration efficace des flux migratoires.  

---

## 📚 Références

- [INSEE](https://www.insee.fr)  
- [Banque mondiale](https://data.worldbank.org)  
- [OCDE](https://data.oecd.org)  
- [PNUD](https://hdr.undp.org)  
- [Eurostat](https://ec.europa.eu/eurostat)  

---

👤 **Auteurs** :  
- Philippe Roumbo *(M1 BIDABI)*  
- Ange-Paul Emmanuel THE *(M1 BIDABI)*  
Université Sorbonne Paris Nord — 2024/2025
