# 💻 Sistem Manajemen Aset IT

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Data Structure](https://img.shields.io/badge/LinkedList-007396?style=for-the-badge&logo=java&logoColor=white)

Program CLI (Command Line Interface) berbasis Java untuk mengelola inventaris aset IT secara dinamis menggunakan struktur data **LinkedList**. Proyek ini dibuat untuk memenuhi tugas praktikum Pemrograman Berorientasi Objek (OOP).

---

## 📌 Fitur Utama

- **Tambah Aset**: Menambahkan data aset baru (ID, Nama Perangkat, Lokasi, dan Status Kondisi).
- **Tampilkan Data**: Menampilkan seluruh daftar aset IT yang tersimpan secara terstruktur.
- **Hapus Aset**: Menghapus data aset secara aman berdasarkan `ID Aset` menggunakan `Iterator` untuk menghindari `ConcurrentModificationException`.
- **Penanganan Edge Case**: Menampilkan pesan peringatan jika ID aset yang ingin dihapus tidak ditemukan.

---

## 🏗️ Struktur Proyek

```text
src/
└── tugasprak4/
    ├── AsetIT.java        # Class Model untuk entitas Aset IT
    ├── ManajemenAset.java # Class Controller penampung LinkedList & logika bisnis
    └── MainAset.java      # Class Main (Entry point program)
