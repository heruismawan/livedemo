# PemesananPenginapan

Aplikasi **Pemesanan Penginapan** ini adalah program sederhana berbasis Java yang memungkinkan pengguna untuk memasukkan data pemesanan penginapan. Program ini menerima input pelanggan seperti nama pelanggan, tipe kamar, dan jumlah malam menginap, lalu menghitung dan menampilkan total biaya penginapan berdasarkan tipe kamar yang dipilih.

## Fitur
- Menghitung biaya penginapan berdasarkan tipe kamar dan jumlah malam menginap.
- Mendukung tipe kamar: `Standard`, `Deluxe`, dan `Suite`.
- Menampilkan informasi pemesanan termasuk nama pelanggan, tipe kamar, jumlah malam, dan total biaya.

## Struktur Kode
Kode utama terdapat dalam kelas `PemesananPenginapan` yang memiliki beberapa metode untuk:
- Mengambil input pelanggan (nama, tipe kamar, jumlah malam).
- Menghitung total biaya penginapan.
- Menampilkan informasi pemesanan kepada pengguna.

### Metode Utama
- `getNamaPelanggan()`: Mengambil nama pelanggan dari input pengguna.
- `tipekamar()`: Mengambil tipe kamar dari input pengguna.
- `getJumlahMalam()`: Mengambil jumlah malam menginap dari input pengguna.
- `getBiayaPerMalam()`: Menentukan biaya per malam berdasarkan tipe kamar.
- `getTotalBiaya()`: Menghitung total biaya berdasarkan jumlah malam dan biaya per malam.

## Cara Menggunakan
1. **Kloning Repository**
   ```bash
   git clone https://github.com/username/nama-repo.git
   cd nama-repo

javac PemesananPenginapan.java
java PemesananPenginapan

Masukkan nama pelanggan:
John Doe
Masukkan tipe kamar (Standard/Deluxe/Suite):
Deluxe
Masukkan jumlah malam menginap:
3
Pelanggan: John Doe
Tipe Kamar: Deluxe
Jumlah Malam: 3
Total Biaya: Rp 2250000

