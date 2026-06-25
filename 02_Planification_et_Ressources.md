# PLANIFICATION, RESSOURCES ET BUDGET (EVM)
Nom du Projet : NexaTech 2026 - Migration Cloud et Intégration IA Hybride  
Directrice de Projet (PMO) : Maria Angels  
Cible : Direction Financière (DAF) et Sponsor Exécutif  

---

## 1. NOTE DE CONSOLIDATION BUDGETAIRE ET RESSOURCES (COMITE DAF)

La consolidation budgétaire du Projet NexaTech instaure une hiérarchie de facturation interne et externe précise. Le taux horaire interne du Chef de Projet s'établit à 93,75 dollars par heure (750 dollars par jour). Ce taux apparaît inférieur à celui des consultants externes, tels que l'Architecte Cloud à 1 100 dollars par jour ou l'Expert Cybersécurité à 850 dollars par jour.

Cette structure tarifaire répond aux contraintes du marché informatique en 2026. L'Intelligence Artificielle et l'architecture Cloud requièrent des compétences d'expertise soumises à une forte tension commerciale. Le pilotage budgétaire encadre l'intervention de ces profils spécialisés pour respecter l'enveloppe financière globale.

La répartition des volumes horaires amortit cet écart tarifaire. L'Expert Cybersécurité intervient sur des fenêtres d'audit précises, ce qui fixe son coût global à 29 750 dollars. L'affectation de la Directrice de Projet couvre l'intégralité des 260 jours ouvrés de l'année. La structuration du plan de charge dans ProjectLibre valide l'adoption d'un modèle de Commando Agile. L'équipe opérationnelle totalise 8 516 heures de travail. Le coût de réalisation s'élève à 1 262 930 dollars, incluant une réserve pour risques de 150 000 dollars. Ce montage génère une économie budgétaire supérieure à 50 % par rapport à l'estimation macroscopique initiale de 2,85 millions de dollars.

---

## 2. POOL DE RESSOURCES ET TAUX HORAIRES

Le logiciel ProjectLibre exploite le taux standard horaire pour calculer le coût des tâches (règle des 8 heures de travail par jour).

| ID | Nom de la Ressource | Type | Initiales | TJM (Taux Journalier) | Taux Standard Horaire | Imputation (Accrual) | Rôle et Fonction |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| 1 | Chef de Projet Senior | Travail | PM | 750 $ / j | 93,75 $/h | Prorata | Direction de projet, gouvernance, PMO. |
| 2 | Architecte Cloud Senior | Travail | ARC | 1 100 $ / j | 137,50 $/h | Prorata | Conception technique HLD/LLD et socle cloud. |
| 3 | Ingénieurs Cloud / DevOps| Travail | DEV | 850 $ / j | 106,25 $/h | Prorata | Déploiement automatisé (Terraform) et Infra. |
| 4 | DBA Senior | Travail | DBA | 680 $ / j | 85,00 $/h | Prorata | Administration et migration BDD (Oracle/Postgre).|
| 5 | Tech Lead IA | Travail | TIA | 800 $ / j | 100,00 $/h | Prorata | Responsable scientifique du modèle IA NexaSense.|
| 6 | Data Scientists | Travail | DSC | 950 $ / j | 118,75 $/h | Prorata | Entraînement des modèles LLM et NLP. |
| 7 | Développeurs Backend API| Travail | API | 600 $ / j | 75,00 $/h | Prorata | Création des API REST de liaison ERP/CRM. |
| 8 | Expert Cybersécurité | Travail | SEC | 850 $ / j | 106,25 $/h | Prorata | Sécurisation des flux, conformité NIS2. |
| 9 | Consultants Conduite Chgt| Travail | CHG | 750 $ / j | 93,75 $/h | Prorata | Formations utilisateurs et communication. |
| 10| Sponsor Exécutif | Travail | SPO | 0 $ / j | 0,00 $/h | Prorata | Directeur Général (Validation des Jalons). |
| 11| Rep. Utilisateurs | Travail | USR | 0 $ / j | 0,00 $/h | Prorata | Ambassadeurs métiers (Validation UAT). |
| 12| Equipe QA | Travail | QA | 600 $ / j | 75,00 $/h | Prorata | Exécution des tests d'intégration et charge. |
| 13| Cabinet Audit Sécurité | Travail | AUD | 1 200 $ / j | 150,00 $/h | Fin | Red Team externe (Hackers pour Pentest). |
| 14| Serveurs Cloud (GPU) | Matériel| GPU | Coût usage | 0,00 $ | Fin | Frais d'infrastructure Cloud alloués à la demande.|

---

## 3. PLAN DE CHARGE ET MATRICE D'AFFECTATION

La formule mathématique du logiciel est la suivante :  
Travail (Heures) = Durée (Jours) x 8h x Unités (%).  
Coût de la Tâche = Somme (Travail Ressource x Taux Horaire Ressource).

| Code WBS | Nom de la Tâche ou du Lot | Durée (j) | Vol. Heures | Ressources Assignées et Unités (%) | Coût Total Tâche |
| :---: | :--- | :---: | :---: | :--- | :---: |
| 1.1.1 | Charte de projet et cadrage initial | 15j | 120h | Chef de Projet Senior (100%) | 11 250 $ |
| 1.1.2 | Suivi budgétaire et planification PMO | 260j | 416h | Chef de Projet Senior (20%) (Fil rouge) | 39 000 $ |
| 1.1.3 | Gestion des comités COPIL/COPROJ | 260j | 416h | Chef de Projet Senior (20%) (Fil rouge) | 39 000 $ |
| 1.1.4 | Bilan de clôture et REX | 10j | 80h | Chef de Projet Senior (100%) | 7 500 $ |
| 1.2.1 | Audit des serveurs et BDD On-Premise | 25j | 200h | DBA Senior (100%), Architecte Cloud (50%) | 22 250 $ |
| 1.2.2 | Expression des besoins métiers IA | 10j | 160h | Tech Lead IA (100%), Data Scientists (100%)| 17 500 $ |
| 1.2.3 | Architecture cible Cloud et Plan Sécurité | 20j | 160h | Architecte Cloud (100%), Expert Cyber (50%)| 19 500 $ |
| 1.2.4 | JALON : Validation Architecture Cloud | 0j | 0h | Sponsor Exécutif (100%), Expert Cyber (100%)| 0 $ |
| 1.3.1 | Création Landing Zone (AWS/Azure) | 20j | 480h | Ingénieurs Cloud / DevOps (300%) (3 DevOps)| 51 000 $ |
| 1.3.2 | Configuration Réseau VPN et ExpressRoute| 25j | 600h | Ingénieurs Cloud / DevOps (300%) (3 DevOps)| 63 750 $ |
| 1.3.3 | Sécurisation IAM Chiffrement et WAF | 15j | 240h | Expert Cyber (100%), DevOps (100%) | 25 500 $ |
| 1.3.4 | Stratégie FinOps et tagging des ressources| 10j | 80h | Architecte Cloud Senior (100%) | 11 000 $ |
| 1.3.5 | JALON : Disponibilité Landing Zone Cloud| 0j | 0h | Sponsor Exécutif (100%), Architecte Cloud (100%)| 0 $ |
| 1.4.1 | Nettoyage et anonymisation des données | 20j | 240h | DBA Senior (100%), Expert Cyber (50%) | 22 100 $ |
| 1.4.2 | Migration BDD ERP (Oracle vers PostgreSQL)| 40j | 960h | DBA Senior (300%) (3 DBAs) | 81 600 $ |
| 1.4.3 | Migration BDD CRM et Datalake | 20j | 480h | DBA Senior (300%) (3 DBAs) | 40 800 $ |
| 1.4.4 | JALON : Fin de la migration des données | 0j | 0h | Sponsor Exécutif (100%), DBA Senior (100%) | 0 $ |
| 1.5.1 | Setup environnement IA (GPU/MLOps) | 15j | 240h | Data Scientists (200%) (2 DS), DevOps (100%) | 27 000 $ |
| 1.5.2 | Sprints 1-3 : Core NLP et Documents | 30j | 480h | Tech Lead IA (100%), Data Scientists (200%) (2 DS)| 52 500 $ |
| 1.5.3 | Sprints 4-6 : Modèles Finance et Fraude | 30j | 480h | Tech Lead IA (100%), Data Scientists (100%)| 52 500 $ |
| 1.5.4 | JALON : Prototype MVP IA validé | 0j | 0h | Sponsor Exécutif (100%), Tech Lead IA (100%)| 0 $ |
| 1.5.5 | Sprints 7-9 : API REST et Intégration | 20j | 400h | Développeurs API (400%) (4 devs), Data Scientists (100%)| 37 000 $ |
| 1.5.6 | Sprints 10 : Optimisation et latence | 30j | 480h | Développeurs API (300%) (3 devs), Tech Lead IA (100%)| 42 000 $ |
| 1.6.1 | Tests d'intégration (SIT) | 15j | 360h | Développeurs API (100%), DBA (100%), QA (100%)| 28 200 $ |
| 1.6.2 | Tests de charge (Performance et Résilience)| 10j | 200h | DevOps (100%), Architecte Cloud (50%), QA (100%)| 20 000 $ |
| 1.6.3 | Audit de sécurité externe (Pentest et NIS2)| 10j | 80h | Cabinet Audit Sécurité (100%) | 12 000 $ |
| 1.6.4 | Recette Utilisateur (UAT) | 15j | 180h | Rep. Utilisateurs (100%), Tech Lead IA (50%)| 6 000 $ |
| 1.6.5 | JALON : Clôture UAT et Validation Sécurité | 0j | 0h | Sponsor Exécutif (100%), Expert Cyber (100%)| 0 $ |
| 1.7.1 | Plan de communication interne | 15j | 120h | Consultants Conduite Chgt (100%) | 11 250 $ |
| 1.7.2 | Conception des supports de formation | 20j | 240h | Consultants Conduite Chgt (100%), Rep. Utilisateurs (50%)| 15 000 $ |
| 1.7.3 | Exécution des sessions de formation | 15j | 120h | Consultants Conduite Chgt (100%) | 11 250 $ |
| 1.7.4 | Bascule Générale (Cut-Over et Go-Live) | 2j | 48h | Chef de Projet (100%), DevOps (100%), DBA (100%)| 4 560 $ |
| 1.7.5 | JALON : GO-LIVE (Mise en production) | 0j | 0h | Sponsor Exécutif (100%), Chef de Projet (100%)| 0 $ |
| 1.7.6 | Support Post-Mise en Production (Hypercare)| 19j | 456h | Tech Lead IA (100%), DevOps (100%), DBA (100%)| 44 270 $ |
| 1.7.7 | JALON : Clôture Hypercare et Bilan | 0j | 0h | Sponsor Exécutif (100%), Chef de Projet (100%)| 0 $ |

---

## 4. TABLEAU DU RESEAU PERT (PREDECESSEURS ET SUCCESSEURS)

Ce tableau fige les relations de dépendance avancées (Leads, Lags, Début-Début, Fin-Fin). La saisie des prédécesseurs génère automatiquement les successeurs dans le logiciel.

| ID | Code WBS | Nom de la Tâche ou du Jalon | Prédécesseurs | Successeurs | Explication Logique du Lien Avancé |
| :---: | :---: | :--- | :---: | :---: | :--- |
| 1 | 1.0 | PROJET NEXATECH (MIGRATION CLOUD & IA) | (Vide) | (Vide) | Tâche récapitulative globale du projet. |
| 2 | 1.1 | Gestion de Projet et Gouvernance | (Vide) | (Vide) | Lot récapitulatif. |
| 3 | 1.1.1 | Charte de projet et cadrage initial | (Vide) | 4DD; 5DD; 9FD-5j | Lance le pilotage en DD et anticipe les besoins IA (9) de 5j. |
| 4 | 1.1.2 | Suivi budgétaire et planification PMO | 3FD | 6FF | Démarre le 23/07/2026, dès la clôture de la charte (lien Fin-Début, sans chevauchement). |
| 5 | 1.1.3 | Gestion des comités COPIL/COPROJ | 3FD | (Vide) | Démarre le 23/07/2026, après la signature de la charte (Fil rouge jusqu'à fin de projet). |
| 6 | 1.1.4 | Bilan de clôture et retours (REX) | 4FF | (Vide) | Le Bilan REX se termine le dernier jour du suivi PMO (4). |
| 7 | 1.2 | Audit et Ingénierie des Besoins | (Vide) | (Vide) | Lot récapitulatif. |
| 8 | 1.2.1 | Audit des serveurs et BDD On-Premise | (Vide) | 10 | Démarre le 1er jour. Alimente l'architecture cloud (10). |
| 9 | 1.2.2 | Expression des besoins métiers IA | 3FD-5j | 10 | On lance les ateliers IA 5 jours avant la signature de la charte (3). |
| 10| 1.2.3 | Architecture cible Cloud et Plan Sécurité | 8; 9 | 11FD+3j | Convergence classique (Audit et Besoins achevés). |
| 11| 1.2.4 | JALON : Validation Architecture Cloud | 10FD+3j | 13; 24 | 3 jours d'attente pour la signature officielle par le ComEx. |
| 12| 1.3 | Socle Infrastructure Cloud (Waterfall) | (Vide) | (Vide) | Lot récapitulatif. |
| 13| 1.3.1 | Création Landing Zone (AWS / Azure) | 11 | 14 | Démarre au feu vert du jalon d'architecture (11). |
| 14| 1.3.2 | Configuration Réseau VPN et ExpressRoute| 13 | 15DD+10j| Enchaînement classique après livraison de la Landing Zone. |
| 15| 1.3.3 | Sécurisation IAM Chiffrement et WAF | 14DD+10j| 16 | La sécurité démarre 10 jours après le début du réseau. |
| 16| 1.3.4 | Stratégie FinOps et tagging des ressources| 15 | 17 | Enchaînement sur l'infrastructure sécurisée. |
| 17| 1.3.5 | JALON : Disponibilité Landing Zone Cloud| 16 | 19FD-15j| Mise à disposition officielle de l'environnement Cloud. |
| 18| 1.4 | Migration des Données et Systèmes | (Vide) | (Vide) | Lot récapitulatif. |
| 19| 1.4.1 | Nettoyage et anonymisation des données | 17FD-15j| 20 | On nettoie les données 15 jours avant la livraison du Cloud (17). |
| 20| 1.4.2 | Migration BDD ERP (Oracle vers PostgreSQL)| 19 | 21DD+10j| Démarrage de la migration de la base ERP après nettoyage. |
| 21| 1.4.3 | Migration BDD CRM et Datalake | 20DD+10j| 22 | Le CRM démarre 10 jours après le début de l'ERP. |
| 22| 1.4.4 | JALON : Fin de la migration des données | 21 | 31 | Fin de la migration BDD, donne le feu vert pour les tests SIT. |
| 23| 1.5 | Développement Module IA (Agile Scrum) | (Vide) | (Vide) | Lot récapitulatif (Les sprints Scrum s'enchaînent séquentiellement). |
| 24| 1.5.1 | Setup environnement IA (GPU/MLOps) | 11 | 25 | Démarre après le jalon d'architecture (11). |
| 25| 1.5.2 | Sprints 1-3 : Core NLP et Documents | 24 | 26 | Sprints initiaux Scrum. |
| 26| 1.5.3 | Sprints 4-6 : Modèles Finance et Fraude | 25 | 27 | Sprints intermédiaires Scrum. |
| 27| 1.5.4 | JALON : Prototype MVP IA validé | 26 | 28 | Présentation officielle du MVP au Sponsor. |
| 28| 1.5.5 | Sprints 7-9 : API REST et Intégration | 27 | 29 | Sprints de connexion aux briques CRM/ERP. |
| 29| 1.5.6 | Sprints 10 : Optimisation et latence | 28 | 31; 37 | Sprints finaux. Libère le code pour SIT (31) et Com (37). |
| 30| 1.6 | Tests, Sécurité et Recette (QA) | (Vide) | (Vide) | Lot récapitulatif. |
| 31| 1.6.1 | Tests d'intégration (SIT) | 22; 29 | 32FD-5j | Convergence : Fusionne les flux Waterfall BDD (22) et Agile IA (29). |
| 32| 1.6.2 | Tests de charge (Performance et Résilience)| 31FD-5j | 33FD+2j | Les tests de charge démarrent 5 jours avant la fin des SIT. |
| 33| 1.6.3 | Audit de sécurité externe (Pentest et NIS2)| 32FD+2j | 34 | 2 jours de battement pour isoler l'environnement avant le Pentest. |
| 34| 1.6.4 | Recette Utilisateur (UAT) | 33 | 35 | Les métiers testent une application certifiée par le Pentest. |
| 35| 1.6.5 | JALON : Clôture UAT et Validation Sécu | 34 | 40FD+3j | Signature officielle de la recette UAT. |
| 36| 1.7 | Conduite du Changement et Déploiement | (Vide) | (Vide) | Lot récapitulatif. |
| 37| 1.7.1 | Plan de communication interne | 29 | 38 | Démarre dès la fin des développements (29). |
| 38| 1.7.2 | Conception des supports de formation | 37 | 39FD-5j | Conception des modules de cours et webinaires. |
| 39| 1.7.3 | Exécution des sessions de formation | 38FD-5j | 40FD+3j | On anime les premiers cours 5 jours avant la fin de la conception. |
| 40| 1.7.4 | Bascule Générale (Cut-Over et Go-Live) | 35FD+3j; 39FD+3j| 41 | 3 jours de gel technique obligatoires avant le week-end de bascule. |
| 41| 1.7.5 | JALON : GO-LIVE (Mise en production) | 40 | 42 | Bascule officielle. Déclenche le support Hypercare (42). |
| 42| 1.7.6 | Support Post-Mise en Production (Hypercare)| 41 | 43 | Assistance post-bascule menant au jalon de clôture (43). |
| 43| 1.7.7 | JALON : Clôture Hypercare et Bilan | 42 | (Fin) | Jalon final constatant l'achèvement d'Hypercare. |

---

## 5. ANALYSE ET DEFENSE DU CHEMIN CRITIQUE

Le diagramme de Gantt fige un chemin critique identifié par le moteur de calcul de ProjectLibre. Ce chemin regroupe les tâches dotées d'une marge totale égale à zéro. Ces activités apparaissent en rouge dans l'interface du logiciel. L'apparition d'un retard sur une tâche rouge impacte instantanément la date de livraison finale du projet.

### 5.1. Défense des trois goulots d'étranglement majeurs
Le réseau PERT organise la convergence de multiples chantiers vers trois points de passage obligatoires.

* Le Nœud de l'Architecture (Ligne 10) :
  La tâche de conception d'architecture centralise la fin de l'audit des serveurs (Ligne 8) et l'expression des besoins IA (Ligne 9). Ce point de convergence protège la phase de déploiement. L'équipe Cloud lance le provisionnement de la Landing Zone uniquement après la validation formelle du dossier technique par le RSSI et le Sponsor.
* Le Nœud des Tests d'Intégration SIT (Ligne 31) :
  Ce nœud constitue le point de rencontre technique central du projet. Il fusionne le flux d'infrastructure géré en Waterfall (Ligne 22 : Fin de migration des bases de données) et le flux applicatif géré en Agile Scrum (Ligne 29 : Clôture des sprints IA). Cette dépendance croisée prouve la pertinence de l'approche hybride. Les équipes de test d'intégration opèrent sur un environnement complet combinant les données réelles et le code finalisé.
* Le Nœud de la Bascule Go-Live (Ligne 40) :
  Le week-end de bascule exige la validation simultanée de la recette utilisateur UAT (Ligne 35) et l'achèvement des sessions de formation (Ligne 39). Cette convergence instaure un verrou de sécurité absolu. Le système bloque le basculement en production si l'application présente des failles ou si les utilisateurs opérationnels ne sont pas formés.

### 5.2. Argumentaire de soutenance technique
La gestion des dépendances applique des règles de gouvernance strictes destinées à fiabiliser l'échéancier face aux auditeurs.

L'examen de la table des liaisons confirme l'intégrité du réseau PERT. L'affectation de prédécesseurs sur les tâches récapitulatives est proscrite. Cette règle élimine les boucles de calcul circulaires et préserve l'exactitude des marges.

L'optimisation de la durée totale du chemin critique recourt à des techniques de Fast-Tracking. Le nettoyage des données démarre 15 jours avant la disponibilité des serveurs Cloud. Cette anticipation contracte le chemin critique de trois semaines.

La protection de la stabilité de la production repose sur l'injection de délais de sécurité. La configuration d'une période de gel technique de 3 jours avant le Cut-Over sanctuarise le temps nécessaire à la vérification des sauvegardes et à la configuration des cellules de crise. Ce pilotage proactif neutralise les risques et assure une mise en production conforme.