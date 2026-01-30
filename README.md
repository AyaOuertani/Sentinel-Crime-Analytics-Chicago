# Sentinel-Crime-Analytics-Chicago
# Objective
The project goes beyond simple crime statistics and provides Actionable Intelligence for security deployments. Instead of where the crime occurred, the system identifies High Risk Zones through a weighted severity index and tactical hotspots through a clustering algorithm called # DBSCAN.

# Key Features
## Weighted Risk Index:
Calculates risk based on crime severity rather than just volume.
## Spatail Intelligence:
Measures distance to "High Value Targets" and city centers using the Haversine formula and GeoPandas.
## Tactical Hotspots:
Uses DBSCAN unsupervised learning algorithm to discover high-density violent crime clusters that traditional maps might miss.
## Predictive Modeling:
Implements a Random Forest Classifier with SMOTE oversampling to predict incident types based on temporal and geospatial features.
## Interactuve Command Maps:
Generates Folium-based tactical maps with risk-radius circles and heatmaps.

# Tech Stack
### Python 3.10+
### Analysis: Pandas, NumPy, GeoPandas
### Machine Learning: Scikit-Learn, Imbalanced-Learn (SMOTE)
### Visualization: Folium, Seaborn, Matplotlib

