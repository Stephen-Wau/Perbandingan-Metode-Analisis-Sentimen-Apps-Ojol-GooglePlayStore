# Perbandingan-Metode-Analisis-Sentimen-Apps-Ojol-GooglePlayStore
Perbandingan metode klasifikasi dalam analisis sentimen dengan data berasal dari google play store berupa review dan rating tentang ojek online di indonesia berdasarkan 3 aplikasi ojol, yaitu : Maxim, Grab dan Gojek. Data ini di crawling pada awal Mei 2023. Berikut metode klasifikasi yang saya bandingkan : 
- SVM
- Naive Bayes
- Logistic Regression
- Random Forest
- Decission Tree

Aplikasi transportasi online menjadi salah satu aplikasi yang paling banyak terinstall di smartphone manusia saat ini. segala macam aktivitas dan layanan dapat dikerjakan melalui aplikasi transportasi online, seperti transportasi, delivery makanan atau barang, pengiriman paket dll. Banyak tanggapan dari user tentang kinerja pelayanan atau aplikasi jasa transportasi online menjadi refrensi atau ulasan bagi para user yang membaca kometar (review) di google play store.

Analisis sentiment dilakukan untuk mengklasifikasikan ulasan-ulasan dari user kedalam sentiment positif, negative, dan netral dengan rating sebagai acuannya. Selanjutnya adalah melakukan klasifikasi dengan beberapa metode untuk melihat perbandingan performance antar metode klasifikasi yag digunakan. Data akan di ambil dari google play store dengan filter most relevant.

Hasil analisis menunjukan dimana sebanyak 1893 data (63,1%) bernilai negatif, 831 data (27,7%) bernilai positif dan 275 data (9,2%) bernilai netral. Penilaian berdasarkan dari rating yang diberikan oleh pengguna (user) aplikasi transportasi online yang terdiri dari aplikasi Gojek, Grab dan Maxim. Data yang ada paling banyak muncul pada bulan dimana data di crawling. Hasil proses evalution (pengujian) berbeda setiap masing-masing metode. Hal yang sama terjadi pada pengukuran accurary dari masing-masing metode dimana metode Random Forest dan SVM memiliki presentase akurasi yang paling tinggi untuk data yang di uji dengan tingkat akurasi 0,91% dan 0,92% sedangkan untuk metode niave bayes, decision tree, dan logistic regression memiliki akurasi cukup tinggi dengan presentasi masing-masing sebesar 0,79%, 0,80%, dan 0,83%.

Untuk penjelasan lebih spesifik silahkan baca dokumen skripsi berikut : 
jalankan terlebih dahulu mySQL anda :
```bash
https://drive.google.com/file/d/1fw_S2F929NFPgTkA3qu_j4JzolDtt_g7/view?usp=sharing
```
