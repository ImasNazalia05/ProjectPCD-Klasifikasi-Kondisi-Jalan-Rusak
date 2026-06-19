# Klasifikasi Kondisi Jalan Berbasis Analisis Tekstur Menggunakan KKN, SVM, dan Random Forest
### Deskripsi Project
Project ini bertujuan untuk mengklasifikasikan kondisi permukaan jalan berdasarkan karakteristik tekstur yang terdapat pada citra, dengan memanfaatkan teknik analisis tekstur seperti Gray Level Co-occurrence Matrix (GLCM) untuk mengekstrak fitur-fitur penting dari citra, antara lain kontras, homogenitas, korelasi, energi, serta entropi. Fitur-fitur tekstur tersebut diharapkan dapat merepresentasikan perbedaan karakteristik visual antara kondisi jalan yang baik, rusak ringan, maupun rusak berat, sehingga dapat dijadikan acuan dalam proses klasifikasi secara otomatis.

Sebelum dilakukan ekstraksi fitur, citra jalan terlebih dahulu melalui serangkaian tahap preprocessing, meliputi proses noise reduction menggunakan median filter, penajaman citra (sharpening) dan deteksi tepi menggunakan operator Sobel, serta segmentasi citra melalui thresholding Otsu yang dilanjutkan dengan operasi morfologi. Tahapan preprocessing ini bertujuan untuk meningkatkan kualitas citra serta menonjolkan informasi tekstur yang relevan, sehingga proses ekstraksi fitur pada tahap selanjutnya dapat menghasilkan representasi data yang lebih akurat dan informatif.

Hasil ekstraksi fitur tekstur tersebut kemudian digunakan sebagai input untuk melatih dan menguji tiga model machine learning, yaitu K-Nearest Neighbors (KNN), Support Vector Machine (SVM), dan Random Forest, yang masing-masing memiliki pendekatan berbeda dalam melakukan klasifikasi. Ketiga model ini selanjutnya dibandingkan performanya berdasarkan metrik evaluasi seperti akurasi, precision, recall, dan f1-score, sehingga dapat diketahui model mana yang paling optimal dan andal dalam mengklasifikasikan kondisi jalan berdasarkan analisis tekstur citra, dengan harapan hasil penelitian ini dapat dimanfaatkan untuk mendukung sistem pemantauan infrastruktur jalan secara lebih efisien dan otomatis.

## Nama Anggota Kelompok 14
### Imas Nazalia Rahmawati : F1D02410055
### Irlan Hadi             : F1D02410058
### yoga Adiguna           : F1D02410028
### Yunda Hayatus Soleha   : F1D02410029