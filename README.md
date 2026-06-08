# Projet CYNA — DAT Groupe 3

Ce dépôt GitHub contient les éléments techniques du projet CYNA Cybersecurity SaaS réalisé dans le cadre du DAT BC3.

## Objectif du projet

CYNA est une entreprise fictive de cybersécurité proposant des services EDR, XDR et SOC en mode SaaS.  
L’objectif du projet est de concevoir, déployer et sécuriser une infrastructure complète comprenant réseau, serveurs, SIEM, automatisation et supervision.

## Contenu du dépôt

- Site web cyna.html : portail web de démonstration avec protection contre les tentatives de brute force
- terraform/ : fichiers Infrastructure as Code
- ansible/ : playbooks de configuration automatisée
- docker/ : fichiers Docker Compose pour les services conteneurisés
- documentation/ : documents techniques et preuves de tests

## Technologies utilisées

- VMware
- Microsoft Azure
- Terraform
- Ansible
- Docker / Docker Compose
- Wazuh SIEM
- OpenSearch
- Nginx
- OpenVPN
- Windows Server 2022
- Ubuntu Server 22.04 LTS

## Sécurité

Le projet applique une logique Zero Trust avec segmentation réseau, supervision centralisée, journalisation des événements et détection des comportements suspects.

Le site web de démonstration inclut une protection contre les tentatives de brute force et simule l’envoi d’alertes vers Wazuh.
