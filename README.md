# 📡 Network Lab – Projet d'exploration réseau

Ce projet est une série de mini-laboratoires pratiques pour apprendre, tester et expérimenter les **fondamentaux du réseau informatique** sous Linux, en particulier sur Arch Linux.

---

## 🎯 Objectifs du projet

- 📦 Lancer un petit service réseau (Flask)
- 🔍 Observer les ports ouverts, IP, trafic réseau
- ⚠️ Diagnostiquer une panne réseau locale
- 🧠 Réviser les commandes essentielles du réseau

---

## 🧪 Missions réalisées

| # | Titre | Description rapide |
|---|-------|---------------------|
| ✅ 1 | [Scan réseau local](./scan_results/scan_results.md) | Lancer un serveur Flask et analyser les ports ouverts, IP et trafic |
| ✅ 2 | [Diagnostic de panne réseau](./analyse_etat_reseau.md) | Analyser si l’interface est UP, si une IP est attribuée, si la route et DNS sont OK |

---

## 🔧 Commandes réseau utilisées

| Commande | Rôle |
|----------|------|
| `ip link`, `ip a` | Statut des interfaces et IP |
| `ip route` | Vérification de la passerelle |
| `cat /etc/resolv.conf` | Vérifier la configuration DNS |
| `ss`, `netstat` | Ports réseau en écoute |
| `nmap` | Scanner les ports locaux |
| `tcpdump` | Sniffer le trafic réseau |

---

## 🖥️ Environnement

- 💻 OS : Arch Linux
- 🧰 Outils : Terminal Linux, Flask, Nmap, tcpdump
- 🌐 Interface réseau : `wlp3s0`
- 🔌 IP locale testée : `192.168.43.10`

---

## 👨‍💻 Auteur

> Réalisé par **Dally** – Étudiant en Data Science & IA passionné aussi par les systèmes et réseaux 🧠🔌  
> 📍 Arch Linux user – Projet 100% fait à la main 🐧