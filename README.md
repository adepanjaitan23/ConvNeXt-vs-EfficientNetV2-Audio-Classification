# ConvNeXt vs EfficientNetV2 - Audio Classification
[![Paper](https://img.shields.io/badge/Media-Pendukung-2563eb?style=for-the-badge&logo=googledrive&logoColor=white)](https://doi.org/10.33005/santika.v6i1.1081)

Repositori ini berisi kode implementasi dan eksperimen untuk keperluan publikasi *proceeding* / penelitian akademik menggunakan arsitektur *Deep Learning* tingkat lanjut pada dataset audio.

## 📌 Deskripsi Proyek
Proyek ini berfokus pada pemrosesan sinyal audio menggunakan ekstraksi fitur (seperti *Log-Mel Spectrogram*) dan evaluasi performa berbagai arsitektur model (*Convolutional Neural Networks* / *Vision Transformer*) untuk klasifikasi data audio.

## 🗂️ Struktur File
- `Presenter_Proseeding_Reduces_60_40.ipynb`: Jupyter Notebook utama yang mencakup:
  * Pra-pemrosesan data (*Data Preprocessing* & *Augmentation*)
  * Ekstraksi fitur audio menggunakan `librosa`
  * Pelatihan model (*Model Training* menggunakan `PyTorch`)
  * Evaluasi performa dan visualisasi metrik (*Confusion Matrix*, *Accuracy*, *Loss*)

## 🛠️ Kebutuhan Sistem (Dependencies)
Pastikan pustaka Python berikut terinstal di lingkungan kerja Anda (atau Google Colab):
```bash
pip install -r requirements.txt
