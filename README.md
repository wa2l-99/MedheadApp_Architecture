# MedHead Platform - Architecture Documentation

Ce repository contient la documentation complète de l'architecture pour la plateforme MedHead. Cette documentation est essentielle pour comprendre la conception, l'intégration et les choix techniques effectués dans le cadre de la réalisation de la preuve de concept (PoC).

## Contenu du Repository

### 1. Diagrams/

Ce dossier contient les différents diagrammes d'architecture qui illustrent les principales composantes et interactions du système.

- **microservices-architecture.png :** Ce diagramme montre l'architecture globale des microservices utilisés dans le projet. Il détaille les différents services (comme l'API Gateway, les microservices de gestion des hôpitaux, d'authentification, de notification, etc.) et leurs interactions via le service de découverte (Eureka) et le serveur de configuration (Config Server).

- **kafka-integration.png :** Ce diagramme illustre l'intégration de Kafka dans l'architecture pour la gestion des événements asynchrones entre les microservices. Il montre comment les microservices de réservation et de notification utilisent Kafka pour la communication événementielle.

### 2. Specifications/

Ce dossier contient les spécifications fonctionnelles et techniques de la plateforme.

### 3. Reporting/

Ce dossier contient le rapport détaillé sur la réalisation du PoC.

- **poc_report.pdf :** Ce document de reporting explique en détail le processus de développement de la PoC, y compris les objectifs initiaux, les choix d'architecture et les résultats obtenus. Il fournit également une évaluation de la conformité du projet par rapport aux exigences initiales et des recommandations pour l'étape suivante du développement.

## Utilité des Documents

Ces documents et diagrammes sont essentiels pour :

- **Comprendre l'architecture globale** : Les diagrammes fournissent une vue d'ensemble des différentes composantes du système et de leurs interactions.
- **Garantir la conformité aux exigences** : Les spécifications et le document de reporting montrent comment le projet répond aux besoins fonctionnels et non fonctionnels définis en amont.
- **Faciliter les futures évolutions** : La documentation de l'architecture sert de référence pour les équipes de développement et de maintenance qui travailleront sur ce projet à l'avenir, assurant ainsi une continuité dans les choix techniques et les bonnes pratiques.

---

**Note :** Ce repository est un complément au repository principal contenant le code source du PoC. Il est conseillé de le consulter conjointement pour une compréhension complète du projet.

