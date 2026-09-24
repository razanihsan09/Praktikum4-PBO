# Manajemen Aset IT (Tugas Praktikum 4)

Program Java untuk mengelola daftar aset IT (seperti server, router, PC, dll) menggunakan `LinkedList`. Program ini mencakup fungsi dasar seperti menambah data, menampilkan seluruh data, dan menghapus data berdasarkan ID Aset.

---

## Fitur
- **Tambah Aset**: Menambahkan data aset baru ke dalam daftar.
- **Tampilkan Data**: Menampilkan seluruh data aset yang tersimpan beserta detailnya.
- **Hapus Aset**: Menghapus data aset spesifik menggunakan ID Aset (memanfaatkan `Iterator` agar aman saat iterasi).

---

## Struktur File
```text
src/
└── tugasprak4/
    ├── AsetIT.java        # Class model untuk entitas Aset IT
    ├── ManajemenAset.java # Class controller (mengelola LinkedList)
    └── MainAset.java      # Main class untuk menjalankan program
```

---

## Cara Menjalankan
1. Pastikan sudah menginstal Java (JDK 8 atau versi di atasnya).
2. Clone repositori ini atau download file source code-nya.
3. Buka proyek menggunakan IDE (NetBeans, Eclipse, VS Code, atau IntelliJ IDEA).
4. Run file `MainAset.java`.

---

## Contoh Output Program
```text
[INFO] Aset dengan ID AST001 berhasil ditambahkan.
[INFO] Aset dengan ID AST002 berhasil ditambahkan.
[INFO] Aset dengan ID AST003 berhasil ditambahkan.
[INFO] Aset dengan ID AST004 berhasil ditambahkan.

===== DAFTAR SEMUA ASET IT =====
ID Aset        : AST001
Nama Perangkat : Server Dell R740
Lokasi         : Ruang Server
Status Kondisi : Baik
-----------------------------------
ID Aset        : AST002
Nama Perangkat : Router Cisco 2900
Lokasi         : Ruang Jaringan
Status Kondisi : Baik
-----------------------------------
ID Aset        : AST003
Nama Perangkat : Switch TP-Link 24 Port
Lokasi         : Ruang Jaringan
Status Kondisi : Rusak
-----------------------------------
ID Aset        : AST004
Nama Perangkat : PC Dell OptiPlex 3090
Lokasi         : Ruang Admin
Status Kondisi : Baik
-----------------------------------

>>> Menghapus aset dengan ID AST003 (Switch) <<<
[INFO] Aset dengan ID AST003 berhasil dihapus.

>>> Mencoba menghapus aset dengan ID yang tidak ada (AST999) <<<
[PERINGATAN] Aset dengan ID AST999 tidak ditemukan!

===== DAFTAR SEMUA ASET IT =====
ID Aset        : AST001
Nama Perangkat : Server Dell R740
Lokasi         : Ruang Server
Status Kondisi : Baik
-----------------------------------
ID Aset        : AST002
Nama Perangkat : Router Cisco 2900
Lokasi         : Ruang Jaringan
Status Kondisi : Baik
-----------------------------------
ID Aset        : AST004
Nama Perangkat : PC Dell OptiPlex 3090
Lokasi         : Ruang Admin
Status Kondisi : Baik
-----------------------------------
```

---

## Pembuat
- **Nama**: Razan Muhammad Ihsan
- **NIM**: L0325010
