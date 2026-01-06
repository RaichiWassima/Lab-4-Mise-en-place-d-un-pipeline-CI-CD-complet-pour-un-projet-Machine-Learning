# Lab 4 — Mise en place d’un pipeline CI/CD complet pour un projet Machine Learning

## Contexte académique
**Université :** Université Chouaib Doukkali  
**École :** École Nationale des Sciences Appliquées d’El Jadida  
**Département :** Télécommunications, Réseaux et Informatique  
**Module :** MLOps  

**Filière :** SDIA  
**Niveau :** 2ᵉ Année  
**Année universitaire :** 2025/2026  

**Réalisé par :** Wassima RAICHI

---

## Objectif du lab
Ce lab a pour objectif de concevoir et mettre en œuvre un **pipeline CI/CD complet pour un projet de Machine Learning**, en s’appuyant sur **GitHub Actions**, afin d’automatiser l’exécution du pipeline ML, le contrôle qualité des modèles et la préparation au déploiement selon les bonnes pratiques MLOps.

---

## Technologies utilisées
- Git & GitHub
- GitHub Actions (CI/CD)
- DVC (Data Version Control)
- Python
- Machine Learning
- Secrets & Variables GitHub

---

## Étapes réalisées

### Étape 1 — Création du dépôt GitHub et connexion du remote
Un dépôt GitHub centralisé a été créé et relié au projet local afin de servir de point d’entrée au pipeline CI/CD et de permettre le versionnement et l’automatisation des futures étapes d’intégration et de déploiement.

---

### Étape 2 — Définition des secrets et variables GitHub
Les paramètres de configuration et informations sensibles (version Python, seuil de validation du modèle, environnement d’exécution et secrets) ont été externalisés via GitHub Secrets et Variables afin de sécuriser et rendre configurable le pipeline CI/CD.

---

### Étape 3 — Création du workflow CI/CD
Un workflow GitHub Actions a été mis en place pour automatiser l’intégration continue et le déploiement simulé du projet, incluant l’installation de l’environnement, l’exécution du pipeline ML via DVC, la validation des performances du modèle (Quality Gate) et la gestion des artefacts.

---

### Étape 4 — Commit et déclenchement du pipeline
Les modifications ont été validées et poussées vers GitHub, déclenchant automatiquement le pipeline CI/CD. Le job CI a exécuté avec succès les étapes de validation et de génération des artefacts, tandis que le job CD a simulé un déploiement sur la branche principale.

---

## Résultats obtenus
- Pipeline CI/CD automatisé et reproductible
- Validation automatique de la qualité des modèles
- Gestion sécurisée des paramètres et secrets
- Simulation réaliste d’un déploiement MLOps

---

## 📌 Conclusion
Ce lab met en évidence l’importance de l’automatisation CI/CD dans un contexte MLOps, en garantissant une intégration continue fiable, un contrôle qualité systématique des modèles et une préparation efficace au déploiement en production.
