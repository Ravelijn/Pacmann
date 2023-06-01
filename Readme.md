**Background**

Project ini adalah Tugas dari Pacmann Data Science. Project ini dibuat untuk membantu Andi, seorang pemilik supermarket besar di salah satu kota di Indonesia. Andi memiliki rencana untuk melakukan perbaikan proses bisnis, yaitu Andi akan membuat sistem kasir yang self-service di supermarket miliknya. Sehingga customer bisa langsung memasukkan item yang dibeli, jumlah item yang dibeli, dan harga item yang dibeli dari fitur yang lain
Sehingga customer yang tidak berada di kota tersebut bisa membeli barang dari supermarket tersebut. Setelah Andi melakukan riset, ternyata Andi memiliki masalah, yaitu Andi membutuhkan programmer untuk membuat fitur-fitur sistem kasir self-service dis supermarket itu bisa berjalan dengan lancar.

**Requirement**

Program kasir mandiri ini berbentuk modular code, yaitu terdapat file yang menyimpan code (modul_py) kemudian satu file main.py untuk mengeksekusi code. Untuk membantu visualisasi tabel dibutuhkan modul pandas. Data akan disimpan dalam bentuk dictionary, program ini akan menggunakan 9 method.


![image](https://github.com/Ravelijn/Pacmann/assets/135209359/a07bd6d9-11a6-46d9-a42f-4d07c3b91bcf)

Fungsi

1. Clash : Membuat suatu class yang diberi nama Transaction yang digunakan untuk menghimpun data dan fungsi
2. Method : init untuk menyimpan data item belanjaan dalam bentuk dictionary
3. Method : add_item untuk menambahkan data belanjaan berdasarkan tiga parameter, yaitu nama, jumlah dan harga
4. Method : update_item untuk mengganti nama item belanja jika terdapat kesalahan penginputan nama item
5. Method : update_item_qty untuk mengubah jumlah dari suatu item belanjaan
6. Method : update_item_price untuk mengubah harga dari suau item belanjaan
7. Method : delete_item untuk menghapus salah satu item
8. Method : reset_transaction untuk menghapus seluruh item data belanja
9. Method : check_order untuk mengecek daftar belanjaan yang sudah diinput
10.Method : total_price untuk menghitung harga total dari semua item
