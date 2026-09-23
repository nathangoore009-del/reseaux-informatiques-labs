[← Retour au sommaire](README.md)

# Chapitre 7 — Couche application

## 📖 Rappel de la théorie
HTTP/HTTPS, DNS, DHCP, FTP, SMTP/POP/IMAP, SSH.

## 🧪 Lab 7.1 — Monter un mini serveur HTTP et analyser les requêtes
- **Objectif :** Observer concrètement le fonctionnement d'un échange HTTP.
- **Prérequis / Outils :** Python, un navigateur, Wireshark
- **Étapes détaillées :**
  1. Dans un dossier, lancer `python -m http.server 8000`.
  2. Ouvrir un navigateur et accéder à `http://localhost:8000`.
  3. Observer dans le terminal les logs de requêtes reçues par le serveur.
  4. Ouvrir Wireshark en parallèle et capturer l'échange.
  5. Identifier la méthode (GET), le code de réponse (200, 404...), les en-têtes échangés.
  6. Documenter le format d'une requête et d'une réponse HTTP observées.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧪 Lab 7.2 — Résoudre un nom de domaine « à la main » (DNS)
- **Objectif :** Comprendre les étapes de résolution d'un nom de domaine.
- **Prérequis / Outils :** `nslookup` ou `dig`
- **Étapes détaillées :**
  1. Utiliser `nslookup <nom-de-domaine>` pour obtenir l'adresse IP correspondante.
  2. Relancer la commande en précisant un serveur DNS particulier (ex : `nslookup google.com 8.8.8.8`).
  3. Observer les différents types d'enregistrements affichés (A, AAAA, CNAME).
  4. Utiliser `dig +trace <nom-de-domaine>` pour visualiser toute la chaîne de résolution (racine → TLD → domaine).
  5. Schématiser les étapes de résolution observées.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧩 Ajouter un nouveau lab
```
### 🧪 Lab 7.X — [Titre]
- **Objectif :**
- **Prérequis / Outils :**
- **Étapes détaillées :**
  1.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire
```
