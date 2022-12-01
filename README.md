# Footwear Identifier (ShoeSandalBoot)
## - KELOMPOK A2'1-21 Projek Akhir Kecerdasan Buatan -
<br>

## DATASET YANG DIGUNAKAN:
[Shoe vs Sandal vs Boot Image Dataset](https://www.kaggle.com/datasets/hasibalmuzdadid/shoe-vs-sandal-vs-boot-dataset-15k-images)

## INFO DATASET
Dataset yang kami gunakan merupakan kumpulan data yang berisikan total 15.000 gambar sepatu, sandal, dan sepatu boot, dengan masing - masing total 5000 gambar untuk setiap kategori yang ada. Gambar yang ditampilkan memiliki resolusi sebesar 136x102 pixel dan dalam model warna RGB. Untuk akses terhadap dataset yang digunakan, dapat dilihat di link yang telah di tautkan di judul dataset.

## PENJELASAN SINGKAT
Pada dataset yang kami gunakan, terdapat total 3 kelas yang ada yaitu **Boot**, **Shoe** dan juga **Sandal** yang mana untuk masing - masing kelas berisikan total 5000 gambar di dalamnya. Namun kami membagi lagi 15000 gambar tadi ke dalam beberapa bagian yaitu
#### 1.) Data Train sebanyak 10500 gambar
#### 2.) Data Test sebanyak 3000 gambar
#### 3.) Data Validation sebanyak 1500 gambar
Untuk gambar dataset yang telah dibagi menjadi **Train**, **Test** dan **Validation** dapat dilihat pada link Google Drive dibawah
#### [Ini Linknya Bang](https://drive.google.com/drive/folders/1QeUahIulSz5oIlD2r4wNXdj1y81uCQu0)

## TUJUAN
Selain untuk memenuhi Nilai dalam Projek Akhir mata kuliah Kecerdasan Buatan, kami juga ingin mengetahui apakah suatu model dapat dipelajari secara baik sehingga nantinya sistem dapat melakukan pengenalan terhadap tipe objek yang sama. Kami ingin melihat seberapa mirip tingkat prediksi yang dihasilkan dari proses pembelajaran model yang ada. Oleh karena itulah nantinya kami juga akan menggunakan data gambar asli untuk melakukan tes terhadap tingkat prediksi dalam mengidentifikasi objek yang ada.

## Anggota Kelompok dan Pembagian Tugasnya
[Muhammad Naufal Ihsan Maulidin // 2109106034 ](https://github.com/nafxyy)
- **Visualisasi Data**

[Ardi Setyiawan // 2109106035 ](https://github.com/ArdiSetiw) 
- **Preprocessing Data**

[Felix Christopher Afrian // 2109106049 ](https://github.com/KustyBoo)
- **Modelling Data**

## - TABLE OF CONTENT PROJECT -
#### 1. Import Library
Tahap pertama yang dilakukan tentu melakukan import library yang akan digunakan di dalam projek. Disini kami menggunakan beberapa library untuk menunjang Projek Akhir yang kami buat. Adapun beberapa library tersebut adalah **Matplotlib**, **Seaborn**, **Numpy** dan library lainnya yang tentu memiliki fungsi dan perannya masing - masing di dalam Projek Akhir kami ini.

#### 2. Load dan Preprocessing Data
Setelah melakukan Import terhadap beberapa library yang digunakan, tahapan selanjutnya adalah melakukan load terhadap data yang akan digunakan untuk selanjutnya dilakukan proes *Preprocessing* terhadap data tersebut. Preprocessing yang dilakukan disini mencakup **Augmentasi** dan juga **Standarisasi** terhadap data yang digunakan di dalam projek.

#### 3. Meta Data
Meta Data berisi tentang penjelasan yang di dapat dari dataset yang digunakan di dalam Projek. Pada Meta Data ini kami menampilkan beberapa informasi terkait dengan hasil yang kami dapat dari menggunakan dataset yang ada. Adapun beberapa informasi yang kami tampilkan antara lain **Nama Dataset**, **Ukuran Gambar**, **Banyak Kelas**, **Pembagian Data** dan yang lainnya.

#### 4. Visualisasi
Tahapan selanjutnya adalah melakukan **Visualisasi** terhadap hasil yang di dapat di dalam projek kami ini. Disini kami melakukan beberapa visualisasi terkait dengan beberapa data yang ada. Seperti contoh **Visualisasi Jumlah Kelas** dengan menggunakan Plot Bar, **Visualisasi Hasil Prediksi** dengan menggunakan Heatmap dan juga **Visualisasi Tingkat Akurasi dan Loss** dengan menggunakan Plot Line.

#### 5. Modelling
Setelah melewati tahap visualisasi, selanjutnya kita masuk ke tahap **Modelling** untuk melatih sistem agar mempelajari model yang telah dibuat. Disini kami menggunakan **Callback** untuk membatasi tingkat *'Accuracy'* agar tidak melebihi 0.97 dan tingkat *'Val_Accuracy'* agar tidak melebihi 0.95

#### 6. Evaluasi
Tahap terakhir yaitu melakukan proses **Evaluasi** dari beberapa tahap yang telah dilakukan sebelumnya. Kami melakukan Evaluasi tingkat Akurasi dan juga tingkat Loss pada model yang ada. Selain itu kami juga melakukan **Testing Validation**, **Testing Error** dan sebagainya guna melihat tingkat kemiripan dari model yang telah dipelajari.

#### TAHAP TAMBAHAN (Optional)
Kami juga mencoba melakukan percobaan dengan memakai data gambar asli untuk dilakukan testing terhadap model yang telah dipelajar. Hal ini ditujukan untuk melihat tingkat kemiripan dari prediksi yang dilakukan terhadap data gambar selain dataset yang digunakan. Hasilnya lebih dari 1/2 gambar yang diinputkan berhasil diidentifikasi (Hasil belum sempurna karena masih ada data gambar yang salah).

### TERIMA KASIH YANG UDAH BACA SAMPAI SINI :man_student: :handshake: :woman_student:
> Kami memohon maaf apabila masih banyak terdapat kekurangan di dalam projek kami. Karena tidak ada manusia yang sempurna :pray:
