# DOSSIER DE CADRAGE ET GOUVERNANCE
Nom du Projet : NexaTech 2026 - Migration Cloud et Intégration IA Hybride  
Directrice de Projet (PMO) : Maria Angels  
Date de Rédaction : 24 Juin 2026  
Sponsor Exécutif : Marc Vandamme (Directeur Général et DSI Groupe)  
Statut : Approuvé (Version 1.0)  

---

## 1. NOTE DE CADRAGE STRATEGIQUE ET OBJECTIFS (KICK-OFF COMEX)

Le système d'information actuel du groupe NexaCorp souffre d'une obsolescence technique majeure sur ses infrastructures locales (On-Premise). Cette contrainte matérielle pèse sur la trésorerie et interdit le déploiement des nouveaux services d'Intelligence Artificielle.

L'objectif de ce projet consiste à migrer 85 % des charges de travail vers le Cloud et à déployer le moteur d'IA générative NexaSense. L'enveloppe budgétaire macroscopique initiale est fixée à 2 850 000 dollars pour une durée ferme de 12 mois. Le pilotage adopte une approche méthodologique hybride. L'infrastructure suit un cycle en V rigoureux (Waterfall) pour figer les engagements contractuels d'hébergement. Le développement de l'Intelligence Artificielle s'exécute en mode Agile Scrum pour favoriser une itération rapide avec les directions métiers. Ce cadrage rigoureux sanctuarise le retour sur investissement et met le groupe en conformité directe avec la directive européenne NIS2.

---

## 2. CHARTE DE PROJET (PROJECT CHARTER)

### 2.1. Description et Contexte du Projet
Le groupe international NexaCorp gère un système d'information hébergé sur des infrastructures locales. Ce système accuse un manque de flexibilité et des coûts de maintenance lourds. Le Projet NexaTech organise la refonte et la migration de l'infrastructure vers le Cloud hybride (AWS et Azure avec pilotage FinOps), ainsi que la conception d'un moteur d'IA générative interne (NexaSense) destiné au support client et au contrôle financier.

### 2.2. Objectifs SMART
* Specifique : Migrer l'infrastructure locale vers le Cloud et déployer le module IA NexaSense sur les services Support et Finance.
* Mesurable : Réduire les coûts d'exploitation informatique de 30 % et automatiser 45 % des requêtes de niveau 1 avant fin juin 2027.
* Atteignable : Utiliser une architecture cloud standardisée et des modèles de langage affinés (fine-tuned) hébergés en espace privatif.
* Pertinent : Assurer la compétitivité digitale du groupe, renforcer la sécurité face aux normes NIS2 et réduire l'empreinte carbone informatique de 40 %.
* Temporel : Démarrer le 1er Juillet 2026, effectuer le Go-Live le 20 Mai 2027 et clôturer la phase d'assistance Hypercare le 17 Juin 2027.

### 2.3. Perimetre (Scope)
Inclus dans le projet (In-Scope) :
* Audit de l'architecture locale existante (250 serveurs virtuels, 4 bases de données majeures).
* Déploiement du socle Cloud hybride (Landing Zone AWS et Azure).
* Migration des bases de données de facturation, ERP et CRM vers le Cloud.
* Développement et entraînement du modèle d'IA NexaSense avec intégration via API REST.
* Sécurisation globale, tests d'intrusion (Pentest) et mise en conformité réglementaire NIS2.
* Conduite du changement avec formation de 1 200 utilisateurs et support post-bascule (Hypercare).

Exclus du projet (Out-of-Scope) :
* Refonte logicielle du CRM (seule la base de données est migrée).
* Renouvellement du parc matériel des utilisateurs finaux (ordinateurs, smartphones).
* Projets des filiales asiatiques (périmètre restreint aux plaques Europe et Amérique du Nord).

### 2.4. Jalons Cles (Milestones)
* M1 (01/07/2026) : Kick-off officiel du projet.
* M2 (08/09/2026) : Validation de l'Architecture et de la Stratégie Cloud.
* M3 (25/11/2026) : Disponibilité de la Landing Zone Cloud.
* M4 (23/12/2026) : Prototype MVP du Module IA validé en démonstration.
* M5 (15/01/2027) : Fin de la migration des données de production.
* M6 (12/05/2027) : Clôture de la Recette Utilisateur (UAT) et Validation Sécurité.
* M7 (20/05/2027) : GO-LIVE (Mise en production officielle globale).
* M8 (17/06/2027) : Clôture de la phase d'Hypercare et Bilan post-projet.

---

## 3. STRUCTURE DE REPARTITION DU TRAVAIL (WBS)
1.0 PROJET NEXATECH (MIGRATION CLOUD & IA)
├── 1.1 Gestion de Projet & Gouvernance
│ ├── 1.1.1 Charte de projet et cadrage initial
│ ├── 1.1.2 Suivi budgétaire et planification (PMO)
│ ├── 1.1.3 Gestion des comités (COPIL / COPROJ)
│ └── 1.1.4 Bilan de clôture et retours d'expérience (REX)
│
├── 1.2 Audit & Ingénierie des Besoins
│ ├── 1.2.1 Audit des serveurs et BDD On-Premise
│ ├── 1.2.2 Expression des besoins métiers (Module IA)
│ ├── 1.2.3 Architecture cible Cloud & Plan Sécurité (HLD/LLD)
│ └── 1.2.4 JALON : Validation Architecture & Stratégie Cloud
│
├── 1.3 Socle Infrastructure Cloud (Waterfall)
│ ├── 1.3.1 Création Landing Zone (AWS / Azure)
│ ├── 1.3.2 Configuration Réseau VPN & ExpressRoute
│ ├── 1.3.3 Sécurisation IAM Chiffrement & WAF
│ ├── 1.3.4 Stratégie FinOps et tagging des ressources
│ └── 1.3.5 JALON : Disponibilité Landing Zone Cloud
│
├── 1.4 Migration des Données & Systèmes
│ ├── 1.4.1 Nettoyage et anonymisation des jeux de données
│ ├── 1.4.2 Migration BDD ERP (Oracle vers PostgreSQL Cloud)
│ ├── 1.4.3 Migration BDD CRM & Datalake
│ └── 1.4.4 JALON : Fin de la migration des données de production
│
├── 1.5 Développement Module IA NexaSense (Agile Scrum)
│ ├── 1.5.1 Setup de l'environnement IA (GPU Cloud / MLOps)
│ ├── 1.5.2 Sprints 1-3 : Core NLP & Traitement de documents
│ ├── 1.5.3 Sprints 4-6 : Modèles d'analyse financière et fraude
│ ├── 1.5.4 JALON : Prototype MVP Module IA NexaSense validé
│ ├── 1.5.5 Sprints 7-9 : Création des API REST et intégration CRM/ERP
│ └── 1.5.6 Sprints 10 : Optimisation latence et mise en cache
│
├── 1.6 Tests, Sécurité & Recette (QA)
│ ├── 1.6.1 Tests d'intégration (SIT) & non-régression
│ ├── 1.6.2 Tests de charge (Performance & Résilience)
│ ├── 1.6.3 Audit de sécurité externe (Pentest & NIS2)
│ ├── 1.6.4 Recette Utilisateur (UAT - User Acceptance Testing)
│ └── 1.6.5 JALON : Clôture UAT & Validation Sécurité
│
└── 1.7 Conduite du Changement & Déploiement
├── 1.7.1 Plan de communication interne
├── 1.7.2 Conception des supports de formation (Webinaires & Guides)
├── 1.7.3 Exécution des sessions de formation utilisateurs
├── 1.7.4 Bascule Générale (Cut-Over / Go-Live)
├── 1.7.5 JALON : GO-LIVE (Mise en production officielle globale)
├── 1.7.6 Support Post-Mise en Production (Hypercare)
└── 1.7.7 JALON : Clôture Hypercare & Bilan post-projet

text


---

## 4. MATRICE DES ROLES ET RESPONSABILITES (RACI)

Légende :  
* R (Responsible) : Exécute la tâche.  
* A (Accountable) : Approbateur final (un seul par ligne).  
* C (Consulted) : Expert consulté.  
* I (Informed) : Informé de l'achèvement.  

| Code WBS | Nom du Lot | Sponsor (M. Vandamme) | DAF (S. Leroy) | PMO (M. Angels) | RSSI (G. Tardieu) | Tech Lead IA | Lead Cloud / DevOps | DBA Senior | Rep. Utilisateurs | Cabinet Pentest |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1.1.1 | Charte et cadrage | A | C | R | C | C | C | I | I | I |
| 1.1.2 | Suivi budgétaire | I | A | R | I | I | I | I | I | I |
| 1.1.3 | Comités COPIL | A | I | R | C | C | I | I | C | I |
| 1.2.1 | Audit serveurs | I | I | A | I | I | C | R | I | I |
| 1.2.2 | Besoins métiers IA| I | I | A | I | R | I | I | C | I |
| 1.2.3 | Architecture Cloud| I | I | C | A | C | R | C | I | C |
| 1.3.1 | Landing Zone Cloud| I | I | A | C | I | R | I | I | I |
| 1.3.2 | Réseau et VPN | I | I | A | C | I | R | I | I | I |
| 1.3.3 | Sécurité IAM et WAF| I | I | C | A | I | R | I | I | C |
| 1.3.4 | Stratégie FinOps | I | A | C | I | I | R | I | I | I |
| 1.4.1 | Nettoyage données | I | I | A | C | I | I | R | I | I |
| 1.4.2 | Migration BDD ERP | I | I | A | I | I | C | R | I | I |
| 1.4.3 | Migration BDD CRM | I | I | A | I | C | C | R | I | I |
| 1.5.1 | Setup IA et GPU | I | I | A | C | R | C | I | I | I |
| 1.5.2 | Sprints 1-3 NLP | I | I | A | I | R | I | I | C | I |
| 1.5.3 | Sprints 4-6 Finance| I | C | A | I | R | I | I | C | I |
| 1.5.5 | Sprints 7-9 API | I | I | A | I | R | C | C | I | I |
| 1.6.1 | Tests SIT | I | I | A | I | C | C | R | I | I |
| 1.6.2 | Tests de charge | I | I | A | I | C | R | C | I | I |
| 1.6.3 | Audit Pentest | I | I | C | A | I | C | I | I | R |
| 1.6.4 | Recette UAT | I | I | A | I | C | I | I | R | I |
| 1.7.1 | Communication | C | I | R | I | I | I | I | A | I |
| 1.7.2 | Supports formation| I | I | A | I | C | I | I | R | I |
| 1.7.4 | Bascule Go-Live | A | I | R | C | C | C | C | I | I |
| 1.7.6 | Support Hypercare | I | I | A | I | R | R | R | C | I |

---

## 5. REGISTRE DES RISQUES (FMEA / AMDEC)

Méthodologie d'Évaluation : Probabilité (P : 1 à 5) x Impact (I : 1 à 5) = Criticité (C : 1 à 25).  
Seuil critique fixé à C = 16.

| ID | Catégorie | Description du Risque | P | I | C | Statut | Responsable | Stratégie de Mitigation | Criticité Résiduelle |
| :---: | :--- | :--- | :---: | :---: | :---: | :---: | :--- | :--- | :---: |
| R01 | Cyber | Fuite de données confidentielles lors de l'entraînement du modèle IA NexaSense. | 3 | 5 | 15 | Actif | RSSI | Isolation stricte de l'environnement IA. Anonymisation automatisée obligatoire des données. Audit externe des accès. | P1 x I5 = 5 (Faible) |
| R02 | Technique | Incompatibilité de schémas ou corruption de données lors de la migration d'Oracle vers PostgreSQL. | 4 | 4 | 16 | Actif | Lead DBA | Mise en place d'un outil de réplication en temps réel (CDC). Exécution de trois bascules à blanc avant le Go-Live. | P2 x I3 = 6 (Faible) |
| R03 | RH | Démission de profils IA ou Cloud clés bloquant l'avancement des développements. | 4 | 4 | 16 | Actif | PMO | Partenariat avec une ESN pour disposer de profils de secours. Attribution d'un bonus de rétention lié au succès du Go-Live. | P2 x I4 = 8 (Faible) |
| R04 | Change | Rejet du module IA par les équipes opérationnelles par crainte de remplacement. | 3 | 4 | 12 | Actif | Rep. Utilisateurs | Implication d'ambassadeurs métiers dans les revues de sprints. Positionnement de l'IA comme assistant de travail. | P1 x I3 = 3 (Faible) |
| R05 | FinOps | Explosion des coûts d'infrastructure Cloud par rapport aux prévisions initiales. | 4 | 3 | 12 | Actif | DAF et Lead Cloud| Mise en place d'un pilotage FinOps hebdomadaire. Souscription d'instances réservées sur un an pour figer les coûts. | P2 x I2 = 4 (Faible) |
| R06 | Réseau | Retard de livraison des liaisons réseau dédiées (ExpressRoute) par l'opérateur. | 3 | 4 | 12 | Actif | Lead Cloud | Anticipation des commandes dès le premier mois. Configuration d'un VPN de secours haute performance. | P1 x I3 = 3 (Faible) |
| R07 | Légal | Non-conformité aux exigences de la directive européenne NIS2. | 2 | 5 | 10 | Actif | RSSI | Intégration des règles NIS2 dès la conception (Security by Design). Mandatement d'un auditeur externe. | P1 x I5 = 5 (Faible) |

### Règles de Déblocage de la Réserve de Contingence (150 000 $ alloués en charte)
* Si matérialisation de R02 (Crise Migration BDD) : Déblocage immédiat de 80 000 $ pour l'embauche d'un commando d'experts DBA PostgreSQL externes pendant un mois.
* Si matérialisation de R03 (Départ ressource IA) : Déblocage de 30 000 $ pour couvrir le surcoût facturé par le partenaire ESN en régie express.
* Si matérialisation de R05 (Dérive FinOps) : Déblocage de 40 000 $ en investissement additionnel pour acquérir des licences logicielles d'optimisation IA.