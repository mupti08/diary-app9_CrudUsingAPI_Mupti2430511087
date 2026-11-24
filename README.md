# Praktikum Mobile Programming — Pertemuan 9 (CRUD Diary App)

Aplikasi pencatatan harian (*Diary App*) berbasis React Native (Expo Router) dan Redux Toolkit yang terintegrasi dengan REST API Node.js, Express.js, dan database MySQL.

## Identitas Mahasiswa
- **Nama:** Mupti
- **NIM:** 2430511087
- **Program Studi:** Teknik Informatika — Universitas Muhammadiyah Sukabumi
- **Mata Kuliah:** Mobile Programming (Pertemuan 9)

## Struktur Proyek
- `backend/` — Server REST API menggunakan Express.js dan MySQL (`src/server.js`, `schema.sql`, `package.json`).
- `diary-app9/` — Aplikasi mobile React Native menggunakan Expo Router, TypeScript, dan Redux Toolkit (`app/`, `src/`).

## Cara Menjalankan Aplikasi

### 1. Database MySQL
1. Aktifkan layanan MySQL Server (Laragon).
2. Jalankan query pada file `backend/schema.sql` melalui phpMyAdmin untuk membuat database `diary_app` dan tabel `diaries`.

### 2. Backend (Express.js)
```bash
cd backend
npm install
npm run dev
