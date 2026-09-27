# Q-SpectralGuard

**Quantum-Inspired Spectral-Spatial Representation Learning for Multispectral Land-Cover Classification**

Q-SpectralGuard is a lightweight deep learning framework for **multispectral Sentinel-2 land-cover classification** using the **EuroSAT** dataset. The proposed approach combines spectral-spatial CNN feature extraction with a compact **quantum-inspired differentiable feature mapping**.

## Highlights

- 13-band Sentinel-2 multispectral imagery
- Spectral-spatial CNN feature extraction
- Compact 8-dimensional feature bottleneck
- Quantum-inspired nonlinear feature mapping
- Lightweight architecture with **409,450 parameters**
- Comprehensive classification, ROC, PR, and confusion-matrix evaluation

## Results

| Metric | Result |
|---|---:|
| Validation Accuracy | **98.12%** |
| Test Accuracy | **97.80%** |
| Macro Precision | **0.9771** |
| Macro Recall | **0.9769** |
| Macro F1-Score | **0.9769** |
| Macro ROC-AUC | **0.9987** |
| Macro Average Precision | **0.9927** |
| Parameters | **409,450** |

## Architecture

```text
13-Band Sentinel-2 Image
          ↓
Spectral-Spatial CNN Encoder
          ↓
256-D Feature Representation
          ↓
64-D Bottleneck
          ↓
8-D Compact Representation
          ↓
Quantum-Inspired Feature Mapping
          ↓
Lightweight Classifier
          ↓
10-Class Land-Cover Prediction
