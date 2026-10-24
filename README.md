# Praktikum Web - JavaScript Dasar

## Tujuan
- Memahami dasar-dasar sintaks JavaScript dan cara menghubungkannya dengan file HTML.
- Menguasai penggunaan *pop-up dialog* bawaan browser seperti `alert()` dan `prompt()`.
- Memahami struktur logika percabangan (`if-else`, `switch-case`).
- Mampu melakukan manipulasi DOM (*Document Object Model*) secara dinamis menggunakan JavaScript.
- Mampu mengambil data dari *form* input HTML, memproses logika matematikanya, dan menampilkannya kembali ke halaman web.

## Langkah Kerja
1. Membuat kerangka halaman web menggunakan HTML (`index.html`).
2. Menghubungkan file HTML dengan file JavaScript eksternal (`script.js`).
3. Menulis logika pemrograman di dalam file `script.js` sesuai dengan instruksi tiap latihan (seperti mengubah konten teks, memanipulasi warna latar, dan mengkalkulasi nilai).
4. Menggunakan *DOM manipulation* (`document.getElementById`) untuk membaca nilai dari input pengguna dan memodifikasi elemen HTML.
5. Menguji setiap fungsi dengan memasukkan berbagai variasi input (angka valid, nilai batas, dsb) untuk memastikan logika berjalan dengan baik.

## Cara Menjalankan
1. Pastikan Anda memiliki *browser* modern (Chrome, Firefox, Edge) dan *Code Editor* (seperti VS Code).
2. Buka folder proyek ini di dalam *Code Editor* Anda.
3. Jalankan file `index.html` menggunakan ekstensi **Live Server** (klik "Go Live" di VS Code) atau cukup buka file `index.html` langsung melalui *File Explorer* ke *browser*.
4. Ikuti instruksi interaktif yang muncul di layar (prompt/alert) dan coba fungsionalitas setiap tombol serta form di halaman web.

---

## Hasil Latihan

### 1. Pengenalan JavaScript (Menampilkan Teks)
Latihan pertama adalah menghubungkan file JS dan menampilkan teks "Hello World" ke dalam elemen HTML menggunakan `textContent`.
![Hasil Latihan 1](Screenshot%20(68).png)

### 2. Interaksi Pengguna dengan Prompt dan Alert
Meminta input dari pengguna berupa Nama, Nilai, dan Angka melalui pop-up `prompt()`, kemudian memproses logika kelulusan dan menampilkannya menggunakan `alert()`.
- **Meminta Input Nama dan Menampilkan Sambutan:**
  <br>
  ![Prompt Nama](Screenshot%20(69).jpg)
  <br>
  ![Alert Nama](Screenshot%20(70).jpg)

- **Meminta Input Nilai (0-100) dan Validasi Kelulusan:**
  <br>
  ![Prompt Nilai Kosong](Screenshot%20(71).jpg)
  <br>
  ![Prompt Nilai 17](Screenshot%20(72).jpg)
  <br>
  ![Prompt Nilai 100](Screenshot%20(73).jpg)
  <br>
  ![Alert Lulus](Screenshot%20(74).jpg)

- **Penggunaan Switch Case (Input angka 1-5):**
  <br>
  ![Switch Case](Screenshot%20(75).jpg)

### 3. Manipulasi DOM (Interaksi Tombol dan Pengecekan Bilangan)
Latihan memanipulasi elemen HTML. Pengguna dapat mengecek apakah bilangan yang dimasukkan bernilai ganjil/genap dan mengubah warna latar belakang secara interaktif.
- **Tampilan Awal & Pengecekan Bilangan Ganjil/Genap:**
  <br>
  ![Cek Bilangan Awal](Screenshot%20(76).jpg)
  <br>
  ![Input Bilangan](Screenshot%20(78).jpg)
  <br>
  ![Hasil Bilangan Ganjil](Screenshot%20(79).jpg)
  <br>
  ![Hasil Bilangan Genap](Screenshot%20(80).jpg)

- **Mengubah Warna Latar (Contoh: Menjadi Hijau):**
  <br>
  ![Latar Hijau](Screenshot%20(77).jpg)

### 4. Daftar Menu Makanan (Checkboxes)
Menambahkan elemen form berupa *checkbox* untuk daftar menu makanan beserta harganya yang nantinya dapat digunakan untuk kalkulasi total pembayaran.
![Daftar Menu Makanan](Screenshot%20(81).jpg)

### 5. Form Penilaian Mahasiswa (Kalkulator Nilai)
Implementasi form interaktif lengkap untuk menghitung Nilai Akhir mahasiswa dari komponen Tugas, UTS, dan UAS. Logika JavaScript akan mengambil *value* input, menghitung bobotnya, menentukan predikat (A, B, dsb), dan menampilkan status kelulusan dengan penyesuaian warna (hijau untuk "Lulus", merah untuk "Belum lulus").
- **Tampilan Form Kalkulator Nilai:**
  <br>
  ![Form Kosong](Screenshot%20(83).jpg)
- **Hasil Kalkulasi Setelah Form Diisi:**
  <br>
  ![Form Terisi dan Dihitung](Screenshot%20(84).jpg)

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
