# LAPORAN PEMROGRAMAN MOBILE KELOMPOK 8 

## MENAMPILKAN GAMBAR DENGAN ANDROID STUDIO DAN FLUTTER

### Dosen Pengampu:
- I Gde Agung Sri Sidhimantra, S.Kom., M.Kom.

### NAMA KELOMPOK:
1. Septi Isdayanna (22091397045)
2. Septian Nur Ikhsan (22097397049)
3. Eva Fitria Novianti Putri (22097397068)

PROGRAM STUDI D4 MANAJEMEN INFORMATIKA (2022B)  
FAKULTAS VOKASI  
UNIVERSITAS NEGERI SURABAYA  
2024


## 1. DIAGRAM ‘APLIKASI I AM CLASSIC’

![Alt Text](https://github.com/septiisdayanna/aplikasi-i_am_classic/blob/f7df9e36688d81cbb37d32781ec8d2e0783218ce/DIAGRAM.jpg)

### Penjelasan Diagram:
Aplikasi ini dari kiri atau diawali dengan “MaterialApp” yang berisi “Scaffold”. Didalam Scaffold ada “Center” untuk gambar atau “Image” yang berisi “Asset Image” dengan nama ‘mobil1.jpeg’, selain itu juga ada “Background Color” untuk Scaffold dengan warna ‘cyan’. Kemudian ada AppBar untuk bagian atasnya yang didalamnya ada “Background Color” dengan warna ‘bluegrey[800]’ dan ada sebuah “Title” untuk titlenya. Lalu yang terakhir pada “Title” berisi text yaitu ‘I Am Classic’ dengan menggunakan TextStyle color ‘white’.

## 2. PENJELASAN KODE PADA FOLDER (MAIN.DART)

`main.dart` adalah file utama yang akan dipakai sebagai file utama yang akan kita gunakan sebagai entry point atau titik masuk untuk melakukan eksekusi pada aplikasi yang akan dijalankan.

- `import 'package:flutter/material.dart';` Ini adalah pernyataan untuk mengimpor pustaka Flutter yang diperlukan, termasuk komponen UI dari paket material.
- `void main() {}` Fungsi main adalah fungsi utama yang akan dieksekusi saat aplikasi Flutter dimulai.
- `runApp()` Metode runApp digunakan untuk menjalankan aplikasi Flutter. Di dalamnya, kita melewatkan widget MaterialApp sebagai widget utama aplikasi.
- `MaterialApp()` Ini adalah widget utama aplikasi yang menyediakan beberapa konfigurasi dasar, seperti tema dan navigator.
- `home: Scaffold()` Widget Scaffold adalah kerangka utama aplikasi yang menyediakan struktur dasar, termasuk app bar dan body.
- `appBar: AppBar()` Widget AppBar adalah elemen antarmuka pengguna yang menyediakan baris judul dan beberapa aksi.
- `title: Text()` Widget Text digunakan untuk menampilkan teks. Di sini, kita memberikan judul "I Am Classic" dengan gaya teks berwarna putih.
- `backgroundColor: Colors.blueGrey[800],` Mengatur warna latar belakang app bar menjadi biru gelap (Colors.blueGrey[800]).
- `body: Center()` Widget Center digunakan untuk menempatkan elemen-elemen anaknya ke tengah layar. Di dalamnya, kita memiliki widget Image yang menampilkan gambar mobil.
- `child: Image()` Widget Image digunakan untuk menampilkan gambar. Disini, gambar mobil diambil dari file 'images/mobil1.jpeg'.
- `backgroundColor: Colors.cyan,` Digunakan untuk mengatur warna latar belakang body sesuai dengan yang kita inginkan.

## 3. PENJELASAN KODE PADA FOLDER (PUBSPEC.YAML)

`pubspec.yaml` adalah file konfigurasi yang digunakan oleh Flutter untuk mengelola dependensi, pengaturan proyek, dan sumber daya lainnya.

- `name: I_AM_Classic` Ini menentukan nama proyek. Disini, proyek dinamai "I_AM_Classic".
- `description: "A new Flutter project."` Deskripsi singkat tentang proyek. Dalam hal ini, deskripsi adalah "A new Flutter project."
- `publish_to: 'none'` Ini menentukan tempat di mana proyek akan dipublikasikan. Dalam hal ini, publish_to diatur ke 'none', yang berarti proyek ini tidak akan dipublikasikan ke pub.dev (tempat umum untuk publikasi paket Flutter).
- `version: 1.0.0+1` Versi proyek. Formatnya adalah major.minor.patch+build, di mana: major: Versi utama. minor: Versi minor. patch: Pembaruan kecil. build: Nomor build. Di sini, versi adalah "1.0.0+1".
- `environment: sdk: '>=3.2.6 <4.0.0'` Menentukan lingkungan yang diperlukan untuk menjalankan proyek. Di sini, spesifikasinya adalah SDK Flutter minimal yang dibutuhkan, yaitu minimal versi 3.2.6 dan kurang dari 4.0.0.
- `dependencies:` `flutter:` `sdk: flutter` `cupertino_icons: ^1.0.2` Daftar dependensi yang dibutuhkan oleh proyek. Dalam hal ini: flutter: SDK Flutter itu sendiri. Versi yang spesifikasikan di sini adalah yang terkini pada saat proyek dibuat. cupertino_icons: Dependensi yang menyediakan ikon-ikon gaya Cupertino (pengaturan default untuk iOS dalam Flutter). Versi yang spesifikasikan adalah minimal 1.0.2.
- `dev_dependencies:` `flutter_test:` `sdk: flutter` `flutter_lints: ^2.0.0` Dependensi yang hanya dibutuhkan selama pengembangan. Dalam hal ini: flutter_test: Paket Flutter untuk menulis dan menjalankan tes unit. Ini hanya dibutuhkan selama pengembangan. Versi yang spesifikasikan adalah SDK Flutter terkini. flutter_lints: Paket yang menyediakan aturan linter tambahan untuk Flutter. Ini membantu memeriksa kode Anda agar sesuai dengan standar kode yang dianjurkan. Versi yang spesifikasikan adalah minimal 2.0.0.
- `flutter:` `uses-material-design: true` `assets:` `- images/mobil1.jpeg` Konfigurasi spesifik untuk Flutter: uses-material-design: Mengindikasikan bahwa proyek ini menggunakan desain material (desain default untuk aplikasi Flutter). assets: Menentukan sumber daya yang disertakan dalam proyek. Di sini, images/mobil1.jpeg adalah satu-satunya aset yang disertakan, yang berarti file gambar mobil1.jpeg dalam folder images akan dimasukkan dalam aplikasi.

## 4. DOKUMENTASI APLIKASI I AM CLASSIC

![Alt Text](https://github.com/septiisdayanna/aplikasi-i_am_classic/blob/main/DOKUMENTASI%20APLIKASI%202.png)

![Alt Text](https://github.com/septiisdayanna/aplikasi-i_am_classic/blob/b3f06ddbb6a5386322a68091014e60ad50d7a5ce/DOKUMENTASI%20APLIKASI.jpg)

