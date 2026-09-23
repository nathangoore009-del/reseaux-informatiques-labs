[← Retour au sommaire](README.md)

# Chapitre 5 — Couche réseau

## 📖 Rappel de la théorie
Adressage IPv4/IPv6, sous-réseaux, routage statique/dynamique, NAT.

## 🧪 Lab 5.1 — Calculer et découper des sous-réseaux IPv4
- **Objectif :** Découper un bloc IPv4 en plusieurs sous-réseaux selon un besoin donné.
- **Prérequis / Outils :** Calculatrice, script Python ou calculateur en ligne
- **Étapes détaillées :**
  1. Partir d'un bloc donné, ex : 192.168.1.0/24.
  2. Définir un besoin (ex : 4 sous-réseaux de tailles égales).
  3. Calculer le nouveau masque nécessaire (ex : /26 pour 4 sous-réseaux).
  4. Lister chaque sous-réseau : adresse réseau, plage utilisable, adresse de broadcast.
  5. Vérifier les calculs avec un script Python ou un outil en ligne.
  6. Appliquer concrètement en configurant ces sous-réseaux sur des VLAN différents dans Packet Tracer.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧪 Lab 5.2 — Mettre en place un routage statique entre 3 réseaux
- **Objectif :** Faire communiquer 3 réseaux différents via des routes statiques.
- **Prérequis / Outils :** Packet Tracer ou GNS3
- **Étapes détaillées :**
  1. Créer 3 sous-réseaux distincts reliés par 2 routeurs.
  2. Configurer les interfaces des routeurs avec les bonnes adresses IP.
  3. Ajouter des routes statiques sur chaque routeur pour atteindre les réseaux non directement connectés.
  4. Configurer la passerelle par défaut sur les PC de chaque réseau.
  5. Tester la connectivité de bout en bout avec `ping` et `tracert`/`traceroute`.
  6. Documenter la table de routage finale de chaque routeur.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧩 Ajouter un nouveau lab
```
### 🧪 Lab 5.X — [Titre]
- **Objectif :**
- **Prérequis / Outils :**
- **Étapes détaillées :**
  1.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire
```
