# Kertas Gunting Batu Klasifikasi

Projek ini adalah tugas akhir dari materi Machine Learning Bagi Pemula yang diadakan oleh Dicoding Indonesia. 

Data yang digunakan adalah kumpulan foto tangan yang membentuk gunting, batu dan kertas. 

Data berjumlah kurang lebih 2188 yang selanjutnya dilakukan *splitting* sesuai kriteria tugas menjadi 874 data validasi dan 1314 data latih. 

Sebelum dilakukan permodelan dengan CNN dilakukan augmentasi.

Augmentasi gambar adalah tahap pemberian variasi pada foto-foto yang dipakai. Misalnya, foto diputar, geser, atau dibalik. Ini membuat mesin dapat belajar lebih baik. 

## Contoh Input

![enter image description here](https://i.ibb.co/PY6VV00/Halaman-Utama.png)

Ini merupakan contoh input yang saya masukkan berupa gambar tangan berbentuk gunting lalu mesin berhasil menebaknya ("*THIS IS SCISSOR*")

## Recommendation

 - Mesin masih jauh dari kata sempurna dikarenakan seringkali gagal menebak gambar apabila gambar pada input memiliki background bukan hijau
 - Masalah ini terjadi dikarenakan data yang digunakan untuk latih kebanyakan berlatar belakang warna hijau, sehingga mesin kesulitan dalam mendeteksi gambar yang lain
 - Perbanyak data gambar selain berlatarbelakang hijau
