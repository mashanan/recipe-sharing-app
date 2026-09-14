# 🍳 Dapurame - Recipe & Culinary Companion App

**Dapurame** adalah aplikasi *mobile* berbasis Flutter yang dirancang untuk memudahkan pengguna dalam menjelajahi, menyimpan, dan mengelola resep masakan favorit. Proyek ini dibangun sebagai solusi praktis untuk memasak sehari-hari dengan antarmuka yang bersih, intuitif, dan responsif.

---

## 📸 Tampilan Aplikasi (Screenshots)

| Beranda | Detail Resep | Favorit |
|:---:|:---:|:---:|
 | <img width="746" height="1600" alt="image" src="https://github.com/user-attachments/assets/d43d2f7e-c291-4db0-afe5-ddb9dc513f06" />
 | <img width="746" height="1600" alt="image" src="https://github.com/user-attachments/assets/e01560a7-5f9d-4bc7-8a8f-7a938bf5f878" />
 | <img width="746" height="1600" alt="image" src="https://github.com/user-attachments/assets/e24d8a53-e6ed-4c1c-9628-904abc855033" />
 |

---

## ✨ Fitur Utama

* **🔍 Eksplorasi & Pencarian Resep:** Cari resep masakan berdasarkan nama, kategori, atau bahan-bahan yang Anda miliki.
* **📋 Langkah Memasak Interaktif:** Panduan memasak langkah-demi-langkah yang rinci lengkap dengan estimasi waktu dan porsi.
* **❤️ Favorit & Koleksi:** Simpan resep favorit Anda agar dapat diakses kembali dengan cepat.
* **🏷️ Filter Kategori:** Kelompokkan resep berdasarkan jenis hidangan (Makanan Utama, Camilan, Minuman, dll.).

---

## 🛠️ Teknologi & Tools

- **Framework:** [Flutter](https://flutter.dev/) (Dart)
- **State Management:** Provider / BLoC / Riverpod *(Sesuaikan dengan yang digunakan)*
- **Database/API:** Firebase / REST API / SQLite *(Sesuaikan)*
- **IDE:** Visual Studio Code / Android Studio
- **Version Control:** Git & GitHub

---

## 🚀 Cara Menjalankan Proyek

### 1. Prasyarat

Pastikan perangkat Anda sudah terpasang:
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (versi stable terbaru)
- [Dart SDK](https://dart.dev/get-dart)
- Android Studio / Xcode (untuk emulator) atau perangkat fisik Android/iOS yang terhubung via USB Debugging.

Cek kesiapan lingkungan dengan menjalankan perintah:
```bash
flutter doctor
```

### 2. Langkah Instalasi

1. **Kloning Repositori ini:**
   ```bash
   git clone https://github.com/username/dapurame.git
   ```

2. **Masuk ke direktori proyek:**
   ```bash
   cd dapurame
   ```

3. **Unduh dependensi yang dibutuhkan:**
   ```bash
   flutter pub get
   ```

4. **Jalankan aplikasi:**
   ```bash
   flutter run
   ```

---

## 📂 Struktur Direktori Proyek

```text
dapurame/
├── android/              # Konfigurasi native Android
├── ios/                  # Konfigurasi native iOS
├── assets/               # Gambar, ikon, dan font
│   ├── images/
│   └── icons/
├── lib/                  # Kode sumber utama Dart
│   ├── core/             # Konfigurasi konstanta, tema, dan utilitas
│   ├── data/             # Model data, repositori, dan API service
│   ├── presentation/     # Komponen UI (Screens & Widgets)
│   │   ├── screens/
│   │   └── widgets/
│   └── main.dart         # Titik awal (entry point) aplikasi
├── pubspec.yaml          # Pengaturan dependensi dan aset
└── README.md             # Dokumen proyek
```

---

## 🤝 Panduan Kontribusi

Kontribusi selalu terbuka dan sangat dihargai! Jika Anda ingin meningkatkan proyek ini:

1. **Fork** repositori ini.
2. Buat *feature branch* baru:
   ```bash
   git checkout -b feature/fitur-baru
   ```
3. Lakukan perubahan dan commit:
   ```bash
   git commit -m "Menambahkan fitur baru"
   ```
4. Push ke branch Anda:
   ```bash
   git push origin feature/fitur-baru
   ```
5. Buka **Pull Request** di GitHub.

---

## 📝 Lisensi

Proyek ini didistribusikan di bawah **MIT License**. Lihat file `LICENSE` untuk informasi lebih lanjut.

---

<p center="align">
  Dibuat dengan ❤️ oleh <b>Tim Dapurame</b>
</p>
