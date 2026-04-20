# 🤖 Projet IA — Déploiement d'une Solution d'Intelligence Artificielle en Entreprise

> Une entreprise de services souhaite améliorer sa performance grâce à l'IA.  
> Ce projet stratégique vise à automatiser, optimiser et renforcer la compétitivité de l'organisation.

**Module :** Management de Projet & Équipes IT  
**Formateur :** Ayedesso Marc Aurèle CHABI ADJOBO  
**TP :** Séance 4 — Structuration en Scrum  
**Auteurs :** Tayvadi Phaisan, Mathis Silotia, Mariama Diakhite, Claude Sabinotte, Camille Douaud

-----

## 📋 Table des matières

  - [Contexte du projet](https://www.google.com/search?q=%23-contexte-du-projet)
  - [Vision du projet](https://www.google.com/search?q=%23-vision-du-projet)
  - [Objectifs SMART](https://www.google.com/search?q=%23-objectifs-smart)
  - [User Stories](https://www.google.com/search?q=%23-user-stories)
  - [Priorisation MoSCoW](https://www.google.com/search?q=%23-priorisation-moscow)
  - [Estimation des efforts](https://www.google.com/search?q=%23-estimation-des-efforts)
  - [Organisation Scrum](https://www.google.com/search?q=%23-organisation-scrum)
  - [Workflow GitHub](https://www.google.com/search?q=%23-workflow-github)

-----

## 🏢 Contexte du projet

Une **entreprise de services** souhaite améliorer sa performance grâce à l'intelligence artificielle. La direction générale a lancé un projet stratégique visant à développer et déployer une solution d'IA capable de :

  - ⚙️ **Automatiser** certaines tâches à faible valeur ajoutée.
  - 📊 **Améliorer la prise de décision** grâce à la data.
  - 🤝 **Optimiser la relation client** / usagers.
  - 🚀 **Renforcer la compétitivité** de l'entreprise.

-----

## 🎯 Vision du projet

> Pour **l'entreprise**, notre solution permet de **simplifier le travail bureautique**, afin d'**uniformiser les réflexions**, contrairement à **l'utilisation manuelle des outils bureautiques**.

-----

## 📝 User Stories

Les issues GitHub et les branches suivent le format : `feature/US-X-nom-court`.

| ID | En tant que | Je veux | Afin de | Points |
|:---|:---|:---|:---|:---|
| **US-1** | Utilisateur | Profiter d'une **rédaction assistée** | Gagner du temps dans la création de contenus | 5 |
| **US-2** | Collaborateur | Une **correction orthographique/grammaticale** | Garantir un professionnalisme irréprochable | 2 |
| **US-3** | Manager | Un **résumé de documents** automatique | Assimiler rapidement les points clés des rapports | 5 |
| **US-4** | Analyste | La **génération de formules Excel** | Éviter les erreurs de calcul complexes | 3 |
| **US-5** | Employé | Une **réponse automatique aux emails** | Gérer plus efficacement ma boîte de réception | 8 |
| **US-6** | Rédacteur | La **reformulation de texte** | Adapter le ton à différentes audiences | 3 |
| **US-7** | Utilisateur | Une **traduction multilingue** | Communiquer facilement avec des partenaires étrangers | 3 |
| **US-8** | Utilisateur | Une **assistance contextuelle en temps réel** | Obtenir de l'aide immédiate sur mes tâches | 8 |

-----

## 🏷️ Priorisation MoSCoW

### Répartition des priorités

| Catégorie | User Stories | Justification |
|-----------|-------------|---------------|
| 🔴 **Must Have** | **US-1, US-2, US-3, US-5** | Fonctionnalités critiques constituant le cœur du Copilot. |
| 🟠 **Should Have** | **US-6, US-4** | Importantes pour l'efficacité mais non bloquantes pour le MVP. |
| 🟡 **Could Have** | **US-7, US-8** | Valeur ajoutée secondaire ou plus complexe à implémenter. |
| ⚪ **Won't Have** | *Intégrations tierces avancées* | Hors périmètre du sprint actuel. |

-----

### 🧐 Analyse détaillée de la priorisation

#### 🔴 Must Have (Indispensable)

Ces fonctionnalités sont critiques. Sans elles, le produit perd son intérêt principal :

  * **Rédaction assistée (US-1) :** Répond au besoin de gain de productivité.
  * **Correction (US-2) :** Fonctionnalité de base attendue pour tout outil pro.
  * **Résumé (US-3) :** Gain de temps majeur pour la prise de décision.
  * **Réponses aux emails (US-5) :** Cas d'usage le plus fréquent en entreprise.

#### 🟠 Should Have (Important)

Fonctionnalités à forte valeur, mais dont l'absence n'empêche pas l'usage du produit :

  * **Reformulation (US-6) :** Améliore la qualité mais n'est pas essentielle au lancement.
  * **Formules Excel (US-4) :** Utile pour un public spécifique, peut être ajouté après la V1.

#### 🟡 Could Have (Optionnel)

Fonctionnalités secondaires apportant un "plus" :

  * **Traduction (US-7) :** Souvent déjà gérée par des outils externes.
  * **Assistance temps réel (US-8) :** Complexe techniquement, priorité moindre.

#### ⚪ Won't Have (Hors périmètre actuel)

Exclus pour limiter la complexité initiale :

  * Intégrations avancées en temps réel avec des ERP tiers.
  * Personnalisation poussée par profil utilisateur (Machine Learning personnalisé).

-----

## 📊 Estimation des efforts (Sprint 1)

| User Story | Complexité | Points (Fibonacci) |
|-----------|-----------|:---:|
| **US-1** | Élevée (Cœur métier) | 5 |
| **US-2** | Faible | 2 |
| **US-3** | Moyenne | 5 |
| **US-5** | Élevée | 8 |

**Vélocité cible :** `20 points / sprint`

-----

## 🛠️ Workflow GitHub

### Branches

Pour chaque tâche, créez une branche dédiée :

```bash
git checkout -b feature/US-1-redaction-assistee
git checkout -b feature/US-2-correction-orthographe-grammaire
git checkout -b feature/US-3-resume-documents
git checkout -b feature/US-4-formules-excel
git checkout -b feature/US-5-reponse-automatique-emails
git checkout -b feature/US-6-reformulation-texte
git checkout -b feature/US-7-traduction-multilingue
git checkout -b feature/US-8-assistance-contextuelle
```

### Definition of Done (DoD)

  - [ ] Code développé et testé.
  - [ ] Pull Request approuvée par un pair.
  - [ ] Critères d'acceptation validés.
  - [ ] Issue GitHub fermée.

-----

*Projet réalisé dans le cadre du module Management de Projet & Équipes IT — 2026*
