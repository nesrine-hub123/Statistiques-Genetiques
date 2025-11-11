# 🌿  Analyse phylogénétique

**Cours :** BIF-4002 — Statistiques génétiques : concepts et analyse  
**Université Laval — Hiver 2025**  
**Auteure :** Nesrine Imloul  

---

## 🔬 Contexte

Ce projet porte sur la **reconstruction phylogénétique** à partir de séquences d’ADN.  
L’objectif est d’analyser les **relations évolutives entre différentes populations ou espèces**, en comparant les séquences de gènes homologues et en utilisant un **groupe externe** pour enraciner les arbres.

Cette approche permet de mieux comprendre les liens de parenté, les événements de divergence et les modèles d’évolution moléculaire.

---

## 🎯 Objectifs

- Aligner les séquences nucléotidiques et identifier les régions homologues.  
- Construire des **arbres phylogénétiques** à l’aide de méthodes statistiques robustes.  
- Évaluer la **cohérence topologique** des arbres obtenus.  
- Comparer différentes méthodes d’inférence (NJ, ML, MP, etc.).

---

## ⚙️ Méthodologie

1. **Préparation des séquences**
   - Importation des séquences en format FASTA.  
   - Ajout d’un **groupe externe** (voir `groupe_externe.txt`) pour l’enracinement.  

2. **Alignement**
   - Alignement multiple des séquences avec **ClustalW / MUSCLE**.  

3. **Construction des arbres**
   - Méthode de **Neighbor-Joining (NJ)** pour une première topologie.  
   - Validation par **Maximum Likelihood (ML)** et **Bootstrap**.  
   - Analyse sous **MEGA X** ou **PhyML**.

4. **Visualisation et Interprétation**
   - Observation des regroupements par espèce/population.  
   - Interprétation des distances évolutives et de la robustesse des branches.

---

## 📈 Résultats

- Les arbres obtenus montrent une bonne séparation entre les groupes internes et le groupe externe.  
- Les valeurs de **bootstrap > 80 %** confirment la stabilité de la majorité des clades.  
- Les méthodes NJ et ML donnent des topologies similaires, validant la cohérence des données.  

---

## 🧠 Logiciels utilisés

- **MEGA X** — alignement et inférence phylogénétique  
- **ClustalW / MUSCLE** — alignement multiple des séquences  
- **PhyML** — estimation par maximum de vraisemblance  
- **FigTree** — visualisation des arbres  

---

## 📁 Fichiers du dossier

- `Devoir2.html` — visualisation interactive de l’arbre obtenu  
- `Phylogénétique_BIF4002.pdf` — rapport complet du projet  
- `groupe_externe.txt` — séquence du groupe externe utilisé pour l’enracinement  

---

*Projet académique — Université Laval, 2025*
