# Projek_Akhir_KB

## PROJEK AKHIR KECERDASAN BUATAN
## IMAGE PROCESSING - KLASIFIKASI KEBAKARAN ATAU BUKAN

### KELOMPOK 3-A1 :
#### 1. 2109106006 --> Kania Putri Ananda
#### 2. 2109106012 --> Nurmedina Maulidiah
#### 3. 2109106025 --> Rismayanti

## Jobdesk Anggota Kelompok
1. Kania Putri Ananda  : - Mencari Dataset
                         - Data Preprocessing
                         - Data Analysis
                         - Dokumentasi
2. Nurmedina Maulidiah : - Mencari Dataset
                         - Data Collecting
                         - Data Visualisasi
                         - Dokumentasi
3. Rismayanti          : - Data Augmentasi
                         - Data Modelling
                         - Evaluasi dan Prediksi
                         - Dokumentasi

## Dataset : https://www.kaggle.com/datasets/phylake1337/fire-dataset
Dataset diambil dari kaggle yang merupakan jenis dataset citra yaitu mengklasifikasikan kebakaran atau bukan

## Model Testing
https://drive.google.com/drive/folders/1pLy7lUXCS5e6nqvcMm0CNGTtkFyCLUv1



## Penjelasan Dataset
Data dibuat untuk melatih model bisa membedakan antara data citra kebakaran dengan data citra biasa (non api), sehingga klasifikasinya adalah klasifikasi biner. Data dibagi menjadi 2 folder yaitu folder fireimages berisi 755 gambar kebakaran yang terjadi di outdoor, beberapa di antaranya mengandung asap tebal. Folder satunya adalah folder non-fireimages yang berisi 244 gambar alam yaitu hutan, pohon, sungai, manusia, hutan berkabut, danau, hewan, jalan dan air terjun

## Penjelasan Project
Project ini dibuat agar mesin bisa mengklasifikasikan apakah terjadi atau tidaknya kebakaran pada data citra yang diberikan sesuai dengan judul project dan dataset kami. Ada beberapa tahapan wajib yang harus dilakukan agar project ini memenuhi ketentuan dari project akhir, tahapan-tahapan itu yaitu data collecting, data preprocessing, data analysis and visualization, data modelling dan evaluasi.

 Dalam project ini kami menggunakan bahasa pemrograman python dan memanfaatkan beberapa library yang ada, diantaranya os, tensorflow, numpy, shutil, random, seaborn, matplotlib, PIL.
 
 Project ini diharap bisa mengklasifikasikan gambar citra sesuai dengan klasifikasinya dan diharapkan bisa memenuhi nilai praktikum kami dalam mata kuliah Kecerdasan Buatan.
 
 ## Table of Content
 ### 1. Data Collecting
 Data collecting adalah proses pengumpulan, pengukuran, dan analisis berbagai tipe informasi menggunakan teknik berstandar. Tujuan utama data collecting adalah untuk mengumpulkan informasi dan data terpercaya sebanyak-banyaknya, yang kemudian dianalisis untuk membuat sebuah keputusan yang krusial. Di sini data yang kami gunakan dicari di kaggle dengan judul fire-dataset yang kemudian melakukan split data dengan pembagian 80% training data dan 20% Validation data
 
 ### 2. Data Preprocessing
 Data preprocessing adalah teknik yang digunakan untuk mengubah data
mentah dalam format yang berguna dan efisien. Hal ini diperlukan karena data
mentah seringkali tidak lengkap dan memiliki format yang tidak konsisten. Processing yang dilakukan pada project kami ini Augmentasi

### 3. Data Analysis and Visualization
Data Analysis merupakan proses inspeksi serangkaian data yang berguna untuk mendapatkan kesimpulan dari informasi yang ada. Digunakan untuk mendapatkan hasil akhir yang lebih baik dan akurat. Setelah data kami dilakukan proses analisis, ditemukan 795 gambar milik 2 kelas.

visualisasi data atau data visualization adalah tampilan berupa grafis atau visual dari informasi dan data. Di project kami, kami menampilkan data citra sebelum dan setelah dilakukan proses augmentasi dengan ukuran 10x10 dan sebanyak 8 gambar dan juga menampilkan grafik antara accuracy train/validation dan loss train/validation

### 4. Data Modeling
Training model merupakan proses belajar mesin dari dataset yang kita
berikan. Tujuan utama dari training model adalah mendapatkan akurasi yang tinggi dengan beban
komputasi sekecil mungkin. Adapun yang kami lakukan adalah membuat arsitektur model, melakukan callback agar pelatihan model dihentikan ketika sudah mencapai akurasi lebih dari 95% sehingga tidak terjadi over fitting, melakukan model compile, melatih model, mengevaluasi dan menyimpan hasil training

### 5. Evaluasi
Evaluasi adalah kegiatan terencana untuk mengukur dan menilai keberhasilan suatu program. Disini kami melakukan prediksi data validasi apakah sesuai dengan kelasnya dan juga melakukan prediksi gambar dari data testing.
