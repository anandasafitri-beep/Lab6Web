# Praktikum 6 - JavaScript DOM dan Event Handling

## 1. Deskripsi

Praktikum ini dilakukan untuk mempelajari cara menggunakan JavaScript dalam mengatur isi dan tampilan halaman web serta membuat halaman web yang dapat merespons tindakan pengguna.

Pada praktikum ini, saya mencoba beberapa latihan, mulai dari mengubah teks pada halaman, menggunakan tombol, mengubah tampilan teks, menghitung jumlah karakter, memvalidasi form, sampai membuat daftar tugas dan form pendaftaran workshop.

## 2. Tujuan Praktikum

- Memahami penggunaan DOM pada JavaScript.
- Mengubah teks dan tampilan elemen HTML menggunakan JavaScript.
- Menggunakan event seperti `click`, `input`, `submit`, `reset`, dan `change`.
- Membuat validasi form pendaftaran.
- Membuat To-do List dengan fitur menambah, menandai selesai, dan menghapus tugas.
- Membuat mini project pendaftaran workshop.

## 3. Struktur Folder

File yang digunakan dalam praktikum ini adalah:

```text
Lab6Web/
├── index.html
├── style.css
├── script.js
├── README.md
└── screenshots/
```

Keterangan:
- `index.html`: berisi struktur halaman web dan elemen yang digunakan dalam latihan.
- `style.css`: mengatur tampilan halaman web.
- `script.js`: berisi kode JavaScript untuk menjalankan fungsi dan event.
- `README.md`: berisi penjelasan mengenai praktikum.
- `screenshots/`: tempat menyimpan tangkapan layar hasil praktikum.

## 4. Latihan yang Dikerjakan

### Latihan 1: Manipulasi DOM

Mengubah judul dan isi teks pada halaman web menggunakan JavaScript melalui properti `textContent`.

### Latihan 2: Event Klik

Menggunakan `addEventListener()` untuk menjalankan fungsi ketika tombol diklik. Halaman akan menampilkan waktu saat tombol ditekan.

### Latihan 3: Mengubah Gaya Elemen

Menggunakan `classList.toggle()` untuk mengubah tampilan teks dengan menambahkan atau menghapus class CSS.

### Latihan 4: Penghitung Karakter

Membuat kolom input nama yang menghitung jumlah karakter secara langsung saat pengguna mengetik.

### Latihan 5: Form Pendaftaran

Membuat form yang berisi nama lengkap, email, dan usia. JavaScript digunakan untuk memeriksa kelengkapan nama, format email, serta usia antara 17 sampai 100 tahun. Pada eksperimen tambahan, validasi nama diubah menjadi minimal 3 karakter.

### Latihan 6: To-do List

Membuat daftar tugas yang dapat ditambahkan melalui tombol. Setiap tugas juga dapat ditandai selesai dan dihapus menggunakan tombol yang tersedia.

## 5. Mini Project: Pendaftaran Workshop

Pada mini project ini, saya membuat form pendaftaran workshop yang berisi nama lengkap, email, dan pilihan sesi workshop.

Fitur yang dibuat meliputi:
- Menghitung jumlah karakter nama secara langsung.
- Menampilkan sesi workshop yang dipilih.
- Memeriksa nama minimal 3 karakter.
- Memeriksa format email.
- Memastikan pengguna memilih sesi workshop.
- Menampilkan pesan jika pendaftaran berhasil atau jika terdapat kesalahan.
- Menyediakan tombol reset untuk mengosongkan form.

## 6. Eksperimen Tambahan

Beberapa eksperimen tambahan yang dikerjakan dalam praktikum ini meliputi:

1. Menambahkan tombol hapus pada setiap item To-do List.
2. Mengubah validasi nama agar minimal terdiri dari 3 karakter.
3. Menggunakan event `change` pada pilihan sesi workshop.
4. Membuat fitur untuk menyembunyikan dan menampilkan paragraf menggunakan class CSS.
5. Menguji penggunaan atribut `defer` pada pemanggilan file JavaScript.

## 7. Cara Menjalankan Program

1. Buka folder `Lab6Web` menggunakan Visual Studio Code.
2. Pastikan file `index.html`, `style.css`, dan `script.js` tersedia.
3. Pastikan file CSS dan JavaScript sudah dihubungkan pada file HTML.
4. Buka file `index.html` melalui browser.
5. Coba setiap tombol, kolom input, form pendaftaran, dan fitur daftar tugas untuk melihat hasilnya.

## 8. Dokumentasi Hasil Praktikum

Simpan tangkapan layar hasil praktikum pada folder `screenshots/`.

Dokumentasi yang dapat dimasukkan:
- Hasil manipulasi DOM dan event klik.
- Hasil perubahan gaya teks.
- Penghitung karakter.
- Form pendaftaran dengan data valid dan tidak valid.
- To-do List setelah menambah, menandai selesai, dan menghapus tugas.
- Mini project pendaftaran workshop.
- Hasil eksperimen menyembunyikan dan menampilkan paragraf.

## 9. Kesimpulan

Melalui praktikum ini, saya belajar menggunakan JavaScript untuk membuat halaman web yang lebih interaktif. Saya juga memahami cara menghubungkan HTML, CSS, dan JavaScript, menggunakan event pada elemen halaman, serta membuat validasi form dan fitur sederhana yang dapat digunakan langsung oleh pengguna.
