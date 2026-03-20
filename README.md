============================================================
PROYEK DATA UNDERSTANDING ICU (CRISP-DM D1-D8)
============================================================

Ringkasan:
- Dataset: ICU Patient Monitoring Mortality Prediction (15.000 baris, 24 kolom)
- Fokus: Data Understanding (bukan modeling)
- Notebook utama: ICU_Data_Understanding_AgenticAI.ipynb
- Bahasa laporan: Indonesia

Struktur folder saat ini:
- dataset/
  - ICU_Patient_Monitoring_Mortality_Prediction_15000.csv
- figures/
  - du_step01_d1_schema_cardinality.png
  - du_step02_d2_representativeness_counts.png
  - du_step03_d2_bias_audit.png
  - du_step04_d3_vital_distributions.png
  - du_step05_d3_missing_heatmap.png
  - du_step06_d3_correlation.png
  - du_step07_d4_pitfall_status.png
  - du_step08_d5_quality_scores.png
  - du_step10_d7_fairness_descriptive.png
- outputs/
  - Data_Card_ICU.md
  - pitfall_checklist.csv
  - data_quality_report.csv
  - evaluation_plan.csv
  - evaluation_plan.md
  - fairness_descriptive_summary.csv
  - deliverable_audit.csv
- docs/
  - ieee_data_understanding_paper_v2.tex
  - documentation_data_understanding_v2.md
  - documentation_data_understanding_v2.docx

Catatan penting per langkah:
- D6 (Evaluation Design Plan): disajikan sebagai tabel/artefak (tanpa chart Included=1).
- D7 (Fairness & Ethical Audit): sudah diperluas jadi multi-subgroup dan multi-metrik.
- D8 (Audit Deliverable): disajikan tabel + skor teks (tanpa chart skor tunggal).

Cara menjalankan ulang notebook:
1) Buka ICU_Data_Understanding_AgenticAI.ipynb
2) Jalankan semua cell dari atas ke bawah (Restart Kernel & Run All)
3) Cek artefak hasil pada folder figures/, outputs/, dan docs/
