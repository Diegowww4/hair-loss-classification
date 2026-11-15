# V3.1 Experimental Results

## Dataset
- Original images: 1,113
- Final cleaned images: 700
- Training: 489
- Validation: 105
- Testing: 106
- Split method: pHash-based grouping with GroupShuffleSplit

## Final Model
MobileNetV2 with Fine-tuning

## Independent Test Results
- Accuracy: 91.51%
- Precision: 94.12%
- Recall: 88.89%
- F1-score: 91.43%
- ROC-AUC: 0.9761

## Confusion Matrix

| Actual / Predicted | Not Bald | Bald |
|---|---:|---:|
| Not Bald | 49 | 3 |
| Bald | 6 | 48 |

The results were obtained from 106 held-out test images. The dataset was cleaned to reduce duplicates and conflicting labels. Further external validation is recommended.
