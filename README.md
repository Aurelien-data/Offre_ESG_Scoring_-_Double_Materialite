# ESG Scoring & Double matérialité
**Analyse ESG - Dataiku -- Python -- Power BI**

## Objectif du projet
Ce projet vie à **analyser, structurer et restituer la performance ESG** d'un portefeuille d'entreprises à travers une aprroche **data-driven**, combinant:

- Analyse exploratoire (EDA) en Python
- Scoring ESG et segmentation non supervisée
- Analyse de la **Double matérialité** (performance ESG vs risque financier)
- Restitution décisionnelle via **Power BI**

L'objectif final est de fournir une **lecture stratégique claire**:
> *où concentrer les efforts ESG, quels profils présentent un risque latent, et quels leviers activer.*

---

## Stack & outils utilisés

### Data & Analyse
- **Python (Jupyer notebook)**
  - pandas, numpy
  - matplotlib/ seaborn
  - EDA ESG (qualité, distribution, corrélation)
  - Préparation des features pour le clustering

- **Machine Learning**
  - **K-Means (non supervisé)**
  - Objectif: identifier des **profils ESG homogènes**
  - Sélection et normalisation des variables ESG
  - Analyse et interprétaion des clusters

### Dataiku DSS
- Centralisation des datasets
- Pipelines de transformation et nettoyage
- Calcul des **scores ESG agrégés (E, S, G, Global)**
- Gestion des variables de **double matérialité**
- Implémentaion du **clustering K-Means**
- Traçabilité et reproductibilité du workflow

### Power BI
- Modélisation en étoile (tables de faits & dimensions)
- Mesures DAX pour les indicateurs ESG
- Visualisations interactives **orientées décisions**
- Segmentation par secteur, pays et maturité ESG
- Pages thématiques:
  - Synthèse ESG
  - Empreinte carbone (Scope 1 & total)
  - Social (capital humain)
  - Gouvernance
  - Double matérialité ESG

 ---

 ## Indicateurs clés analysés

 ### Environnement(E)
 - Emissions CO² Scope 1 & total
 - Intensité carbone (tCO² / M€ de CA)
 - Score environnemental agrégé

### Social (S)
- Heures de formation
- Accidents du travail (LTI)
- Ratio hommes / femmes
- Score social agrégé

### Gouvernance (G)
- Indépendance du board
- Score anti-corruption
- Score éthique
- Score gouvernance agrégé

### Risque & matérialité
- Score de risque financier
- **Double matérialité**:
  - Performance ESG vs exposition au risque
  - Classification en quadrants stratégiques

 ---

 ## Double matérialité & lecture stratégique

 Les entreprises sont positionnées selon:
 - **Performance ESG globale**
 - **Niveau de risque financier**

Une variable de lecture permet d'identifier 4 profils:

- **Situation maîtrisée**
- **Vigilance stratégique**
- **Potentiel d'amélioration**
- **Priorité d'action ESG**

Cette segmentation facilite:
- la priorisation des actions
- l'allocation des ressources ESG
- la lecture portefeuille pour un comité de direction ou d'investissement

---

## Restitution & storytelling

Le rapport Power BI propose:
- Une **page de synthèse exécutive**
- Des pages analytiques par pilier ESG
- Des visualisations de corrélation (scatter plots)
- une lecture sectorielle et géographique
- Des commentaires interprétatifs intégrés aux pages

Le focus est mis sur:
> **La compréhension des écarts, pas seulement sur les scores**

---

## Ce que démontre ce projet:

- Capacité à construire un **pipeline ESG complet**
- Maîtrise de la chaîne data:
  **EDA => Scoring => ML => BI**
- Compréhension métier des enjeux ESG & CSRD
- Capacité à transformer des données complexes en **décisions lisibles**

---

## Pistes d'évolution possibles
- Pondération dynamique des scores ESG
- Intégration d'un scoring temporel
- Ajout de scénario de transition
- Enrichissement CSRD / double matérialité règlementaire

---

## Auteur
**Aurélien Prat**
- Consultant BI & Data Analyst
