# LATIHAN7DPBO2023
> Saya Anandita Kusumah M dengan nim 2101114 mengerjakan Latihan Praktikum 7 DPBO dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Desain Program

   Program ini memiliki beberapa class, yaitu :

  - Controller, berfungsi untuk menerima inputan apabila User menekan tombol W A S D atau ⬆ ⬇ ⬅ ➡.
  - Display, berfungsi untuk membuat dan menampilkan frame.
  - Game, merupakan class utama yang  berfungsi untuk mengontrol jalannya game.
  - GameObject, merupakan sebuah class template yang dapat digunakan untuk membuat semua objek yang ingin ditambahkan dalam permainan.
  - GameInterface, bukan class, melainkan sebuah Interface yang berisi dua method yaitu render() dan loop(). Method render() digunakan untuk menampilkan objek-     objek pada layar, sedangkan method loop() berfungsi untuk mengatur perilaku objek-objek tersebut setiap detik.
  - Player, merupakan objek berbentuk bulatan yang dapat bergerak, dan merupakan turunan atau anak kelas dari GameObject.
  - Kotak, merupakan objek yang dapat berpindah secara acak ketika disentuh dan juga merupakan turunan atau anak kelas dari GameObject.
  - Handler, merupakan class yang berfungsi untuk mengatur semua objek yang ada di dalam sebuah permainan atau game.
  - Synchronization, merupakan kelas yang dipanggil pertama kali ketika program dijalankan, dan kemudian akan memanggil kelas Game.
  
  

## Alur
- Pemain membuka program pengendali bola.
- User menekan tombol W A S D atau ⬆ ⬇ ⬅ ➡.
- Jika user menekan tombol kanan dan berhenti, maka skor bertambah +1.
- Jika user menekan tombol atas, bawah, atau kiri, maka skor akan menjadi +3.
- Namun jika user menekan tombol yang sama secara bersamaan seperti kanan lalu kanan lagi maka skor hanya +1 bukan +2.
- Lalu jika user menyetuh objek kotak maka skor akan bertambah +10 lalu posisi objek kotak akan berpindah secara random/acak.

## Dokumentasi
![bandicam 2023-04-23 21-07-07-077](https://user-images.githubusercontent.com/100897554/233844708-172de25a-f018-44ef-b390-4e4902b5fbf1.gif)
