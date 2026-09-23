[← Retour au sommaire](README.md)

# Chapitre 10 — Sécurité réseau

## 📖 Rappel de la théorie
Menaces (DDoS, phishing, spoofing), pare-feu, IDS/IPS, VPN, chiffrement.

## 🧪 Lab 10.1 — Mettre en place un pare-feu (iptables/pfSense)
- **Objectif :** Écrire des règles de filtrage et vérifier leur effet.
- **Prérequis / Outils :** VM Linux (iptables) ou pfSense
- **Étapes détaillées :**
  1. Vérifier les règles actuelles (`sudo iptables -L`).
  2. Bloquer un port spécifique (ex : `sudo iptables -A INPUT -p tcp --dport 23 -j DROP`).
  3. Tester avant/après avec `telnet` ou `nmap` depuis une autre machine.
  4. Autoriser uniquement certains flux (ex : SSH depuis une IP précise).
  5. Sauvegarder les règles et documenter chaque commande utilisée.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧪 Lab 10.2 — Monter un tunnel VPN (WireGuard/OpenVPN)
- **Objectif :** Établir un tunnel chiffré entre deux machines.
- **Prérequis / Outils :** 2 VM, WireGuard ou OpenVPN
- **Étapes détaillées :**
  1. Installer WireGuard sur les deux machines.
  2. Générer une paire de clés publique/privée sur chaque machine.
  3. Configurer le fichier de config du serveur (IP du tunnel, clé publique du client).
  4. Configurer le fichier client correspondant (IP du tunnel, clé publique du serveur, endpoint).
  5. Démarrer le tunnel des deux côtés (`wg-quick up wg0`).
  6. Vérifier avec `ping` que le tunnel fonctionne, puis capturer le trafic pour confirmer qu'il est chiffré.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧩 Ajouter un nouveau lab
```
### 🧪 Lab 10.X — [Titre]
- **Objectif :**
- **Prérequis / Outils :**
- **Étapes détaillées :**
  1.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire
```
