````markdown
# 📊 Dashboard Finances Personnelles — Power BI

## 🎯 Présentation
Ce projet présente un tableau de bord Power BI dédié au suivi et au pilotage de finances personnelles.  
Il permet d’analyser les revenus, les dépenses, l’épargne et leur évolution dans le temps, afin d’aider à la prise de décision budgétaire.

Ce dashboard a été conçu dans une logique **Business / Data Analytics**, avec un fort accent sur la lisibilité, la cohérence des indicateurs et la valeur métier.




---

## 🧩 Objectifs du projet
- Suivre l’évolution mensuelle des dépenses
- Mesurer le taux d’épargne
- Identifier les principaux postes de dépenses
- Comparer les performances financières d’une année à l’autre
- Fournir une vue synthétique et exploitable rapidement

---

## 📌 Fonctionnalités principales
- **KPIs clés**
  - Revenus
  - Dépenses
  - Épargne
  - Taux d’épargne (%)

- **Analyses visuelles**
  - Évolution des dépenses par mois
  - Répartition des dépenses / épargne par catégorie
  - Comparaison annuelle

- **Filtres interactifs**
  - Année
  - Mois

---

## 🧱 Stack technique
- **Power BI Desktop**
- **Microsoft Fabric**
- **DAX** (mesures et indicateurs)

---

## 📊 Modèle de données (format attendu)

Le dashboard repose sur une table de transactions contenant au minimum :

| Colonne        | Description                |
| -------------- | -------------------------- |
| date           | Date de la transaction     |
| type           | Revenu / Dépense / Épargne |
| categorie      | Catégorie de dépense       |
| montant        | Montant                    |
| moyen_paiement | (optionnel)                |
| commentaire    | (optionnel)                |

---

## 🧠 Mesures principales (exemples)

* **Total Revenus**
* **Total Dépenses**
* **Épargne** = Revenus - Dépenses
* **Taux d’épargne (%)** = Épargne / Revenus
* **Analyse mensuelle / annuelle**
* **Comparaison période N vs N-1** (optionnel)

Les mesures sont implémentées directement dans le fichier Power BI via **DAX**.

---

## 🚀 Utilisation

1. Installer **Power BI Desktop**
2. Cloner ou télécharger le dépôt
3. Ouvrir le fichier `dashboard_finances.pbix`
4. Mettre à jour la source de données si nécessaire :

   * Accueil → Transformer les données
5. Actualiser le rapport

---

## 🔒 Confidentialité & données

* Les données réelles ne sont **pas publiées**
* Les jeux de données fournis sont **anonymisés ou simulés**
* Le projet met l’accent sur :

  * la modélisation
  * la qualité des indicateurs
  * la visualisation de données

---

## 📸 Aperçu

il ya une capture du dashboard disponible qui est le fichier `image`.

---

## 📈 Améliorations possibles

* Ajout d’objectifs budgétaires
* Alertes sur dépassement de seuil
* Analyse prédictive des dépenses
* Segmentation par type de revenu

---


✨ *Projet réalisé dans une démarche Data / Business Analytics, orientée pilotage et prise de décision.*

```
```
