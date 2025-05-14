# Proyek Kalkulator Sederhana

Ini adalah proyek kalkulator sederhana yang dibuat menggunakan HTML, CSS, dan JavaScript.

## Deskripsi

Kalkulator ini memungkinkan pengguna untuk melakukan operasi aritmatika dasar seperti penjumlahan, pengurangan, perkalian, dan pembagian. Antarmukanya bersih dan mudah digunakan.

## Struktur Berkas

* `index.html`: Berkas utama HTML yang menyusun struktur kalkulator.
* `style.css`: Berkas CSS yang mengatur tampilan dan gaya kalkulator.
* `index.js`: Berkas JavaScript yang berisi logika untuk fungsionalitas kalkulator.

## Cara Menggunakan

1.  *Clone* repositori ini atau unduh berkas-berkasnya.
2.  Buka berkas `index.html` di peramban web Anda.
3.  Anda akan melihat antarmuka kalkulator dan dapat mulai menggunakannya.

## Teknologi yang Digunakan

* HTML
* CSS
* JavaScript

## Tampilan

Antarmuka kalkulator terdiri dari:
* Sebuah layar (display) untuk menampilkan input dan hasil perhitungan.
* Tombol-tombol angka (0-9).
* Tombol-tombol operator (+, -, \*, /).
* Tombol titik (.) untuk angka desimal.
* Tombol sama dengan (=) untuk menghitung hasil.
* Tombol C (Clear) untuk menghapus tampilan.

## Fungsionalitas (JavaScript - `index.js`)

* `appendtodisplay(input)`: Fungsi ini menambahkan input (angka atau operator) ke layar.
* `cleardisplay()`: Fungsi ini membersihkan layar (mengatur ulang nilai menjadi string kosong).
* `calculate()`: Fungsi ini menghitung ekspresi yang ada di layar menggunakan `eval()`. Jika terjadi kesalahan dalam perhitungan (misalnya, pembagian dengan nol atau sintaks yang salah), layar akan menampilkan "Eror".
