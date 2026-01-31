# Soverys-Infrastructure. 
# le contenant (Fondation) et le contenu (Cerveau/Auto).
# 🛡️ Soverys Infrastructure : Le socle de la souveraineté numérique

Bienvenue dans le cœur technique de **Soverys**. Ce dépôt centralise les configurations Docker permettant de déployer des environnements d'IA et d'automatisation sécurisés et privés.

## 🎯 La Vision
La plupart des solutions d'automatisation actuelles imposent un transfert de données vers des serveurs tiers. **Soverys** inverse ce paradigme en apportant l'intelligence directement sur l'infrastructure du client (**On-Premise**), garantissant une confidentialité absolue et une conformité RGPD native.

## 🏗️ Structure du projet
J'ai conçu cette architecture de manière modulaire pour répondre à deux niveaux de besoins :

### 📁 [Soverys-Light](./Soverys-Light) (Offre Standard)
**Objectif :** Automatisation pure de flux de travail.
* **Service :** n8n (Workflow Manager).
* **Usage :** Idéal pour les PME souhaitant automatiser leurs processus administratifs sans infrastructure lourde.

### 📁 [Soverys-Full](./Soverys-Full) (Offre Ultime)
**Objectif :** Intelligence Artificielle Locale & Privée.
* **Services :** * **Ollama :** Serveur d'inférence pour LLM (Mistral / Llama 3).
    * **n8n :** Orchestrateur de tâches.
    * **Qdrant :** Base de données vectorielle (Vector DB) pour le RAG.
* **Usage :** Dédié aux professions réglementées (Avocats, Santé) pour interroger des documents confidentiels via une IA locale.

## 🛠️ Stack Technique
* **Conteneurisation :** Docker & Docker Compose.
* **Automatisation :** n8n (Low-code / No-code).
* **IA Générative :** Modèles Open-source via Ollama.
* **Mémoire Vectorielle :** Qdrant.

---
*Projet développé par Cathy-Mélissa dans le cadre de Soverys - 2026*
