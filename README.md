# Tales & Tails Cafe 🏰🐈

#### Kelompok: A-11  
#### Anggota:
- Andi Salsabila Ardian
- Fariska Fedira Ardhanariswari
- Febrian Irvansyah
- Muhammad Madhani Putra
- Shaquille Athar Adista

#### Link
[Website](https://talesandtailscafe-a11-tk.pbp.cs.ui.ac.id/)

#### Cerita Aplikasi:
Tales and Tails Cafe adalah sebuah Cafe yang mengambil konsep Cat Cafe, tetapi memiliki sebuah perpustakaan untuk meminjam buku juga. Cafe ini memiliki tujuan untuk memadukan suasana santai kafe dengan kemudahan akses ke koleksi buku yang beragam, hal ini bertujuan untuk menciptakan ruang yang menggabungkan dua kegiatan yang menyenangkan dan mendidik.

#### Modul yang digunakan:
- Login
  - Field username/email
  - Field password
- Register
  - Field firstname
  - Field lastname
  - Field username
  - Field e-mail
  - Field no. telp
  - Field tanggal lahir
- Homepage
- ##### User Modul
  - Katalog:
    Menampilkan koleksi buku yang disediakan  
    Atribut:  
    - Menampilkan stok
    - Menampilkan sections sesuai tema buku
  - Detail buku
    - Menampilkan metadata dari buku
    - Tempat user meminjam buku
  - Profile
    - Data pribadi
    - List buku yang sudah dipinjam
    - Tempat pengembalian buku
- ##### Admin Modul
  - Profile
    - Data pribadi
  - Hapus/Tambah Buku
    - Tempat admin untuk menambah atau menghapus buku dari katalog
  - List Peminjam
    - Menampilkan list user serta buku yang dipinjam
  
#### Sumber dataset:
Google Books API

#### Role:
- Admin:
  - Hapus/nambah buku
  - Melihat list peminjam dan buku yang dipinjam
  - Dapat bernavigasi dalam web
- Member (pengguna yang login):
  - Meminjam buku
  - Mengembalikan buku
  - Dapat bernavigasi dalam web
- Guest (pengguna yang tidak login):
  - Dapat bernavigasi dalam web
  - Tidak mempunyai hak dalam meminjam atau menambah buku
  
