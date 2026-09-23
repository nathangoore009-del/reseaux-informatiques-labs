[← Retour au sommaire](README.md)

# Chapitre 4 — Couche liaison de données

## 📖 Rappel de la théorie
Adressage MAC, trames Ethernet, commutation, VLAN, domaines de collision et de diffusion, ARP.

## 🧪 Lab 4.1 — Observer l'apprentissage MAC d'un switch
- **Objectif :** Visualiser comment un switch construit sa table d'adresses MAC.
- **Prérequis / Outils :** Packet Tracer (ou switch réel)
- **Étapes détaillées :**
  1. Créer un réseau avec 1 switch et 3 PC.
  2. Vider ou réinitialiser la table MAC du switch.
  3. Envoyer un `ping` du PC1 vers le PC2.
  4. Afficher la table d'adresses MAC (`show mac address-table`) et observer les entrées apprises.
  5. Envoyer un ping vers un PC qui n'a jamais communiqué et observer la diffusion (flooding) avant apprentissage.
  6. Documenter l'évolution de la table MAC après chaque échange.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧪 Lab 4.2 — Configurer des VLAN et vérifier l'isolation
- **Objectif :** Créer 2 VLAN et prouver qu'ils sont isolés sans routage inter-VLAN.
- **Prérequis / Outils :** Switch manageable ou Packet Tracer
- **Étapes détaillées :**
  1. Créer 2 VLAN (ex : VLAN 10 et VLAN 20) sur le switch.
  2. Assigner certains ports au VLAN 10 et d'autres au VLAN 20.
  3. Connecter des PC sur ces ports, avec des IP du même sous-réseau.
  4. Tenter un `ping` entre un PC du VLAN 10 et un PC du VLAN 20 : constater l'échec.
  5. Tenter un `ping` entre deux PC du même VLAN : constater le succès.
  6. (Optionnel) Ajouter un routeur pour router entre les VLAN et rétablir la communication.
  7. Documenter la configuration (commandes utilisées, captures d'écran).
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧩 Ajouter un nouveau lab
```
### 🧪 Lab 4.X — [Titre]
- **Objectif :**
- **Prérequis / Outils :**
- **Étapes détaillées :**
  1.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire
```
