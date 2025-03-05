# **Klasifikasi Gambar Kucing🐈🐈‍⬛**  

Proyek ini bertujuan untuk mengklasifikasikan gambar kucing ke dalam beberapa jenis berdasarkan ciri-ciri visualnya. Prosesnya dimulai dengan mengambil dataset gambar, lalu dilakukan beberapa tahap seperti pengolahan gambar, pelatihan model, dan evaluasi hasil.  

Gambar-gambar yang digunakan terlebih dahulu diproses agar lebih siap digunakan dalam model, seperti diubah ukurannya dan diberi variasi tambahan agar model bisa mengenali pola dengan lebih baik. Setelah itu, model dilatih menggunakan contoh gambar yang sudah dikategorikan, sehingga bisa mempelajari perbedaan antar jenis kucing.  

Setelah model selesai dilatih, dilakukan pengujian untuk melihat seberapa baik model bisa mengenali gambar baru. Hasil evaluasi menunjukkan seberapa akurat model dalam mengklasifikasikan gambar, serta area yang masih bisa ditingkatkan.  

Proyek ini bisa berguna untuk berbagai keperluan, seperti membantu identifikasi jenis kucing dalam penelitian atau aplikasi lain yang memerlukan pengenalan gambar hewan.  

## **Cara Menjalankan**  
1. Pastikan semua dependensi sudah terinstall. Jika belum, jalankan perintah berikut untuk menginstalnya:  
   ```bash
   pip install -r requirements.txt
   ```  
2. Jika ingin menyimpan daftar dependensi yang digunakan dalam proyek ini, bisa menjalankan:  
   ```bash
   pip freeze > requirements.txt
   ```  

## **Struktur Folder**  
````  
submission  
├───tfjs_model  
│   ├───group1-shard1of1.bin  
│   └───model.json  
├───tflite  
│   ├───model_1.tflite  
│   └───label1.txt  
├───saved_model  
│   ├───model_1.h5   
├───notebook.ipynb  
├───README.md  
└───requirements.txt  
````  
