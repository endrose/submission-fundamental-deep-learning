# Final Project Belajar Fundamental Deep Learning - Dicoding

## Rice Image Classification
Proyek ini membangun model Convolutional Neural Network (CNN) untuk melakukan klasifikasi gambar varietas beras (Rice Image Dataset).

### Kriteria Submission:
- **Dataset**: Rice Image Dataset (>1000 gambar, 5 kelas: Arborio, Basmati, Ipsala, Jasmine, Karacadag).
- **Pembagian Data**: Train (80%), Validation (10%), Test (10%).
- **Arsitektur Model**: Sequential dengan layer Conv2D & MaxPooling2D.
- **Akurasi**: >85% pada Training, Validation, dan Testing set.
- **Export Formats**: SavedModel, TFLite, dan TensorFlow.js (TFJS).

### Fitur & Struktur Folder:
- `notebook.ipynb`: Jupyter Notebook utama berisi eksperimen, training, visualisasi, dan evaluasi.
- `requirements.txt`: Daftar dependensi library Python.
- `saved_model/`: Model dalam format SavedModel TensorFlow.
- `tflite/`: Model TFLite beserta `label.txt`.
- `tfjs_model/`: Model TensorFlow.js (`model.json` dan weights binary).
