# Machine Translation dengan PyTorch

Repo ini berisi implementasi Neural Machine Translation (NMT) berbasis PyTorch, menggunakan dataset English–Indonesian.  
Eksperimen dilakukan untuk melatih model Transformer dengan berbagai konfigurasi (dropout, ukuran vocab, beam search, dll).

---

## 📂 Isi Repository
- machine-translation-dengan-pytorch.ipynb → Notebook utama berisi kode training, evaluasi, dan eksperimen.  
- DAFTAR GAMBAR OUTPUT.pdf → Kumpulan hasil output berupa grafik, tabel, dan ilustrasi hasil eksperimen.

---

## 🚀 Cara Menjalankan
1. Clone repository ini:
   ```bash
   https://github.com/nailafath/Machine_Translation_dengan_PyTorch

2. Install dependensi:
   pip install torch sentencepiece sacrebleu pandas matplotlib

3. Jalankan notebook:
   - Upload dataset English–Indonesian ke environment (misalnya Kaggle/Colab).
   - Buka dan jalankan machine-translation-dengan-pytorch.ipynb.

## 📊 Eksperimen
Eksperimen yang dilakukan meliputi:
- Pembersihan dan tokenisasi data
- Pembagian train/validation/test set
- Variasi ukuran vocab
- Pengaruh dropout terhadap performa model
- Evaluasi dengan SacreBLEU
- Perbandingan beam search size terhadap kualitas terjemahan

Detail hasil eksperimen dapat dilihat pada folder gambar_output
