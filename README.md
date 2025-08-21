# hassio

---

# 🏠 Projet Domotique avec Home Assistant (Hass.io)

Ce projet est mon **premier serveur domotique personnel et local**, basé sur **Home Assistant (Hass.io)**.
Il m’a permis de découvrir en profondeur la configuration **YAML**, d’apprendre Linux et de mettre en place une véritable plateforme domotique complète.

---

## 🎯 Objectifs du projet

* Automatiser certaines **tâches quotidiennes** de la maison
* **Digitaliser la liste de courses** pour la gérer depuis n’importe quel appareil
* Monitorer le **réseau**, le **serveur** et mon **imprimante 3D**
* Servir de **serveur de stockage** (ProFTPD)
* Servir de **serveur multimédia** (Plex)
* Découvrir et mettre en place le protocole **MQTT**
* Configurer un **ESP32 + capteur DHT11** pour envoyer périodiquement les données à Home Assistant
* Approfondir mon usage de Linux (moi qui venais exclusivement de Windows à l’époque)

---

## 🧑‍💻 Compétences acquises

* Maîtrise **complète du YAML** (configuration Home Assistant, automatisations, scripts)
* Mise en place d’un **serveur Linux (Linux Mint → basé sur Ubuntu → basé sur Debian)**
* Déploiement et configuration de **Home Assistant Hass.io avec Add-on Store**
* Découverte et pratique de protocoles et services : **MQTT, ProFTPD, Plex, OctoPrint, Glances API, Speedtest.net API, Todoist API, DarkSky API**
* Réalisation d’un écosystème domotique **100% open-source et local**

> Contrairement à mes autres projets, celui-ci comporte très peu de code en Python ou JavaScript : **99% du travail a été fait en YAML et en configuration système**.

---

## 📚 Contenu du repository

Ce dépôt contient mes principaux fichiers de configuration Home Assistant :

* `configuration.yaml` → configuration principale
* `automations.yaml` → automatisations (ex : éclairage jardin, chauffage, réveil)
* `scripts.yaml` → scripts pour exécuter des actions personnalisées

---

## 🖼️ Illustrations

*(Toutes les captures d’écran proviennent de **MON interface Home Assistant**, elles varient selon les configurations de chacun.)*

* **Page d’accueil**
  ![Accueil](https://github.com/user-attachments/assets/16ec8287-c3ed-4330-ab5d-5625775535ef)


* **Liste de courses interactive** (ajout, suppression, cases à cocher)
  ![Liste de courses](https://github.com/user-attachments/assets/31561fa8-11ac-4aaf-a1b1-98853591a0a9)


* **Météo (DarkSky API)** → détails + prévisions popup
  ![Météo](https://github.com/user-attachments/assets/17432751-26c0-4b26-bbdd-9e5f5c419f98)
  ![Météo détails](https://github.com/user-attachments/assets/180c921c-04f5-4abe-8506-e0c31c425dc7)




* **Carte du monde** (positions des appareils & zones configurées)
  ![Carte du monde](map.png)

* **Contrôle du salon**
  ![Salon](https://github.com/user-attachments/assets/4bb5f2d9-e766-4187-af22-7c45687ff4a9)


* **Contrôle du jardin** (profils + horaires + modes soleil/heure)
  ![Jardin](https://github.com/user-attachments/assets/7aad6106-2f35-4d97-9075-a9603437dea5)


* **Contrôle chambre & imprimante 3D (OctoPrint sur Raspberry Pi 3B)**
  ![Chambre](https://github.com/user-attachments/assets/a672d964-ffaa-45aa-bbfc-18aa000a67f6)


* **Module de contrôle du réveil**
  ![Réveil](https://github.com/user-attachments/assets/3089a205-d194-4a05-ba9d-23f8db5616c8)


* **Monitoring réseau et serveur (Speedtest API + Glances)**
  ![Monitoring](https://github.com/user-attachments/assets/10d4cc36-f89a-42a9-98db-062baa114371)


* **Gestion des devoirs à rendre (Todoist API)**
  ![Devoirs](https://github.com/user-attachments/assets/769c2e75-edc7-40b8-9c48-512ce045fb1b)


* **Add-ons installés + thème dark mode**
  ![Add-ons](https://github.com/user-attachments/assets/fd8718c3-6740-4aba-9cab-d023c8a55090)


---

## ⚙️ Prérequis

* **PC recyclé** avec Linux Mint (ou autre distrib basée sur Debian/Ubuntu)
* **Home Assistant (Hass.io)** installé avec Add-on Store
* Matériel domotique compatible (ESP32, DHT11, imprimante 3D, capteurs, etc.)
