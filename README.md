**PRAKTIKUM 1**

1. Menjalankan Apache dan MySQL
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/5tRTW02.png">
</p>


2. Menjalankan http://localhost/phpmyadmin pada web browser

3. Lalu Create database dengan nama : penjualan_produk
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/Ma6cDuT.png">
</p>

4. Lalu import file penjualan_produk.sql
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/nVQ4QRG.png">
</p>
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/7IkVPX4.png">
</p>

**PRAKTIKUM 2**

1. Pilih tab More, Pilih menu Designer 
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/vqqQuyx.png">
</p>

2. Diagram Database
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/KwO17Ee.png">
</p>

3. Data Barang
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/7j5J7fM.png">
</p>

**PRAKTIKUM 3**

1. SOAL 1
- kode_penjualan = 3
- tgl = 8 Februari 2021
- kasir = Dini
- total_penjualan = 10.000
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/o2UV1u0.png">
</p>
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/xNv5dA1.png">
</p>

2. SOAL 2
- kode_penjualan = 2
- tgl = 10 Februari 2021
- kasir = Dini
- total_penjualan = 20.000
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/6bTK57u.png">
</p>
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/hnLqcQr.png">
</p>

3. SOAL 3
- Jelaskan bagaimana solusi agar data pada soal 2 dapat ditambahkan <SOAL 3>
> Jawab: Pada kolom Value diganti nomer 4. Karena kode_penjualan (2) Basis Datanya sudah ada sebelumnya. Jika Value kode_penjualannya sama maka akan terjadi eror.
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/KWfF9no.png">
</p>
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/dnbq2k7.png">
</p>

4. SOAL 4
- kode_penjualan = 2
- kode_barang = 3
- harga = 5.000
- jumlah = 5
- Apakah data dapat ditambahkan? Jelaskan alasannya !
> Jawab: Bisa Ditambahkan. Karena semua kolomnya valid dan memiliki tipe data yang sesuai (kode_penjualan dan kode_barang). Kode penjualan 2 sudah ada di tabel penjualan, sehingga data detail_penjualan dengan kode_penjualan 2 dapat ditambahkan.
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/Hiv1SLK.png">
</p>
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/yCuvAHw.png">
</p>

5. SOAL 5
- Jelaskan bagaimana solusi agar data pada soal 4 dapat ditambahkan
> Jawab: Tidak ada. Karena data dari kode_penjualan 2 dan kode_barang 3 sudah ada ditabel, jadi data bisa langsung ditambahkan.

6. SOAL 6
-Terangkan apa yang bisa anda pahami dari soal 1-5 terkait dengan duplikasi dan inkonsisten data 
> Jawab: Adanya data yang sama (Duplikasi) disimpan di kode_penjualan yang menyebabkan data tidak dapat ditambahkan.Dan munculnya data yang tidak konsisten pada medan/kolom yang sama (Inkonsisten data) dalam satu atau beberapa file data yang dihubungkan/direlasikan.


**PRAKTIKUM 4**

1. SOAL 7
- Tambahkan data detail_penjualan sebagaimana berikut 
- kode_penjualan = 2
- kode_barang = 3
- harga = 5.000
- jumlah = 5
- Apakah data dapat ditambahkan? Jelaskan alasannya !
 > Jawab : Tidak dapat ditambahkan. Karena Data sudah ada/adanya Duplikasi.
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/AO9OfZn.png">
</p>

- Tampilkan struktur dari basis data dan hapus garis hubung antara tabel penjualan dan
detail_penjualan
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/sjBiOTV.png">
</p>

- Ulangi kembali langkah ke-1 pada praktikum 4. Apakah data dapat ditambahkan? jelaskan
alasannya!
 > Jawab: Data tidak dapat ditambahakan. Karena Datanya sudah ada.
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/mT0DvR4.png">
</p>
