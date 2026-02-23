# LAB 2 – VLAN & Spanning Tree Protocol (STP)

Ce laboratoire met en œuvre la segmentation réseau via VLAN, la configuration du trunking, la gestion du VTP et l’analyse du Spanning Tree Protocol (STP) sur des équipements Cisco.  
L’objectif est de comprendre le fonctionnement des réseaux commutés, d’éviter les boucles de niveau 2 et d’assurer une topologie stable et redondante.

---

## Objectifs du projet
- Configurer des VLANs et assigner les ports d’accès
- Mettre en place du trunking 802.1Q
- Déployer un domaine VTP (Server / Client)
- Comprendre et manipuler STP (root bridge, priorité, coûts)
- Tester la convergence STP et observer les états des ports
- Activer PortFast et BPDU Guard pour sécuriser les accès

---

## Architecture du réseau
Le lab repose sur une topologie composée de plusieurs switches Cisco interconnectés :

- Switch 1 (VTP Server + Root Bridge)
- Switch 2 (VTP Client)
- Switch 3 (VTP Client)
- Hôtes répartis dans différents VLANs

Les VLANs typiques :
- VLAN 10 – Users
- VLAN 20 – Admin
- VLAN 30 – Servers
- VLAN 99 – Management


## Commandes principales utilisées
### VLAN
