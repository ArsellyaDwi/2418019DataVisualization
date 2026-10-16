# Data Visualization Hasil Praktikum Mahasiswa Teknik Informatika

## Deskripsi

Proyek ini merupakan tugas visualisasi data menggunakan Python untuk memahami informasi dari dataset hasil praktikum mahasiswa Teknik Informatika.

Visualisasi dibuat untuk melihat distribusi nilai, membandingkan kategori, serta mengamati pola dan hubungan antarvariabel dalam dataset agar lebih mudah dipahami.

## Tujuan

1. Menampilkan distribusi nilai praktikum mahasiswa.
2. Membandingkan rata rata nilai berdasarkan mata praktikum.
3. Mengetahui distribusi status kelulusan dan kehadiran.
4. Mengamati jumlah praktikum berdasarkan waktu.
5. Melihat hubungan antara durasi praktikum, jumlah percobaan, dan nilai.
6. Mempelajari penggunaan Python untuk visualisasi data.

## Dataset

Dataset yang digunakan merupakan data hasil praktikum mahasiswa Teknik Informatika dengan 2.996 baris dan 12 kolom.

Informasi dalam dataset meliputi nilai praktikum, mata praktikum, modul, tanggal praktikum, kehadiran, durasi praktikum, jumlah percobaan, status praktikum, dan status kelulusan.

## Tools yang Digunakan

Python: bahasa pemrograman untuk mengolah dan menganalisis data.

Google Colab: lingkungan untuk menjalankan notebook Python.

Pandas: membaca, mengelola, dan merangkum data.

Matplotlib: membuat grafik visualisasi.

NumPy: membantu pengolahan data numerik.

## Jenis Visualisasi

1. Histogram distribusi nilai: melihat persebaran nilai praktikum mahasiswa.
2. Rata rata nilai per mata praktikum: membandingkan nilai rata rata setiap mata praktikum.
3. Status kelulusan: melihat jumlah data pada setiap kategori kelulusan.
4. Kehadiran: membandingkan kategori kehadiran mahasiswa.
5. Nilai berdasarkan jumlah percobaan: melihat persebaran nilai berdasarkan jumlah percobaan.
6. Durasi praktikum dan nilai: mengamati pola hubungan antara durasi praktikum dan nilai.
7. Jumlah praktikum per bulan: melihat jumlah catatan praktikum berdasarkan bulan yang tersedia.
8. Visualisasi tambahan: membandingkan informasi lain berdasarkan kategori pada dataset.

## Catatan Data Tanggal

Terdapat 65 tanggal praktikum yang tidak tersedia pada dataset. Tanggal tersebut tetap dibiarkan kosong karena tanggal sebenarnya tidak diketahui dan tidak ingin diganti dengan tanggal perkiraan.

Oleh karena itu, grafik yang menggunakan tanggal hanya memanfaatkan data dengan tanggal valid. Jumlah data pada grafik bulanan dapat lebih sedikit daripada jumlah keseluruhan baris dataset.

## Cara Menjalankan

1. Download atau clone repository ini.
2. Buka notebook `.ipynb` menggunakan Google Colab.
3. Siapkan file `dataset_bersih.csv` sesuai lokasi yang digunakan pada kode.
4. Sesuaikan lokasi file apabila diperlukan.
5. Jalankan seluruh sel notebook dari awal sampai akhir.
6. Amati grafik dan hasil ringkasan yang ditampilkan.

## Kesimpulan

Visualisasi data membantu memahami karakteristik hasil praktikum mahasiswa melalui distribusi nilai, perbandingan kategori, dan hubungan antarvariabel.

Interpretasi grafik tetap perlu mempertimbangkan isi dataset dan keterbatasan informasi yang tersedia, termasuk 65 tanggal praktikum yang tidak diketahui.

Proyek ini dibuat sebagai bagian dari pembelajaran visualisasi data menggunakan Python.