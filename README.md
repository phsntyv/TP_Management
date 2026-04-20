# 🤖 Projet IA — Déploiement d'une Solution d'Intelligence Artificielle en Entreprise

> Une entreprise de services souhaite améliorer sa performance grâce à l'IA.  
> Ce projet stratégique vise à automatiser, optimiser et renforcer la compétitivité de l'organisation.

**Module :** Management de Projet & Équipes IT  
**Formateur :** Ayedesso Marc Aurèle CHABI ADJOBO  
**TP :** Séance 4 — Structuration en Scrum
**Auteurs :** Tayvadi Phaisan, Mathis Silotia, Mariama Diakhite, Claude Sabinotte, Camille Douaud

---

## 📋 Table des matières

- [Contexte du projet](#-contexte-du-projet)
- [Vision du projet](#-vision-du-projet)
- [Objectifs SMART](#-objectifs-smart)
- [Contraintes](#-contraintes)
- [Parties prenantes](#-parties-prenantes)
- [Gouvernance & Management](#-gouvernance--management)
- [Gestion des risques](#-gestion-des-risques)
- [User Stories](#-user-stories)
- [Backlog produit](#-backlog-produit)
- [Priorisation MoSCoW](#-priorisation-moscow)
- [Estimation des efforts](#-estimation-des-efforts)
- [Organisation Scrum](#-organisation-scrum)
- [Workflow GitHub](#-workflow-github)
- [Livrables](#-livrables)

---

## 🏢 Contexte du projet

Une **entreprise de services** souhaite améliorer sa performance grâce à l'intelligence artificielle. La direction générale a lancé un projet stratégique visant à développer et déployer une solution d'IA capable de :

- ⚙️ **Automatiser** certaines tâches à faible valeur ajoutée
- 📊 **Améliorer la prise de décision** grâce à la data
- 🤝 **Optimiser la relation client** / usagers
- 🚀 **Renforcer la compétitivité** de l'entreprise

Ce projet s'inscrit dans un environnement incertain, avec des enjeux à la fois **techniques**, **organisationnels** et **humains**.

---

## 🎯 Vision du projet

> Pour **l'enterpise**, notre solution permet de **simplifier le travail bureautique**, afin de **uniformiser les reflexions**, contrairement à **l'utilisation manuel des outils bureautique**.

---

## ✅ Objectifs SMART

| # | Objectif | Mesure | Échéance |
|---|----------|--------|----------|
| 1 | *Automatiser les rapports écrit* | *% de rapports automatisé* | *< 3 months* |
| 2 | *Automatiser les RDV* | *% de RDV automatisé* | *< 6 months* |
| 3 | *Automatiser les notes frais* | *% de notes des frais automatisé* | *< 9 months* |

---

## ⚠️ Contraintes

| Contrainte | Description |
|-----------|-------------|
| 💰 Budget | Budget limité, arbitrages nécessaires |
| ⏱️ Délais | Délai de déploiement imposé par la direction |
| 👥 Parties prenantes | Multiples acteurs aux intérêts divergents |
| 🏆 Enjeux stratégiques | Projet visible et prioritaire pour la direction |
| 🔄 Résistance au changement | Impact organisationnel potentiellement fort |
| 🔗 Coordination | Forte dépendance entre équipes métiers, IT et data |

---

## 👥 Parties prenantes

### Identification

| Partie prenante | Rôle | Intérêt | Pouvoir |
|----------------|------|---------|---------|
| 🏛️ Direction générale | Porte la vision, finance le projet | Élevé | Élevé |
| 💻 Direction informatique | Encadre la dimension technique | Élevé | Élevé |
| 🧑‍💼 Équipes métiers | Expriment les besoins fonctionnels | Élevé | Moyen |
| 🤖 Équipe Data / IA | Conçoit et développe la solution | Élevé | Moyen |
| 👤 Utilisateurs finaux | Utiliseront l'outil au quotidien | Moyen | Faible |
| 🤝 Prestataires externes | Soutien technique ou expertise spécifique | Faible | Faible |

### Matrice Pouvoir / Intérêt

```
Pouvoir
  ↑
  │  Gérer étroitement  │  Satisfaire & informer
  │─────────────────────│────────────────────────
  │  Surveiller         │  Informer régulièrement
  └─────────────────────────────────────→ Intérêt
```

### Stratégie de gestion

*À compléter par groupe.*

---

## 🏛️ Gouvernance & Management

> *Section à compléter progressivement au fil des séances du module.*

### Structure organisationnelle

| Dimension | Choix | Justification |
|-----------|-------|---------------|
| 🗂️ Organisation du projet | *À définir* | |
| 👔 Style de management | *À définir* | |
| 🏗️ Structure d'équipe | *À définir* | |
| 📋 Instance de pilotage | *À définir* | |

### Scénarios de pilotage

Le projet est susceptible de rencontrer des imprévus réels à gérer :

- ⚡ Tensions entre parties prenantes
- 🔄 Changement de périmètre en cours de route
- ⏳ Pression accrue sur les délais
- 🚶 Départ d'un membre clé de l'équipe
- ✂️ Arbitrages budgétaires imposés
- 🔀 Difficultés de coordination ou de management

---

## 🛡️ Gestion des risques

| # | Risque | Probabilité | Impact | Stratégie de mitigation |
|---|--------|------------|--------|------------------------|
| R1 | Résistance au changement des utilisateurs | Élevée | Élevé | Plan de conduite du changement, formation |
| R2 | Dépassement de budget | Moyenne | Élevé | Suivi budgétaire hebdomadaire, priorisation stricte |
| R3 | Retard de livraison | Moyenne | Élevé | Buffer de sprint, revue de sprint hebdomadaire |
| R4 | Départ d'un membre clé | Faible | Élevé | Documentation continue, pair programming |
| R5 | Données insuffisantes ou non conformes | Moyenne | Élevé | Audit data en amont, validation RGPD |
| R6 | Désalignement métier / technique | Élevée | Moyen | Rituels Scrum, Product Owner impliqué |

---

## 📝 User Stories

Les issues GitHub suivent le format :

```
[US-X] En tant que <rôle>, je veux <fonctionnalité>, afin de <bénéfice>
```

Chaque User Story contient :
- ✅ **Critères d'acceptation**
- 🏷️ **Priorité** (MoSCoW)
- 📊 **Estimation** (points d'effort)

### Liste des User Stories

| ID | En tant que | Je veux | Afin de | Priorité | Points |
|----|------------|---------|---------|----------|--------|
| US-1 | Collaborateur | générer un rapport automatique à partir de mes données | supprimer la rédaction manuelle et chronophage | Haute | 5 |
| US-2 | Manager | imposer des modèles de rapports prédéfinis | uniformiser les réflexions et la structure des livrables | Haute | 3 |
| US-3 | Commercial | proposer un lien de prise de rendez-vous synchronisé | automatiser la gestion de mon calendrier | Haute | 5 |
| US-4 | Client | recevoir des rappels automatiques avant un RDV | réduire les oublis et les relances manuelles | Moyenne | 2 |
| US-5 | Employé | scanner mes reçus via une reconnaissance optique | automatiser la création de mes notes de frais | Haute | 8 |
| US-6 | Comptable | valider automatiquement les notes de frais conformes | accélérer le processus de remboursement | Moyenne | 5 |
| US-7 | Administrateur | centraliser l'ensemble des documents produits | simplifier l'accès à l'information pour l'entreprise | Faible | 3 |
| US-8 | Utilisateur | intégrer mes outils bureautiques actuels à la solution | abandonner l'utilisation manuelle isolée des outils | Moyenne | 5 |

> ℹ️ Minimum 8 user stories requises.

---

## 🗂️ Backlog produit

```
📦 EPIC 1 — [Nom de l'épic]
 └── 🔷 Feature 1.1 — [Nom de la feature]
      ├── US-1 : [Titre]
      └── US-2 : [Titre]

📦 EPIC 2 — [Nom de l'épic]
 └── 🔷 Feature 2.1 — [Nom de la feature]
      ├── US-3 : [Titre]
      └── US-4 : [Titre]
```

---

## 🏷️ Priorisation MoSCoW

| Catégorie | User Stories | Justification |
|-----------|-------------|---------------|
| 🔴 **Must Have** | US-1, US-2, … | *Fonctionnalités critiques* |
| 🟠 **Should Have** | US-3, US-4, … | *Importantes mais non bloquantes* |
| 🟡 **Could Have** | US-5, US-6, … | *Valeur ajoutée si temps disponible* |
| ⚪ **Won't Have** | US-7, US-8, … | *Hors périmètre sprint actuel* |

---

## 📊 Estimation des efforts

Estimation en **Story Points** (suite de Fibonacci : 1, 2, 3, 5, 8, 13…)

| User Story | Complexité | Points |
|-----------|-----------|--------|
| US-1 | Faible | 2 |
| US-2 | Moyenne | 5 |
| US-3 | Élevée | 8 |
| … | … | … |

**Vélocité estimée de l'équipe :** `XX points / sprint`

---

## 🔄 Organisation Scrum

### Rôles

| Rôle | Membre(s) |
|------|-----------|
| 🧭 Product Owner | *Collectif (groupe)* |
| 🏗️ Scrum Master | *À désigner* |
| 👨‍💻 Development Team | *Tous les membres* |

### Sprints

- **Durée d'un sprint :** `X semaines`
- **Sprint 1 :** [Date début] → [Date fin]
- **Cérémonies :** Sprint Planning · Daily · Sprint Review · Rétrospective

### Definition of Done (DoD)

Une User Story est **Done** quand :

- [ ] Le code est développé et testé
- [ ] La Pull Request est approuvée et mergée sur `main`
- [ ] Les critères d'acceptation sont tous validés
- [ ] La documentation est mise à jour
- [ ] L'issue GitHub est fermée et la carte déplacée dans **Done**

### Règles d'équipe

- 📌 Tout travail passe par une issue GitHub
- 🔀 Aucun commit direct sur `main`
- ✅ Validation obligatoire avant merge (Pull Request)
- 📣 Communication transparente sur les blocages

---

## 🛠️ Workflow GitHub

### Project Board

| Backlog | Ready | In Progress | In Review | Done |
|---------|-------|-------------|-----------|------|
| Issues créées | Prêtes à démarrer | En cours de développement | PR ouverte, en attente de review | Validées & mergées |

### Branches

```bash
# Créer une branche pour une User Story
git checkout -b feature/US-X-nom-court
```

### Cycle de vie d'une User Story

```
Backlog → Ready → In Progress → In Review → Done
```

### Pull Requests

Chaque PR doit inclure :
- 🔗 Lien avec l'issue associée (`Closes #X`)
- 📄 Description du travail réalisé
- ✅ Validation par au moins un autre membre

---

## 📦 Livrables

- [ ] 🖥️ Support de présentation (slides)
- [ ] 📁 Repository GitHub structuré avec Project Board
- [ ] 📋 Backlog complet (épics, features, user stories)
- [ ] 🔄 Démonstration du cycle complet d'une User Story

---

## 👨‍💼 Restitution

Présentation orale face au client (formateur) :

| Critère | Description |
|---------|-------------|
| 🎯 Vision claire | Énoncé de vision compris en 30 secondes |
| 🧠 Justification des choix | Argumentation MoSCoW, estimations, organisation |
| 🔗 Cohérence globale | Alignement entre vision, backlog et sprints |
| 💬 Réponses aux questions | Capacité à défendre chaque décision |

> ⚠️ **Le formateur peut demander une démonstration en direct du cycle complet d'une User Story dans GitHub.**

---

*Projet réalisé dans le cadre du module **Management de Projet & Équipes IT** — Fil rouge pédagogique*  
*Formateur : Ayedesso Marc Aurèle CHABI ADJOBO | TP Groupe — Séance 4*
