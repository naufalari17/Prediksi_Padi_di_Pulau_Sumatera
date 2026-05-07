# Prediksi Produksi Padi di Pulau Sumatera

## Deskripsi Project

Project ini bertujuan untuk membandingkan performa beberapa algoritma dalam melakukan prediksi berdasarkan dataset yang digunakan. Model yang diuji meliputi Linear Regression, Random Forest, K-Nearest Neighbors (KNN), dan Decision Tree.

---

## Tujuan

* Membangun model regresi untuk prediksi
* Membandingkan performa beberapa algoritma
* Menentukan model terbaik berdasarkan evaluasi

---

## 📂 Dataset

Dataset yang digunakan berisi beberapa fitur numerik yang digunakan untuk memprediksi variabel target (misalnya produksi).
*(Tambahkan sumber dataset jika ada, misalnya Kaggle)*

---

## Model yang Digunakan

1. Linear Regression
2. Random Forest Regressor
3. K-Nearest Neighbors (KNN)
4. Decision Tree Regressor

---

## Metode Evaluasi

Model dievaluasi menggunakan:

* R2 Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

---

## Hasil Evaluasi

| Model             |  R2-score | Mean Absolute Error | Mean Squared Error |
| ----------------- | --------: | ------------------: | -----------------: |
| Linear Regression | 84.590840 |            0.211612 |           0.154092 |
| Random Forest     | 86.281533 |            0.210990 |           0.137185 |
| K-Neighbors       | 82.353772 |            0.294686 |           0.176462 |
| Decision Tree     | 79.059485 |            0.267631 |           0.209405 |

---

## Kesimpulan

Berdasarkan hasil evaluasi, **Random Forest** merupakan model terbaik dengan nilai R2-score tertinggi serta error paling rendah dibandingkan model lainnya. Model ini mampu memberikan prediksi yang lebih akurat dan stabil. Linear Regression juga menunjukkan performa yang cukup baik, sementara KNN dan Decision Tree memiliki performa yang lebih rendah pada dataset ini.

---

##Pengembangan Selanjutnya

* Hyperparameter tuning
* Menambahkan model lain seperti Gradient Boosting / XGBoost
* Deployment model (API / Web App)
