# PILOTAGE PROJECTLIBRE, GESTION DE CRISE ET CLOTURE
Nom du Projet : NexaTech 2026 - Migration Cloud et Intégration IA Hybride  
Directrice de Projet (PMO) : Maria Angels  
Outil mis en avant : ProjectLibre (Alternative open-source à MS Project)  

---

## 1. RAPPORT DE PILOTAGE DE CRISE ET CLOTURE EVM

L'analyse d'avancement établie à la date d'état du 15 décembre 2026 confirme la clôture de la première phase d'Audit et d'Architecture. Les indicateurs financiers constatent une Valeur Acquise stricte de 121 500 dollars, en parfaite adéquation avec la Valeur Planifiée. L'indice de performance des coûts (CPI) s'établit à 1.0.

L'analyse prévisionnelle portant sur janvier 2027 détecte la matérialisation du risque technique R02. La fragmentation de la base de données ERP génère un retard prévisionnel de 10 jours. L'évaluation de la Valeur Acquise dans ProjectLibre calcule un coût final estimé (EAC) de 1 295 000 dollars, soit un dépassement brut de 43 000 dollars par rapport à la Ligne de Base.

La gestion budgétaire neutralise cet écart financier. La provision pour risques de 150 000 dollars, affectée au Lot 1.1, absorbe intégralement le surcoût de la crise. L'élimination du retard sur le chemin critique proscrit le Fast-Tracking afin de préserver la sécurité informatique. La direction du projet applique un Crashing ciblé sur le développement des API en élevant la capacité de l'équipe à 400 %. Cette intervention contracte la durée de la tâche de 30 à 20 jours. Le jalon de mise en production (Go-Live) retrouve sa position contractuelle fixée au 20 mai 2027.

Le bilan de clôture arrêté au 29 juillet 2027 entérine un taux d'achèvement de 100 % sur l'intégralité des 43 lots et tâches. L'audit des comptes valide une symétrie parfaite des indicateurs. La Valeur Planifiée (PV), la Valeur Acquise (EV) et le Coût Réel Final (AC) s'équilibrent sur le montant absolu de 1 262 930 dollars. Les indices de performance de calendrier (SPI) et de coût (CPI) se figent à 1.0. 

L'absorption des surcoûts de la crise de base de données et des renforts de développement a mobilisé 25 600 dollars sur la réserve pour aléas. L'ajustement comptable de clôture restitue un reliquat net de 124 400 dollars à la trésorerie du groupe NexaCorp. La Ligne de Base finale enregistrée dans le fichier ProjectLibre fige l'état définitif du projet tel que construit, livrant une archive de gouvernance parfaite.

---

## 2. GUIDE PRATIQUE DE DEPLOIEMENT SOUS PROJECTLIBRE

Ce guide documente les manipulations techniques requises dans le logiciel pour reproduire l'architecture du projet.

### 2.1. Initialisation et Paramétrage du Calendrier
1. Créer un nouveau projet intitulé Projet NexaTech 2026 - Migration Cloud & IA (Date de début : 01/07/2026).
2. Ouvrir l'onglet Fichier > Calendrier. Sélectionner le calendrier Standard.
3. Sélectionner les dates des jours fériés de 2026 et 2027 (14 Juillet, 15 Août, 1er Novembre, 11 Novembre, 25 Décembre, 1er Janvier, Lundi de Pâques, 1er Mai, 8 Mai, Ascension, Pentecôte).
4. Activer l'option Chômé (Non-working time) pour chaque date. Valider par OK.

### 2.2. Budgétisation Ascendante (Bottom-Up)
Le logiciel additionne les coûts du travail (taux horaire des ressources) et les coûts fixes.
* Saisie des Coûts Fixes : Faire un clic droit sur la case grise vide en haut à gauche du tableau Excel. Sélectionner la table Coût (Cost). Saisir les forfaits sur les lignes d'infrastructure Cloud (30 000 \$), de serveurs GPU IA (150 000 \$), de licences (67 650 \$) et de Pentest (50 000 \$).
* Saisie de la Réserve pour Aléas : Créer la tâche [PROVISION] Réserve de Contingence dans le Lot 1.1 (Durée 260j, sans ressource humaine). Dans la table Coût, saisir 150000 en Coût Fixe et régler l'imputation sur Fin (End).
* Enregistrement de la Baseline : Ouvrir l'onglet Fichier > Enregistrer le planning de référence > Sélectionner Pour le projet entier. Une barre grise contractuelle s'imprime sous chaque tâche.

### 2.3. Astuce de la Date d'État (EVM)
Par défaut, si l'horloge système est située avant la date de début du projet, les tables de Valeur Acquise affichent zéro.
* Solution : Ouvrir l'onglet Fichier > Informations sur le projet. Modifier le champ Date d'état (Status Date) pour inscrire une date de diagnostic en cours d'exécution (ex: 15/12/2026).

---

## 3. BILAN ET RETOURS D'EXPERIENCE (REX)

Dans le cadre du Lot WBS 1.1.4, trois enseignements majeurs sont archivés pour la gouvernance de l'entreprise.

### 3.1. Puissance de la Méthodologie Hybride
L'affectation de l'infrastructure en cycle en V (Waterfall) garantit le respect strict des contrats d'hébergement et des fenêtres de maintenance. La gestion de l'Intelligence Artificielle en sprints Scrum offre la flexibilité nécessaire pour ajuster les modèles aux exigences des utilisateurs finaux, ce qui élimine les résistances au changement lors du Go-Live.

### 3.2. Substitution Globale des Outils Propriétaires
La direction du projet confirme que ProjectLibre remplace efficacement Microsoft Project sur des programmes complexes de refonte du système d'information. La gestion du nivellement, le calcul du chemin critique et la comptabilité EVM opèrent avec une précision absolue, ce qui annule le besoin d'acquérir des licences propriétaires coûteuses.

### 3.3. Sanctuarisation de la Réserve Budgétaire
L'insertion d'une réserve de contingence distincte dans la structure WBS représente une pratique de gouvernance indispensable. Cette réserve agit comme un amortisseur financier direct face aux crises techniques. Elle préserve la relation de confiance avec la Direction Financière et finance les actions de redressement de calendrier.

---

## 4. PROCEDURES DE CLOTURE FINALE DU FICHIER .POD

Pour générer l'archive définitive du projet (As-Built Schedule) :
1. Ouvrir Fichier > Informations sur le projet. Régler la Date d'état sur le 29/07/2027.
2. Basculer sur la table Suivi (Tracking). Sélectionner la Ligne 1 et saisir 100% dans la colonne % Achevé.
3. Basculer sur la table Coût. Sélectionner la tâche de provision pour risques et ajuster le Coût Fixe sur 124400 (soustraction des 25 600 dollars de surcoût de la crise).
4. Ouvrir Fichier > Enregistrer le planning de référence pour valider la Ligne de Base révisée finale.
5. Sauvegarder le fichier .pod. Le dossier est clos.