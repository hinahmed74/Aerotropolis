# Airport Master Plan for Carbon Neutrality

## Repository Structure

Airport Master Plan for Carbon Neutrality/
├── data/                        # External data links + metadata
│   ├── metadata/                # Data schema, layer IDs, CRS, update logs
│   └── files/                   # Small files
│
├── scripts/                     # Data analysis + visualization
│   ├── preprocess/              # Clean, merge, convert data
│   ├── analytics/               # KPI, scenario analysis
│   └── visualization/           # Charts, map layers, heatmaps
│
├── models/                      # Simulation models
│   ├── urban_risk/              # ABM for evacuation
│   └── urban_regeneration/      # Urban form, carbon modeling, energy simulation
│
├── dashboards/                  # Interactive platform 
│
└── docs/                        # Project documentation

## Tools and Technologies

* GIS: ArcGIS Pro, ArcGIS Online, Experience Builder
* Simulation: Rhino/Grasshopper, AnyLogic, Python (ABM, NetworkX)
* Data: 3D CityGML from PLATEAU, Street Networks from OSM, GPS Human Flows, Socioeconomic Data
