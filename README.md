# Terravik-Optimizing-Urban-Heat-Mitigation-and-cooling-strategies-via-AIML

# 🌍 AeroCool AI
### *Turning Satellite Intelligence into Actionable Urban Cooling Strategies.*

> **What if cities could predict tomorrow's heat and know exactly where to plant trees, install cool roofs, or redesign urban spaces before extreme temperatures impact millions?**
>
> **AeroCool AI** leverages **Earth Observation**, **Physics-Informed Artificial Intelligence**, **Explainable AI**, and **Reinforcement Learning** to transform satellite data into optimized, scientifically validated cooling strategies for climate-resilient cities.

---

## 🚀 Overview

**AeroCool AI** is an AI-powered geospatial decision support system developed by **Team Terravik** for the problem statement:

> **Optimizing Urban Heat Mitigation and Cooling Strategies via Artificial Intelligence and Machine Learning (AIML).**

The platform integrates multi-source satellite imagery, geospatial analytics, and advanced AI models to identify urban heat hotspots, quantify the key environmental drivers responsible for heat accumulation, and recommend optimized cooling interventions based on spatial and budget constraints.

Rather than simply visualizing heat maps, AeroCool AI provides **predictive, explainable, and optimization-driven recommendations** that assist urban planners in making informed climate adaptation decisions.

---

# ✨ Key Features

- 🛰 Multi-source Earth Observation data integration
- 🌡 High-resolution Urban Heat Stress Mapping
- 🧠 Physics-Informed Graph Neural Network (PI-GNN)
- 🔍 Explainable AI (TreeSHAP) Driver Diagnostics
- 🤖 Reinforcement Learning-based Cooling Optimization
- 🗺 Interactive Geospatial Dashboard
- 💰 Budget-aware Intervention Planning
- 📈 Temperature Reduction & ROI Estimation

---

# 🏗 System Workflow

<img width="1656" height="950" alt="ChatGPT Image Jul 1, 2026 at 11_00_29 PM" src="https://github.com/user-attachments/assets/496022d4-a63d-4f64-bd0e-ba3c396d5030" />

---

# ⚙ Technology Stack

### AI & Machine Learning
- PyTorch Geometric
- Stable Baselines3 (PPO)
- SHAP (TreeSHAP)
- MLflow

### Geospatial Analytics
- Google Earth Engine
- GeoPandas
- Rasterio
- Shapely
- Uber H3

### Backend
- FastAPI
- PostgreSQL + PostGIS
- Redis
- Celery

### Frontend
- React
- TypeScript
- Mapbox GL JS

### Deployment
- Docker
- Kubernetes
- Google Cloud Platform (GCP) / AWS
- GitHub Actions

---

# 🛰 Datasets Referred

### Landsat-8
- **Landsat-8 Collection (Google Earth Engine)**
  [developers.google.com/earth-engine/datasets/catalog/landsat-8](https://developers.google.com/earth-engine/datasets/catalog/landsat-8?hl=en)
  Used for surface reflectance and thermal band data via Earth Engine's processed collection.

- **USGS Earth Explorer**
  [usgs.gov/landsat-missions/landsat-data-access](https://www.usgs.gov/landsat-missions/landsat-data-access)
  Direct access portal for raw Landsat scenes and archival data.

### ECOSTRESS
- **NASA ECOSTRESS L2T LSTE V2 (Google Earth Engine)**
  [developers.google.com/earth-engine/datasets/catalog/NASA_ECOSTRESS_L2T_LSTE_V2](https://developers.google.com/earth-engine/datasets/catalog/NASA_ECOSTRESS_L2T_LSTE_V2)
  Tiled, geolocated land surface temperature and emissivity data at high spatial resolution.

- **NASA Earthdata Search**
  [search.earthdata.nasa.gov/search?q=ecostress](https://search.earthdata.nasa.gov/search?q=ecostress&ac=true)
  Used for discovering and accessing additional ECOSTRESS granules.

- **NASA JPL ECOSTRESS Mission Data Portal**
  [ecostress.jpl.nasa.gov/data](https://ecostress.jpl.nasa.gov/data/)
  Mission-level documentation and direct data downloads.

> All datasets are processed and integrated primarily through **Google Earth Engine**, with feature extraction pipelines aligned to **H3 spatial indexing** for urban graph construction.

---

# 🔄 Workflow

1. Acquire multi-source satellite and meteorological data.
2. Preprocess and extract urban environmental features.
3. Model urban heat dynamics using Physics-Informed Graph Neural Networks.
4. Identify hotspot drivers using Explainable AI.
5. Optimize cooling interventions using Reinforcement Learning.
6. Visualize recommendations through an interactive dashboard.

<img width="1693" height="929" alt="ChatGPT Image Jun 30, 2026 at 10_26_47 PM" src="https://github.com/user-attachments/assets/9e57c1eb-8c0c-4288-acd5-2faa4812cc15" />

---

# 🌱 Cooling Interventions

- 🌳 Urban Tree Plantation
- 🏠 Cool Roofs
- 🌿 Green Roofs
- 🛣 Reflective Pavements
- 🌊 Water Bodies
- 🌱 Urban Green Spaces

---

# 📸 Screenshots

<!-- Replace the placeholders below with actual images, e.g. ![Dashboard](./assets/dashboard.png) -->

| Urban Heat Stress Map | Intervention Report |
|:---:|:---:|
| <img width="1600" height="1280" alt="screen" src="https://github.com/user-attachments/assets/a7f64430-3755-4de4-be06-bcdd422b95d4" /> | <img width="1263" height="1600" alt="screen" src="https://github.com/user-attachments/assets/bd72b691-ae3e-4b46-af89-25777093fc27" /> |

| XAI Driver Diagnotics | Analytics and Monitoring |
|:---:|:---:|
| <img width="1620" height="1300" alt="Screenshot 2026-07-06 at 3 38 30 PM" src="https://github.com/user-attachments/assets/ebc35a3b-edeb-4308-92b0-9d3ff1dec704" /> | <img width="1600" height="1575" alt="screen" src="https://github.com/user-attachments/assets/b505322d-3c29-4020-8c47-ce4d0affd0af" /> |

---

# 📊 Expected Outcomes

- Urban Heat Stress Maps
- Hotspot Driver Attribution
- Physics-Constrained Heat Prediction
- AI-Optimized Cooling Strategies
- Up to **3.5°C Localized Temperature Reduction**
- Enhanced Climate Resilience

---

# 🌎 Impact

AeroCool AI empowers municipalities, urban planners, and smart city authorities with **scientifically validated**, **AI-driven**, and **cost-effective** solutions for mitigating Urban Heat Islands. By combining satellite intelligence with physics-informed machine learning, the platform enables evidence-based planning that improves thermal comfort, reduces energy consumption, lowers carbon emissions, and supports sustainable urban development.

---

# 👥 Team Terravik

| Name | Role |
|------|------|
| **Mayank Agrawal** | AI/ML — PI-GNN & Reinforcement Learning |
| **Kavya Goyal** | Backend & Data Pipeline |
| **Dushyant Saini** | Geospatial Analytics & Earth Engine Integration |
| **Unnati Gupta** | Frontend & Dashboard Design |

### **Building Smarter Cities for a Cooler Tomorrow.** 🌿

Developed with ❤️ by **Team Terravik**
