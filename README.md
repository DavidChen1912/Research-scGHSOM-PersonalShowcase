# Research-scGHSOM Personal Showcase

**scGHSOM: A Hierarchical Framework for Single-Cell Data Clustering and Visualization**

---

## ⚠️ Disclaimer
I am a **co-author of the scGHSOM project**, and this repository is **not the official implementation**.  
This repository serves solely as a personal demo for my **Master’s program application**, highlighting my contributions as a co-author and contributor.

- 🔗 Official repository: [changlabtw/scGHSOM](https://github.com/changlabtw/scGHSOM)  
- 📄 Full paper available on *IEEE Xplore*: DOI [10.1109/TCBBIO.2025.3593632](https://doi.org/10.1109/TCBBIO.2025.3593632)  
- © Copyright belongs to **Chang Lab (NCCU)**  

All technical details, reproducibility materials, and the official source code remain under the authority of the original lab and can be accessed through the official channels linked above.

---

## 🙏 Acknowledgements
I would like to sincerely thank **Shang-Jung Wen** and **Prof. Jia-Ming Chang** for their guidance and leadership, which enabled me to **contribute and grow** throughout this project.

---

## 📌 My Contributions

### 1. Pipeline Integration & Optimization
Optimized and streamlined the **end-to-end single-cell clustering framework** of scGHSOM, transforming it into an automated analysis pipeline covering:
- Data input  
- Preprocessing  
- Clustering  
- Evaluation metrics  

**Key scripts**:  
- `programs/data_processing/format_ghsom_input_vector.py`  
- `programs/data_processing/get_ghsom_dim.py`  
- `programs/data_processing/save_cluster_with_cluster_label.py`  
- `programs/evaluation/clustering_scores.py`  
- `execute.py`  
- `grid_runner.py`  

---

### 2. Visualization Enhancement
Enhanced and extended visualization modules to improve interpretability of clustering results.  

**Key scripts**:  
- `programs/Visualize/cluster_feature_map.py`  
- `programs/Visualize/cluster_distribution_map.py`  
- `programs/Visualize/generate_treemap.py`  

---

### 3. Parameter Evaluation on CYTOF Data
Evaluated scGHSOM on CYTOF datasets across different parameter settings, recording outcomes and identifying performance patterns.

---

### 4. Benchmarking Against State-of-the-Art Methods
Benchmarked scGHSOM against recent high-performing clustering methods (e.g., **KMD**, **Costal**) and evaluated both **clustering accuracy** and **runtime efficiency**, providing insights for further optimization.

---



