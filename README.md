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

## 10. Pertanyaan Evaluasi

1. Apa yang dimaksud dengan DOM dan apa manfaatnya?
Pengertian: DOM (Document Object Model) itu ibarat jembatan atau penerjemah yang bikin JavaScript bisa "ngobrol" sama dokumen HTML kita. Jadi, struktur HTML dibikin jadi pohon objek (tree structure) supaya setiap elemen (tag, atribut, teks) bisa diakses, diubah, atau dihapus lewat kodingan JS.

Manfaatnya:

Bisa nge-update tampilan web secara dinamis tanpa harus reload halaman (contohnya kayak tombol like atau keranjang belanjaan yang langsung nambah angkanya).

Bisa nambahin, ngapus, atau ngubah elemen HTML dan CSS secara real-time pas user lagi interaksi sama web kita.

2. Apa perbedaan getElementById(), querySelector(), dan querySelectorAll()?
Biar gampang, kita bedain dari cara pakai dan hasil keluarannya:

getElementById('id'): Cuma khusus buat nyari elemen berdasarkan ID doang. Hasilnya cuma satu elemen tunggal (karena ID kan harus unik). Performanya paling cepet.

querySelector('selector'): Lebih fleksibel karena bisa pakai selektor apa aja (ID pakai #, class pakai ., atau nama tag langsung). Tapi, dia cuma bakal ngebalikin elemen pertama yang dia ketemukan di halaman.

querySelectorAll('selector'): Mirip kayak querySelector, tapi bedanya dia bakal ngebalikin semua elemen yang cocok ke dalam bentuk NodeList (mirip array), jadi kita bisa looping datanya satu-satu.

3. Apa fungsi addEventListener() dan sebutkan tiga contoh event?
Fungsi: Buat "nangkep" atau nunggu aksi tertentu yang dilakuin user ke sebuah elemen, terus ngejalanin fungsi JavaScript tertentu pas aksi itu kejadian.

Tiga Contoh Event:

click: Kejadian pas user nge-klik suatu elemen (kayak tombol submit atau gambar).

submit: Kejadian pas form dikirim (biasanya dipakai buat ngecek validasi sebelum data dikirim ke server).

input atau change: Kejadian pas user ngetik atau ngubah isi di dalam form input (text box, dropdown, dll).

4. Mengapa event.preventDefault() digunakan pada event submit form?
Secara default, kalau form di-submit, browser bakal otomatis nge-reload halaman dan ngirim data. Nah, fungsi event.preventDefault() dipakai buat nge-block perilaku bawaan browser itu.

Kenapa diblock? Biar kita bisa handle datanya dulu pake JavaScript (misalnya divalidasi dulu atau dikirim pake fetch/AJAX) tanpa bikin halamannya kedap-kedip atau ke-refresh sendiri.

5. Apa perbedaan textContent dan innerHTML dari sisi penggunaan dan keamanan?
textContent:

Penggunaan: Cuma buat ngambil atau ngubah teks murni doang di dalam elemen, nggak peduli ada tag HTML di dalamnya atau nggak.

Keamanan: Aman dari celah XSS (Cross-Site Scripting) karena kalau ada inputan user yang bentuknya tag script (kayak <script>alert('hacked')</script>), bakal dianggap teks biasa, bukan dieksekusi sebagai kode berbahaya.

innerHTML:

Penggunaan: Dipakai kalau kita mau ngambil atau nyisipin teks sekaligus struktur tag HTML (misalnya mau nambahin <b> atau <div> baru lewat JS).

Keamanan: Rentan banget kalau dipakai buat nampilin inputan langsung dari user tanpa disaring dulu, karena bisa disusupi script jahat oleh hacker.

6. Bagaimana classList.toggle() membantu mengubah tampilan elemen?
classList.toggle() itu ibarat tombol saklar lampu (on/off).

Kalau elemennya belum punya kelas tertentu, dia bakal nambahin kelas itu.

Sebaliknya, kalau elemennya sudah punya kelas itu, dia bakal ngapus kelas tersebut.

Fitur ini ngebantu banget buat bikin fitur interaktif yang butuh state bolak-balik, contohnya bikin tombol dark mode (nyalain/matiin kelas dark), buka-tutup sidebar menu (hamburger menu), atau efek dropdown.

7. Sebutkan minimal tiga skenario pengujian validasi form.
Buat mastiin form kita aman dan ramah user, skenario pengujiannya minimal ada tiga ini:

Skenario Form Kosong (Required Field): User ngeklik tombol submit pas semua kolom inputan masih kosong, buat mastiin pesan error "Wajib diisi" muncul dan form gagal ke-submit.

Skenario Format Email Salah: User ngetik email ngawur (misal cuma ngetik namaku doang tanpa tanda @ atau domain), buat mastiin validasi regex/format email jalan dan nolak inputan tersebut.

Skenario Password Tidak Sesuai (Mismatch): User ngisi kolom Password dan Konfirmasi Password dengan nilai yang beda, buat mastiin sistem ngasih peringatan kalau password-nya belum klop sebelum dikirim.