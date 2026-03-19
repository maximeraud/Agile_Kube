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

**user story :**
- En tant d'admin on veux un temps de formation sur kub afin d'acquérir les compétences nécessaires (complexité : 3)
- En tant qu'admin on veux déployer un cluster kub pour héberger l'application et les différent service (complexité : 8)
- En tant d'admin on veux qu'il y ait plusieurs VM avec de la redondance afin de rendre l'application et les services hébergé à haute disponibilité (complexité : 8)
- En tant qu'utilisateur je dois avoir accès à l'application depuis n'importe quel réseau (complexité : 13)

**sprint goal :**
- mettre en place le cluster kube pour déployer l'application web afin que les utilisateurs puissent y accèder


- 11h45 : Sprint Review

### 🕐 Session 2

### 🕐 Session 3

### 🕐 Session 4

### 🕐 Sessions suivantes

Chaque session suit le cycle Scrum :

1. Sprint Planning
2. Développement
3. Daily Scrum Tout les heures 
4. Sprint Review
5. Rétrospective


