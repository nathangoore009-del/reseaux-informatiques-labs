[← Retour au sommaire](README.md)

# Chapitre 11 — Administration et qualité de service

## 📖 Rappel de la théorie
SNMP, supervision, QoS, outils ping/traceroute/nslookup/Wireshark.

## 🧪 Lab 11.1 — Superviser un petit réseau (SNMP)
- **Objectif :** Mettre en place une supervision basique d'équipements via SNMP.
- **Prérequis / Outils :** Zabbix, Nagios ou LibreNMS
- **Étapes détaillées :**
  1. Installer un outil de supervision sur une VM.
  2. Activer SNMP sur les équipements à superviser (routeur, switch, serveur).
  3. Ajouter ces équipements dans l'outil via leur IP et leur communauté SNMP.
  4. Configurer une alerte simple (ex : équipement injoignable).
  5. Simuler une panne (couper un lien) et vérifier que l'alerte se déclenche.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧪 Lab 11.2 — Script de monitoring ping + journalisation
- **Objectif :** Automatiser la surveillance de disponibilité de plusieurs machines.
- **Prérequis / Outils :** Python
- **Étapes détaillées :**
  1. Écrire un script qui lit une liste d'adresses IP depuis un fichier.
  2. Pour chaque IP, envoyer un ping (via `os.system` ou la librairie `ping3`).
  3. Journaliser le résultat (date, IP, succès/échec) dans un fichier log.
  4. Planifier l'exécution du script toutes les X minutes (cron ou tâche planifiée).
  5. Analyser le fichier log après quelques heures pour repérer des indisponibilités.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧩 Ajouter un nouveau lab
```
### 🧪 Lab 11.X — [Titre]
- **Objectif :**
- **Prérequis / Outils :**
- **Étapes détaillées :**
  1.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire
```
