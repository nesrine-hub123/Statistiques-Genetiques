# 🧬 Génétique des populations  

**Cours :** BIF-4002 — Statistiques génétiques : concepts et analyse  
**Université Laval — Hiver 2025**  
**Auteure :** Nesrine Imloul  

---

## 🧫 Contexte

Ce projet porte sur l’étude de la **diversité génétique et du polymorphisme moléculaire** au sein de populations.  
Les séquences analysées proviennent de gènes modèles (NRG, SXL et VERMILION), incluant des **outgroups** permettant l’analyse comparative.  
L’objectif principal est d’**évaluer la variabilité génétique intra- et inter-populations**, ainsi que d’estimer la structure génétique via des statistiques de population.

---

## 🎯 Objectifs

- Importer et aligner des séquences ADN multi-individus à l’aide de **DnaSP6**.  
- Calculer la diversité nucléotidique, le nombre de polymorphismes et la fréquence des haplotypes.  
- Évaluer les **tests neutres** (Tajima’s D, Fu & Li’s D*, F*) pour détecter la sélection.  
- Générer des graphiques et tableaux résumant les indices de diversité.

---

## ⚙️ Méthodologie

1. **Alignement des séquences** (`*.fas`) dans DnaSP6.  
2. Définition des populations et configuration des paramètres d’analyse.  
3. Calcul automatique des statistiques suivantes :
   - **S** (nombre de sites polymorphes)  
   - **π** (diversité nucléotidique)  
   - **θw** (diversité de Watterson)  
   - **Tajima’s D**, **Fu & Li D\***, **Fu & Li F\***  
4. Export des résultats et analyse comparative entre gènes.

---

## 📊 Résultats principaux

- Variabilité génétique significative observée dans les trois gènes.  
- Les gènes **SXL** et **VERMILION** montrent une diversité plus élevée.  
- Aucun signal fort de sélection directionnelle n’a été détecté selon Tajima’s D.  
- Corrélation entre la structure génétique et la taille des échantillons.

---

## 🧠 Logiciels utilisés

- **DnaSP 6** — analyses de polymorphisme moléculaire  
- **MEGA X** — alignement et visualisation  
- **Excel / R** — traitement et représentation graphique des résultats  

---

## 📁 Fichiers du dossier

- `NRG_wOUTGROUP.fas` — séquences du gène *NRG*  
- `SXL_wOUTGROUP.fas` — séquences du gène *SXL*  
- `VERMILION_wOUTGROUP.fas` — séquences du gène *VERMILION*  
- `alignement pops *.fas` — alignements des populations  
- `travail analyse de données de polymorphisme moléculaire2024.pdf` — rapport complet  
- `DnaSP6_Documentation_6.10-1.pdf` — documentation de référence  

---

*Projet académique — Université Laval, 2025*
