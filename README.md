# Lab4Web.
tugas pemrograman web
# Lab4Web - Praktikum 4 CSS Lanjutan
---
**Nama:** maulana akbar
**NIM:** 312510381
**Mata Kuliah:** Pemrograman Web  
**Universitas:** Universitas Pelita Bangsa

Repository ini berisi hasil pengerjaan **Praktikum Pemrograman Web (Modul 4: CSS Layout)**. Praktikum ini bertujuan untuk memahami dan mengimplementasikan tata letak (*layout*) website menggunakan teknik CSS Box Element, CSS Float, serta elemen semantik HTML5.

## 📝 Penjelasan Langkah Praktikum & Tugas

### 1. Praktik Dasar Box Element & Float (`lab4_box.html`)
Pada tahap ini, saya membuat struktur dasar menggunakan elemen `<div>` yang merepresentasikan *box element*. 
* **Langkah:** Membuat beberapa kotak (Div 1, Div 2, Div 3) dan memberikan warna latar yang berbeda. Kemudian, saya menambahkan properti CSS `float: left` agar elemen tersebut berjajar secara horizontal. Saya juga mengimplementasikan teknik **Clearfix** menggunakan properti `clear: left` pada kotak ke-4 (Div 4) agar elemen tersebut turun ke baris baru dan tidak mengikuti arus *float* di atasnya
  <img width="305" height="275" alt="kodingan float1" src="https://github.com/user-attachments/assets/99c174c6-3177-4c21-a91e-7c205d7272e6" />
  **dan ini hasilnya**
  <img width="302" height="192" alt="hasil with folat" src="https://github.com/user-attachments/assets/7078f260-825c-4491-893f-d41add7ce936" />



### 2. Membuat Header & Navigasi Bar
Pembuatan kerangka atas website menggunakan elemen semantik agar struktur lebih rapi.
* **Perubahan Kode:** Menambahkan tag `<header>` untuk judul utama website dan `<nav>` untuk menu tautan. Pada sisi CSS, menu navigasi dimodifikasi dari bentuk teks biasa menjadi tombol blok menggunakan `display: inline-block` dan ditambahkan efek warna yang berubah saat kursor diarahkan (*hover*) atau saat menu sedang aktif (*active*).
  <img width="1155" height="781" alt="codingan navdan header" src="https://github.com/user-attachments/assets/146dac42-1e6b-4a2f-bfab-d5188adaa64d" />
  **hasilnya seperti ini**
  <img width="990" height="155" alt="hasilmembuatheaderdannav" src="https://github.com/user-attachments/assets/01486767-4049-4bb7-82af-387854c2c681" />



### 3. Membuat Konten & Artikel
Proses membagi badan halaman menjadi beberapa tata letak yang kompleks.
* **Perubahan Kode:** 
  * Menambahkan `<section id="main">` untuk area konten utama dan `<aside>` untuk *sidebar*. Kedua elemen ini diatur berdampingan menggunakan persentase lebar (*width*) dan `float`.
  * Menambahkan **Grid Box**: Menggunakan tag `<div>` yang dibagi menjadi 3 kolom rata dengan ukuran `width: 33.33%`.
  * Menambahkan **Artikel**: Menggunakan tag `<article>`, di mana gambar disisipkan bersama teks. CSS `float: left` dan `float: right` digunakan agar teks dapat membungkus (mengelilingi) gambar dengan rapi.
    ## membuat konten ##
    css membuat konetn
    <img width="387" height="387" alt="css contetn2" src="https://github.com/user-attachments/assets/438a8389-8171-461a-a786-ef9c1021bc75" />
    hasilnya
    <img width="1326" height="907" alt="hasil content2" src="https://github.com/user-attachments/assets/355821e4-557b-45c0-9572-4894446a9f18" />
    ## oembuatan artikel ##
    css artikel
    <img width="311" height="396" alt="css artikel" src="https://github.com/user-attachments/assets/c417bd98-cd02-444f-8b89-6be845271ade" />
    hasilnya
    <img width="1330" height="422" alt="image" src="https://github.com/user-attachments/assets/fff6f3a7-b454-4a19-9516-cd44be31c99b" />




### 4. Halaman Home (`home.html`)
Halaman beranda utama yang merupakan penggabungan dari semua struktur di atas.
* **Penjelasan:** Halaman ini menggabungkan kode Header, Navigasi, *Hero Panel* (banner ucapan selamat datang), Konten, Artikel, *Sidebar*, dan *Footer* menjadi satu kesatuan dokumen utuh. Halaman ini menjadi tampilan default saat website pertama kali dibuka.
  

### 5. Halaman About (`about.html`)
Pembuatan halaman khusus (Tugas 1) untuk menampilkan profil dan portofolio.
* **Perubahan Kode:** Menggunakan kerangka layout `home.html`, namun menghapus bagian artikel dan grid box, lalu menggantinya dengan informasi profil. Perubahan CSS dilakukan untuk menyejajarkan foto profil di sebelah kiri teks deskripsi, serta merapikan *margin* pada *list* (daftar) keahlian/portofolio agar selaras dengan desain utama.
  **html**
  <img width="1272" height="817" alt="html aboaut" src="https://github.com/user-attachments/assets/fe48957c-53e1-4b92-bcce-2123354193bb" />
  **kode css**
  <img width="345" height="356" alt="cssabout" src="https://github.com/user-attachments/assets/e9af37c9-4964-4626-bf8d-3e0fa960f498" />

  **hasilnya**
  <img width="1341" height="542" alt="about hasil" src="https://github.com/user-attachments/assets/6805ee2b-b661-493c-9c60-20a3db82e686" />


### 6. Halaman Contact (`kontak.html`)
Pembuatan halaman khusus (Tugas 2) untuk menyediakan media komunikasi interaktif.
* **Perubahan Kode:** Bagian konten utama diganti dengan elemen formulir (`<form>`). Ditambahkan elemen `<input>` (untuk nama dan email) serta `<textarea>` (untuk pesan panjang). Kode CSS ditambahkan untuk mengatur lebar form menjadi 100% (*full-width*), memberikan jarak antar-kolom (*margin-bottom*), dan memberikan efek perubahan warna garis tepi (*border*) saat form tersebut diklik/diketik oleh pengguna.
  **kode html**
  <img width="1236" height="951" alt="image" src="https://github.com/user-attachments/assets/5990e43c-b1e1-4a35-a57f-86f48ebaacfe" />
  **kode css**
  <img width="1206" height="520" alt="image" src="https://github.com/user-attachments/assets/69e93877-3c84-4488-8db4-80310f270979" />
  **hasilnya**
  <img width="1130" height="502" alt="hasil kontak" src="https://github.com/user-attachments/assets/1fb86225-c4e8-4803-ba52-8f8b5355f055" />





