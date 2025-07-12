# 🛠️ Mission 2 – Diagnostic d'une Panne Réseau Locale

Cette mission consiste à analyser étape par étape l’état du réseau local pour identifier une éventuelle panne (pas d’accès internet, ping KO, etc.).

---

## ✅ Résultat final

> Toutes les vérifications sont conformes :  
> ✅ Interface active  
> ✅ IP attribuée  
> ✅ Passerelle détectée  
> ✅ Résolution DNS configurée

---

## 🔍 Détail des vérifications

### 📡 1. Vérifier l'état de l'interface réseau
```bash
ip link
```
Affiche toutes les interfaces réseau (actives ou non), leur état (`UP`, `DOWN`, `DORMANT`, etc.)

### 🌐 2. Vérifier la configuration IP
```bash
ip a
```
Affiche les adresses IP associées à chaque interface.

### 🚦 3. Vérifier la route par défaut (passerelle)
```bash
ip route
```
Affiche les routes réseau connues par le système, y compris la **passerelle**.

### 📡 4. Vérifier la configuration DNS
```bash
cat /etc/resolv.conf
```
Affiche les serveurs DNS utilisés pour résoudre les noms de domaine.

---

## 🧰 Commandes utilisées

| Commande | Utilité |
|---------|---------|
| `ip link` | Statut des interfaces |
| `ip a` | Adresse IP par interface |
| `ip route` | Routes connues (dont passerelle) |
| `cat /etc/resolv.conf` | Vérifie les serveurs DNS |