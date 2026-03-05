# Veille-N8N

## Description

Ce projet utilise N8N pour automatiser des workflows de veille technologique et d'analyse avec intégration d'IA (LLM). Il permet de surveiller des sources d'information, traiter des données et générer des rapports automatisés.

## Fonctionnalités

- Automatisation de workflows avec N8N
- Intégration de modèles de langage (LLM) pour l'analyse de contenu
- Configuration via Docker Compose pour un déploiement facile
- Stockage des données N8N dans un répertoire dédié

## Prérequis

- Docker et Docker Compose installés
- Python 3.8+ (pour les scripts Python si nécessaire)

## Installation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/Adjaaaaaaaa/Veille-N8N.git
   cd Veille-N8N
   ```

2. Lancez les services avec Docker Compose :
   ```bash
   docker-compose up -d
   ```

3. Accédez à N8N via votre navigateur à l'adresse `http://localhost:5678`

## Utilisation

- Importez les workflows depuis le dossier `Flux_n8n/` (fichiers `.json`)
- Configurez vos connexions et déclencheurs selon vos besoins
- Les données sont stockées dans `n8n_data/`

## Structure du projet

- `docker-compose.yml` : Configuration Docker pour N8N
- `Flux_n8n/` : Workflows N8N exportés
- `n8n_data/` : Données persistantes de N8N
- `pyproject.toml` : Configuration du projet Python
