---
layout: post
title: "Form di HTML"
---

Penjelasan tentang cara membuat form di HTML.

✅ Pengertian Form HTML
Form (formulir) dalam HTML adalah elemen yang digunakan untuk mengumpulkan data dari pengguna. Data ini bisa dikirim ke server untuk diproses, misalnya untuk pendaftaran, login, pencarian, atau pengisian data lainnya.

✅ Atribut Penting dalam Formulir
name: Nama yang digunakan untuk mengidentifikasi data saat dikirim ke server.

id: Identitas unik untuk menghubungkan elemen form dengan label atau styling.

value: Menentukan nilai default pada input.

required: Menjadikan suatu input wajib diisi.

readonly: Membuat input hanya bisa dibaca tanpa bisa diubah.

disabled: Menonaktifkan input agar tidak bisa digunakan.

placeholder: Menampilkan teks petunjuk di dalam kolom input.

maxlength dan minlength: Membatasi jumlah karakter.

pattern: Menentukan pola (format) input menggunakan ekspresi reguler.

✅ Metode Pengiriman Data
GET

Data dikirim melalui URL (terlihat).

Cocok untuk pencarian atau data tidak rahasia.

Terbatas jumlah karakter.

POST

Data dikirim secara tersembunyi.

Cocok untuk data pribadi atau sensitif.

Tidak terbatas karakter.

✅ Validasi Formulir (HTML5)
Form HTML dapat divalidasi secara otomatis oleh browser dengan atribut seperti:

required: wajib diisi

type="email" atau type="number": memeriksa format input

pattern: memeriksa input berdasarkan pola tertentu

min, max: untuk nilai angka atau tanggal

![Form di HTML](/assets/image/gambar4.jpg)
