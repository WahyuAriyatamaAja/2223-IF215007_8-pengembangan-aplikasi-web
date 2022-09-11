# Proposal : Aplikasi Web Jajanan

## Permasalahan
- Warung yang sering mengalami kehabisan stok dan kesulitan untuk mendata 

## Rancangan Solusi
- Membuat aplikasi untuk mendata barang di warung
- Data barang berupa jumlah ketersediaan dan harga barang

## Use Case
- User pemilik warung dapat melakukan registrasi untuk memasukkan data warung
- User pemilik warung bisa memasukan nama, jumlah, dan harga barang yang tersedia di warungnya
- User warga dapat melihat barang yang tersedia dan harganya

## Struktur Data

### User
Atribut|Tipe Data|Contoh
---|---|---
ID | integer | 1
username | string | Wahyu
password | string | gantengbanget

### Warung
Atribut|Tipe Data|Contoh
---|---|---
ID | integer | 1
nama warung | string | jajan teros

### Barang
Atribut|Tipe Data|Contoh
---|---|---
ID | integer | 1
jenis barang | string | Minuman
nama barang | string | Teh Pucuk
jumlah barang | integer | 0
harga barang | integer | 1000

## UX Wireframe
![Beranda Belum Login](https://user-images.githubusercontent.com/106895141/189530739-93d78930-0dcd-4b64-ab29-f4d704d8952f.png)

![Beranda Setelah Login](https://user-images.githubusercontent.com/106895141/189530757-5c4150df-599d-48fb-8d3f-a42be5510a05.png)
