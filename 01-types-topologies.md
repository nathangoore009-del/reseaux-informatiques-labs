[← Retour au sommaire](README.md)

# Chapitre 1 — Types et topologies de réseaux

## 📖 Rappel de la théorie
PAN, LAN, MAN, WAN ; topologies bus, étoile, anneau, maillée — chacune avec ses avantages et inconvénients en termes de résilience et de câblage.

## 🧪 Lab 1.1 — Comparer les topologies réseau
- **Objectif :** Simuler bus, étoile, anneau et maillée pour observer leurs comportements en cas de panne.
- **Prérequis / Outils :** Packet Tracer ou GNS3
- **Étapes détaillées :**
  1. Ouvrir Packet Tracer et créer un nouveau projet vide.
  2. Construire une topologie en bus : relier 4 PC sur un même segment.
  3. Construire une topologie en étoile : relier les mêmes 4 PC à un switch central.
  4. Construire une topologie en anneau : relier chaque PC à ses deux voisins pour former une boucle.
  5. Pour chaque topologie, supprimer un lien et lancer un `ping` entre deux PC pour observer l'impact.
  6. Noter dans un tableau : nombre de PC affectés, facilité de dépannage, complexité de câblage.
  7. Conclure : quelle topologie est la plus résiliente ? La plus simple à mettre en place ?
- **Résultat obtenu / Vérification :*[Voir le fichier Packet Tracer](lab-1-1-topologies.pkt)*
- **Difficultés rencontrées :**
- **Statut :** ✅ Terminé

## 🧪 Lab 1.2 — Câbler un mini-LAN en étoile
- **Objectif :** Monter un petit réseau en étoile autour d'un switch (physiquement ou en VM).
- **Prérequis / Outils :** Switch, câbles Ethernet (ou simulateur)
- **Étapes détaillées :**
  1. Rassembler le matériel : 1 switch, 3-4 PC (ou VM), câbles Ethernet droits.
  2. Relier chaque PC au switch avec un câble Ethernet.
  3. Configurer une adresse IP statique sur chaque PC dans le même sous-réseau (ex : 192.168.1.10, .11, .12).
  4. Vérifier la connectivité avec `ping` entre chaque paire de PC.
  5. Observer les voyants du switch qui s'allument à chaque connexion active.
  6. Documenter le schéma du réseau réalisé (photo ou schéma).
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire

## 🧩 Ajouter un nouveau lab
```
### 🧪 Lab 1.X — [Titre]
- **Objectif :**
- **Prérequis / Outils :**
- **Étapes détaillées :**
  1.
- **Résultat obtenu / Vérification :**
- **Difficultés rencontrées :**
- **Statut :** ⬜ À faire
```
