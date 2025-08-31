# Cour : Introduction à NestJS

## 1. Définition

-   **NestJS** est un **framework backend Node.js** basé sur **TypeScript**.
-   Inspiré d’Angular, il utilise une architecture modulaire (Modules, Contrôleurs, Services).
-   Il est construit au-dessus de **Express** (par défaut) ou **Fastify**.
-   Objectif : **structurer les applications backend** avec une architecture claire, maintenable et testable.

## 2. Installation

### a. Prérequis

-   **Node.js** (>= 18 recommandé)
-   **npm** ou **yarn**

### b. Installer le CLI de NestJS

```bash
npm i -g @nestjs/cli
```

### c. Créer un nouveau projet

```bash
nest new projet-nest
```

👉 Choisis **npm** ou **yarn** pour gérer les dépendances.

### d. Lancer le projet

```bash
cd projet-nest
npm run start:dev
```

👉 Accès par défaut : `http://localhost:3000`

## 3. Use cases & projets où NestJS est intéressant

### ✅ Quand utiliser NestJS ?

-   Si tu veux un **backend bien structuré** (au lieu d’Express pur qui devient vite brouillon).
-   Pour des **APIs REST** classiques ou complexes.
-   Pour du **GraphQL** facilement intégré.
-   Pour du **Microservices** (Kafka, RabbitMQ, Redis, gRPC).
-   Pour des **applications d’entreprise** où la maintenabilité et les tests sont importants.

### 📌 Exemples de projets concrets :

1. **API CRUD** pour un site e-commerce (produits, utilisateurs, commandes).
2. **Auth système** (JWT + sessions).
3. **Backends microservices** pour une application bancaire/fintech.
4. **Application temps réel** (chat, notifications) avec WebSockets.
5. **Backend GraphQL** pour une app mobile.
