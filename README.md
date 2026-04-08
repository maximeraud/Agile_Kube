# Agile_Kube

##  Contexte

Dans le cadre d’un TP, nous mettons en pratique la méthodologie Scrum à travers un projet DevOps.

L’objectif est de concevoir et déployer une infrastructure Kubernetes capable d’héberger :
- une application web
- une API
- des services exposés

⚠️ Le besoin peut évoluer en cours de projet (simulation client).

### 🧑‍💼 Product Owner
- Ellios

### 🧑‍🔧 Scrum Master
- Alexandre

### 👨‍💻 Développeurs
- Kylian
- Maxime 

##  Analyse du besoin

Suite aux échanges avec le client, nous avons identifié :

- Backend : Symfony / PHP
- Frontend : React
- Charge : 1000 utilisateurs simultanés environ
- Sécurité : HTTPS obligatoire
- Monitoring : requis
- Logs : obligatoires
- Deadline : 8 avril
- IP : publique a definir par le client  

## ⚙️ Organisation Scrum

Nous avons organisé le projet en plusieurs sessions simulant des sprints.

### 🕐 Session 1

- 10h00 – 10h45 : Définition du besoin avec le client
- 10h45 - 11h00 : Daily Scrum  | Définition des objectifs jusqu’à 12h

Mise en place des outils :

- Kanban
- Gestion des accès GitHub
- Planning Poker

Répartition des rôles :

Scrum Master → organisation
Product Owner → backlog
Développeurs → préparation technique

#### Sprint 1

**user stories :**
- En tant d'admin on veut un temps de formation sur kub afin d'acquérir les compétences nécessaires 3
- En tant qu'admin on veut déployer un cluster kub pour héberger l'application et les différent service, ainsi que de la redondance afin de rendre le produit hébergé à haute disponibilité 8
- En tant d'admin on veut déployer l'application web sur le cluster 8
- En tant d'admin on veut exposer l'application en HTTPS 8

**Sprint goal :**
- mettre en place le cluster kube pour déployer l'application web afin que les utilisateurs puissent y accèder

**Sprint backlog :**
- formation Kubernetes
- déploiement cluster k3s
- déploiement application web sur workers
- exposer l'appli en https


**Sprint Review :**
- Présentation du sprint goal et sprint backlog au client
- Démo de l'apllication déployer sur le cluster k3s

**Sprint Retro :**
- organisation à toutes épreuves
- développement rapide et efficace 

### 🕐 Session 2

#### Sprint 2

**user stories :**
- En tant qu'admin on veut une solution de supervision afin de visualiser l'état des machines et des services
- En tant qu'admin on veut mettre en place une solution d'aggrégation de log afin de récupérer les journaux d'événements liés à l'application

**Sprint goal :**
- mettre en place une supervision en temps réel de l'état des machines et des services, ainsi que d'une solution centralisée d'agrégation des logs applicatifs.

**Sprint Backlog :**
- déployer supervision serveur et applicative
- implémentation de log de l'appli

**Sprint Review :**
- Présentation du sprint goal et sprint backlog au client
- Démo des différentes focntionnalités au client

**Sprint Retro :**
- organisation à toutes épreuves
- développement rapide et efficace 

### 🕐 Session 3 RETEX

| 👍 Positif | 👎 Négatif |
|-----------|-----------|
| - Compréhension rapide des besoins | - Pas de tests au niveau du projet |
| - Répartition des tâches | |
| - Documentation | |
| - Autonomie entre les rôles | |
| - Poker planning | |

<br>

| 💡 Idées | ❓ Questions |
|---------|-------------|
| - Centraliser les wikis (Constellation, SharePoint ou autres) | - Pourquoi il n’y a pas eu de tests ? |
| - Créer une procédure d’installation | |
| - Formation technique approfondie | |




Chaque session suit le cycle Scrum :

1. Sprint Planning
2. Développement
3. Daily Scrum Tout les heures 
4. Sprint Review
5. Rétrospective


