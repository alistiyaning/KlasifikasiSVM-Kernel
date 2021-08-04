# KlasifikasiSVM-Kernel
Program ini merupakan program Klasifikasi Artikel Ilmiah Ilmu Komputer Berbahasa Indonesia  menggunakan Metode Support Vektor Machine dengan beberapa kernel sebagai bahan komparasi, projek in dibuat untuk memenuhi syarat kelulusan S1- Informatika (Skripsi) Universitas Pembangunan Nasional Veteran Yogyakarta.

Dataset yang didapatkan dari website GARUDA dan portal jurnal ilmiah dari berbagai kampus, pengambilannya dilakukan secara selektif dengan mengambil artikel yang terbit dalam janga 5 tahun kebelakang sejak projek ini dibuat yaitu antara tahun 2016 -2020.

Peneliti menggunakan algoritma klasifikasi Support vektor machine dengan komparasi kernel linier, kernel polynomial, dan kernel RBF.

Klasifikasi dilakukan terhadap dokumen teks pendek seperti judul , abstrak, keyword mapun potongan dari isi artikel  dan disarankan untuk input data yang memiliki banyak kata untuk mempermudah klasifikasi, karna data text yang sedikit membuat sistem cenderung berfokus pada kata tersebut sehingga tidak mencerminkan keseluruhan isi jurnal yang dapat mempengaruhi klasifikasi . 

Tujuan dari penelitian ini adalah untuk mengetahui kernel yang paling efisien jika digunakan dalam klasifikasi artikel ilmiah ilmu komputer menggunakan metode support vektor machine yang  mana metode ini menggunakan konsep linier dalam memisahkan data (memisahkan data kedalam 2 kelas menggunakan batas pemisah yang disebut dengan hyperplane) sedangkan klasifikasi artikel ilmiah bersifat multiclass (memiliki banyak kelas).

Penelitian ini terdiri dari beberapa tahap yaitu pengumpulan data, pengelompokan data, pelabelan data, pre-processing text, pembobotan kata menggunakan vector space model dan tf-idf, kernelisasi menggunakan kernel RBF  klasifikasi menggunakan support vector machine, mekanisme pengujian pada sistem ini menggunakan confusion matrix dengan pendekatan k-fold cross validation dan membagi data mejadi data training dan testing,
