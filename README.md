
---

## **README – `grid_anomaly_detection`**

```markdown
# Grid Anomaly Detection

**Objective**  
Detect anomalies in SCADA/AMI time-series data using statistical, ML, and hybrid methods for operational monitoring and fault detection.

## Dataset
- **Source**: [Dataset link or synthetic note]
- **Sampling**: [e.g., 15-min intervals]
- **Injected Anomalies**: Spikes, drifts, missing data

## Methodology
1. Statistical: IQR, 3-sigma rules
2. Forecast residual-based detection
3. Change point detection
4. Optional: Autoencoder-based detection

## Results
| Method           | Precision | Recall | PR-AUC |
|------------------|-----------|--------|--------|
| IQR Rule         | XX%       | XX%    | X.XX   |
| Residual Method  | XX%       | XX%    | X.XX   |

**Sample Anomaly Plot**  
![anomaly](results/sample_anomaly.png)

## How to Run
```bash
python src/detect.py --input data/raw/sample.csv --output results/anomaly_report.csv
