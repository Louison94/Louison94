# 📡 Déploiement d'un Cœur de Réseau Cellulaire 4G/5G Standalone (Open5GS & SDR)

![5G](https://img.shields.io/badge/Network-5G%20SA%20%2F%20NSA-0055A5?style=for-the-badge)
![Open5GS](https://img.shields.io/badge/Core-Open5GS-blue?style=for-the-badge)
![SDR](https://img.shields.io/badge/Hardware-SDR-orange?style=for-the-badge)
![Linux](https://img.shields.io/badge/OS-Ubuntu%20Server-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

---

## 📌 Présentation du Projet

Ce projet académique, réalisé dans le cadre du cursus **BUT Réseaux & Télécommunications à l'IUT de Créteil-Vitry (UPEC)**, porte sur l'étude théorique, le déploiement et la mise en œuvre pratique d'un réseau cellulaire **4G (LTE)** et **5G (Standalone / Non-Standalone)**.

L'objectif principal a été de partir de la découverte des architectures logicielles et protocolaires de la téléphonie mobile pour aboutir à l'intégration sur des équipements physiques de radio logicielle (**SDR - Software Defined Radio**).

---

## 🎯 Objectifs Techniques

* 🏗️ **Architecture Cœur de Réseau :** Instancier, configurer et interconnecter les entités logicielles du cœur de réseau Open5GS (AMF, SMF, UPF, NRF, UDM, AUSF, NAUSF, etc.).
* 🔄 **Comparatif SA vs NSA :** Analyser et comprendre les différences structurelles et comportementales entre une architecture **5G SA (Standalone)** et **5G NSA (Non-Standalone)**.
* 📻 **Traitement Radio (SDR) :** Utiliser des équipements SDR pour assurer la transmission et la réception du signal radiofréquence, ainsi que le traitement des bandes de fréquences.
* 👥 **Gestion des Abonnés :** Alimenter la base de données de souscription SIM/USIM via WebUI/Open5GS pour valider l'enregistrement, l'authentification et l'établissement de sessions de données (PDU Sessions).

---

## 🛠️ Stack Technique & Outils

* **Cœur de Réseau (Core Network) :** [Open5GS](https://open5gs.org/) (Cœur open-source 4G/5G)
* **Équipements Radio :** Software Defined Radio (SDR)
* **Système d'Exploitation :** Linux Ubuntu Server
* **Analyse de Trafic / Capture :** Wireshark (Filtres NGAP, NAS, GTP-U, PFCP)
* **Protocoles clés :** NGAP, NAS, GTP-U, PFCP, HTTP/2 (Interface basée sur les services SBA en 5G)


## 📑 Documents & Rapports Disponibles

Tous les documents relatifs à l'ingénierie et aux résultats de ce projet sont consultables directement dans ce dossier :

* 📄 **[Rapport de projet - Déploiement 5G & 4G](./Rapport_5G_Open5GS.pdf)** *(Analyse des architectures, étapes de configuration et relevés de captures Wireshark)*
* 📊 **[Présentation / Infographie du projet](./Presentation_5G_4G.pdf)** *(Support synthétique décrivant la démarche technique)*

---

## 👥 Contributeurs

* **Louison PENAUD** — *Étudiant en Ingénierie Réseaux & Sécurité (ESIEE Paris / Orange)*
* **Équipe projet IUT de Créteil-Vitry (UPEC)**

            
