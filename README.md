# 🏠 Kamer Home Solution

Plateforme web de gestion et de mise en relation dans le domaine immobilier (achat, location, gestion de biens).

---

## 🚀 Objectif du projet

Kamer Home Solution est une application web permettant :

* 🔍 Rechercher des logements
* 🏘️ Publier des biens immobiliers
* 👤 Gérer les utilisateurs (clients / admins)
* 📦 Gérer les réservations et commandes
* 🔐 Assurer la sécurité des données

---

## 🧱 Stack technique

### Frontend

* Next.js
* TypeScript
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js
* TypeScript

### Base de données

* (à définir : MySQL / MongoDB)

---

## 📁 Structure du projet

```
kamer.home.solution/
│
├── frontend/        # Application Next.js
├── backend/         # API REST Node.js
│
└── README.md
```

---

## ⚙️ Installation du projet

### 1. Cloner le projet

```
git clone https://github.com/ariol135/kamer.home.solution.git
cd kamer.home.solution
```

---

### 2. Lancer le frontend

```
cd frontend
npm install
npm run dev
```

---

### 3. Lancer le backend

```
cd backend
npm install
npm run dev
```

---

## 🔌 Architecture

Le projet suit une architecture API REST :

```
Route → Controller → Service → Model
```

Exemple :

* GET /houses
* POST /users

---

## 🔁 Méthodologie Agile

Le projet est organisé en sprints :

### Sprint 0 – Préparation

* Initialisation du projet
* Choix de l’architecture
* Mise en place des outils Agile

### Sprint 1 – Authentification

* Login / Register
* API utilisateurs

### Sprint 2 – Gestion des biens

* CRUD logements
* Interface utilisateur

---

## 🌿 Workflow Git

Branches utilisées :

* main → production
* dev → développement
* feature/... → nouvelles fonctionnalités

Exemple :

```
git checkout -b feature/login
```

---

## 👥 Équipe

* Frontend Developer
* Backend Developer
* Designer UI/UX
* Scrum Master

---

## 📌 Bonnes pratiques

* Ne jamais push `node_modules`
* Utiliser `.env` pour les variables sensibles
* Commits clairs et structurés
* Travail en branches

---

## 🔒 Sécurité

* Validation des données
* Gestion des erreurs
* Authentification sécurisée (JWT à venir)

---

## 📈 Évolutions futures

* Intégration paiement (Mobile Money)
* Dashboard admin
* Notifications
* Déploiement cloud (AWS)

---

## 📬 Contact

Projet réalisé dans le cadre d’un apprentissage professionnel en développement web fullstack et architecture cloud.

---
