# 💡 Access Under Water: Mapping Flood Exposure and Service Reach in the Philippines

This repository documents a geospatial case study analyzing flood exposure and accessibility of critical services (hospitals, evacuation centers) in the Philippines. The project demonstrates practical applications of **GeoPandas, rasterio, contextily, and Folium/Kepler.gl** to produce reproducible maps, spatial analyses, and interactive visualizations for local government planners.

---

## 📌 Objectives
- Identify barangays most exposed to flooding using hazard overlays and population data.
- Assess accessibility of hospitals and evacuation centers under flood-disrupted road networks.
- Provide clear, publication-quality maps and an interactive dashboard for decision-makers.

---

## 🛠️ Features
- **Data Integration**: Philippine administrative boundaries, road networks, flood hazard layers, health facilities, and population grids.
- **Spatial Analysis**: Buffers, dissolves, overlays, and zonal statistics for exposure metrics.
- **Network Disruption Modeling**: Travel-time analysis before and after flood-induced road closures.
- **Cartography & Visualization**: Choropleths, bivariate maps, and locator maps with color-blind friendly palettes.
- **Interactivity**: Folium/Kepler.gl HTML maps with toggles for hazard, facilities, travel-time, and barangay statistics.
- **Communication**: Executive brief summarizing findings, top actions, limitations, and ethical considerations.

---

## 🌍 Data Sources
- **Administrative Boundaries**: GADM v4.1, OCHA COD-AB, PSGC-based shapefiles  
- **Road Network**: Geofabrik (OSM)  
- **Population**: WorldPop Philippines (~100m resolution)  
- **Critical Facilities**: HOTOSM Health Facilities (HDX)  
- **Flood Hazard Layers**: HazardHunterPH, PAGASA Flood Hazard Maps  

You can access and download all datasets using this link ([Dataset](https://drive.google.com/drive/folders/1Y5Ip_irXkfSIW9L1Xl5r__uY3inmegBW?usp=drive_link)) .

---

## 🚀 Getting Started
### Prerequisites
- Python 3.9+  
- Conda or virtualenv for environment management  

### Installation
```bash
# Clone the repository
git clone https://github.com/Gurlly/case_study_flood.git
cd case-study-flood

# Create environment
conda env create -f environment.yml
conda activate flood-analysis
```

----

## Members

David Raniel Cauba
Kendrick Beau Calvo
Dodge Lapis
Nathanael Martinez
Hannah Tuazon