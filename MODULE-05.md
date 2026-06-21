# Module 5 — Burndown Chart et Métriques


---

## Description

Ce module est consacré aux outils de visualisation et de suivi en Agile Scrum : le Burndown Chart, le Burnup Chart, le Cumulative Flow Diagram et le Velocity Chart. Il couvre leur création, leur interprétation, leurs limites et les bonnes pratiques pour les utiliser efficacement dans l'amélioration continue.

---

## Introduction aux Burndown Charts

Les **burndown charts** et **burnup charts** sont des outils visuels utilisés dans Agile Scrum pour suivre l'avancement du travail d'une équipe pendant un sprint ou un projet.

### A. Burndown Chart (Vue rapide)

- **Utilité** : Visualiser la quantité de travail restante dans le sprint.
- **Interprétation** :
  - Une courbe descendante indique une progression normale.
  - Des plateaux ou des remontées peuvent signaler des problèmes.

---

## Burndown Chart (Diagramme d'Avancement)

Le **Burndown Chart**, ou diagramme d'avancement, est un outil essentiel en méthodologie Agile Scrum pour visualiser la progression d'un sprint ou d'un projet. Il permet à l'équipe et aux parties prenantes de suivre le travail restant au fil du temps, facilitant ainsi la gestion des attentes et l'identification précoce des problèmes.

### 1. Définition

Le **Burndown Chart** est un graphique qui représente la quantité de travail restante à accomplir dans un sprint ou un projet, en fonction du temps. L'axe horizontal (X) représente le temps, généralement en jours, et l'axe vertical (Y) représente le travail restant, souvent mesuré en story points, en heures ou en nombre de tâches. Le graphique comprend généralement deux lignes :

- **Ligne idéale (Ideal Burn)** : Une ligne droite qui indique le taux d'avancement idéal pour terminer tout le travail à temps.
- **Ligne réelle (Actual Burn)** : Une ligne qui trace le travail effectivement terminé au fil du temps.

### 2. Objectif du Burndown Chart

Le Burndown Chart sert plusieurs objectifs clés :

- **Suivi de la progression** : Il offre une visualisation claire et immédiate de l'avancement du sprint ou du projet.
- **Identification des problèmes** : En comparant la ligne réelle à la ligne idéale, l'équipe peut détecter rapidement les retards ou les obstacles potentiels.
- **Communication** : Il fournit aux parties prenantes une vue d'ensemble de l'état d'avancement, facilitant ainsi la communication et la prise de décision.
- **Aide à la planification** : En fonction de la progression réelle, l'équipe peut ajuster les priorités, réaffecter les ressources ou modifier le scope du travail pour respecter les délais.

### 3. Composantes du Burndown Chart

Pour bien comprendre et utiliser le Burndown Chart, il est important de connaître ses composantes principales :

- **Axe horizontal (X)** : Représente le temps, généralement en jours pour un sprint (par exemple, 10 jours pour un sprint de deux semaines).
- **Axe vertical (Y)** : Représente le travail restant à accomplir, mesuré en story points, en heures ou en nombre de tâches.
- **Ligne idéale (Ideal Burn)** : Une ligne droite qui va du total du travail au début du sprint (jour 0) jusqu'à zéro travail restant à la fin du sprint. Elle représente le rythme constant nécessaire pour terminer tout le travail à temps.
- **Ligne réelle (Actual Burn)** : Une ligne qui montre le travail réellement terminé chaque jour. Elle est mise à jour quotidiennement en fonction du travail accompli.

### 4. Comment Créer un Burndown Chart

#### Étape 1 : Rassembler les Données

Avant de créer le graphique, vous devez collecter les informations suivantes :

- **Total du travail à accomplir** : Déterminez la quantité totale de travail prévue pour le sprint. Cela peut être la somme des story points attribués à chaque user story, le total des heures estimées ou le nombre de tâches.
- **Durée du sprint** : Définissez la période du sprint en jours ouvrables. Par exemple, un sprint de deux semaines peut comporter 10 jours ouvrables.

#### Étape 2 : Configurer les Axes

- **Axe X (Temps)** : Marquez chaque jour du sprint sur l'axe horizontal, de 0 jusqu'au dernier jour.
- **Axe Y (Travail restant)** : Commencez à l'origine avec le total du travail à accomplir et marquez les graduations appropriées jusqu'à zéro.

#### Étape 3 : Tracer la Ligne Idéale

- **Dessiner la ligne idéale** : Tracez une ligne droite allant du point de départ (travail total au jour 0) jusqu'au point final (zéro travail restant au dernier jour du sprint). Cette ligne représente le rythme constant d'avancement nécessaire pour terminer le sprint à temps.

#### Étape 4 : Mettre à Jour Quotidiennement la Ligne Réelle

- **Collecte des données** : À la fin de chaque journée de travail, calculez le travail restant en soustrayant le travail accompli ce jour-là du travail restant de la veille.
- **Mise à jour du graphique** : Placez un point sur le graphique correspondant au travail restant pour le jour en question.
- **Relier les points** : Connectez les points entre eux pour visualiser la tendance de progression.

### 5. Interprétation du Burndown Chart

L'analyse du Burndown Chart permet d'évaluer la performance de l'équipe par rapport au plan initial :

- **Au-dessus de la ligne idéale** : Si la ligne réelle est au-dessus de la ligne idéale, cela signifie que l'équipe est en retard sur le plan prévu. Le travail restant est supérieur à ce qu'il devrait être à ce stade du sprint.
- **En dessous de la ligne idéale** : Si la ligne réelle est en dessous de la ligne idéale, l'équipe est en avance. Le travail restant est inférieur à ce qui était prévu, ce qui est positif.
- **Plateaux (lignes horizontales)** : Une stagnation de la ligne réelle indique qu'aucun travail n'a été terminé ce jour-là. Cela peut signaler des blocages, des imprévus ou des tâches plus complexes que prévu.
- **Remontées (lignes ascendantes)** : Si la ligne réelle remonte, cela signifie que du travail a été ajouté au sprint (scope creep) ou que des estimations ont été révisées à la hausse, augmentant le travail restant.

### 6. Avantages du Burndown Chart

Le Burndown Chart offre plusieurs bénéfices :

- **Visibilité** : Il fournit une représentation visuelle claire de l'avancement, accessible à tous les membres de l'équipe et aux parties prenantes.
- **Anticipation** : En identifiant rapidement les écarts par rapport à la ligne idéale, l'équipe peut anticiper les retards et prendre des mesures correctives.
- **Motivation** : Voir la ligne réelle descendre vers zéro peut être motivant pour l'équipe, renforçant le sentiment d'accomplissement.
- **Communication** : Il facilite les discussions lors des réunions quotidiennes et permet de partager facilement l'état d'avancement avec les parties prenantes.

### 7. Bonnes Pratiques pour le Burndown Chart

Pour tirer le meilleur parti du Burndown Chart, il est important de suivre certaines bonnes pratiques :

- **Mise à jour quotidienne** : Pour refléter fidèlement la progression, le graphique doit être mis à jour chaque jour, idéalement après le stand-up quotidien.
- **Inclure tout le travail** : N'oubliez pas d'inclure les petites tâches, les bugs, les tâches de support ou toute autre activité qui consomme du temps et affecte le travail restant.
- **Transparence** : Encouragez l'équipe à signaler honnêtement les progrès et les obstacles. Une communication ouverte est essentielle pour une interprétation précise du graphique.
- **Analyser les écarts** : Utilisez les divergences par rapport à la ligne idéale pour identifier les problèmes potentiels et prendre des mesures proactives.

### 8. Limitations et Comment les Surmonter

Bien que le Burndown Chart soit un outil puissant, il présente certaines limitations :

- **Travail non visible** : Les tâches en cours mais non terminées n'affectent pas le travail restant, ce qui peut donner l'impression d'une progression stagnante.
  - **Solution** : Utiliser un **Burnup Chart** en complément, qui montre à la fois le travail accompli et le travail total, offrant une vue plus complète de la progression.
- **Ajout de travail en cours de sprint** : L'ajout de nouvelles tâches peut fausser la lecture du graphique, rendant difficile la prévision.
  - **Solution** : Limiter les changements de scope pendant le sprint ou documenter clairement tout ajout de travail, en ajustant le graphique en conséquence.
- **Sur-focus sur les chiffres** : Se concentrer uniquement sur la descente de la ligne peut inciter à négliger la qualité du travail pour terminer rapidement les tâches.
  - **Solution** : Équilibrer l'attention entre la progression quantitative et la qualité du travail. Rappeler que l'objectif est de livrer de la valeur ajoutée, pas seulement de "brûler" des points.

---

## Comparaison des Types de Graphiques Agile

### 1. Burndown Chart

- **Définition** : Un **burndown chart** montre la quantité de travail restante à accomplir par rapport au temps.
- **Axe X (horizontal)** : Le temps (jours ou sprints).
- **Axe Y (vertical)** : La quantité de travail restante (en points de story, heures, etc.).
- **Interprétation** : Une courbe descendante indique la progression de l'équipe vers la complétion du sprint. Si la courbe descend sous la ligne idéale, l'équipe est en avance ; si elle est au-dessus, l'équipe est en retard.

**Usage principal** : Suivre la réduction progressive du travail restant pendant un sprint.

**Avantages** :
- Visualise la vitesse de travail de l'équipe.
- Permet d'identifier rapidement si l'équipe est en avance ou en retard.

**Limites** :
- Ne montre pas l'évolution de la portée du travail (si des tâches sont ajoutées ou supprimées).

### 2. Burnup Chart

- **Définition** : Un **burnup chart** montre la quantité de travail complétée par rapport au total du travail à faire. Il indique également les changements dans la portée du projet.
- **Axe X (horizontal)** : Le temps (jours ou sprints).
- **Axe Y (vertical)** : La quantité de travail total et accompli (en points de story, heures, etc.).
- **Interprétation** : Deux lignes : l'une représentant le travail accompli (montante) et l'autre la portée totale du projet (stagnante ou croissante). La distance entre les deux lignes montre le travail restant.

**Usage principal** : Suivre la progression du travail terminé tout en gardant une vue sur l'évolution de la portée.

**Avantages** :
- Visualise l'évolution de la portée du projet.
- Montre l'achèvement par rapport à l'objectif global.
- Utile pour voir à la fois la progression et les modifications de la portée.

**Limites** :
- Peut être moins intuitif que le burndown chart pour les débutants.

### 3. Cumulative Flow Diagram (CFD)

- **Définition** : Un diagramme qui montre le flux de travail à travers différentes étapes du processus (To Do, In Progress, Done).
- **Axes** :
  - **X (horizontal)** : Le temps.
  - **Y (vertical)** : Le nombre de tâches.
- **Interprétation** : Différentes couleurs représentent les étapes du flux de travail. L'épaisseur de chaque couleur montre la quantité de travail à chaque étape. Un flux uniforme indique un bon processus, tandis qu'un goulot d'étranglement est visible par l'élargissement d'une couleur spécifique.

**Usage principal** : Identifier les blocages dans le processus et mesurer le débit de l'équipe.

**Avantages** :
- Visualise les goulots d'étranglement.
- Aide à équilibrer le flux de travail.

**Limites** :
- Peut nécessiter plus de compétences en lecture et interprétation que les burndown ou burnup charts.

### 4. Velocity Chart

- **Définition** : Un graphique montrant la vélocité de l'équipe sur plusieurs sprints. Il aide à comparer la capacité de l'équipe d'un sprint à l'autre.
- **Axe X (horizontal)** : Les sprints.
- **Axe Y (vertical)** : Les points de story complétés.
- **Interprétation** : Chaque barre représente le total des points de story complétés par sprint. Une tendance à la hausse montre que l'équipe s'améliore, tandis qu'une tendance stable ou décroissante peut indiquer un problème.

**Usage principal** : Aider à la planification des sprints futurs et à l'évaluation de la capacité de l'équipe.

**Avantages** :
- Simple à comprendre.
- Utile pour prévoir les capacités futures.

**Limites** :
- Peut être influencé par des événements imprévus (changement de la taille de l'équipe, vacances, etc.).

### Comparaison des Différents Types de Graphiques

| Type de graphique | Usage principal | Avantages | Limites |
|---|---|---|---|
| **Burndown Chart** | Suivi de la quantité de travail restant | Simple à utiliser, facile à comprendre | Ne montre pas les changements de portée |
| **Burnup Chart** | Suivi du travail complété et de la portée totale | Montre les changements de portée, plus flexible | Peut être moins intuitif |
| **Cumulative Flow** | Suivi du flux de travail et identification des blocages | Identifie les goulots d'étranglement, bon suivi global | Lecture plus complexe |
| **Velocity Chart** | Comparaison de la vélocité sur plusieurs sprints | Simple et utile pour la planification future | Ne prend pas en compte les changements imprévus |

---

## 9. Exemple Pratique

Illustrons le Burndown Chart avec un exemple concret.

### Contexte

- **Durée du sprint** : 10 jours ouvrables.
- **Total du travail à accomplir** : 100 story points.

### Ligne Idéale

- Chaque jour, le travail restant devrait diminuer de 10 points pour atteindre zéro au jour 10.

### Mise à Jour Quotidienne

| Jour | Travail Restant (Idéal) | Travail Restant (Réel) | Points Complétés |
|------|-------------------------|------------------------|------------------|
| 0    | 100                     | 100                    | 0                |
| 1    | 90                      | 95                     | 5                |
| 2    | 80                      | 85                     | 10               |
| 3    | 70                      | 80                     | 5                |
| 4    | 60                      | 75                     | 5                |
| 5    | 50                      | 70                     | 5                |
| 6    | 40                      | 60                     | 10               |
| 7    | 30                      | 50                     | 10               |
| 8    | 20                      | 40                     | 10               |
| 9    | 10                      | 25                     | 15               |
| 10   | 0                       | 10                     | 15               |

### Interprétation

- **Retard accumulé** : Au jour 5, le travail restant réel est de 70 points, alors qu'il devrait être de 50 points selon la ligne idéale. L'équipe est donc en retard de 20 points.
- **Accélération en fin de sprint** : On constate une augmentation du rythme à partir du jour 6, avec plus de points complétés par jour.
- **Travail non terminé** : À la fin du sprint, il reste 10 points non complétés.

### Actions Possibles

- **Réévaluer les priorités** : Se concentrer sur les tâches les plus critiques pour maximiser la valeur livrée.
- **Identifier les obstacles** : Discuter lors des stand-ups des problèmes qui ralentissent l'équipe (blocages techniques, dépendances, etc.).
- **Ajuster les ressources** : Si possible, réaffecter des membres de l'équipe ou obtenir de l'aide externe.
- **Communiquer avec les parties prenantes** : Informer sur le retard et proposer des solutions (extension du sprint, ajustement du scope, etc.).

---

## 10. Utilisation du Burndown Chart pour l'Amélioration Continue

Le Burndown Chart n'est pas seulement un outil de suivi quotidien, il est également précieux pour l'amélioration continue :

- **Rétrospectives** : Analyser les Burndown Charts des sprints précédents pour identifier des schémas récurrents (par exemple, retards systématiques en début de sprint).
- **Identifier les obstacles récurrents** : Si des plateaux ou des remontées se produisent fréquemment, explorer les causes profondes (problèmes de planification, estimations imprécises, interruptions fréquentes).
- **Ajuster les estimations futures** : Utiliser les données historiques pour affiner les estimations et la planification des prochains sprints.
- **Améliorer les processus** : Modifier les pratiques de l'équipe pour résoudre les problèmes identifiés (par exemple, améliorer la définition des user stories, renforcer les revues de code).

---

## 11. Outils pour Créer des Burndown Charts

Il existe plusieurs outils pour créer et maintenir des Burndown Charts :

- **Logiciels de gestion de projet Agile** :
  - **Jira** : Génère automatiquement les Burndown Charts à partir des tickets et des story points saisis.
  - **Trello** (avec des extensions comme Corrello) : Permet de créer des Burndown Charts à partir des cartes.
  - **Azure DevOps** : Offre des fonctionnalités intégrées pour le suivi Agile, y compris les Burndown Charts.
- **Feuilles de calcul** :
  - **Microsoft Excel** ou **Google Sheets** : Pour créer des Burndown Charts personnalisés en saisissant manuellement les données.
  - **Avantages** : Flexibilité totale sur la présentation et les calculs.
- **Applications dédiées** :
  - **Burndown for Trello**, **Agile Scrum App**, **BurnDown Chart Generator** : Outils spécifiques pour le suivi Agile qui peuvent être intégrés à votre flux de travail.
- **Tableaux physiques** :
  - **Tableau blanc avec des post-it** : Dans un environnement de bureau, un Burndown Chart peut être dessiné à la main et mis à jour quotidiennement.

---

## 12. Conseils pour une Mise en Œuvre Réussie

Pour assurer l'efficacité du Burndown Chart dans votre équipe, voici quelques conseils pratiques :

- **Formation de l'équipe** : Assurez-vous que tous les membres comprennent le fonctionnement du Burndown Chart et son utilité. Une bonne compréhension favorise l'engagement et la précision des données.
- **Consistance dans les mesures** : Utilisez les mêmes unités de mesure (story points, heures, tâches) tout au long du projet pour maintenir la cohérence.
- **Intégration dans les réunions quotidiennes** : Discutez du Burndown Chart pendant les stand-ups pour maintenir la focalisation sur les objectifs du sprint et favoriser la collaboration.
- **Flexibilité** : Soyez prêt à ajuster les méthodes si le Burndown Chart ne reflète pas fidèlement la réalité du projet. Par exemple, si les estimations initiales s'avèrent systématiquement inexactes, revoyez votre processus d'estimation.
- **Culture de l'amélioration continue** : Encouragez une attitude proactive pour résoudre les problèmes identifiés grâce au Burndown Chart, plutôt que de chercher des coupables.
