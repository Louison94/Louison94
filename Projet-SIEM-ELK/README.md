# 🛡️ Mise en Place d'un SIEM avec la Suite ELK

![ELK](https://img.shields.io/badge/SIEM-ELK%20Stack-005571?style=for-the-badge&logo=elastic&logoColor=white)
![Nginx](https://img.shields.io/badge/Service-NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Cisco](https://img.shields.io/badge/Network-Cisco%20Switches-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)

---

## 📌 Présentation du Projet

Déploiement d'une plateforme **SIEM** (*Security Information and Event Management*) reposant sur la suite **ELK** (*Elasticsearch, Logstash, Kibana*). Ce projet vise à centraliser, parser et analyser en temps réel les journaux d'événements (logs) de sécurité issus d'une infrastructure web (NGINX) et d'équipements réseaux physiques (Switchs Cisco).

---

## 🎯 Objectifs Techniques

* 📥 **Injest & Centralisation :** Récupération des flux Syslog en provenance des switchs Cisco et des logs d'accès/erreurs du serveur web NGINX.
* ⚙️ **Parsing personnalisé (Grok) :** Conception de filtres **Grok** avancés sous Logstash pour structurer la donnée brute.
* 📊 **Tableaux de bord (Dashboards) :** Création de visualisations et dashboards sur Kibana pour la supervision du trafic et la détection d'anomalies.

---

## 🛠️ Stack Technique

* **SIEM :** Elasticsearch, Logstash, Kibana (ELK Stack)
* **Parsing :** Filtres Grok, Logstash Pipelines
* **Sources de données :** Serveur Web NGINX, Switchs Cisco (Syslog)

---

## 📑 Documents & Visuels

* 📊 **[Dashboard Kibana & Documentation SIEM](./Dashboard_ELK.pdf)** *(Visuels des tableaux de bord et règles de parsing Grok)*

---

## 👥 Contributeurs

* **Louison PENAUD**
* **Équipe projet IUT de Créteil-Vitry (UPEC)**
