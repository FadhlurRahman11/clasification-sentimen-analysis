# Analisis Sentimen Keluhan Masyarakat terhadap Jaringan Internet Menggunakan XLNet dan RoBERTa

Repository ini berisi implementasi penelitian skripsi mengenai **Analisis Sentimen Keluhan Masyarakat terhadap Jaringan Internet di Kabupaten Banggai Kepulauan** menggunakan model **XLNet** dan **RoBERTa** berbasis Transformer.

## 📌 Latar Belakang

Keluhan masyarakat mengenai kualitas jaringan internet merupakan sumber informasi yang penting untuk mengevaluasi kualitas layanan telekomunikasi. Penelitian ini memanfaatkan teknologi **Natural Language Processing (NLP)** untuk mengklasifikasikan sentimen masyarakat ke dalam tiga kategori, yaitu **Positive**, **Neutral**, dan **Negative**.

Dataset terdiri dari **646 komentar** yang dikumpulkan dari **WhatsApp Group** dan **Google Form**, kemudian diproses menggunakan beberapa tahapan preprocessing sebelum dilakukan pelatihan model.

## 🎯 Tujuan Penelitian

- Melakukan analisis sentimen terhadap keluhan masyarakat.
- Membandingkan performa model **XLNet** dan **RoBERTa**.
- Menentukan model terbaik untuk klasifikasi sentimen pada dataset berbahasa Indonesia.

## ⚙️ Tahapan Penelitian

- Pengumpulan Dataset
- Data Cleaning
- Case Folding (Lowercase)
- Tokenization
- Text Normalization
- Automatic Labeling menggunakan Indonesian RoBERTa Sentiment Classifier
- Random Oversampling untuk menangani data tidak seimbang
- Train-Test Split (80:20)
- Training Model XLNet
- Training Model RoBERTa
- Evaluasi menggunakan:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

## 🧠 Model yang Digunakan

- XLNet (`xlnet-base-cased`)
- DistilRoBERTa (`distilroberta-base`)
- HuggingFace Transformers
- PyTorch

## 📊 Hasil

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|----------|-----------|--------|----------|
| XLNet | **83.45%** | 83.75% | 83.45% | 83.37% |
| RoBERTa | **87.77%** | 87.75% | 87.77% | 87.75% |

Hasil penelitian menunjukkan bahwa **RoBERTa memberikan performa terbaik** dibandingkan XLNet dalam melakukan klasifikasi sentimen terhadap keluhan jaringan internet.

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- PyTorch
- HuggingFace Transformers
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Imbalanced-learn

## 📂 Struktur Repository

```
├── dataset/
├── model/
├── notebook/
│   └── program_skripsi.ipynb
├── results/
├── requirements.txt
└── README.md
```

## 🚀 Cara Menjalankan

```bash
git clone https://github.com/username/repository.git

cd repository

pip install -r requirements.txt

jupyter notebook
```

Buka file `program_skripsi.ipynb` kemudian jalankan notebook secara berurutan.

## 📖 Referensi

Penelitian ini merupakan implementasi skripsi:

**Analisis Sentimen Keluhan Masyarakat terhadap Jaringan Internet Menggunakan Metode XLNet dan RoBERTa di Kabupaten Banggai Kepulauan**

## 👨‍💻 Author

**Nur Fadhlur Rahman**

Program Studi Informatika  
Universitas Amikom Yogyakarta

---

⭐ Jika repository ini bermanfaat, jangan lupa berikan **Star**.
