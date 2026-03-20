| komponen | rencana |
|---|---|
| Split strategy | Train/Valid/Test = 70/15/15 |
| Stratifikasi | Ya, stratify = mortality_label |
| Baseline | Majority accuracy = 0.7721 |
| Metrik utama | PR-AUC, Recall, F1, MCC (+ ROC-AUC) |
| Catatan leakage | Drop patient_id; fit preprocessing hanya pada train set |