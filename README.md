# 🎮 Retro Tetris – Neon Edition

Project ini merupakan **Game Tetris bertema Neon Retro** yang dikembangkan menggunakan **Python dan Pygame** sebagai bagian dari **Ujian Akhir Semester (UAS)** mata kuliah **Pemrograman Berorientasi Objek (PBO)**.

Fokus utama dari project ini adalah penerapan konsep **Object Oriented Programming (OOP)** secara nyata ke dalam sebuah aplikasi game interaktif.

---

## 📌 Deskripsi Singkat

Retro Tetris – Neon Edition adalah adaptasi dari game Tetris klasik dengan tampilan visual neon modern. Game ini memiliki sistem score, level, combo, serta fitur menu, pause, dan game over. Seluruh logika permainan disusun secara modular menggunakan paradigma OOP agar kode lebih terstruktur dan mudah dikembangkan.

---

## 🧠 Konsep OOP yang Diterapkan

Project ini menerapkan tiga konsep utama OOP:

### 1. Encapsulation

* Diterapkan pada class `Shape`
* Atribut seperti tipe, warna, rotasi, dan posisi dibuat private
* Akses data menggunakan getter dan setter

### 2. Inheritance

* Class `TetrisGame` berperan sebagai parent class
* Menyimpan logika utama permainan seperti board, score, level, dan status game

### 3. Polymorphism

* Diterapkan melalui class `ShapeFactory`
* Digunakan untuk membuat berbagai tipe tetromino dengan interface yang sama

---

## ✨ Fitur Utama

* Pergerakan block (kiri, kanan, turun)
* Rotasi block
* Hard drop (langsung jatuh ke bawah)
* Collision detection
* Clear line otomatis
* Sistem score, level, dan combo
* Preview next block
* Menu awal, pause, dan game over
* Tampilan UI neon retro

---

## 🎮 Kontrol Game

| Tombol | Fungsi                      |
| ------ | --------------------------- |
| ⬅ / ➡  | Geser block ke kiri / kanan |
| ⬆      | Rotasi block                |
| ⬇      | Soft drop                   |
| Space  | Hard drop                   |
| P      | Pause / Resume game         |
| Enter  | Mulai game / Main lagi      |

---

## 🛠️ Teknologi yang Digunakan

* **Python 3**
* **Pygame**
* Paradigma **Object Oriented Programming (OOP)**

---

## ▶️ Cara Menjalankan Program

1. Pastikan Python sudah terinstall
2. Install Pygame:

   ```bash
   pip install pygame
   ```
3. Jalankan file utama:

   ```bash
   python TetrisRetroGame.py
   ```

---

## 📚 Tujuan Project

* Mengimplementasikan konsep OOP ke dalam aplikasi nyata
* Membuat game sederhana berbasis Python dan Pygame
* Menghasilkan kode yang modular, rapi, dan mudah dipahami
* Memenuhi kriteria penilaian UAS Pemrograman Berorientasi Objek

---

## 👩‍💻 Author

**Frysa Nayla Ayu**
D4 Manajemen Informatika
Universitas Negeri Surabaya
Tahun 2025

---

## 📄 Lisensi

Project ini dibuat untuk keperluan akademik dan pembelajaran.
Bebas digunakan sebagai referensi dengan mencantumkan sumber.

---

⭐ Jangan lupa beri star pada repository ini jika project ini bermanfaat!
