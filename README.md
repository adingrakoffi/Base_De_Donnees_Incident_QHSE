# 📊 Tableau de Bord QHSE \& Système de Gestion des Incidents

> \*\*Système professionnel complet de Business Intelligence et de pilotage opérationnel des risques Sécurité, Hygiène, Qualité et Environnement (QHSE).\*\* Conçu pour centraliser, auditer et analyser les incidents industriels et logistiques à travers de multiples sites.

\---

## 🚀 Aperçu du Projet

Ce projet présente un tableau de bord exécutif et une base de données sous Excel, développés pour transformer des données brutes d'incidents en **indicateurs clés de performance (KPIs) exploitables** pour les directions opérationnelles, les responsables QHSE et les comités de sécurité.

L'objectif est d'assurer un suivi rigoureux de la conformité, de quantifier les impacts financiers et opérationnels (jours d'arrêt) des accidents, et d'optimiser le suivi des plans d'actions correctives.

\---

## 🗂️ Structure de la Base de Données (`Base\_Incidents\_QHSE`)

La base de données centralise l'ensemble des signalements selon une structure normalisée rigoureuse :

|Colonne / Champ|Description Technique|Type de Donnée|
|-|-|-|
|`ID\_Incident`|Identifiant unique de l'événement (ex: `QHSE-2026-105`)|Texte / Clé|
|`Date` / `Mois`|Horodatage précis de survenance de l'incident|Date \& Mois|
|`Site`|Implantation géographique (Usine Principale, Entrepôt, Agence)|Catégoriel|
|`Departement`|Service concerné (Production, Maintenance, Logistique, etc.)|Catégoriel|
|`Type\_Evenement`|Typologie (Accident avec/sans arrêt, Presqu'accident, Non-conformité)|Catégoriel|
|`Gravité`|Évaluation du niveau de criticité sur une échelle graduée (1 à 4)|Numérique|
|`Cause\_Racine`|Analyse causale (Erreur humaine, Défaut de maintenance, Procédure)|Texte / Catégoriel|
|`Jours\_Arret`|Impact opérationnel en jours d'arrêt de travail|Numérique|
|`Cout\_Estime\_FCF`|Évaluation financière de l'impact en Francs CFA (FCFA)|Numérique (Devise)|
|`Statut\_Action`|État de traitement (Clôturée, En cours, En retard, Planifiée)|Statut|
|`Responsable\_Traitement`|Service ou collaborateur assigné au suivi correctif|Texte|
|`Score\_Audit\_5`|Note de conformité d'audit interne (sur 100)|Numérique|

\---

## 📈 Indicateurs Clés \& Tableau de Bord Exécutif (`Tableau de bord`)

Le tableau de bord interactif intègre des cartes de synthèse (*KPI Cards*) et des graphiques dynamiques avancés :

* 📌 **Total des Événements / Incidents :** `500` enregistrements suivis.
* 💰 **Coût Total Estimé :** `178 349 917 F CFA` d'impacts financiers cumulés.
* ⚡ **Total Jours d'Arrêt :** `562` jours d'interruption cumulés.
* ⚠️ **Accidents avec Arrêt :** `247` cas majeurs référencés.
* 📈 **Taux de Conformité Global :** `82,36 %` de conformité opérationnelle.

### 📊 Visualisations Intégrées

1. **Coût Total Estimé par Événement :** Analyse de Pareto mettant en évidence le poids financier critique des accidents du travail avec arrêt par rapport aux presqu'accidents et situations dangereuses.
2. **Nombre d'Incidents par Département :** Suivi comparatif des volumes d'incidents entre Production, Maintenance, Logistique, Administration et Conditionnement.
3. **Taux de Conformité par Site :** Graphique en anneau / camembert illustrant la répartition des scores de conformité réglementaire et interne par implantation.
4. **Suivi du Statut des Actions Correctives :** Baromètre de réactivité opérationnelle (répartition des actions clôturées, en cours, planifiées ou en retard).

\---

## 🛠️ Stack Technique \& Compétences Mobilisées

* **Business Intelligence \& Data Analysis :** Modélisation de données, normalisation, nettoyage et structuration.
* **Outils Avancés :** Microsoft Excel (Power Query, Power Pivot, Formules Avancées, TCD, Graphiques).
* **Domain Expertise (QHSE) :** Gestion des risques professionnels, analyse des causes racines (RCA), conformité aux normes industrielles et logistiques, indicateurs de performance de sécurité au travail.

\---

## 👤 Auteur

**Adingra Koffi Jean-Marc**  
*Data Analyst / Assistant Traçabilité \& Risques*  
📍 Abidjan, Côte d'Ivoire  
🔗 [LinkedIn](#) | 🐙 [GitHub](#)

\---

*Ce projet fait partie du portfolio professionnel d'analyse de données et d'optimisation des processus industriels et QHSE.*

