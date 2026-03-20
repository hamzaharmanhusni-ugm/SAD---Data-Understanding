# Dokumentasi Data Understanding

## Informasi Umum
- Proyek: ICU Patient Monitoring and Mortality Prediction
- Fokus: Data Understanding (bukan modeling)
- Notebook utama: `ICU_Data_Understanding_AgenticAI_.ipynb`
- Tanggal: 2026-03-20

## Struktur Alur (D1–D8)
1. **D1 Data Card**: provenance, schema, limitations
2. **D2 Representativeness & Bias Audit**
3. **D3 Advanced EDA**: distribusi, missingness, outlier, korelasi
4. **D4 Semantic Validation & Leakage Checklist**
5. **D5 Data Quality (ISO/IEC 25012)**
6. **D6 Evaluation Design Plan**
7. **D7 Fairness & Ethical Audit (deskriptif)**
8. **D8 Audit Deliverable dan skor keterpenuhan

## Ringkasan Hasil Utama
- Ukuran dataset: **15.000 x 24**
- Missing value: **0**
- Duplikasi baris: **0**
- Prevalensi mortalitas: **0.2279**
- Baseline majority accuracy: **0.7721**
- Skor keterpenuhan deliverable v2: **100.0/100**

## Daftar Artefak Output v2
- `outputs/Data_Card_ICU_v2.md`
- `outputs/pitfall_checklist_v2.csv`
- `outputs/data_quality_report_v2.csv`
- `outputs/evaluation_plan_v2.csv`
- `outputs/fairness_descriptive_summary_v2.csv`
- `outputs/deliverable_audit_v2.csv`

## Daftar Gambar v2 (Generated from Code)
- `figures/du_step01_d1_schema_cardinality_v2.png`
- `figures/du_step02_d2_representativeness_counts_v2.png`
- `figures/du_step03_d2_bias_audit_v2.png`
- `figures/du_step04_d3_vital_distributions_v2.png`
- `figures/du_step05_d3_missing_heatmap_v2.png`
- `figures/du_step06_d3_correlation_v2.png`
- `figures/du_step07_d4_pitfall_status_v2.png`
- `figures/du_step08_d5_quality_scores_v2.png`
- `figures/du_step09_d6_evaluation_plan_v2.png`
- `figures/du_step10_d7_fairness_descriptive_v2.png`
- `figures/du_step11_d8_deliverable_score_v2.png`

## Catatan Metodologis
- Seluruh visual v2 dibuat ulang dari kode notebook.
- Data Card ditempatkan di awal alur (sesuai praktik data understanding).
- Fairness masih deskriptif pada fase ini; fairness prediktif dilakukan setelah model baseline tersedia.
