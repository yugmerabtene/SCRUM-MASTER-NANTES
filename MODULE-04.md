# Module 4 — Vélocité de l'Équipe

> **Auteur :** yugmerabtene
> **Version :** 2.0

---

## Description

Ce module approfondit la notion de vélocité en Agile Scrum : techniques de calcul, métriques de performance complémentaires, Planning Poker avec la suite de Fibonacci, et bonnes pratiques pour utiliser la vélocité comme outil de planification et d'amélioration continue.

---

## 1. Introduction à la Vélocité en Agile Scrum

La **vélocité** est une mesure essentielle en Agile Scrum qui représente la quantité de travail qu'une équipe peut accomplir au cours d'un sprint. Elle aide à prévoir la capacité de l'équipe pour les sprints futurs, permettant ainsi une meilleure planification et estimation du projet.

**Définition** : La vélocité est calculée comme la somme des points de story des user stories complétées dans un sprint.

---

## 2. Techniques de Calcul de la Vélocité

### a. Points de Story

Les points de story sont attribués à chaque tâche (ou user story) pour estimer l'effort requis. Ils prennent en compte :

- **Complexité**
- **Quantité de travail**
- **Risques et incertitudes**

**Exemple** : Si une équipe termine les tâches suivantes au cours de trois sprints :

- Sprint 1 : 30 points de story
- Sprint 2 : 25 points de story
- Sprint 3 : 35 points de story

La **vélocité moyenne** se calcule ainsi :

![image](https://github.com/user-attachments/assets/b246109e-9f6b-4141-82f8-f69fb2f41935)

### b. Suivi sur le Burndown Chart

Un **burndown chart** est un graphique qui montre la quantité de travail restante par rapport au temps restant dans le sprint. Il aide à visualiser la progression et à vérifier si l'équipe est sur la bonne voie.

**Interprétation** : Si l'équipe démarre un sprint avec 50 points de story à accomplir et en termine 30 dans la première moitié, le graphique montrera la tendance de la réduction du travail restant.

### c. Calcul Basé sur les Tâches Terminées

La vélocité peut aussi être calculée en mesurant le nombre de tâches terminées lorsque celles-ci sont estimées de façon uniforme.

**Exemple** : Si une équipe termine en moyenne 15 tâches par sprint, avec chaque tâche estimée à 2 points :

![image](https://github.com/user-attachments/assets/6bf691ab-9853-4ed4-ada1-7ebe1ede6e7a)

---

## 3. Métriques de Performance Complémentaires

### a. Taux de Complétion

Le **taux de complétion** indique le pourcentage des user stories planifiées qui ont été terminées dans le sprint.

![image](https://github.com/user-attachments/assets/29ba7d70-ad21-4187-9894-d412415ba02d)

**Exemple** : Si l'équipe planifie 40 points de story et en termine 35, le taux de complétion est :

![image](https://github.com/user-attachments/assets/24c09c6a-63f2-4599-bbe4-f331d75fda46)

### b. Lead Time et Cycle Time

- **Lead Time** : Temps total entre la création d'une tâche et sa livraison.
- **Cycle Time** : Temps nécessaire pour accomplir une tâche une fois qu'elle a commencé.

Ces métriques aident à comprendre l'efficacité du processus et à identifier les goulets d'étranglement.

### c. Taux de Défectuosité

Le **taux de défectuosité** mesure la qualité du travail en identifiant le nombre de défauts par rapport aux user stories livrées.

---

## 4. Planning Poker et la Suite de Fibonacci

**Planning Poker** est une technique de planification utilisée par les équipes Agile pour estimer les points de story. Chaque membre de l'équipe utilise un jeu de cartes numérotées selon la suite de Fibonacci (1, 2, 3, 5, 8, 13, 21, etc.) pour attribuer une estimation aux user stories.

**Étapes du Planning Poker** :

1. **Présentation de la user story** : Le Product Owner explique la user story à l'équipe.
2. **Discussion et questions** : L'équipe pose des questions pour clarifier les détails.
3. **Choix de la carte** : Chaque membre choisit une carte représentant l'estimation.
4. **Révélation simultanée** : Tous les membres révèlent leurs cartes en même temps.
5. **Discussion sur les différences** : Si les estimations varient beaucoup, l'équipe discute des raisons et réitère le processus.

**Pourquoi la suite de Fibonacci ?**
Elle reflète l'incertitude croissante avec l'augmentation de la taille et de la complexité de la tâche. Les intervalles plus larges entre les nombres aident l'équipe à mieux évaluer les grandes user stories.

**Exemple** :
Pour une user story de complexité moyenne, l'équipe pourrait estimer un effort de 5 ou 8 points. Si certains membres estiment 5 et d'autres 8, la discussion portera sur la différence de perception et aidera à converger vers un consensus.

---

## 5. Exemple Complet de Calcul de la Vélocité avec le Planning Poker

Supposons qu'une équipe utilise le Planning Poker pour estimer trois user stories :

- **Story A** : 5 points (consensus après discussion)
- **Story B** : 8 points
- **Story C** : 13 points

Après un sprint où l'équipe a complété toutes les stories planifiées, la vélocité du sprint est :

![image](https://github.com/user-attachments/assets/e05c9322-09d6-4ace-99b7-cbd3d29cbcb3)

Pour calculer la **vélocité moyenne** sur trois sprints :

- Sprint 1 : 26 points
- Sprint 2 : 28 points
- Sprint 3 : 30 points

La moyenne est :

![image](https://github.com/user-attachments/assets/e5096d4b-daa3-4793-ac2a-d6b02ed46ea7)

---

## 6. Précautions et Bonnes Pratiques

- **Ne pas comparer la vélocité entre équipes.** Chaque équipe a ses propres critères d'estimation et contexte de travail.
- **Éviter de surcharger l'équipe.** Utiliser la vélocité comme guide de planification et non comme un objectif de performance.
- **Réévaluer régulièrement.** Les points de story doivent être réévalués au fur et à mesure que l'équipe gagne en expérience.
