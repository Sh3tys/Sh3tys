# TodoApp
<span style="width:20px; justify-center;">![Logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR_ly2wNDz-JtvuG3ICM9S2qKYz4ud3ggJfsw&s)</span>

[![uv](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/uv/main/assets/badge/v0.json)](https://google.com)
[![image](https://img.shields.io/pypi/v/uv.svg)](https://pypi.python.org/pypi/uv)
[![Static Badge](https://img.shields.io/badge/todoapp-todapp-brightgreen)](https://youtube.com)
[![Actions status](https://github.com/astral-sh/uv/actions/workflows/ci.yml/badge.svg)](https://github.com/astral-sh/uv/actions)
[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?logo=discord&logoColor=white)](https://www.linkedin.com/in/titouan-conquéré-de-monbrison/)

![Logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEciD8gAyCLEQIcmuQUy3FfFN07Uxe_KQCtg&s)

Une application moderne ***extrêment rapide*** pour **gérer efficacement ses tâches**, construite avec **Rust, React et PostgreSQL**.

## Sommaire

- [📌 TodoApp](#-todoapp)
  - [📢 À propos](#-à-propos)
  - [✨ Fonctionnalités](#-fonctionnalités)
  - [⚙️ Technologies utilisées](#️-technologies-utilisées)
  - [📋 Prérequis](#-prérequis)
  - [🚀 Installation](#-installation)
  - [⚡ Commandes utiles](#-commandes-utiles)
  - [🛠️ Déploiement](#️-déploiement)
  - [🧪 Tests](#-tests)
  - [🤝 Contribution](#-contribution)
  - [📜 Licence](#-licence)

## 📢 À propos

TodoApp optimise l'organisation des tâches avec une interface intuitive, une gestion en temps réel et une IA pour la rédaction ainsi que le suivi et le partage des tâches.

### 🎯 Objectifs principaux

✔️ Offrir une **expérience utilisateur très rapide**  
✔️ Permettre la **gestion et synchronisation des tâches**  
✔️ Intégrer un **système sécurisé d'authentification**  
✔️ Proposer une **API REST pour les intégrations**


## ✨ Fonctionnalités
- ✅ Création, modification et suppression de tâches
- ✅ Tableau de bord interactif
- ✅ Responsive design (mobile et desktop)
- ✅ Gestion des tâches en temps réel (WebSockets)
- ✅ Notifications par e-mail et push
- ❌ Mode hors-ligne (prévu dans une future version)

## ⚙️ Technologies utilisées

| **Technologie**    | **Usage** |
|--------------------|-----------|
| **Node.js**       | Backend serveur |
| **Express.js**    | API REST |
| **PostgreSQL**    | Base de données relationnelle |
| **React.js**      | Interface utilisateur |
| **Jest**         | Tests unitaires |
| **Cypress**      | Tests end-to-end |

## 📋 Prérequis

> [!IMPORTANT]
> Avant de commencer, assurez-vous d'avoir installé :

- [ ] **Node.js** >= 18.x
- [ ] **Git**
- [ ] **PostgreSQL** (*local ou distant*)

## 🚀 Installation

### Etape 1 : Cloner le projet
```bash
git clone https://github.com/sh3tys/todoapp.git
cd todoapp
```

### Etape 2 : Installer les dépendances
```bash
npm install
```

### Etape 3 : Configurer les variables d'environnement
Créer un fichier `.env` et ajouter les paramètres suivants :
```env
PORT=3000
DATABASE_URL=postgres://user:password@localhost:5432/todoapp
JWT_SECRET=supersecretkey
``` 

### Etape 4 : Démarrer l'application
```bash
npm start
```

### Etape 5 : Hébergement de l'application
```
http://localhost:3000
```

## Commandes utiles
>[!TIP] 
>Les commandes suivantes pourront peut-être vous aidez lors de l'utilisation

| **Commande**       | **Description**                             |
|--------------------|---------------------------------------------|
| `npm start`        | Démarre l'application en mode développement |
| `npm run build`    | Compile l'application pour la production    |
| `npm test`         | Exécute les tests unitaires                 |
| `npm run lint`     | Vérifie la qualité du code                  |

<details>
  <summary><strong>Voir plus ...</strong></summary>
  <ol>
    <li><a href="https://google.com">Documentation Node.js</a></li>
    <li><a href="https://google.com">Documentation Express.js</a></li>
    <li><a href="https://google.com">Documentation PostgreSQL</a></li>
    <li><a href="https://google.com">Documentation React.js</a></li>
    <li><a href="https://google.com">Documentation Jest</a></li>
    <li><a href="https://google.com">Documentation Cypress</a></li>
  </ol>
</details>

## Architecture du projet

| Dossier/Fichier             | Description                           |
|-----------------------------|---------------------------------------|
| `/todoapp`                  | Dossier principal du projet          |
|                  |          |
| `/todoapp/backend`                  | Backend (API)                        |
| `/todoapp/backend/server.js`             | Serveur Node.js                      |
| `/todoapp/backend/routes.js`             | Routes de l'API                      |
| `/todoapp/backend/models.js`             | Modèles de données                   |
|                  |          |
| `/todoapp/frontend`                 | Frontend (React)                     |
| `/todoapp/frontend/index.html`            | Page principale                      |
| `/todoapp/frontend/app.js`                | Application React                    |
| `/todoapp/frontend/components`           | Composants React                      |
|                  |          |
| `/todoapp/.gitignore`                | Fichiers à ignorer par Git           |
|                  |          |
| `/todoapp/README.md`                 | Documentation du projet              |
|                  |          |
| `/todoapp/package.json`              | Dépendances et scripts                |




## 🧪 Tests

### ✅ Tests automatisés
- **Tests unitaires** avec Jest
- **Tests d'intégration** avec Supertest
- **Tests End-to-End** avec Cypress

### 🔄 Exécuter les tests
```bash
npm test
```


## 🤝 Contribution

Les contributions sont les bienvenues !

### Les derniers contributeurs
- Beloubz
- ShadowBlaze42
- NeoVortexX

## 👨‍💻Créateur du projet

- 👑[Lightningmax](https://github.com/LightningMax)💻
- 👑[Sh3tys](https://github.com/Sh3tys)💻

### Contact
- **Lightningmax :** *max.silva-dos-reis@efrei.net*
- **Sh3tys :** *titouan.conquere-de-monbrison@efrei.net*

### Projet

*lien du projet : [https://github.com/Sh3tys/TodoApp]()*
<div>
  <p>
    <a href="https://google.com">View Demo</a>
    &middot;
    <a href="https://google.comd">Report Bug</a>
    &middot;
    <a href="https://google.com">Request Feature</a>
  </p>
</div>



## 📜 Licence

Ce projet est sous licence **MIT**. Vous pouvez l'utiliser librement et contribuer à son amélioration.

## Nos projets similaires
+ [Agenda intelligent 📅]()
+ [Suivi d’habitudes 📊]()
+ [Gestionnaire de projets 📂]()
+ [Gestion de budget personnel 💰]()




- 👋 Hi, I’m @Sh3tys
- 👀 I’m interested in Java code
- 🌱 I’m currently learning Python, Java, Django, React
- 📫 How to reach me on my discord: sh3tys
