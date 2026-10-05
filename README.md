# 🩺 Sistem Pakar Identifikasi Penyakit Kulit

Sebuah aplikasi web interaktif yang memadukan arsitektur web modern dengan logika komputasi cerdas untuk mengidentifikasi penyakit kulit. Sistem ini mengintegrasikan model *Deep Learning* (MobileNetV2) untuk analisis citra dan metode *Certainty Factor* (Sistem Pakar) untuk mengukur tingkat kepastian diagnosis berdasarkan gejala yang dialami pengguna.

## 📸 Antarmuka Aplikasi
![Expert System Screenshot] <img width="1903" height="905" alt="Screenshot 2026-09-20 205448" src="https://github.com/user-attachments/assets/296807f4-d310-4b99-b6ff-b68ef42e3f75" />


## 💻 Tech Stack & Architecture
- **Back-End Framework:** Python (Flask)
- **Machine Learning & AI:** TensorFlow.js, MobileNetV2
- **Algoritma Sistem Pakar:** Certainty Factor
- **Database:** MySQL
- **Front-End:** Bootstrap, HTML5, CSS3, JavaScript
- **System Modeling:** PlantUML, draw.io

## ✨ Fitur Utama
- **Diagnosis Berbasis Citra (Image Classification):** Pengguna dapat mengunggah foto kondisi kulit, dan sistem akan memprosesnya menggunakan model MobileNetV2 untuk deteksi awal.
- **Sistem Tanya Jawab Gejala interaktif:** Menggunakan perhitungan *Certainty Factor* untuk memberikan persentase tingkat keyakinan diagnosis berdasarkan observasi gejala yang dipilih pengguna.
- **Manajemen Basis Pengetahuan (Knowledge Base):** Dashboard admin untuk menambah, mengedit, atau menghapus data penyakit, gejala, dan nilai bobot pakar (*MB/MD*).
- **Desain Responsif:** Antarmuka yang dioptimalkan dengan Bootstrap sehingga mudah diakses baik melalui desktop maupun perangkat *mobile*.
