# 5ISS-2024-2025-JAULHIAC

This repository contains work I conducted as a part of the courses around the fabrication of a nano-particles based gas sensor and the processing of its data.

## Description

Ce projet intègre :
1. **Un capteur de gaz (WS2024)** pour mesurer des gaz tels que l'ammoniac (NH3), le dioxyde d'azote (NO2) et l'éthanol (C2H6O).
2. **Une application mobile** pour le contrôle et l'affichage, utilisant une connexion Bluetooth vers un microcontrôleur.
3. **Un système Arduino** pour gérer la capture des données du capteur, leur traitement et leur communication avec l'application mobile.

### Objectifs :
- Suivre les concentrations de gaz et déclencher des alertes si nécessaire.
- Contrôler des fonctionnalités à distance (comme allumer/éteindre une LED).
- Intégrer des commandes vocales pour faciliter l'interaction.

---

## 📂 Structure du Projet

- **Fichiers de Code :**
  - `BT_App.ino` : Contrôle Bluetooth pour Arduino.
  - `Gas_Sensor-OLED_Screen-W.ino` : Gestion du capteur de gaz avec affichage OLED.
  - `BTcodeArduino.ino` : Échange Bluetooth entre l'Arduino et l'application mobile.
- **Images et Schémas :**
  - `HomeScreenApp.png` et `MainControlScreenApp.png` : Aperçus de l'application mobile.
  - `Screen1BlockDiagram.png` et `Screen2BlockDiagram.png` : Diagrammes des blocs de l'application.
- **Documentation Technique :**
  - Rapport complet sur la simulation et la conception : `Rapport Elec Gas sensor - JAULHIAC.pdf`.
  - Datasheet du capteur : `JUMIN_JAULHIAC_GAUCHE_MARIN-MULLER_BOUJON_Datasheet_AIME.pdf`.

---

## Fonctionnalités

### 🌫️ Détection de gaz :
- Capteur WS2024 avec nanoparticules de trioxide de tungstène.
- Détection précise et faible consommation d'énergie.

### 📱 Application mobile :
- **Écran 1** : Page d'accueil avec accès au centre de contrôle.
- **Écran 2** : Contrôle Bluetooth :
  - Boutons pour allumer/éteindre une LED.
  - Commandes vocales pour exécuter des actions.
  - Réception des données du capteur en temps réel.

### Communication Bluetooth :
- Connexion entre l'application et un Arduino pour les commandes et le retour d'informations.

---

## Installation et Utilisation

### 🔹 Matériel requis :
- Capteur WS2024.
- Microcontrôleur Arduino (ou équivalent).
- Module Bluetooth HC-05 ou HC-06.
- Smartphone Android avec l'application installée.

### 🔹 Installation du code :
1. **Arduino** :
   - Téléverse les fichiers `.ino` dans l'Arduino via l'IDE.
   - Connecte le capteur et le module Bluetooth selon le schéma fourni.
2. **Application mobile** :
   - Installe l'APK générée pour Android.
   - Active le Bluetooth et connecte l'application au microcontrôleur.

### 🔹 Utilisation :
- Lance l'application mobile.
- Connecte-toi au module Bluetooth.
- Utilise les boutons ou la commande vocale pour interagir.

---

## Simulation et Analyse

- **Simulation LTSpice** : Réalisée pour valider les performances du système.
- **Filtrage et amplification** :
  - Gain du signal faible : 100x, conforme aux attentes.
  - Réduction du bruit 50 Hz via filtres passe-bas.
- **Réponse fréquentielle et temporelle** : Optimisée pour les signaux faibles du capteur.

---

## Roadmap

### Améliorations envisagées :
- Ajout d'une alerte sonore pour des seuils critiques.
- Intégration d'une base de données pour historiser les mesures.
- Portage de l'application vers iOS.

---

## Contact information

For any questions or suggestions regarding this project, feel free to contact me:

- **Name:** Paul JAULHIAC
- **Email:** jaulhiac@insa-toulouse.fr
- **GitHub:** [@PaulJaulhiac](https://github.com/PaulJaulhiac/)
