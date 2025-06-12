```perl
# 🧠 Student Performance Classification 🎓

This project classifies students' academic performance using machine learning,
and provides recommendations to help improve their grades 📈.

## 📁 Project Structure

student-performance-classification/
├── data/
│   ├── raw/
│   │   └── student_performance.csv
│   └── processed/
│       ├── preprocessed_data.csv
│       ├── predicted_grades.csv
│       └── recommendation_output.csv
├── scripts/
│   ├── preprocessing.ipynb
│   ├── train_model.ipynb
│   ├── predict.ipynb
│   ├── recommender.ipynb
│   └── utils.ipynb
├── models/
│   └── student_grade_model.pkl
└── README.md

## 🚀 How to Use

1. Jalankan semua notebook di folder `scripts/` secara berurutan:
   - `preprocessing.ipynb` untuk membersihkan dan menyiapkan data
   - `train_model.ipynb` untuk melatih model klasifikasi
   - `predict.ipynb` untuk memprediksi nilai siswa
   - `recommender.ipynb` untuk memberikan rekomendasi belajar
   - `utils.ipynb` untuk fungsi tambahan

2. Hasil akan tersimpan di `data/processed/`:
   - `preprocessed_data.csv`
   - `predicted_grades.csv`
   - `recommendation_output.csv`

3. Model tersimpan di:
   - `models/student_grade_model.pkl`

## 🧠 Features Digunakan

- Gender
- Department
- Attendance
- Study Hours, Sleep Hours
- Parent Education Level
- Family Income
- Stress Level
- Internet Access at Home
- Participation in Extracurricular Activities
- Midterm & Final Scores

## 🤖 Model

- Logistic Regression (class_weight='balanced')
- Accuracy: ±90% di data uji
- Preprocessing menggunakan:
  - OneHotEncoding untuk fitur kategorikal
  - MinMaxScaler untuk fitur numerik

## 🎯 Tujuan

Untuk memprediksi grade siswa dan memberikan rekomendasi belajar personal
yang dapat membantu meningkatkan performa akademik mereka 🎓✨

## 👨‍💻 Author

- Khanifan (@Lucafivan)
```
