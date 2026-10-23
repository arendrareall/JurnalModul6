# Tugas Pendahuluan Modul 6 - JavaScript dan jQuery
# NAMA: ARIEL ARENDRA
# NIM: 103092400046
# Kelas: IT-07-01

## 1. Apa itu JavaScript dan kegunaannya

JavaScript adalah bahasa pemrograman yang berjalan di browser untuk membuat halaman web menjadi dinamis dan interaktif. Kegunaannya antara lain mengubah isi dan tampilan elemen HTML, merespons aksi pengguna seperti klik dan input, serta memvalidasi data pada form.

## 2. Apa itu jQuery dan kegunaannya

jQuery adalah library JavaScript yang dibuat untuk menyederhanakan penulisan kode JavaScript. Kegunaannya antara lain memilih dan memanipulasi elemen HTML, menangani event seperti klik, membuat efek seperti hide/show dan animasi, serta mempermudah penggunaan Ajax, semuanya dengan kode yang lebih singkat.

## 3. Perbedaan JavaScript dan jQuery

JavaScript adalah bahasa pemrograman yang bisa langsung dijalankan di browser, sedangkan jQuery adalah library yang ditulis menggunakan JavaScript sehingga tidak bisa berjalan tanpa JavaScript. Untuk memakai jQuery, kita harus memasangnya terlebih dahulu, baik dengan mengunduh file-nya maupun lewat CDN, sementara JavaScript tidak memerlukan pemasangan apa pun.

Dari sisi penulisan kode, JavaScript biasanya lebih panjang, sedangkan jQuery lebih ringkas untuk tugas yang sama. Sebagai contoh, untuk menyembunyikan elemen dengan JavaScript kita menulis `document.getElementById("kotak").style.display = "none";`, sedangkan dengan jQuery cukup `$("#kotak").hide();`.