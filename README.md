# Automated IDC Detection — CNN Data Pipeline

End-to-end deep learning pipeline for Invasive Ductal Carcinoma (IDC) detection 
from breast histology images.

## Pipeline Stages
```
Raw Images (277,524 patches) → Preprocessing → Augmentation → CNN Training → Evaluation → Results
```

## Results
| Metric | Improvement |
|--------|-------------|
| Accuracy | +1.47% |
| F1-Score | +10.8% |

## Tech Stack
- Python, TensorFlow/Keras, Pandas, NumPy, Matplotlib
- Dataset: Breast Cancer Histology Image Dataset (kaggle)

## Key Files
- `_~breast_cancer.ipynb` → Main pipeline notebook (preprocessing → training → evaluation)
- `SGD/` → SGD optimizer experiments
- `Perdiction-csv-SGD/` → Prediction output CSVs
- `learning_rate_search.csv` → Hyperparameter search results
