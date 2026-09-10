# ML models for parameter extraction from ECG signals (DH307)

R&D project course DH307, Koita Centre for Digital Health, IIT Bombay, Jan – May 2025. Supervisor: Prof. Nirmal Punjabi.

Pipeline for automatic ECG analysis on the MIT-BIH arrhythmia database: R-peak detection, wavelet-based and
morphological feature extraction, class balancing, and arrhythmia classification with XGBoost and PyTorch models.

## Contents

- `DH307_ECG_Feature_Extraction_and_Classification.ipynb` – full pipeline (uses `wfdb`, `pywt`, `imblearn`, `xgboost`, `torch`)
- `data/master_ecg_features_validated.csv` – extracted feature table

## Running

```bash
pip install wfdb pywavelets imbalanced-learn xgboost torch scikit-learn pandas matplotlib seaborn
```

The notebook downloads MIT-BIH records through `wfdb`.

Harshul Bhatt, B.Tech Engineering Physics, IIT Bombay (2021-2025).
