# Projet_MiniLab_Reseau-
# 🌐 MiniLab Réseau : Routage Inter-VLAN & DHCP

## 📝 Présentation du projet
Ce projet consiste à configurer une infrastructure réseau complète pour 3 bureaux, incluant la segmentation par VLAN, le routage inter-VLAN (Router-on-a-Stick) et la distribution automatique d'adresses IP via DHCP.

## 🛠️ Matériel utilisé
- 1 Routeur Cisco 1941
- 3 Switchs PT
- 3 Points d'accès Wi-Fi
- 6 PC fixes, 3 Laptops, 3 Téléphones IP

## ⚙️ Configuration Réseau
### 1. Segmentation VLAN
- **VLAN 1** (VoIP) : 192.168.0.0/24
- **VLAN 10** (WiFi) : 192.168.10.0/24
- **VLAN 20** (PC Fixes) : 192.168.20.0/24
- **VLAN 30** (Admin) : 192.168.30.0/24

### 2. Services
- **DHCP** : Configuré sur le routeur pour distribuer les IPs de .10 à .50.
- **Trunking** : Configuré sur les ports 1 et 9 des switchs (IEEE 802.1Q).

## ✅ Résultats
- Attribution IP automatique fonctionnelle.
- Routage Inter-VLAN opérationnel (Pings Successful).

## 📸 Captures d'écran
![Topologie du réseau](images/topologie.png)
![Tests de connectivité](images/pings_reussis.png)
