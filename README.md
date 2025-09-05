[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/cUqDT752)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=20297368&assignment_repo_type=AssignmentRepo)
# React Native Template – Praktikum PPMB
v1
# RN Template siap pakai utk tugas
## 📌 Instruksi
1. Clone repo ini
2. Install dependencies
   ```bash
   npm install
   ```
3. Jalankan aplikasi
   ```bash
   npx expo start
   ```

## 📷 Bukti Praktikum
- Tambahkan minimal **2 screenshot** hasil running app di folder `/screenshots`.

## ✅ Submission
- Push ke repo GitHub Anda
- Buka Pull Request (template akan muncul otomatis)
- Pastikan CI (lint & test) **hijau** ✅

## refleksi
Saat mengerjakan tugas Expo React Native, saya sempat mengalami kendala karena perbedaan versi antara project yang masih menggunakan SDK 52 dengan aplikasi Expo Go di Android yang sudah menggunakan SDK 53. Saya mencoba berbagai cara, termasuk meng-upgrade project ke SDK 53, namun justru muncul error merah TurboModuleRegistry,getEnforcing(...) ketika melakukan pemindaian barcode di Expo Go. Kebingungan membuat saya mencari solusi dari berbagai sumber seperti komunitas Expo, YouTube, hingga StackOverflow, dan mencoba berbagai saran yang diberikan. Setelah berjam-jam berusaha, akhirnya saya memutuskan untuk tidak melanjutkan upgrade dan memilih menurunkan versi Expo Go dari 53 ke 52. Keputusan ini akhirnya berhasil membuat project berjalan dengan baik, dan saya merasa sangat senang serta lega karena bisa menyelesaikan tugas meskipun penuh dengan tantangan.