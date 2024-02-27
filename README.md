# Projet DevOps : Déploiement d'un service web avec Kubernetes.

## Description du projet

Ce projet vise à transformer et à faire évoluer une architecture web classique en une solution moderne et scalable grâce à Kubernetes. Nous repartons des bases d'un travail Linux comprenant deux serveurs web (NGINX dans ce cas) équipés d'un CMS (Wordpress) et d'un Load Balancer pour développer une application web déployable sur un cloud provider tel qu'AWS.

## Objectifs

- **Containerisation** : Création des Dockerfiles pour chaque composant de l'application afin de faciliter le déploiement et l'isolation des services.
  
- **Tests** : Mise en place d'un environnement de test pour valider le fonctionnement de l'application à l'aide de tests unitaires simples.
  
- **Orchestration** : Utilisation de Kubernetes pour orchestrer les conteneurs et gérer l'évolutivité et la disponibilité de l'application.

- **Automatisation** : Mise en place d'un pipeline CI/CD (via Codepipeline, GitHub Actions, GitLab CI, Jenkins, etc.) pour automatiser le déploiement et les mises à jour de l'application.
  
- **Infrastructure As Code (IaC)** : Création de templates IaC pour une mise en place et une gestion automatisées de l'infrastructure nécessaire à l'application.
  
- **Production** : Déploiement final de la solution en environnement de production en s'assurant de la sécurité, de la performance et de la fiabilité.

## Prérequis

- Connaissance en administration Linux, Docker et Kubernetes.
- Accès à un fournisseur de cloud (AWS, GCP, Azure...).
- Compréhension des principes de CI/CD et d'Infrastructure As Code.

## Installation et déploiement

1. **Préparation de l'environnement**:
   - Installer Docker et Kubernetes sur votre machine locale pour le développement et les tests.
   - Configurer un compte sur un fournisseur cloud pour le déploiement de production.

2. **Développement des Dockerfiles**:
   - Créer un Dockerfile pour chaque service web et CMS.
   - Construire les images Docker et les tester localement.

3. **Configuration de Kubernetes**:
   - Écrire les fichiers de configuration YAML pour les déploiements, les services et les ingress de Kubernetes.
   - Appliquer les configurations dans un cluster Kubernetes local pour les tests.

4. **Automatisation CI/CD**:
   - Configurer les pipelines dans l'outil CI/CD choisi.
   - Automatiser les tests, la construction des images Docker, et le déploiement sur Kubernetes.

5. **Infrastructure As Code**:
   - Écrire les templates IaC pour déployer l'infrastructure nécessaire (réseaux, VMs, balances de charge, etc.).
   - Utiliser ces templates pour déployer l'infrastructure dans le cloud.

6. **Déploiement en production**:
   - Valider le fonctionnement en environnement de test.
   - Déployer l'application en production en suivant les meilleures pratiques de sécurité et de performance.

## Contribution

N'hésitez pas à ouvrir une issue ou à proposer une pull request, nous regarderons les améliorations et les features proposés au projet.
