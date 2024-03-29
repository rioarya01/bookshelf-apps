# 📚 Bookshelf Apps
**Submission Aplikasi Pengelolaan Data Menggunakan DOM dan Web Storage**<br>
Kelas Belajar Membuat Front-End Web untuk Pemula.<br>
Disusun oleh : Dicoding Indonesia.<br>
Level : Pemula.

### 📱 Mobile
<p align="middle">
    <img alt="GIF" src="https://github.com/rioarya01/bookshelf-apps/blob/main/mockup-readme-smartphone.gif" width="200" height="400"/>&numsp;
    <img alt="GIF" src="https://github.com/rioarya01/bookshelf-apps/blob/main/mockup-readme-tablet.gif" width="300" height="400"/>
</p>

### 💻 Desktop
<p align="middle">
    <img alt="GIF" src="https://github.com/rioarya01/bookshelf-apps/blob/main/mockup-readme-desktop.gif" width="550" height="300"/>
</p>

## Kriteria 1 : Mampu Menambahkan Data Buku

* Bookshelf Apps harus mampu menambahkan data buku baru.
* Data buku yang disimpan merupakan objek JavaScript.

Berikut strukturnya:

    {
      id: string | number,
      title: string,
      author: string,
      year: number,
      isComplete: boolean,
    }

Berikut contoh data riilnya :

    {
      id: 3657848524,
      title: 'Harry Potter and the Philosopher\'s Stone',
      author: 'J.K Rowling',
      year: 1997,
      isComplete: false,
    }
    
#### Catatan :

> Untuk id buku pada tiap buku yang disimpan haruslah unik. Tips dalam menetapkan nilai untuk adalah Anda bisa memanfaatkan nilai 
timestamp. Untuk mendapatkan nilai timestamp di JavaScript cukup mudah, cukup dengan menuliskan expressions **+new Date().**

## Kriteria 2: Memiliki Dua Rak Buku
* Bookshelf Apps harus **memiliki 2 Rak buku.** Yakni, “Belum selesai dibaca” dan “Selesai dibaca”.
* Rak buku "Belum selesai dibaca" hanya menyimpan buku jika properti `isComplete` bernilai *false.*
* Rak buku "Selesai dibaca" hanya menyimpan buku jika properti `isComplete` bernilai *true.*

## Kriteria 3: Dapat Memindahkan Buku antar Rak
* Buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca"<br>
**harus dapat dipindahkan di antara keduanya.**

## Kriteria 4: Dapat Menghapus Data Buku
* Buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca"<br>
**harus dapat dihapus.**

## Kriteria 5: Manfaatkan localStorage dalam Menyimpan Data Buku
* Data buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca"<br>
**harus dapat bertahan walaupun halaman web ditutup.**
* Dengan begitu, Anda **harus menyimpan data buku pada localStorage.**
