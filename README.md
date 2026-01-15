# 🩺 PySpark Health Data Analysis - Diabetes Prediction

Proyek analisis data kesehatan menggunakan PySpark untuk prediksi diabetes dengan teknik Big Data dan Machine Learning.

## 📋 Deskripsi Proyek

Proyek ini merupakan implementasi analisis data kesehatan untuk prediksi diabetes menggunakan PySpark (Apache Spark) dengan dataset Big Data. Proyek mencakup preprocessing data, pembangunan model machine learning, evaluasi model, dan visualisasi hasil.

## 🎯 Tujuan

1. **Pengumpulan dan Pemrosesan Data**: Menggunakan dataset diabetes berskala besar dengan preprocessing yang komprehensif
2. **Model AI**: Membangun dan membandingkan beberapa model machine learning (Logistic Regression, Random Forest, Gradient Boosting)
3. **Analisis dan Visualisasi**: Menampilkan hasil analisis dengan visualisasi yang informatif
4. **Integrasi Big Data Tools**: Menggunakan PySpark untuk menangani data berskala besar

## 🛠️ Teknologi yang Digunakan

- **PySpark**: Framework Big Data untuk pemrosesan data berskala besar
- **Apache Spark MLlib**: Library machine learning untuk Spark
- **Matplotlib**: Visualisasi data
- **Pandas**: Manipulasi data untuk visualisasi
- **Python 3.x**: Bahasa pemrograman utama

## 📊 Dataset

- **File**: `diabetes_012.csv`
- **Deskripsi**: Dataset kesehatan untuk prediksi diabetes
- Dataset utama berisi lebih dari 250,000 records

## 🚀 Cara Menjalankan

### Prasyarat

1. Install Python 3.7 atau lebih tinggi
2. Install Java JDK (diperlukan untuk PySpark)
3. Install PySpark dan dependencies lainnya

### Instalasi

```bash
# Clone repository
git clone <repository-url>
cd FP

# Install dependencies
pip install -r requirements.txt
```

### Menjalankan Notebook

```bash
# Buka Jupyter Notebook
jupyter notebook coba2.ipynb
```

Atau gunakan JupyterLab:

```bash
jupyter lab coba2.ipynb
```

## 📁 Struktur Proyek

```
FP/
│
├── coba2.ipynb              # Notebook utama dengan analisis lengkap
├── diabetes_012.csv         # Dataset utama
├── requirements.txt          # Dependencies Python
├── README.md                # Dokumentasi proyek
├── .gitignore               # File yang diabaikan Git
│
└── archive/                 # Dataset arsip (opsional)
    ├── diabetes_data.csv
    ├── hypertension_data.csv
    └── stroke_data.csv
```

## 🔍 Fitur Utama

### 1. Preprocessing Data

- Handling missing values
- Target engineering
- Handling class imbalance dengan oversampling
- Feature selection
- Normalisasi dengan StandardScaler

### 2. Model Machine Learning

- **Logistic Regression**: Model linear untuk klasifikasi
- **Random Forest**: Ensemble method dengan multiple decision trees
- **Gradient Boosting Trees (GBT)**: Boosting algorithm untuk meningkatkan akurasi

### 3. Evaluasi Model

- Accuracy
- F1 Score
- AUC (Area Under Curve)
- Feature Importance Analysis

### 4. Visualisasi

- Perbandingan performa model (Accuracy, F1, AUC)
- Feature importance visualization
- Analisis distribusi data

### 5. Hyperparameter Tuning

- Optimasi parameter untuk Random Forest
- Train-Validation Split untuk evaluasi

## 📈 Hasil

Model terbaik yang dihasilkan:

- **GBT**: Accuracy ~75.3%, F1 Score ~75.2%, AUC ~83.1%
- **Logistic Regression**: Accuracy ~74.5%, F1 Score ~74.5%, AUC ~82.2%
- **Random Forest**: Accuracy ~74.0%, F1 Score ~73.9%, AUC ~81.3%

## 📝 Catatan Penting

- Pastikan Java JDK sudah terinstall sebelum menjalankan PySpark
- Dataset `diabetes_012.csv` harus berada di direktori yang sama dengan notebook
- Proses training membutuhkan waktu yang cukup lama karena ukuran dataset yang besar
- Disarankan menggunakan komputer dengan RAM minimal 8GB

## 👤 Authors

- **Ali Rafli Putra Hakiki** (120322107)
- **Okky Rangga Pratama** (1203220011)
- **Bagus Christiannanta** (1203220161)

## 📄 License

Proyek ini dibuat untuk keperluan akademik.

## 🙏 Acknowledgments

- Dataset dari CDC (Centers for Disease Control and Prevention)
- Apache Spark Community
- PySpark Documentation
