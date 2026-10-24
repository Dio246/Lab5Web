Praktikum Pengenalan JavaScript (Lab 5)

Repositori ini berisi kumpulan latihan praktikum dasar JavaScript. Latihan-latihan ini mencakup manipulasi DOM dasar, pengambilan input dari pengguna, penggunaan struktur kontrol (percabangan), penanganan event pada elemen HTML, hingga pembuatan kalkulator sederhana.

🎯 Tujuan Pembelajaran

Memahami cara menautkan file JavaScript ke dalam dokumen HTML.

Mampu melakukan manipulasi DOM sederhana (mengubah teks dan gaya/warna tampilan).

Memahami penggunaan fungsi bawaan browser untuk interaksi pengguna (prompt, alert, console.log).

Mengimplementasikan logika percabangan menggunakan if-else dan switch-case.

Menerapkan Event Handling dasar (seperti onclick, onchange) pada elemen interaktif seperti tombol dan checkbox.

Membangun form kalkulasi dinamis untuk menghitung total nilai dan menampilkan status berdasarkan kondisi tertentu.

🚀 Cara Menjalankan

Pastikan Anda memiliki text editor (misalnya Visual Studio Code) dan web browser (Chrome, Edge, Firefox, dll).

Unduh atau clone seluruh file proyek (index.html dan script.js) ke dalam satu folder di komputer Anda.

Buka file index.html langsung di browser dengan cara klik ganda (double-click) pada file tersebut.

Opsional tapi Disarankan: Gunakan ekstensi Live Server di VS Code untuk menjalankan file secara langsung dan melihat perubahannya secara real-time saat kode disimpan.

📝 Daftar Latihan dan Hasil

1. Output Dasar dan Manipulasi DOM (Hello World)

Tujuan: Memahami cara kerja eksekusi script dasar dan memanipulasi konten teks pada HTML menggunakan JavaScript.
Langkah Kerja:

Membuat file script.js dan menghubungkannya dengan index.html.

Menggunakan document.getElementById("pesan").textContent untuk mengubah teks pada elemen paragraf HTML menjadi "Hello World".

Menampilkan pesan di console browser menggunakan console.log().

Hasil:
![Output Dasar Hello World](Screenshot\ (68).png)

2. Input Pengguna (Prompt)

Tujuan: Menggunakan kotak dialog prompt() untuk meminta input teks dari pengguna dan menampilkannya kembali ke layar.
Langkah Kerja:

Menambahkan pemanggilan fungsi prompt("Masukkan nama Anda:") saat halaman dimuat.

Menyimpan hasil inputan pengguna ke dalam variabel, lalu menggabungkannya dengan teks sapaan.

Menampilkan hasilnya ("Selamat datang, [nama_pengguna].") ke dalam halaman web.

Hasil:
Tampilan saat meminta input:
![Prompt Nama](Screenshot\ (69).jpg)
Tampilan halaman setelah nama dimasukkan:
![Hasil Sapaan](Screenshot\ (70).jpg)

3. Logika Percabangan (If-Else & Switch)

Tujuan: Mengimplementasikan kondisi untuk memeriksa nilai ujian dan menjalankan operasi matematika dasar.
Langkah Kerja:

Meminta input nilai rentang (0-100) dari pengguna menggunakan prompt().

Menggunakan struktur if-else untuk mengecek apakah input valid, apakah nilai memenuhi KKM (>= 60) agar "Lulus", atau "Belum lulus". Hasil ditampilkan dengan alert().

Menyertakan program switch-case untuk membaca angka 1 hingga 5 dan menampilkannya dalam bentuk teks.

Hasil:
Prompt input nilai:
![Input Nilai 1](Screenshot\ (71).jpg)
![Input Nilai 2](Screenshot\ (72).jpg)
![Input Nilai 3](Screenshot\ (73).jpg)

Alert hasil kelulusan:
![Alert Lulus](Screenshot\ (74).jpg)

Prompt input untuk switch-case 1-5:
![Switch Case Prompt](Screenshot\ (75).jpg)

4. Event Handling Lanjutan: Perubahan Latar Belakang & Cek Bilangan

Tujuan: Menerapkan fungsi JavaScript pada tombol HTML (button) melalui atribut onclick untuk mengubah gaya halaman dan memproses input matematika.
Langkah Kerja:

Ubah Latar: Membuat fungsi ubahWarnaLatar(color) yang akan merubah document.body.style.backgroundColor sesuai dengan warna tombol yang diklik ("Latar Hijau", "Latar Putih", "Latar Kuning").

Cek Bilangan: Membuat fungsi cekBilangan() untuk mengambil value dari input teks, memproses apakah bilangan tersebut genap atau ganjil menggunakan operator modulus (%), dan menampilkannya ke layar.

Hasil:
Ubah Latar Belakang (Hijau & Kuning):
![Latar Hijau](Screenshot\ (77).jpg)
![Latar Kuning](Screenshot\ (78).jpg)

Cek Bilangan Ganjil/Genap:
![Bilangan Ganjil](Screenshot\ (79).jpg)
![Bilangan Genap](Screenshot\ (80).jpg)

5. Daftar Menu Makanan (Kalkulasi Checkbox)

Tujuan: Menggunakan input tipe checkbox untuk menghitung total nilai secara dinamis setiap kali pengguna memilih item.
Langkah Kerja:

Membuat form dengan opsi checkbox untuk menu makanan (Ayam Goreng - Rp5.000, Tempe - Rp500, Telur Dadar - Rp2.500).

Memberikan nilai (value) pada masing-masing checkbox yang merepresentasikan harga.

Membuat fungsi JavaScript yang akan dipanggil ketika checkbox diklik, menjumlahkan semua value dari checkbox yang berstatus tercentang (checked), dan menampilkan total harganya.

Hasil:
![Daftar Menu Makanan](Screenshot\ (81).jpg)

6. Kalkulator Penilaian Mahasiswa

Tujuan: Mengambil beberapa input numerik sekaligus, memproses perhitungannya menjadi nilai akhir, serta menampilkan konversi predikat dan status kelulusan dengan manipulasi gaya teks (warna).
Langkah Kerja:

Membuat form input untuk "Nilai Tugas", "Nilai UTS", dan "Nilai UAS" (rentang 0-100).

Membuat fungsi yang dipanggil saat tombol "Hitung Nilai" ditekan untuk menghitung rata-rata atau bobot akhir dari ketiga nilai tersebut.

Menggunakan struktur if-else if untuk menentukan Predikat (misal: A, B, C, dst) berdasarkan rentang nilai akhir.

Menentukan status "Lulus" atau "Belum lulus" dan merubah warna teks status tersebut (misalnya, teks hijau jika lulus) menggunakan manipulasi DOM style.color.

Hasil:
Tampilan Form Penilaian Kosong:
![Form Penilaian Kosong](Screenshot\ (83).jpg)

Tampilan Hasil Kalkulasi Nilai:
![Hasil Penilaian Mahasiswa](Screenshot\ (84).jpg)


<img width="1366" height="768" alt="Screenshot (83)" src="https://github.com/user-attachments/assets/8d0d4e73-12fd-49d5-84a9-4ef0cbd0c543" />
<img width="1366" height="768" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/66249376-d166-42eb-b4ad-b199e3aa8dfc" />
<img width="1366" height="768" alt="Screenshot (80)" src="https://github.com/user-attachments/assets/b3ef3379-37c9-4799-84f8-54dfc72b23cb" />
<img width="1366" height="768" alt="Screenshot (79)" src="https://github.com/user-attachments/assets/1d0952a3-4fee-45c5-9bb7-060917bcea2b" />
<img width="1366" height="768" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/c0315fdb-5779-4ac6-bd59-6de508ddded6" />
<img width="1366" height="768" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/2bb9e5aa-f2f2-4cb0-8e3f-47bcf746bca7" />
<img width="1366" height="768" alt="Screenshot (76)" src="https://github.com/user-attachments/assets/dc7daa9a-c5a5-4bd4-958d-3b5e67ec758b" />
<img width="1366" height="768" alt="Screenshot (75)" src="https://github.com/user-attachments/assets/60328af7-864a-44c3-bb63-6907ebcf67cc" />
<img width="1366" height="768" alt="Screenshot (74)" src="https://github.com/user-attachments/assets/048c2494-975b-414a-8a17-de78bee45cc3" />
<img width="1366" height="768" alt="Screenshot (73)" src="https://github.com/user-attachments/assets/8183f632-e96a-49e0-85bb-8f58a89b2906" />
<img width="1366" height="768" alt="Screenshot (72)" src="https://github.com/user-attachments/assets/827edb36-bfe0-4a8a-864f-e0c286a30350" />
<img width="1366" height="768" alt="Screenshot (71)" src="https://github.com/user-attachments/assets/7dec552a-b506-475b-a822-43495b3d3348" />
<img width="1366" height="768" alt="Screenshot (70)" src="https://github.com/user-attachments/assets/643e23be-a2d6-4181-9f8a-7d308fef1d58" />
<img width="1366" height="768" alt="Screenshot (69)" src="https://github.com/user-attachments/assets/5d64d6c1-ecfb-4aaa-a1fb-5e3709d08d19" />
<img width="1366" height="768" alt="Screenshot (68)" src="https://github.com/user-attachments/assets/ffd7d347-1b71-4515-9f81-2daedabb8315" />
<img width="1366" height="768" alt="Screenshot (68) - Copy" src="https://github.com/user-attachments/assets/5a035a61-51a8-4ef9-ade6-bf1f2b019feb" />
<img width="1366" height="768" alt="Screenshot (84)" src="https://github.com/user-attachments/assets/9408cbab-99d0-47c7-993f-82d72b3ba47a" />
