# 📋 PointagePro — FKIH BEN SALAH

> Tableau de suivi de pointage journalier du personnel magasin

---

## 📌 Description

Application web locale pour gérer la **feuille de présence journalière** du personnel du magasin FKIH BEN SALAH (CDI, ANAPEC, Stagiaires).

Fonctionne **100% hors ligne** — aucune installation requise, aucun serveur.

---

## ✅ Fonctionnalités

- 📅 Sélection de la date avec affichage automatique du jour
- 👥 Liste complète du personnel avec matricule et nom
- ⏱ Saisie des heures d'entrée/sortie (jusqu'à 4 plages horaires)
- 🧮 Calcul automatique des heures travaillées
- 🔍 Recherche rapide par nom ou matricule
- ➕ Ajout de nouveaux employés
- 🗑 Suppression d'un employé du tableau
- 💾 Sauvegarde automatique dans le navigateur (localStorage)
- 📄 Export PDF professionnel (format A4 paysage)

---

## 🚀 Utilisation

1. Ouvrir le fichier `Pointage_FKIH_BEN_SALAH.html` dans un navigateur
2. Sélectionner la date du jour
3. Saisir les heures d'entrée et de sortie pour chaque employé
4. Les données sont sauvegardées automatiquement
5. Cliquer sur **PDF** pour exporter la feuille de présence

---

## 💾 Sauvegarde des données

| Données | Stockage |
|---|---|
| Liste des employés | Permanente (localStorage) |
| Heures par date | Par date (localStorage) |

> Les données restent dans le navigateur. Changer de navigateur = données perdues.

---

## 📁 Structure

```
Pointage_FKIH_BEN_SALAH.html   ← fichier unique, tout inclus
README.md                       ← ce fichier
```

---

## 🛠 Technologies

- HTML5 / CSS3 / JavaScript (Vanilla)
- [jsPDF](https://github.com/parallax/jsPDF) — génération PDF
- [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) — tableaux PDF
- Google Fonts — Cairo

---

## 👤 Personnel concerné

- CDI
- ANAPEC
- Stagiaires

---

## 📄 Export PDF

Le PDF généré contient :
- En-tête avec nom du magasin et date
- Tableau complet avec heures et total
- Zone de signatures (Responsable / Directeur Régional / RH)

---

*FKIH BEN SALAH — Gestion présence magasin*
