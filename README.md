# Analyse-des-Donnees-educatives-avec-Power-BI
# 📊 Analyse des Données Éducatives avec Power BI

## 📌 Description du projet

Ce projet consiste à analyser des données éducatives provenant d'un établissement scolaire fictif à l'aide de **Power BI**. L'objectif est de nettoyer, transformer, modéliser et visualiser les données afin de produire un tableau de bord décisionnel interactif permettant de suivre les performances académiques des élèves, la charge de travail des enseignants et l'efficacité des cours.

---

## 🎯 Objectifs du projet

* Analyser les performances académiques des élèves.
* Étudier l'impact de l'absentéisme sur les résultats scolaires.
* Évaluer la charge de travail et la performance des enseignants.
* Mesurer le taux de réalisation des cours et le taux de réussite.
* Concevoir un dashboard interactif facilitant la prise de décision.

---

## 📂 Jeux de données

### students.csv

Contient les informations relatives aux élèves :

* Identifiant de l'élève
* Nom complet
* Date de naissance
* Genre
* Date d'inscription
* Niveau scolaire
* Section
* Statut
* Moyenne générale
* Nombre d'absences
* Professeur principal

### teachers.csv

Contient les informations relatives aux enseignants :

* Identifiant de l'enseignant
* Nom complet
* Date d'embauche
* Matière enseignée
* Département pédagogique
* Niveau attribué
* Type de contrat
* Heures hebdomadaires
* Ville
* Note d'évaluation

### courses.csv

Contient les informations relatives aux cours :

* Identifiant du cours
* Nom du cours
* Enseignant responsable
* Élève concerné
* Semestre
* Année scolaire
* Heures prévues
* Heures réalisées
* Note obtenue
* Résultat (Réussi / Échoué)

---

## 🛠️ Technologies utilisées

* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Modélisation de données
* Visualisation de données

---

## 🔄 Étapes de réalisation

### 1. Exploration et profilage des données

* Importation des fichiers CSV dans Power Query.
* Analyse des types de données.
* Détection des valeurs manquantes et des doublons.
* Identification des valeurs aberrantes.

### 2. Nettoyage et préparation des données

* Gestion des valeurs manquantes.
* Standardisation des formats de dates et de textes.
* Correction des incohérences.
* Création de nouvelles colonnes :

  * Âge de l'élève
  * Ancienneté de l'enseignant
  * Taux de réalisation des cours
  * Année d'inscription

### 3. Modélisation des données

Relations créées :

* students[teacher_id] → teachers[teacher_id]
* courses[student_id] → students[student_id]
* courses[teacher_id] → teachers[teacher_id]

Création d'une table calendrier (**DimDate**) pour les analyses temporelles.

### 4. Mesures DAX

* Total Élèves
* Moyenne Générale
* Taux de Réussite
* Élèves à Risque
* Heures Moyennes par Enseignant
* Top Matières
* Évolution des Inscriptions

---

## 📈 Tableaux de bord réalisés

### 📄 Page 1 – Vue Élèves

**KPIs :**

* Total élèves
* Moyenne générale
* Taux de réussite global
* Nombre d'élèves à risque

**Visualisations :**

* Répartition des élèves par niveau et section
* Évolution des inscriptions
* Corrélation entre absences et moyenne générale
* Répartition par statut

### 👩‍🏫 Page 2 – Vue Enseignants

**KPIs :**

* Total enseignants
* Ancienneté moyenne
* Heures hebdomadaires moyennes
* Note d'évaluation moyenne

**Visualisations :**

* Répartition par matière et type de contrat
* Distribution des notes d'évaluation
* Top 5 et Flop 5 enseignants

### 📚 Page 3 – Vue Cours & Résultats

**KPIs :**

* Total cours
* Taux de réalisation moyen
* Taux de réussite par semestre

**Visualisations :**

* Réussite / Échec par matière
* Évolution des notes moyennes
* Matières avec moyenne supérieure ou égale à 12

---

## 🔍 Principaux Insights

* Identification des matières ayant le taux d'échec le plus élevé.
* Détection des enseignants sous-chargés ou surchargés.
* Identification des élèves à risque en fonction des absences et des notes.
* Proposition de recommandations pour améliorer la réussite scolaire.

---

## 📦 Livrables

* Fichier Power BI (.pbix)
* Présentation PowerPoint
* Documentation du projet

---

## 👩‍💻 Réalisé par

**Fatima Ezzahra**
## 📊 Dashboard
<img width="1137" height="634" alt="image" src="https://github.com/user-attachments/assets/209b4734-a071-48d1-9a0f-ca31d8450b13" />
<img width="1138" height="632" alt="image" src="https://github.com/user-attachments/assets/cdb28bf2-166c-4546-917c-1bd10a3cda55" />
<img width="1132" height="634" alt="image" src="https://github.com/user-attachments/assets/bf2321df-67f4-4ec4-9713-5abe8e89e2d3" />


