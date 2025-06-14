# Marine Habitat Clustering Using Hierarchical Analysis

Contained in this repo is a project that demonstrates how to **generate synthetic marine ecological data** and apply **unsupervised machine learning** (hierarchical clustering) to explore patterns in policy coverage across marine zones.

---

### Project Overview

- 🔧 **Data Generation**: Simulates 20 marine zones with binary presence/absence data for 6 ecological policies.
- 🧠 **Distance Metric**: Jaccard distance — ideal for binary attributes.
- 🌳 **Clustering Method**: Hierarchical clustering with complete linkage.
- 🌿 **Visualization**: Dendrogram to reveal how zones group based on shared protections.
- 📊 **Output**:
  - `generated_marine_zones.csv` — synthetic raw data
  - `clustered_marine_zones.csv` — same data with cluster labels
  - `dendrogram_marine_zones.png` — dendrogram image
---

### Ecological Policies Simulated

Each marine zone is evaluated for the presence (1) or absence (0) of the following protections:
- Coral Reef Protection
- Fishing Ban
- Turtle Nesting Zone
- Oil Drilling Ban
- Marine Sanctuary Status
- Mangrove Forest Protection

---

## 🛠️ How to Run

1. Clone or download this repo
2. Install dependencies:
   ```bash
   pip install numpy pandas scipy matplotlib
