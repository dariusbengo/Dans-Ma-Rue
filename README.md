# Déclarations d'infractions sur l'application Dans Ma Rue — Dashboard Power BI

![Dashboard Dans Ma Rue](https://github.com/user-attachments/assets/8d2b450a-740e-4c5b-a6ff-ace6fbc1b7cd)

## Présentation du Projet

Elaboration d'un dashboard interactif sur **Power BI** pour analyser les infractions sur la voie publique déclarées à Paris via l'application **Dans Ma Rue**.

Ce dashboard permet de :
- Visualiser de manière interactive (cartes, filtres, graphiques) les signalements effectués à Paris
- Identifier les tendances et les zones sensibles
- Formuler des recommandations sur l'affectation prioritaire des équipes d'intervention

---

## Stack Technique

* **Visualisation :** Power BI (`.pbix`)
* **Source de données :** `dans-ma-rue-2025.csv`

---

## Contexte

Les données couvrent la période du **1er juin 2025 au 14 août 2025**, soit **225 059 déclarations d'infractions** signalées dans l'espace public parisien.

---

## Analyse des Données

### Répartition géographique

La **heat map** révèle une forte concentration des déclarations dans la **partie nord-est de Paris**. Cela est confirmé par le classement des arrondissements les plus touchés :

> **18e, 17e, 20e, 15e, 11e, 19e, 10e, 12e**

7 arrondissements sur 8 se situent au nord ou au nord-est de Paris.

### Types d'infractions les plus fréquents

Trois catégories se démarquent nettement :

1. **Objets abandonnés**
2. **Graffitis et tags**
3. **Propreté**

### Répartition des équipes d'intervention

| Type d'infraction | Équipes affectées | Observations |
| :--- | :--- | :--- |
| Objets abandonnés | 5 équipes | Principalement la **DPE STPP DT** |
| Graffitis et tags | Nombreuses équipes | Chacune réalise peu d'interventions, l'équipe *Graffitis* est la plus active |
| Propreté | Moins d'équipes que pour les graffitis | La **DPE STPP DT** prend encore la majorité en charge |

---

## Recommandations

### Réaffectation des ressources

* **Concentrer les efforts** sur les objets abandonnés, les graffitis et la propreté dans la **partie nord-est de Paris**, qui représente l'essentiel des déclarations.
* **Se séparer des équipes** qui réalisent très peu d'interventions (notamment les 3 premières en queue de classement).
* **Déléguer une partie du travail de la DPE STPP DT** à une autre équipe, en particulier sur les infractions relatives à la propreté.
* **Réduire le nombre d'équipes affectées aux graffitis** et réaffecter ces ressources vers les objets abandonnés et la propreté, où la demande est plus concentrée.

---

## Structure du Dépôt

| Fichier | Description |
| :--- | :--- |
| `PROJET_DANS_MA_RUE.pbix` | Rapport Power BI interactif |
| `README.md` | Documentation du projet |

---

## Comment utiliser ce projet ?

Ouvrir `PROJET_DANS_MA_RUE.pbix` dans **Power BI Desktop**.
