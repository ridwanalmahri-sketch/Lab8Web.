# Praktikum 8 – PHP dan Database MySQL

` Langkah paling awal menyalakan xamppp Control Panel `

<img width="1919" height="1035" alt="Screenshot 2026-11-16 193541" src="https://github.com/user-attachments/assets/e0f6b1b5-af6f-4da2-b569-7d05d34a4601" />

## Identitas Praktikan
```
- Nama: M.Ridwan Al Mahri
- NIM: 312510157
- Program Studi: Teknik Informatika
- Mata Kuliah: Pemrograman Web
```
## Deskripsi
Project ini merupakan hasil Praktikum 8 Pemrograman Web mengenai integrasi PHP dengan database MySQL. Project menggunakan database `latihan1` dan tabel `data_barang` untuk mengelola data barang melalui operasi CRUD (Create, Read, Update, Delete).

## Teknologi yang Digunakan
```
- PHP
- MySQL
- XAMPP
- phpMyAdmin
- HTML
- CSS
- Visual Studio Code
```
## Langkah Pengerjaan

### 1. Membuat Database
Membuat database `latihan1` menggunakan phpMyAdmin.

<img width="1915" height="595" alt="Screenshot 2026-11-16 184833" src="https://github.com/user-attachments/assets/917dbe15-3119-43ed-b786-abf39d75a888" />


### 2. Membuat Tabel dan Data Barang
Membuat tabel `data_barang` dengan kolom id_barang, kategori, nama, gambar, harga_beli, harga_jual, dan stok. Kemudian memasukkan data barang awal.

<img width="1916" height="707" alt="Screenshot 2026-11-16 184851" src="https://github.com/user-attachments/assets/aa8afd08-9b76-4b3f-8007-79609ec6563e" />


### 3. Membuat Folder Project
Membuat folder project `lab8_php_database` di dalam direktori htdocs dan membukanya menggunakan Visual Studio Code.

<img width="1919" height="382" alt="Screenshot 2026-11-16 185114" src="https://github.com/user-attachments/assets/1c4fd614-2db2-43d6-8404-f02624fbe77f" />


### 4. Membuat Koneksi Database
Membuat file `koneksi.php` untuk menghubungkan aplikasi PHP dengan database MySQL.

<img width="1619" height="345" alt="Screenshot 2026-11-16 185445" src="https://github.com/user-attachments/assets/7ad9f735-7e41-4e45-9d6b-49de3ff2dc48" />

### 5. Menampilkan Data (Read)
Membuat halaman `index.php` untuk menampilkan seluruh data barang dari tabel `data_barang`.

<img width="1674" height="825" alt="Screenshot 2026-11-16 185907" src="https://github.com/user-attachments/assets/44cbe5ed-9a84-411a-9e50-17dff901846c" />


### 6. Menambahkan Data (Create)
Membuat halaman `tambah.php` untuk menambahkan data barang baru ke database.

<img width="1664" height="905" alt="Screenshot 2026-11-16 185949" src="https://github.com/user-attachments/assets/71b31129-0766-44fd-8995-7c05ee7c58b7" />

<img width="1672" height="876" alt="Screenshot 2026-11-16 190004" src="https://github.com/user-attachments/assets/712799b0-9a14-466c-872f-66ac219c4765" />

### 7. Mengubah Data (Update)
Membuat halaman `ubah.php` untuk mengubah informasi barang yang sudah tersimpan.

<img width="1662" height="883" alt="Screenshot 2026-11-16 190106" src="https://github.com/user-attachments/assets/61789c96-dc6e-43ba-9872-b47834c712e2" />

<img width="1660" height="881" alt="Screenshot 2026-11-16 190116" src="https://github.com/user-attachments/assets/8e480bcf-12ce-49e3-a0a6-0c26fe092714" />

### 8. Menghapus Data (Delete)
Membuat halaman `hapus.php` untuk menghapus data barang berdasarkan ID barang.

<img width="1627" height="255" alt="Screenshot 2026-11-16 190212" src="https://github.com/user-attachments/assets/08768e5a-2a5f-471b-88b5-dc0920715bd3" />


## Struktur Project

<img width="228" height="227" alt="Screenshot 2026-11-16 190246" src="https://github.com/user-attachments/assets/5d348847-88ae-4daf-a2c6-6ad1eb4d94ef" />


## Cara Menjalankan Project

1. Jalankan Apache dan MySQL melalui XAMPP.
2. Pastikan database `latihan1` sudah tersedia.
3. Letakkan folder project di dalam `htdocs`.
4. Buka browser.
5. Akses alamat berikut:

`http://localhost/lab8_PHP_database/index.php`

## Hasil Praktikum

Berdasarkan pengujian, fungsi CRUD telah berhasil dijalankan:
- Create: menambahkan data barang.
- Read: menampilkan data barang.
- Update: mengubah data barang.
- Delete: menghapus data barang.

## Kesimpulan

Praktikum ini memberikan pemahaman mengenai penggunaan PHP untuk menghubungkan aplikasi web dengan database MySQL. Melalui operasi CRUD, data barang dapat ditambahkan, ditampilkan, diubah, dan dihapus melalui halaman web.
