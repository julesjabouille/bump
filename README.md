# Bump chart (GitHub Pages)

Outil web pour visualiser l’évolution de classements à partir d’un CSV, avec export PNG/PDF. Interface au **[DSFR](https://www.systeme-de-design.gouv.fr/)** (Système de design de l’État). **Aucune donnée n’est envoyée sur un serveur** : tout se fait dans le navigateur.

## Parcours utilisateur

1. **Importer** un fichier `.csv` (glisser-déposer ou parcourir).
2. **Aperçu** du bump chart généré automatiquement.
3. **Exporter** en PNG ou PDF (boutons actifs une fois l’aperçu affiché).

## Format CSV

| Colonne 1 | Colonnes 2+ |
|-----------|-------------|
| Nom (candidat, entreprise…) | Rang à chaque temporalité |

La première ligne contient les libellés des périodes (ex. `2020`, `2021`…).

```csv
Liste,2020,2021,2022
Entreprise A,1,3,2
Entreprise B,2,1,3
```

Fichier d’exemple : `csv_bump_test.csv` (téléchargeable depuis l’interface via « Télécharger le fichier exemple : csv_bump_test.csv »).

## Utilisation en local

Ouvrez `index.html` dans le navigateur, importez votre CSV.

