[← Retour au sommaire](README.md)

# Chapitre 6 — Couche transport

## 📖 Rappel de la théorie
TCP (fiable, orienté connexion) vs UDP (rapide, sans connexion), notion de ports.

## 🧪 Lab 6.1 — Comparer TCP et UDP avec des sockets Python
- **Objectif :** Observer concrètement les différences de fiabilité entre TCP et UDP.
- **Prérequis / Outils :** Python
- **Étapes détaillées :**
  1. Écrire un serveur TCP simple (`socket.SOCK_STREAM`) qui reçoit un message et répond.
  2. Écrire un client TCP qui se connecte et envoie un message.
  3. Écrire un serveur UDP équivalent (`socket.SOCK_DGRAM`), sans connexion préalable.
  4. Écrire le client UDP correspondant.
  5. Couper le serveur en plein échange et observer le comportement du client TCP puis du client UDP.
  6. Noter les différences observées (erreurs, timeouts, fiabilité).
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧪 Lab 6.2 — Capturer le 3-way handshake TCP
- **Objectif :** Identifier SYN, SYN-ACK et ACK dans une vraie capture réseau.
- **Prérequis / Outils :** Wireshark
- **Étapes détaillées :**
  1. Lancer Wireshark et démarrer une capture.
  2. Initier une connexion TCP (ex : ouvrir une page web ou faire `telnet <ip> 80`).
  3. Arrêter la capture et filtrer avec `tcp.flags.syn==1 or tcp.flags.ack==1`.
  4. Identifier les 3 paquets du handshake : SYN, SYN-ACK, ACK.
  5. Noter les numéros de séquence (Seq) et d'accusé de réception (Ack) de chaque paquet.
  6. Expliquer avec ses propres mots le rôle de chaque étape du handshake.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧩 Ajouter un nouveau lab
```
### 🧪 Lab 6.X — [Titre]
- **Objectif :**
- **Prérequis / Outils :**
- **Étapes détaillées :**
  1.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire
```
