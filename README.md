# 👋 Bonjour, c'est Sainaro Khalid

### 🚀 Développeur Fullstack JavaScript orienté SaaS, Temps Réel & DevOps

📍 Basé à Nice (06) <br>
🚗 Mobile : Monaco, Nice, Antibes, Sophia Antipolis, Cannes, Cagnes-sur-Mer <br>
🟢 Disponible immédiatement (CDI / Freelance / Prestation) <br>

---

## 🚀 À propos de moi

Développeur Fullstack passionné par l'écosystème JavaScript moderne, je conçois des applications web et SaaS robustes, sécurisées et orientées produit.

Mon expertise s'articule autour de :
- 🏢 **SaaS B2B Multi-tenant** : Logique métier complexe, conformité légale (Facturation électronique 2026), facturation récurrente Stripe.
- ⚡ **Temps Réel & Omnicanalité** : WebSockets (**Socket.IO**), messagerie unifiée (**SMS Twilio, WhatsApp Business, Emailing via Resend & IMAP/SMTP**).
- 📱 **Mobile & PWA First** : Expérience fluide hors-ligne / PWA, signature électronique tactile, gestion de planning interactif.
- 🛠 **DevOps & Architecture** : Conteneurisation (**Docker & Compose**), orchestration VPS (**Hetzner**), cache & rate-limiting distribué (**Redis**), pipelines **CI/CD automatisés (GitHub Actions)**.

👉 **Mon objectif** : Transformer des besoins métiers complexes en outils intuitifs, performants et à haute valeur ajoutée.

---

## 🏆 Projet Phare en Production

### ⚡ [GestArt CRM — SaaS Omnicanal & Facturation 2026 pour Artisans](https://gestart.fr)

Plateforme SaaS complète (Web & PWA) dédiée aux artisans et entreprises de maintenance technique (chauffagistes, frigoristes, ramoneurs, électriciens). Elle centralise les interventions sur le terrain, le planning d'équipe, la messagerie client omnicanale et la facturation conforme aux réformes légales.

[![Production Live](https://img.shields.io/badge/Production%20Live-gestart.fr-556B2F?style=for-the-badge&logo=google-chrome&logoColor=white)](https://gestart.fr)
[![API Status](https://img.shields.io/badge/API%20Status-En%20Ligne-green?style=for-the-badge&logo=fastapi&logoColor=white)](https://api.gestart.fr)

#### 🎯 Points clés de l'architecture & Fonctionnalités :
- 📜 **Facturation & Devis Électroniques (Loi 2026)** : Génération PDF vectorielle dynamique à la volée, mentions légales obligatoires, ventilation TVA, catégories URSSAF (BIC/BNC) et portail client de signature en ligne.
- 💬 **Inbox Omnicanale Unifiée en Temps Réel** : Moteur de messagerie centralisé avec synchronisation **Socket.IO** bidirectionnelle :
  - **SMS** via l'API Twilio
  - **WhatsApp** via l'API Meta Cloud / WhatsApp Business
  - **Emailing transactionnel** via Resend API (HTTP 443) avec fallback SMTP et synchronisation IMAP de boîtes Gmail/Workspace.
- 📅 **Planning & Dispatch Techniciens** : Vue calendrier dynamique, gestion d'interventions géolocalisées, fiches de travail mobiles avec signature tactile client et photos avant/après intervention.
- 📱 **PWA & Mobile-First** : Expérience native sur smartphone (PWA installable, gestuelle Pull-to-Refresh, barre de navigation élastique, support offline partiel).
- 💳 **Monétisation & Abonnements** : Intégration complète de l'API **Stripe** (gestion des abonnements Starter / Pro / Unlimited, portail client, webhooks sécurisés).
- 🛡️ **Sécurité & Résilience** : Authentification stateless double-token (JWT Access + Refresh Token en cookie `HttpOnly` sécurisé SameSite), Rate Limiting distribué sous **Redis** pour bloquer les attaques brute-force.
- 🚀 **DevOps & Déploiement Continu** : 
  - Conteneurisation complète avec **Docker Compose** (services Client, Server, PostgreSQL, Redis).
  - Déploiement automatique sans interruption via **GitHub Actions** sur serveur VPS dédié **Hetzner** avec reverse-proxy Nginx & certificats SSL Let's Encrypt.

**Stack :**  
`React 19` · `Vite 8` · `Node.js (ESM)` · `Express` · `Socket.IO` · `PostgreSQL` · `Prisma ORM` · `Redis` · `Twilio API` · `Resend API` · `Stripe API` · `Docker` · `GitHub Actions` · `Hetzner Cloud`

---

## 💼 Autres réalisations

### 💻 [SaaS Pro — Plateforme Collaborative de Tâches](https://saaspro.online)
Outil SaaS d'organisation et de gestion de projets agiles avec synchronisation instantanée des tableaux d'activité entre collaborateurs.
- Synchronisation d'état temps réel avec **Socket.IO** et stockage persistant optimisé.
- Sécurisation des endpoints critiques via Redis Rate Limiter et Google OAuth2.

**Stack :** `React` · `TailwindCSS` · `Express` · `Prisma` · `PostgreSQL` · `Redis` · `Docker`

---

### 🛒 E-Commerce & Dashboard Administrateur
Boutique en ligne avec catalogue dynamique, panier persistant, suivi des stocks en temps réel et back-office de gestion des ventes et statistiques.

**Stack :** `Node.js` · `Express` · `PostgreSQL / MongoDB` · `JWT` · `REST API`

---

## 🧠 Compétences techniques

### 🎨 Frontend & Mobile Web
![React](https://img.shields.io/badge/-React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/-Vite_8-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript_ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/-PWA_Ready-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)
![Tailwind](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/-Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

### ⚙️ Backend & Architecture
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/-Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/-Prisma_ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### 🔌 APIs & Intégrations Tierces
![Stripe](https://img.shields.io/badge/-Stripe_Payments-008CDD?style=for-the-badge&logo=stripe&logoColor=white)
![Twilio](https://img.shields.io/badge/-Twilio_SMS-F22F46?style=for-the-badge&logo=twilio&logoColor=white)
![WhatsApp](https://img.shields.io/badge/-WhatsApp_Business-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Resend](https://img.shields.io/badge/-Resend_Email-000000?style=for-the-badge&logo=resend&logoColor=white)

### 🚀 DevOps, Cloud & CI/CD
![Docker](https://img.shields.io/badge/-Docker_&_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions_CI/CD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Hetzner](https://img.shields.io/badge/-Hetzner_Cloud-D50C2F?style=for-the-badge&logo=hetzner&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx_Proxy-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 🎯 Ce que j’apporte à votre équipe

- 🛠️ **Vision Produit de bout en bout** : Capacité à mener un SaaS de l'idée initiale à la production réelle (architecture, code, déploiement, conformité, UX).
- 🧩 **Fiabilité & Robustesse** : Maîtrise des problématiques de concurrence, de sessions sécurisées (anti-CSRF/XSS) et de gestion d'erreurs en production.
- ⚡ **Culture du Temps Réel** : Savoir architecturer des WebSockets propres sans fuite mémoire ni surcharge serveur.
- 🔄 **Autonomie DevOps** : Capable de monter et maintenir une infrastructure conteneurisée sécurisée avec déploiements automatisés sans interruption de service.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Saynaro&show_icons=true&theme=radical&hide_border=true" height="160px"/>
  <img src="https://streak-stats.demolab.com?user=Saynaro&theme=radical&hide_border=true" height="160px"/>
</p>

---

## 📬 Me Contacter

- 💼 **LinkedIn** : [linkedin.com/in/sainaro-khalid](https://www.linkedin.com/in/sainaro-khalid)
- 📧 **Email** : [khalid.sainaro@gmail.com](mailto:khalid.sainaro@gmail.com)
- 🌐 **Portfolio** : [khalidsainaro.site](https://khalidsainaro.site)
- **Projet** : [gestart.fr](https://gestart.fr)
