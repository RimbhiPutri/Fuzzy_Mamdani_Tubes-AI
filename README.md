# Fuzzy_Mamdani_Tubes-AI
Program ini digunakan untuk menyeleksi 5 bengkel terbaik berdasarkan mutu layanan dan tingkat harga dengan menggunakan metode Fuzzy Mamdani. Tahapan yang dilakukan mencakup proses pembacaan data, fuzzifikasi, inferensi, serta defuzzifikasi.

# DataSet
Dataset yang digunakan berupa data bengkel dengan atribut: 
- ID Bengkel: ID atau kode bengkel
- Nilai Servis: Nilai kualitas servis (0-100)
- Harga Servis: Harga servis (dalam satuan rupiah)
Dataset tersiri dari 20 data bengkel dan di susun secara manual menggunakan format CSV berbasis teks.
Nama file dataset:
- data_bengkel.csv

# Metode yang digunakan:
Metode yang digunakan adalah fuzzy mamdani dengan tahapan:
1. Penentuan fungsi keanggotaam input (segitiga dan trapesium)
2. Proses fuzzification
3. Penerapan aturan inerensi fuzzy (IF-THEN)
4. Inferensi Mamdani menggunakan operator MIN dan MAX
5. Defuzzification menggunakan metode rata-rata berbobot
6. Perangkingan untuk memperoleh 5 bengkel terbaik

# Struktur File
- fuzzy_bengkel.ipynb : Program utama sistem fuzzy
- data_bengkel.csv   : Dataset bengkel
- top_5_bengkel.txt  : Output hasil 5 bengkel terbaik
- poster.pdf         : Poster tugas besar
- README.txt         : Penjelasan program

# Cara Menjalankan Program
Cara menjalankan program menggunakan Google Colab:
1. Buka file "fuzzy_bengkel.ipynb" menggunakan Google Colab
2. Upload file "data_bengkel.csv" ke environment Colab
3. Jalankan seluruh cell secara berurutan dari atas ke bawah
4. Program akan menampilkan hasil perangkingan bengkel
5. File output "top_5_bengkel.txt" akan otomatis dibuat

Cara menjalankan program secara lokal:
1. Pastikan Python telah terinstal pada komputer
2. Konversi notebook ke file Python (.py) atau gunakan versi .py
3. Letakkan file program dan "data_bengkel.csv" dalam satu folder
4. Jalankan program melalui terminal dengan perintah:
   python fuzzy_bengkel.py
5. Output hasil akan ditampilkan dan disimpan ke file teks

# Peran anggota kelompok:
1. Rebeca Grace Catlia Wahyudi (103132400015) : Bertanggung jawab dalam perancangan konsep sistem fuzzt, penyusunan rule base, serta pembuatan poster dan laporan.
2. Rimbhi Putri Aulia Azzahra (103132400018): Bertanggung jawab dalam implementasi program python, proses fuzzification, inferensi, defuzzification, pengujian program, serta penyusunan laporan.

