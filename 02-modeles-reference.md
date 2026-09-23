[← Retour au sommaire](README.md)

# Chapitre 2 — Modèles de référence (OSI / TCP-IP)

## 📖 Rappel de la théorie
7 couches OSI, 4 couches TCP/IP, principe d'encapsulation d'une donnée en segment, paquet, trame puis bits.

## 🧪 Lab 2.1 — Visualiser l'encapsulation OSI
- **Objectif :** Suivre concrètement une donnée qui descend les couches jusqu'aux bits, puis remonte côté récepteur.
- **Prérequis / Outils :** Wireshark, un navigateur
- **Étapes détaillées :**
  1. Lancer Wireshark et démarrer une capture sur l'interface réseau active.
  2. Charger une page web simple dans un navigateur.
  3. Arrêter la capture et repérer une trame HTTP dans la liste.
  4. Développer les couches affichées par Wireshark : Frame, Ethernet II, Internet Protocol, TCP, HTTP.
  5. Associer chaque couche affichée à la couche OSI correspondante (physique/liaison, réseau, transport, application).
  6. Noter les informations clés relevées à chaque niveau (adresse MAC, IP, port, données).
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧪 Lab 2.2 — Faire correspondre OSI et TCP/IP sur une capture réelle
- **Objectif :** Identifier dans une capture Wireshark à quelle couche TCP/IP et OSI appartient chaque en-tête.
- **Prérequis / Outils :** Wireshark
- **Étapes détaillées :**
  1. Réutiliser la capture du Lab 2.1 (ou en refaire une incluant du DNS).
  2. Pour chaque trame, identifier les 4 couches TCP/IP : Accès réseau, Internet, Transport, Application.
  3. Construire un tableau de correspondance : couche TCP/IP ↔ couches OSI regroupées ↔ protocole observé.
  4. Repérer un paquet DNS et un paquet HTTP, comparer la structure de leurs en-têtes.
  5. Conclure sur le rôle joué par chaque couche dans l'échange observé.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧩 Ajouter un nouveau lab
```
### 🧪 Lab 2.X — [Titre]
- **Objectif :**
- **Prérequis / Outils :**
- **Étapes détaillées :**
  1.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire
```
