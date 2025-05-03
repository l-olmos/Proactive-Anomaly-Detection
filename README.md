Datasets Used

This repository uses four multivariate time series datasets, each curated for benchmarking anomaly detection models. The datasets span real-world spacecraft telemetry and server infrastructure data.

---

### SMAP (Soil Moisture Active Passive Satellite)

The SMAP dataset consists of telemetry data from NASA’s SMAP satellite. It includes labeled point and contextual anomalies, annotated using NASA's Incident Surprise Anomaly (ISA) reports.

#### Key Stats
- **55** telemetry channels
- **429,735** total values
- **69** anomalies

#### Format
- `.csv` and `.npy` files: `train`, `test`, `labeled_anomalies.csv`

#### Source 
- Original Authors: *Kyle Hundman et al., NASA JPL*
- GitHub: [https://github.com/khundman/telemanom](https://github.com/khundman/telemanom)
- Kaggle: [SMAP Dataset on Kaggle](https://www.kaggle.com/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl)

---

### MSL (Mars Science Laboratory – Curiosity Rover)

The MSL dataset includes telemetry from NASA’s Mars rover. Anomalies are hand-labeled using domain knowledge from NASA engineers and documents.

#### Key Stats
- **27** telemetry channels
- **66,709** total values
- **36** anomalies

#### Format
- `.csv` and `.npy` files: `train`, `test`, `labeled_anomalies.csv`

#### Source 
- Original Authors: *Kyle Hundman et al., NASA JPL*
- GitHub: [https://github.com/khundman/telemanom](https://github.com/khundman/telemanom)
- Kaggle: [MSL Dataset on Kaggle](https://www.kaggle.com/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl)

---

### SMD (Server Machine Dataset – OmniAnomaly Version)

The SMD dataset consists of server infrastructure metrics collected from 28 machines over a 5-week period. It includes train/test splits and anomaly labels for each machine entity.

#### Key Stats
- **28** different machines/entities
- **38** features per machine
- Balanced train/test splits

#### Format
- `.txt` files: `train`, `test`, `test_label`, `interpretation_label`

#### Source 
- Original Authors: *NetMan AIOps Team – OmniAnomaly project*
- GitHub: [https://github.com/NetManAIOps/OmniAnomaly](https://github.com/NetManAIOps/OmniAnomaly)
- Kaggle: [SMD Dataset on Kaggle](https://www.kaggle.com/datasets/mgusat/smd-onmiad)

---

### 📈 PSM (Pooled Server Metrics – from eBay Inc.)

The PSM dataset was publicly released by eBay Inc. as part of the RANSynCoders project. It contains real server telemetry data for asynchronous anomaly detection.

#### Key Stats
- Contains labeled normal/anomalous server data

#### Format
- `.csv` files: `train`, `test`, `test_label`

#### Source 
- Authors: *Abdulaal et al., eBay Inc.*
- GitHub: [https://github.com/eBay/RANSynCoders](https://github.com/eBay/RANSynCoders)
- Kaggle: [PSM Dataset on Kaggle](https://www.kaggle.com/datasets/ljolm08/pooled-server-metrics-psm)

---

**Usage Note:** All datasets are used strictly for academic and research purposes. Always cite the original authors and comply with license terms where applicable.
