# 🧪 Mes Labs — Réseaux Informatiques

Ce fichier me permet de structurer tous mes **labs pratiques**, chapitre par chapitre, en suivant un gabarit unique. Chaque lab suit toujours le même format, ce qui rend le suivi et la relecture faciles — et le fichier peut être poussé tel quel comme README d'un dépôt GitHub.

## 📖 Comment l'utiliser

1. Chaque chapitre contient déjà 2 labs suggérés, prêts à être remplis au fur et à mesure.
2. Pour ajouter un lab supplémentaire, copie le **gabarit vierge** tout en bas du fichier.
3. Coche le statut au fil de ta progression : ⬜ À faire → 🔄 En cours → ✅ Terminé.
4. Mets à jour le tableau de suivi global ci-dessous en même temps que chaque lab.

---

## 📊 Suivi global

| Chapitre | Lab | Titre | Statut |
|---|---|---|---|
| 1 | 1.1 | Comparer les topologies réseau | ⬜ |
| 1 | 1.2 | Câbler un mini-LAN en étoile | ⬜ |
| 2 | 2.1 | Visualiser l'encapsulation OSI | ⬜ |
| 2 | 2.2 | Faire correspondre OSI et TCP/IP sur une capture réelle | ⬜ |
| 3 | 3.1 | Sertir et tester un câble RJ45 | ⬜ |
| 3 | 3.2 | Comparer cuivre vs fibre optique | ⬜ |
| 4 | 4.1 | Observer l'apprentissage MAC d'un switch | ⬜ |
| 4 | 4.2 | Configurer des VLAN et vérifier l'isolation | ⬜ |
| 5 | 5.1 | Calculer et découper des sous-réseaux IPv4 | ⬜ |
| 5 | 5.2 | Mettre en place un routage statique entre 3 réseaux | ⬜ |
| 6 | 6.1 | Comparer TCP et UDP avec des sockets Python | ⬜ |
| 6 | 6.2 | Capturer le 3-way handshake TCP | ⬜ |
| 7 | 7.1 | Monter un mini serveur HTTP et analyser les requêtes | ⬜ |
| 7 | 7.2 | Résoudre un nom de domaine « à la main » (DNS) | ⬜ |
| 8 | 8.1 | Maquetter un petit réseau d'entreprise | ⬜ |
| 8 | 8.2 | Configurer un routeur et un switch | ⬜ |
| 9 | 9.1 | Scanner et comparer les réseaux Wi-Fi à portée | ⬜ |
| 9 | 9.2 | Configurer un point d'accès en WPA2/WPA3 | ⬜ |
| 10 | 10.1 | Mettre en place un pare-feu (iptables/pfSense) | ⬜ |
| 10 | 10.2 | Monter un tunnel VPN (WireGuard/OpenVPN) | ⬜ |
| 11 | 11.1 | Superviser un petit réseau (SNMP) | ⬜ |
| 11 | 11.2 | Script de monitoring ping + journalisation | ⬜ |
| 12 | 12.1 | Créer un réseau virtuel entre plusieurs VM | ⬜ |
| 12 | 12.2 | Déployer un VPC sur un cloud gratuit | ⬜ |

---

## Chapitre 1 — Types et topologies de réseaux

### 🧪 Lab 1.1 — Comparer les topologies réseau
- **Objectif :** Simuler bus, étoile, anneau et maillée pour observer leurs comportements en cas de panne.
- **Prérequis / Outils :** Packet Tracer ou GNS3
- **Topologie / Schéma :**
- **Étapes réalisées :**
  1. Construire chaque topologie
  2. Simuler la panne d'un lien / d'un nœud
  3. Observer et noter l'impact
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 1.2 — Câbler un mini-LAN en étoile
- **Objectif :** Monter physiquement (ou virtuellement) un petit réseau en étoile autour d'un switch.
- **Prérequis / Outils :** Switch, câbles Ethernet (ou simulateur)
- **Topologie / Schéma :**
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 2 — Modèles de référence (OSI / TCP-IP)

### 🧪 Lab 2.1 — Visualiser l'encapsulation OSI
- **Objectif :** Suivre une donnée qui descend les 7 couches OSI jusqu'aux bits, puis remonte côté récepteur.
- **Prérequis / Outils :** Papier/schéma ou Wireshark
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 2.2 — Faire correspondre OSI et TCP/IP sur une capture réelle
- **Objectif :** Identifier, dans une capture Wireshark, à quelle couche appartient chaque en-tête.
- **Prérequis / Outils :** Wireshark
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 3 — Couche physique

### 🧪 Lab 3.1 — Sertir et tester un câble RJ45
- **Objectif :** Réaliser un câble droit (et un croisé) et vérifier son fonctionnement.
- **Prérequis / Outils :** Pince à sertir, connecteurs RJ45, testeur de câble
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 3.2 — Comparer cuivre vs fibre optique
- **Objectif :** Établir un comparatif chiffré (débit, portée, coût, sensibilité aux interférences).
- **Prérequis / Outils :** Recherche documentaire
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 4 — Couche liaison de données

### 🧪 Lab 4.1 — Observer l'apprentissage MAC d'un switch
- **Objectif :** Visualiser comment un switch construit sa table d'adresses MAC.
- **Prérequis / Outils :** Packet Tracer / switch réel + Wireshark
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 4.2 — Configurer des VLAN et vérifier l'isolation
- **Objectif :** Créer 2 VLAN et prouver qu'ils ne communiquent pas sans routage inter-VLAN.
- **Prérequis / Outils :** Packet Tracer ou switch manageable
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 5 — Couche réseau

### 🧪 Lab 5.1 — Calculer et découper des sous-réseaux IPv4
- **Objectif :** Découper un bloc IPv4 en plusieurs sous-réseaux selon un besoin donné.
- **Prérequis / Outils :** Calculatrice / script Python
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 5.2 — Mettre en place un routage statique entre 3 réseaux
- **Objectif :** Faire communiquer 3 réseaux différents via des routes statiques.
- **Prérequis / Outils :** Packet Tracer / GNS3
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 6 — Couche transport

### 🧪 Lab 6.1 — Comparer TCP et UDP avec des sockets Python
- **Objectif :** Écrire un client/serveur en TCP puis en UDP et comparer fiabilité/vitesse.
- **Prérequis / Outils :** Python
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 6.2 — Capturer le 3-way handshake TCP
- **Objectif :** Identifier SYN, SYN-ACK, ACK dans une capture réseau.
- **Prérequis / Outils :** Wireshark
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 7 — Couche application

### 🧪 Lab 7.1 — Monter un mini serveur HTTP et analyser les requêtes
- **Objectif :** Lancer un serveur HTTP local et observer les requêtes reçues.
- **Prérequis / Outils :** Python (`http.server`), navigateur
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 7.2 — Résoudre un nom de domaine « à la main » (DNS)
- **Objectif :** Interroger un serveur DNS et comprendre les étapes de résolution.
- **Prérequis / Outils :** `nslookup` / `dig`
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 8 — Équipements réseau

### 🧪 Lab 8.1 — Maquetter un petit réseau d'entreprise
- **Objectif :** Intégrer switch, routeur, pare-feu et point d'accès dans une seule maquette.
- **Prérequis / Outils :** Packet Tracer
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 8.2 — Configurer un routeur et un switch
- **Objectif :** Réaliser une configuration de base (interfaces, VLAN, routage) en CLI.
- **Prérequis / Outils :** Packet Tracer / matériel réel
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 9 — Réseaux sans fil

### 🧪 Lab 9.1 — Scanner et comparer les réseaux Wi-Fi à portée
- **Objectif :** Lister les réseaux Wi-Fi environnants et leur niveau de sécurité (WEP/WPA/WPA2/WPA3).
- **Prérequis / Outils :** Outil de scan Wi-Fi
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 9.2 — Configurer un point d'accès en WPA2/WPA3
- **Objectif :** Comparer la configuration et la sécurité offerte par WPA2 et WPA3.
- **Prérequis / Outils :** Point d'accès configurable
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 10 — Sécurité réseau

### 🧪 Lab 10.1 — Mettre en place un pare-feu (iptables/pfSense)
- **Objectif :** Écrire des règles de filtrage et vérifier leur effet.
- **Prérequis / Outils :** VM Linux (iptables) ou pfSense
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 10.2 — Monter un tunnel VPN (WireGuard/OpenVPN)
- **Objectif :** Établir un tunnel chiffré entre deux machines.
- **Prérequis / Outils :** 2 VM, WireGuard ou OpenVPN
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 11 — Administration et qualité de service

### 🧪 Lab 11.1 — Superviser un petit réseau (SNMP)
- **Objectif :** Mettre en place une supervision basique d'équipements via SNMP.
- **Prérequis / Outils :** Zabbix / Nagios
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 11.2 — Script de monitoring ping + journalisation
- **Objectif :** Automatiser la surveillance de disponibilité de plusieurs machines.
- **Prérequis / Outils :** Python
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## Chapitre 12 — Cloud et virtualisation

### 🧪 Lab 12.1 — Créer un réseau virtuel entre plusieurs VM
- **Objectif :** Interconnecter plusieurs machines virtuelles sur un réseau isolé.
- **Prérequis / Outils :** VirtualBox / VMware
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

### 🧪 Lab 12.2 — Déployer un VPC sur un cloud gratuit
- **Objectif :** Créer un réseau virtuel privé chez un fournisseur cloud et documenter l'architecture.
- **Prérequis / Outils :** AWS / Azure / GCP (offre gratuite)
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

---

## 🧩 Gabarit vierge (à dupliquer pour tout nouveau lab)

```
### 🧪 Lab X.Y — [Titre du lab]
- **Objectif :**
- **Prérequis / Outils :**
- **Topologie / Schéma :**
- **Étapes réalisées :**
  1.
  2.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire
```
