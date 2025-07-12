# 🧪 Résultats d’analyse réseau – Mission 1

Ce dossier contient les résultats détaillés de la première mission réseau du projet **Network Lab**.

---

## 📌 Objectif de la mission

Lancer un serveur Flask local, et diagnostiquer son accessibilité réseau à l’aide de plusieurs outils classiques sous Linux.

---

## 🔍 Outils utilisés

- `ss` → vérifier les ports à l'écoute
- `netstat` → afficher les connexions et ports réseau
- `ip` → voir les adresses IP et interfaces
- `nmap` → scanner les ports locaux
- `tcpdump` → sniffer le trafic réseau sur un port donné

---

## 📁 Fichiers inclus

- `scan_results.md` → résumé complet des sorties de commande
- `tcpdump_examples.md` (à ajouter plus tard) → exemples d’analyse de paquets réseau

---

## 🔧 Système utilisé

- OS : Arch Linux (utilisateur : Dally)
- Interface réseau testée : `wlp3s0`
- IP locale : `192.168.43.10`
- Serveur Flask en écoute sur le port `5000`

---

## ✅ Résultat final

Le serveur est détecté comme actif sur le réseau, toutes les commandes ont confirmé l’écoute et l’ouverture du port. Trafic observable avec `tcpdump`. Test concluant ✅