# map-minner
# 🗺️ map-miner

> **Mapping Urbanisation & Healthcare Access in Dalanwala Ward, Dehradun**

A geospatial research project focused on creating administrative boundaries, spatial layers, and integrated datasets to analyse the relationship between urbanisation and women's healthcare access in Dalanwala ward, Dehradun, Uttarakhand.

---

## 📌 About the Project

This repository contains GIS datasets, boundary maps, and spatial analysis outputs developed as part of an MSc Geography dissertation at the Department of Geography, Dehradun.

The project investigates how rapid urbanisation in Dalanwala ward has affected the accessibility, distribution, and utilisation of healthcare services — with a specific focus on women's health outcomes.

---

## 🎯 Objectives

- Delineate administrative and ward-level boundaries of Dalanwala, Dehradun
- Map the spatial distribution of healthcare facilities (Sub Centres, PHCs, CHCs)
- Integrate demographic and census data for spatial analysis
- Visualise patterns of healthcare access relative to urbanisation indicators

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python** | Core scripting and data processing |
| **GeoPandas** | Spatial data manipulation and analysis |
| **Folium** | Interactive map generation |
| **Shapely** | Geometric operations on spatial data |
| **Pandas** | Tabular data handling |
| **Matplotlib** | Static map visualisation |

---

## 📁 Repository Structure

```
map-miner/
│
├── data/
│   ├── raw/              ← Original shapefiles, census PDFs
│   ├── processed/        ← Cleaned GeoJSON and CSV files
│   └── boundaries/       ← Ward and administrative boundary files
│
├── maps/
│   ├── static/           ← Exported PNG/JPG map images
│   └── interactive/      ← HTML Folium maps
│
├── notebooks/            ← Jupyter notebooks for analysis
│   ├── 01_boundary_mapping.ipynb
│   ├── 02_healthcare_facilities.ipynb
│   └── 03_accessibility_analysis.ipynb
│
├── scripts/              ← Standalone Python scripts
│   ├── process_boundaries.py
│   └── generate_maps.py
│
└── README.md
```

---

## 🗺️ Study Area

- **Ward:** Dalanwala
- **City:** Dehradun, Uttarakhand
- **State:** Uttarakhand, India
- **Context:** Rapidly urbanising ward with mixed land use and varying healthcare infrastructure

---

## 📊 Data Sources

- Census of India (2011) — Primary demographic data
- Uttarakhand GIS Portal — Administrative boundaries
- District Health Department, Dehradun — Healthcare facility locations
- OpenStreetMap — Base map and road network data
- IPHS Framework (MoHFW, GoI) — Healthcare norms and benchmarks

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install geopandas folium pandas matplotlib shapely jupyter
```

### Clone the Repository
```bash
git clone https://github.com/bhupi008/map-minner.git
cd map-minner
```

### Run a Notebook
```bash
jupyter notebook notebooks/01_boundary_mapping.ipynb
```

---

## 📸 Sample Outputs

*(Map screenshots and visualisations will be added here as the project progresses)*

---

## 👤 Author

**Bhupi** (Roll No. 24MGE56)
MSc Geography — Department of Geography, Dehradun
Dissertation: *Urbanisation and Women's Healthcare Access in Dalanwala Ward, Dehradun*

---

## 📄 License

This project is for academic research purposes. Please cite appropriately if using any datasets or outputs.

---

## 🤝 Acknowledgements

- Department of Geography, Dehradun
- Centre for Public Policy and Good Governance (CPPGG), Uttarakhand
- PM Gati Shakti Initiative
