# 🎮 Modul 10 - API Game App

Aplikasi **API Game App** ini dibuat menggunakan **Flutter**, bertujuan untuk menampilkan data game dari API eksternal secara dinamis.  
Melalui modul ini, kamu akan mempelajari cara mengambil data dari **REST API**, menampilkannya di UI, serta mengelola state secara efisien.

## 📘 Tentang Proyek
**Nama Proyek:** api_game_app  
**Deskripsi:** Aplikasi untuk menampilkan daftar game menggunakan data dari API publik.  
**Framework:** Flutter  
**Bahasa:** Dart  

## 🚀 Fitur Utama
- 🔹 Menampilkan daftar game dari API (FreeToGame API)
- 🔹 Menampilkan detail game (judul, genre, platform, rating, dll)
- 🔹 Mencari game berdasarkan kata kunci
- 🔹 Menampilkan gambar (cover art) dari API
- 🔹 Menangani loading dan error state dengan elegan

## 🎯 Tujuan Pembelajaran
- Memahami cara kerja **HTTP Request** di Flutter menggunakan package `http`
- Menggunakan **FutureBuilder** untuk menampilkan data async dari API
- Mengimplementasikan **model data (JSON parsing)**
- Menerapkan **state management sederhana**
- Membuat tampilan dinamis berdasarkan data API

## 🧩 Struktur Folder
```
lib/
├── main.dart
├── model/
│ ├── detailgame.dart
│ └── game.dart
├── view/
│ ├── detail.dart
│ └── home.dart
├── viewmodel/
│ └── fetchgame.dart
```

## 🧰 Tools yang Digunakan
- Flutter SDK
- Dart
- VS Code / Android Studio
- REST API (FreeToGame API)
