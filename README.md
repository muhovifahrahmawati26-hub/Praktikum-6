# 📘 PRAKTIKUM 6   
### Bahasa Pemograman
---

</div>

## 📌 LATIHAN
### 🎯 Hasil Akhir
<img width="887" height="262" alt="output latihan" src="https://github.com/user-attachments/assets/5dac1c38-f1d4-4835-9509-5b6e081acd84" />


## 📘 TUGAS PRAKTIKUM 6
Program sederhana dengan mengaplikasikan penggunaan fungsi yang akan menampilkan daftar nilai mahasiswa.

---

## 🧩 Flowchart Program
<img width="792" height="952" alt="flowchart" src="https://github.com/user-attachments/assets/1d683f23-1441-4efa-9ea8-f54c625d1202" />

## Penjelasan Flowchart
- Alur Awal dan Loop: Program dimulai dan langsung masuk ke [Lingkaran] LOOP MENU UTAMA. Ini adalah perulangan tak terbatas (while True) yang memastikan program selalu siap menerima perintah.

- Keputusan Utama (Pilihan): Setelah menerima input Pilihan, alur program akan masuk ke serangkaian [Belah Ketupat] Keputusan. Ini adalah struktur percabangan (if-elif-else) yang menentukan aksi selanjutnya.

- Pemanggilan Fungsi: Ketika sebuah pilihan valid (1, 2, 3, atau 4) dipilih, alur program diarahkan ke [Persegi Panjang Bergaris], yang berarti terjadi pemanggilan fungsi (misalnya, tambah() atau ubah()). Fungsi ini kemudian menjalankan logikanya di cabang terpisah.

- Pengakhiran: Jika pengguna memilih Pilihan 5 (Keluar), alur program keluar dari loop dan berakhir di [Oval] SELESAI.

- Prinsip Modular: Struktur akar ini sangat efektif menunjukkan bahwa logika inti setiap operasi (seperti mencari dan menghapus data) diisolasi di Cabang Fungsi masing-masing, sementara Akar Utama hanya bertugas mengarahkan alur kendali.

## Penjelasan kode python 
1. Struktur Data (List of Dictionaries)
Program ini menggunakan sebuah List global bernama data_mahasiswa ([]). List ini bertindak sebagai database sementara yang menampung data. Setiap mahasiswa disimpan sebagai Dictionary di dalam List tersebut, yang memiliki pasangan key: value seperti 'nama' dan 'nilai'.

2. Fungsi Utama
Seluruh logika program dijalankan melalui lima bagian utama:

- main_menu(): Ini adalah fungsi pengendali utama yang menampilkan menu interaktif dan terus berulang (loop) sampai pengguna memilih keluar. Ia hanya bertugas menerima pilihan dan memanggil fungsi lain yang sesuai.

- tambah(): Fungsi ini menerima input nama dan nilai dari pengguna. Data tersebut kemudian dikemas dalam bentuk dictionary baru dan ditambahkan ke akhir data_mahasiswa menggunakan metode .append().

- tampilkan(): Fungsi ini memeriksa apakah data_mahasiswa kosong. Jika tidak, ia akan melakukan perulangan (loop) untuk menampilkan semua data nama dan nilai yang tersimpan secara terstruktur.

- hapus(nama): Fungsi ini menerima nama sebagai argumen. Ia kemudian menyaring (filter) atau mencari data di dalam data_mahasiswa yang namanya cocok dengan argumen yang diberikan, lalu menghapus data tersebut dari list.

- ubah(nama): Fungsi ini juga menerima nama sebagai argumen. Ia mencari data yang cocok. Jika ditemukan, ia meminta input nilai_baru dari pengguna, kemudian mengubah (update) nilai lama di dictionary tersebut dengan nilai yang baru.

- Intinya, pemrograman ini menekankan pada penggunaan fungsi untuk membuat kode yang rapi, mudah dikelola, dan setiap fungsi hanya melakukan satu tugas (misalnya, tambah() hanya menambah, tidak menampilkan).

### 🎯 Hasil Akhir
<img width="1053" height="972" alt="61" src="https://github.com/user-attachments/assets/4b06fb6d-2abe-423f-83d5-829b6a50b3fa" />
<img width="875" height="1020" alt="62" src="https://github.com/user-attachments/assets/fc9fae00-1833-4e98-a235-5df069503e65" />
