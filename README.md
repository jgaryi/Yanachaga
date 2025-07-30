# Repositorio del Proyecto ANP Yanachaga #
## II CopernicusLAC Hackathon: Reducción del riesgo de desastres ##

Este repositorio contiene las capas vectoriales y raster del modelo FSLAM, junto con mapas, simbología y visualizadores web.

```plaintext

fslam-capas/
│
├── data/
│   ├── raster/            ← Capas tipo TIFF, IMG, etc.
│   │   ├── elevacion.tif
│   │   └── dem.tif
│   │
│   ├── vector/            ← Capas vectoriales (GeoJSON, Shapefile)
│   │   ├── centros_poblados.geojson
│   │   └── rios.shp
│   │
│   └── symbology/         ← Archivos QGIS para simbología
│       └── fslam_styles.qml
│
└── maps/                  ← Mapas en PDF o imágenes exportadas
    └── mapa_riesgos_2024.pdf
