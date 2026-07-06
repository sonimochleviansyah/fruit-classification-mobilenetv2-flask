# 🍎 Fruit Classification AI using MobileNetV2

Implementasi **Transfer Learning MobileNetV2** untuk klasifikasi jenis buah berbasis website menggunakan **Flask**. Aplikasi ini mampu mengenali beberapa jenis buah melalui gambar yang diunggah oleh pengguna dan menampilkan hasil prediksi beserta tingkat kepercayaan (*confidence score*) secara real-time.

---

## 📖 Deskripsi

Project ini merupakan implementasi metode **Transfer Learning** menggunakan arsitektur **MobileNetV2** pada bidang *Computer Vision*. Model dilatih menggunakan dataset citra buah yang terdiri dari lima kelas, kemudian diintegrasikan ke dalam aplikasi web menggunakan framework **Flask** sehingga pengguna dapat melakukan klasifikasi gambar secara langsung melalui browser.

Aplikasi ini dibuat sebagai implementasi pembelajaran Deep Learning sekaligus sebagai media demonstrasi penerapan Artificial Intelligence (AI) berbasis web.

---

## 🎯 Tujuan

- Mengimplementasikan metode Transfer Learning menggunakan MobileNetV2.
- Melatih model klasifikasi citra buah menggunakan TensorFlow dan Keras.
- Mengembangkan aplikasi web berbasis Flask untuk melakukan prediksi gambar.
- Menampilkan hasil klasifikasi beserta nilai confidence secara real-time.

---

## 🍇 Kelas Dataset

Dataset yang digunakan terdiri dari lima kelas buah, yaitu:

- 🍎 Apple
- 🍌 Banana
- 🍇 Grape
- 🥭 Mango
- 🍓 Strawberry

---

## 🧠 Model Deep Learning

Model yang digunakan pada penelitian ini adalah:

| Komponen | Keterangan |
|----------|------------|
| Model | MobileNetV2 |
| Metode | Transfer Learning |
| Framework | TensorFlow 2.15 |
| Backend | Keras |
| Input Size | 224 × 224 |
| Optimizer | Adam |
| Loss Function | Sparse Categorical Crossentropy |
| Output Layer | Softmax |

---

## 📊 Hasil Training

Model berhasil dilatih menggunakan dataset buah dan memperoleh performa sebagai berikut:

| Metric | Hasil |
|---------|-------|
| Test Accuracy | **94%** |
| Epoch | 15 |
| Framework | TensorFlow + Keras |

---

## 🚀 Fitur Aplikasi

- Upload gambar buah
- Preview gambar
- Klasifikasi otomatis menggunakan AI
- Menampilkan nama buah
- Menampilkan confidence score
- Tampilan modern menggunakan Bootstrap
- Berbasis website menggunakan Flask

---

## 🛠️ Teknologi yang Digunakan

- Python
- TensorFlow
- Keras
- MobileNetV2
- Flask
- HTML5
- CSS3
- Bootstrap 5
- NumPy
- Pillow
- Matplotlib
- Scikit-learn

---

## 📁 Struktur Project

```text
fruit-classification-mobilenetv2-flask/
│
├── dataset/
│   ├── train/
│   ├── valid/
│   └── test/
│
├── model/
│   ├── fruit_model.keras
│   └── labels.txt
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── uploads/
│
├── templates/
│   └── index.html
│
├── app.py
├── train_model.py
├── requirements.txt
├── Procfile
├── README.md
└── .gitignore
```

---

## ⚙️ Instalasi

Clone repository

```bash
git clone https://github.com/sonymochleviansyah/fruit-classification-mobilenetv2-flask.git
```

Masuk ke folder project

```bash
cd fruit-classification-mobilenetv2-flask
```

Install dependency

```bash
pip install -r requirements.txt
```

Jalankan aplikasi

```bash
python app.py
```

Buka browser

```text
http://127.0.0.1:5000
```

---

## 💻 Cara Menggunakan

1. Jalankan aplikasi Flask.
2. Buka browser.
3. Upload gambar buah.
4. Klik tombol **Prediksi**.
5. Sistem akan menampilkan:
   - Nama buah
   - Confidence Score
6. Selesai.

---

## 📸 Tampilan Aplikasi

Tambahkan screenshot aplikasi di sini setelah proses deployment.

```text
assets/
├── home.png
├── prediction.png
└── result.png
```

---

## 🔮 Pengembangan Selanjutnya

Beberapa pengembangan yang dapat dilakukan pada aplikasi ini:

- Menambahkan lebih banyak kelas buah.
- Mendukung klasifikasi video secara real-time.
- Menambahkan fitur kamera/webcam.
- Deploy menggunakan Railway atau Docker.
- Menambahkan REST API.

---

## 📄 License

Project ini dibuat untuk keperluan pembelajaran dan tugas akademik.

---

## 👨‍💻 Author

**Soni Moch Leviansyah**

GitHub: https://github.com/sonymochleviansyah

---

⭐ Apabila project ini bermanfaat, jangan lupa berikan **Star** pada repository ini.
