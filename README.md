| Nama      | Firman Lintar Nurrohman |
| ----------- | ----------- |
| NIM     | 312010197       |
| Kelas   | TI.20.A.1        |

## Langkah langkah praktikum 9

# Praktikum 9: PHP Modular

### 1. Buat file baru dengan nama header.php
![img1](assets/img/9.1.PNG)

### 2. Buat file baru dengan nama footer.php
![img1](assets/img/9.2.PNG)

### 3. Buat file baru dengan nama home.php
![img1](assets/img/9.3.PNG)

### 4. Buat file baru dengan nama about.php
![img1](assets/img/9.4.PNG)

### 5. Output
- Halaman Home
![img1](assets/img/9.5.PNG)

- Halaman About
![img1](assets/img/9.6.PNG)

## Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

## Berikut struktur yang saya buat
Lab9_php_database
```
├── config
│   ├── hapus.php
│   ├── koneksi.php
│   ├── tambah.php
│   └── ubah.php
├── layouts
│   ├── footer.php
│   ├── head-static.php
│   ├── header.php
│   ├── main.php
│   ├── tambah.php
│   └── ubah.php
├── static
│   ├── css
│   │   └── style.css
│   └── img
├── index.php
├── tambah.php
└── ubah.php
```

## Config 
Dalam folder tersebut menyimpan file khusus php yang nanti akan dieksekusi

- koneksi.php
![img1](assets/img/9.7.PNG)

- tambah.php
![img1](assets/img/9.8.PNG)

- ubah.php
![img1](assets/img/9.9.PNG)
![img1](assets/img/9.9.1.PNG)

- hapus.php
![img1](assets/img/9.10.PNG)

## Layouts
Untuk menyimpan tampilan utama pada website, dan dibagi pada beberapa file

- head-static.php
![img1](assets/img/9.11.PNG)

- header.php
![img1](assets/img/9.12.PNG)

- main.php
![img1](assets/img/9.13.PNG)

- footer.php
![img1](assets/img/9.14.PNG)

## Static
Untuk menyimpan file yang diperlukan seperti css, js, gambar

- style.css
![img11](assets/img/9.15.PNG)
![img1](assets/img/9.15.1.PNG)

## index.php, tambah.php, ubah.php
File utama dan berfungsi sebagai wadah untuk memanggil sub-file di beberapa direktori

- index.php
![img1](assets/img/9.16.PNG)

- tambah.php
![img1](assets/img/9.17.PNG)

- ubah.php
![img1](assets/img/9.18.PNG)

# Output
![img1](assets/img/9.19.PNG)

- Tambah barang
![img1](assets/img/9.20.PNG)

![img1](assets/img/9.21.PNG)

- Ubah barang
![img1](assets/img/9.22.PNG)

![img1](assets/img/9.23.PNG)