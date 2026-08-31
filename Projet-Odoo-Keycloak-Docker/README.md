# 🔐 Déploiement ERP Odoo & Authentification Centralisée Keycloak (Docker)

![Odoo](https://img.shields.io/badge/ERP-Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white)
![Keycloak](https://img.shields.io/badge/IAM-Keycloak-008A87?style=for-the-badge&logo=keycloak&logoColor=white)
![Docker](https://img.shields.io/badge/Orchestration-Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/OS-Ubuntu%20Server-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

---

## 📌 Présentation du Projet

Projet réalisé dans le cadre du cursus à l'**IUT de Créteil-Vitry (UPEC)**. L'objectif était de déployer une solution ERP open-source (**Odoo**) intégrée à une gestion centralisée des identités et des accès (IAM) avec **Keycloak** pour permettre l'authentification unique (**SSO**).

L'ensemble de la solution a été conteneurisé afin d'automatiser le déploiement et d'assurer une gestion fluide des services.

---

## 🎯 Objectifs Techniques

* 🚀 **Conteneurisation :** Orchestration multi-conteneurs d'Odoo, Keycloak et de la base de données PostgreSQL via **Docker Compose**.
* 🔑 **Intégration IAM / SSO :** Configuration de Keycloak pour la gestion des utilisateurs et liaison avec Odoo via le module `auth_oauth_keycloak`.
* 🖥️ **Hébergement :** Déploiement et sécurisation de l'infrastructure sur une VM **Ubuntu Server**.
* 📊 **Gestion de Projet Agile :** Suivi du projet en sprints avec **GitHub Projects** et versionnage sous **Git/GitLab**.

---

## 🛠️ Stack Technique

* **ERP :** Odoo
* **Identity Management :** Keycloak (OAuth2 / OpenID Connect)
* **Conteneurisation :** Docker, Docker Compose
* **OS & Tools :** Ubuntu Server, Git, GitHub Projects, GitLab

---

## 📑 Documents Disponibles

* 📄 **[Rapport de Projet Odoo & Keycloak](./Rapport_Odoo_Keycloak.pdf)** *(Guide d'installation, configuration OAuth2 et retour d'expérience)*

---

## 👥 Contributeurs

* **Louison PENAUD**
* **Équipe projet IUT de Créteil-Vitry (UPEC)**
