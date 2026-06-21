# Module 3 — Estimation et Planification

> **Auteur :** yugmerabtene
> **Version :** 2.0

---

## Description

Ce module couvre les techniques d'estimation et de planification en Agile Scrum, notamment le Planning Poker, le T-Shirt Sizing, les Story Points, le suivi du temps, et la planification à différents niveaux (produit, release, sprint). Il inclut également une introduction à la vélocité de l'équipe.

---

## Introduction

Dans le cadre de la méthodologie Agile Scrum, l'estimation et la planification sont des éléments clés pour assurer le bon déroulement d'un projet. Ces techniques permettent à l'équipe de développement de prévoir le travail à accomplir, de suivre la progression et d'adapter le plan en fonction des imprévus. Parmi les outils et méthodes utilisés, on retrouve le **Planning Poker**, la **vélocité**, les **sprints**, et d'autres pratiques essentielles. Ce cours détaillera ces techniques pour vous aider à les mettre en œuvre efficacement dans vos projets.

---

## I. Estimation du Temps et des Efforts

### A. Importance de l'Estimation

L'estimation permet de :

- **Prévoir la charge de travail** : Évaluer le temps nécessaire pour accomplir chaque tâche.
- **Planifier les sprints** : Organiser le travail de l'équipe sur des périodes définies.
- **Gérer les attentes** : Informer les parties prenantes sur les délais et les livrables.

### B. Techniques d'Estimation

#### 1. Planning Poker

Le Planning Poker est une technique collaborative d'estimation basée sur le consensus de l'équipe.

- **Processus** :
  - Chaque membre de l'équipe reçoit un jeu de cartes avec des valeurs numériques (par exemple, la suite de Fibonacci : 1, 2, 3, 5, 8, 13, etc.).
  - Une user story ou une tâche est présentée et discutée.
  - Chaque membre sélectionne secrètement une carte qui représente son estimation.
  - Tous révèlent simultanément leur carte.
  - Les écarts d'estimations sont discutés pour comprendre les divergences.
  - Le processus est répété jusqu'à ce qu'un consensus soit atteint.

- **Avantages** :
  - Favorise la discussion et la compréhension commune.
  - Évite l'influence hiérarchique ou de groupe sur les estimations individuelles.
  - Rapide et efficace pour estimer plusieurs tâches.

#### 2. T-Shirt Sizing

Une méthode d'estimation plus grossière où les tâches sont classées par tailles de T-shirt : XS, S, M, L, XL.

- **Utilisation** :
  - Utile en début de projet pour estimer rapidement de grandes quantités de travail.
  - Les tailles sont ensuite converties en points ou en temps pour la planification.

#### 3. Story Points

Les story points sont une unité de mesure abstraite qui reflète la complexité, l'effort et le risque associés à une tâche.

- **Caractéristiques** :
  - Non linéaires : une tâche de 8 points n'est pas nécessairement le double d'une tâche de 4 points.
  - Basés sur la complexité relative entre les tâches.
  - Aident à estimer la vélocité de l'équipe.

### C. Facteurs à Considérer lors de l'Estimation

- **Complexité technique** : Difficulté du travail à accomplir.
- **Volume de travail** : Quantité de code ou de tâches à réaliser.
- **Risques et incertitudes** : Inconnues qui pourraient affecter le travail.
- **Dépendances** : Nécessité d'attendre d'autres tâches ou équipes.

---

## II. Suivi du Temps Passé sur les Tâches

### A. Importance du Suivi

- **Mesurer la performance** : Comprendre si les estimations étaient précises.
- **Améliorer les prévisions futures** : Ajuster les estimations basées sur les données réelles.
- **Identifier les obstacles** : Repérer les tâches qui prennent plus de temps que prévu.

### B. Outils de Suivi

- **Feuilles de temps** : Enregistrement manuel des heures travaillées.
- **Logiciels de gestion de projet** : Outils comme Jira, Trello ou Asana qui intègrent le suivi du temps.
- **Tableaux Kanban** : Visualisation du flux de travail et du temps passé dans chaque étape.

### C. Bonnes Pratiques

- **Transparence** : Encourager l'équipe à enregistrer honnêtement le temps passé.
- **Fréquence** : Mettre à jour régulièrement pour une précision maximale.
- **Analyse** : Utiliser les données collectées pour identifier les tendances et les points d'amélioration.

---

## III. Planification Agile Scrum

### A. Planification à Différents Niveaux

1. **Planification du Produit (Product Planning)**

   - **Backlog Produit** : Liste priorisée de toutes les fonctionnalités, améliorations et corrections à apporter.
   - **Roadmap** : Vision à long terme des évolutions du produit.

2. **Planification de la Release**

   - **Objectifs** : Déterminer quelles fonctionnalités seront livrées et quand.
   - **Critères de succès** : Définir les indicateurs clés de performance (KPI) pour la release.

3. **Planification du Sprint**

   - **Sprint Planning Meeting** : Réunion pour déterminer les user stories à inclure dans le sprint.
   - **Engagement de l'équipe** : L'équipe s'engage sur ce qu'elle pense pouvoir accomplir pendant le sprint.

### B. Le Rôle du Scrum Master et du Product Owner

- **Scrum Master** : Facilite les réunions, aide à éliminer les obstacles, veille au respect du processus Scrum.
- **Product Owner** : Définit les priorités, maintient le backlog produit, communique la vision du produit.

### C. Adaptabilité

- **Réunions Quotidiennes (Daily Stand-ups)** : Permettent d'ajuster quotidiennement le plan en fonction des progrès et des obstacles.
- **Révisions de Sprint (Sprint Reviews)** : Évaluation du travail accompli et ajustement des priorités pour le prochain sprint.
- **Rétrospectives** : Analyse de ce qui a bien fonctionné et ce qui peut être amélioré pour les prochains sprints.

---

## IV. La Vélocité de l'Équipe (Introduction)

### A. Définition

La vélocité est une mesure de la quantité moyenne de travail terminée par l'équipe pendant un sprint. Elle est généralement exprimée en nombre de story points ou d'unités similaires.

### B. Calcul de la Vélocité

- **Total des Story Points** : Additionner les points des user stories terminées lors du sprint.
- **Moyenne sur Plusieurs Sprints** : Calculer la moyenne sur les derniers sprints pour une estimation plus fiable.

### C. Utilisation de la Vélocité

- **Prévision** : Estimer combien de story points l'équipe peut traiter dans les futurs sprints.
- **Planification de Release** : Prévoir quand les fonctionnalités seront terminées.
- **Amélioration Continue** : Suivre la vélocité pour identifier les tendances et optimiser les processus.

### D. Facteurs Affectant la Vélocité

- **Changements dans l'Équipe** : Entrée ou sortie de membres de l'équipe.
- **Complexité des Tâches** : Variations dans la nature des user stories.
- **Obstacles Externes** : Problèmes techniques, dépendances, interruptions.
