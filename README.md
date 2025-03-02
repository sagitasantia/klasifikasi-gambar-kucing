# Klasifikasi Gambar Kucing

Proyek ini bertujuan untuk melakukan klasifikasi gambar kucing ke dalam tiga kategori: **Anggora**, **Persia**, dan **Kampung**. Model ini menggunakan **Convolutional Neural Networks (CNN)** untuk menganalisis dan mengklasifikasikan gambar berdasarkan kategori yang diberikan.

## Struktur Dataset

Dataset terdiri dari tiga kelas gambar:
- **Anggora**
- **Persia**
- **Kampung**

Gambar-gambar tersebut terstruktur dalam folder masing-masing sesuai dengan kelasnya dan digunakan untuk pelatihan, validasi, dan pengujian model.

## Arsitektur Model

Model yang digunakan dalam proyek ini adalah **Convolutional Neural Network (CNN)**, yang dilatih dengan beberapa lapisan konvolusi, lapisan pooling, serta lapisan fully connected untuk menghasilkan prediksi berdasarkan gambar input.

Model ini juga menggunakan **Batch Normalization** dan **Dropout** untuk meningkatkan kinerja dan mengurangi overfitting.

## Proses Pelatihan

Model dilatih menggunakan dataset gambar dengan menggunakan **ImageDataGenerator** dari Keras untuk menghasilkan data batch secara otomatis. Penggunaan **class_weight** juga diterapkan untuk mengatasi ketidakseimbangan jumlah gambar antar kelas.

Model dilatih selama beberapa epoch, dan proses pelatihan dapat dihentikan lebih awal jika tidak ada peningkatan pada **validation loss**.

## Evaluasi Model

Setelah model dilatih, model dievaluasi menggunakan data uji dan menghasilkan metrik seperti **accuracy**, **precision**, **recall**, dan **f1-score** untuk masing-masing kelas. Hasil evaluasi disajikan dalam bentuk **confusion matrix** dan **classification report**.

## Instalasi

1. Clone repositori ini:
   ```bash
   git clone <repo_url>
pip install -r requirements.txt

Dataset/
├───train/
│   ├───Anggora/
│   ├───Persia/
│   └───Kampung/
├───validation/
│   ├───Anggora/
│   ├───Persia/
│   └───Kampung/
└───test/
```

