# 📦 Projets SSIS

Bienvenue dans ce dépôt Git regroupant l’ensemble de mes mini-projets réalisés sous SQL Server Integration Services (SSIS) dans le cadre de mon apprentissage des flux ETL.

Chaque projet explore un ou plusieurs composants clés de SSIS à travers des cas concrets.

---

## 🗂️ Contenu des projets

### ✅ Projet 1 – Initiation aux flux SSIS

> **Objectifs :**
- Utilisation de composants de base :
  - `Derived Column` (ajout d’une colonne sur les revenus)
  - `Sort` (tri des données)
  - `Aggregate` (somme des revenus par produit)

  ![aggregation1](https://github.com/user-attachments/assets/e5ca6838-afd2-4cdc-9143-77caf8919291)



### ✅ Projet 2 – Gestion locative (flux avancé)

> **Objectifs :**
- Mise en pratique de composants intermédiaires à avancés :
  - `Derived Column` (ajout d’une colonne sur la durée des contrats)
  - `Sort` (tri des données)
  - `Merge Join` (jointure entre les données de locations et les informations sur les locataires)
  - `Conversion` (conversion des données)
  - `Multicast` (duplication du flux de données)

![jointure de fusion](https://github.com/user-attachments/assets/ece4a89e-6fd3-4413-811e-7dc368007117)



### ✅ Projet 3 – Tableau Croisé Dynamique (Pivot)

> **Objectifs :**
- Expérimentation du composant `Pivot` :
  - Configuration des `SetKey`, `PivotKey`, `PivotValue`
  - Ajout manuel de colonnes de regroupement dans la sortie
  - Utilisation de l’éditeur avancé et des propriétés comme `SourceColumn` et `PivotKeyValue`

![tableau_croise_dynamique](https://github.com/user-attachments/assets/927a4586-f5ec-4df0-b8b6-930569a03745)



### ✅ Projet 4 – Fractionnement conditionnel des ventes

  Objectifs :

  Identifier les ventes hautes et basses selon un seuil défini.

  Composants utilisés :

  - Derived Column : ajout ou modification d'une colonne (ex. : calcul du montant total)

  - Sort : tri des ventes

  - Conditional Split : séparation du flux selon une règle (ex. : [Montant] >= 1000)

  - Data Conversion : conversion des types de données pour l’export Excel

  - Excel Destination : deux sorties distinctes (Ventes Hautes, Ventes Basses)


  ![fractionnement_conditionnel1](https://github.com/user-attachments/assets/bee19234-a6b4-4a9a-b541-86acb60d3d1d)
  



## 💡 Technologies & Environnement

- **SSIS** via Visual Studio
- **Sources/Destinations** : Fichiers Excel `.xlsx` - Fichiers Plats `.csv`
- **Environnement local** : SQL Server Data Tools (SSDT)

