
# Analyse géospatiale de villes — SDD1001

Notebook Python combinant Pandas et GeoPandas pour nettoyer, analyser et visualiser des données géographiques sur des villes mondiales, avec cartographie interactive et tests unitaires.

## Contenu du notebook

- Chargement d'un CSV de villes mondiales depuis Google Drive
- Nettoyage des données : détection et correction manuelle de valeurs mal formatées (Seoul), détection de doublons et valeurs aberrantes
- Statistiques descriptives sur la population (min, max, moyenne, médiane, mode)
- Visualisations : histogramme de distribution, boîte à moustaches
- Conversion en GeoDataFrame avec GeoPandas (coordonnées lat/lon → géométrie Point)
- Cartographie des villes sur fond de carte mondiale avec gradient de population
- Standardisation des données avec StandardScaler
- Tests unitaires avec `unittest`

## Technologies

- Python
- GeoPandas
- Pandas / NumPy
- Shapely
- Matplotlib
- scikit-learn (StandardScaler)
- Google Colab

## Prérequis

```bash
pip install geopandas pandas numpy matplotlib shapely scikit-learn requests
```

Le fichier `ville.csv` est chargé depuis Google Drive — le lien peut nécessiter une mise à jour selon l'environnement.

## Structure

```
Geopanda.ipynb  — notebook principal (2 parties : Pandas + GeoPandas)
```

---

Projet universitaire solo — cours SDD1001, UQTR.
