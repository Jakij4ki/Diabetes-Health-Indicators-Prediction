# Capstone Project: Diabetes Prediction with Machine Learning & IBM Granite

# Project Overview
Proyek ini bertujuan untuk memprediksi risiko diabetes menggunakan dataset Diabetes Health Indicators BRFSS 2015 yang dirilis oleh CDC (Centers for Disease Control and Prevention). Latar belakang dari penelitian ini adalah tingginya angka penderita diabetes di dunia, khususnya yang sering tidak terdiagnosis sejak dini.

Permasalahan yang ingin diselesaikan:
- Bagaimana cara memanfaatkan data kesehatan publik untuk memprediksi risiko diabetes?
- Model machine learning mana yang paling efektif untuk prediksi ini?
- Bagaimana dukungan AI (IBM Granite Model) dapat membantu menghasilkan insight dan kesimpulan yang lebih baik?

Pendekatan yang digunakan:
- Data Understanding → eksplorasi dataset, distribusi target, korelasi antar fitur
- EDA (Exploratory Data Analysis) → analisis pola kesehatan, hubungan faktor risiko dengan diabetes
- Modeling (ML) → Logistic Regression, Random Forest, XGBoost
- Evaluation → akurasi, precision, recall, F1 Score
- Insight Generation & AI Support → menggunakan IBM Granite Model untuk membantu menyusun insight dan kesimpulan berbasis data

  # Raw Dataset Link
  Dataset yang digunakan adalah Diabetes Health Indicators (BRFSS 2015):
  https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

  # Analysis Process
  1. Data Understanding
     - Mengecek dimensi data, distribusi target, dan unique values tiap fitur.
     - Melihat distribusi class (imbalance antara diabetes vs non-diabetes).

  2. Data Cleaning & Preparation
     - Menangani missing values, outlier, serta scaling data.
     
  3. EDA (Exploratory Data Analysis)
     - Visualisasi distribusi umur, BMI, kebiasaan merokok, aktivitas fisik.
     - Korelasi heatmap antar variabel.
     
  4. Modeling (ML)
     - Logistic Regression (baseline model).
     - Random Forest (ensemble).
     - XGBoost (boosting model).
     
  5. Evaluation
     - Accuracy, Precision, Recall, F1 Score.
     - Perbandingan hasil tiap model.
     
  6. Insight & Findings
     - Faktor paling berpengaruh terhadap diabetes.
     - Model terbaik untuk prediksi.
     
  7. Conclusion & Recommendations
     - Rekomendasi berbasis hasil analisis.
     - Potensi penggunaan model di bidang kesehatan masyarakat.
     
  8. AI Support (IBM Granite Model)
     - Membantu meringkas hasil analisis.
     - Menyusun insight dan kesimpulan berbasis data.
     - Memberikan rekomendasi yang actionable.

  # Insight & findings
  - Faktor utama yang berhubungan erat dengan diabetes adalah: BMI, Age, HighBP, HighChol, dan Physical Activity.
  - Dari hasil modeling:
    1. Logistic Regression → baseline dengan akurasi 64.5%
    2. Random Forest → performa lebih baik dengan akurasi 83.9%
    3. XGBoost → model terbaik dengan akurasi 85.0% dan F1 Score 81.2%
  - XGBoost dipilih sebagai model final karena memberikan hasil paling optimal untuk prediksi diabetes.
 
  # AI Support Explanation (IBM Granite Model)
  Dalam proyek ini, IBM Granite Model digunakan untuk:
  - Membantu summarization dari hasil analisis data.
  - Memberikan penjelasan logis mengenai insight dan temuan.
  - Menyusun kesimpulan dan rekomendasi secara lebih runtut dan dapat dipahami.
  Dengan dukungan IBM Granite, insight yang dihasilkan menjadi lebih komprehensif, jelas, dan actionable untuk mendukung pengambilan keputusan di bidang kesehatan.

