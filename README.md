# UTS Pemrograman Web 2 - Eksperimen WebAssembly (Wasm)

Repositori ini dibuat untuk memenuhi tugas **Ujian Tengah Semester (UTS)** pada mata kuliah **Situs Web Pemrograman 2**. [cite_start]Proyek ini fokus pada penulisan artikel teknis dan eksperimen performa antara **WebAssembly** dan **JavaScript**. [cite: 1, 2]

---

## 📝 Informasi Mahasiswa
* **Nama:** Adellia Rezqi Salmabillah
* **NIM:** 312410395
* **Kelas:** TI.24.A4/I241D
* **Mata Kuliah:** Situs Web Pemrograman 2

---

## 🚀 Topik: WebAssembly (Wasm)
Proyek ini mengeksplorasi penggunaan WebAssembly untuk meningkatkan performa komputasi di sisi klien (browser). [cite_start]Fokus utama eksperimen adalah membandingkan kecepatan eksekusi algoritma berat (Recursive Fibonacci) antara JavaScript dan WebAssembly. [cite: 15, 20]

### 🧪 Detail Eksperimen
[cite_start]Eksperimen dilakukan dengan langkah-langkah berikut: [cite: 11, 12]
1. [cite_start]**Menulis Fungsi C++**: Membuat logika matematika berat yang memerlukan banyak iterasi. [cite: 26]
2. [cite_start]**Kompilasi**: Mengubah kode C++ menjadi format biner `.wasm`. [cite: 26]
3. [cite_start]**Pengujian**: Menjalankan fungsi di browser dan mencatat waktu eksekusi menggunakan `performance.now()`. [cite: 26, 38]

### 📊 Hasil Analisis
Berdasarkan pengujian sebanyak 5 kali, didapatkan rata-rata hasil sebagai berikut:
* **JavaScript**: ~1.262 ms
* **WebAssembly**: ~681 ms
* [cite_start]**Kesimpulan**: WebAssembly mampu berjalan **1.85x lebih cepat** dibandingkan JavaScript untuk tugas komputasi intensif. [cite: 26, 28]

---

## 🔗 Publikasi & Bukti
* [cite_start]**Link Artikel (Medium/Blog):**https://medium.com/@billahsalma50/menguji-batas-perfoma-browser-eksperimen-komputasi-berat-menggunakan-webassembly-vs-javascript-8fbec7f89b3b [cite: 33]
* [cite_start]**Hasil Pengecekan Plagiasi:** Terlampir di folder `proof/` (Skor: < 30%). [cite: 13, 14, 40]

---

## 📁 Struktur Repositori
* `src/` : Berisi source code eksperimen (C++ dan JS).
* `dist/` : Berisi file biner `.wasm` hasil kompilasi.
* `proof/` : Bukti screenshot eksperimen dan hasil cek plagiasi.
* [cite_start]`README.md` : Dokumentasi utama proyek. [cite: 22]

---

## 🛠️ Cara Menjalankan Eksperimen
1. Clone repositori ini.
2. Jalankan server lokal (misalnya menggunakan ekstensi Live Server di VS Code).
3. Buka `index.html` di browser.
4. Buka **Console (F12)** untuk melihat perbandingan waktu eksekusi secara real-time.

---
© 2026 - Adellia Rezqi Salma Billah. All Rights Reserved.







