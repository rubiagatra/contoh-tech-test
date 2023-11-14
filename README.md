# Take Home Test: Pengembangan Aplikasi Web dengan Golang dan Microservices

## Deskripsi Test
- **Judul**: Pengembangan Aplikasi Web dengan Golang dan Microservices
- **Durasi**: 3 hari
- **Tujuan**: Menguji kemampuan kandidat dalam mengembangkan aplikasi web kompleks menggunakan Golang, fokus pada microservices, database, dan autentikasi.

## Persyaratan
- Menggunakan bahasa pemrograman Go.
- Implementasi arsitektur microservices.
- Menggunakan PostgreSQL atau MongoDB untuk database.
- Autentikasi dan otorisasi pengguna.
- Penggunaan Docker dan Kubernetes/Docker Compose untuk deployment.
- Pengujian unit dan integrasi.

## Tugas
- **Membangun Aplikasi Web dengan Microservices**:
  - **Service 1**: Autentikasi dan Manajemen Pengguna.
  - **Service 2**: Manajemen Konten (misal: artikel, komentar).
  - **Service 3**: Dashboard Administrasi (statistik, pengguna aktif, konten populer).
- Komunikasi antar-service (misal, dengan gRPC atau REST API).
- Frontend Sederhana (opsional): HTML/CSS/JavaScript untuk interaksi dengan backend.
- **Dokumentasi**: Mendokumentasikan arsitektur sistem, cara penggunaan API, dan setup project.

## Kriteria Penilaian
- **Arsitektur dan Desain Sistem**: Efisiensi dan kejelasan arsitektur microservices.
- **Kualitas Kode**: Struktur, modularitas, dan efisiensi kode.
- **Database Design**: Efektivitas desain skema dan query.
- **Keamanan**: Implementasi autentikasi dan otorisasi.
- **Dokumentasi**: Kelengkapan dan kejelasan dokumentasi.
- **Pengujian**: Kualitas dan kelengkapan pengujian unit dan integrasi.
- **Containerisasi dan Deployment**: Penggunaan Docker dan Kubernetes/Docker Compose.

## Pengiriman Hasil
- Kode sumber di repository Git dengan README yang mendetail.
- Instruksi untuk menjalankan aplikasi dan layanan secara lokal.
- Dokumentasi API dan arsitektur sistem.

## Feedback
- Berikan umpan balik yang konstruktif tentang desain sistem, kualitas kode, dan pendekatan yang digunakan.

# Whiteboard Interview Test: Problem Solving dan Pemrograman

## Deskripsi Test
- **Tujuan**: Mengukur kemampuan problem solving, pemahaman algoritma, dan dasar-dasar pemrograman kandidat.
- **Format**: Kandidat diminta untuk menulis dan menjelaskan solusi mereka di whiteboard.
- **Durasi**: Setiap soal diberikan 20-30 menit untuk diskusi dan penyelesaian.

## Soal

### Soal 1: Reverse a String
- **Deskripsi**: Tuliskan fungsi untuk membalikkan string. Misalnya, input 'hello' harus menghasilkan output 'olleh'.
- **Fokus**: Pemahaman string dan array, loop.

### Soal 2: FizzBuzz
- **Deskripsi**: Untuk bilangan 1 sampai 100, cetak 'Fizz' jika bilangan tersebut habis dibagi 3, 'Buzz' jika habis dibagi 5, dan 'FizzBuzz' jika habis dibagi baik 3 maupun 5. Jika tidak memenuhi kondisi tersebut, cetak bilangannya.
- **Fokus**: Logika kondisional, loop.

### Soal 3: Cari Bilangan Terbesar dalam Array
- **Deskripsi**: Diberikan sebuah array bilangan, tuliskan fungsi untuk menemukan bilangan terbesar dalam array tersebut.
- **Fokus**: Pemahaman array, penggunaan loop, dan pemilihan kondisional.

### Soal 4: Fibonacci Series
- **Deskripsi**: Tuliskan fungsi yang menghasilkan n bilangan pertama dalam seri Fibonacci.
- **Fokus**: Pemahaman rekursi dan/atau iterasi.

### Soal 5: Deteksi Palindrom
- **Deskripsi**: Tuliskan fungsi yang menentukan apakah sebuah string adalah palindrom (membaca sama dari depan atau belakang).
- **Fokus**: Pemahaman string, loop, dan logika kondisional.

## Kriteria Penilaian
- **Kemampuan Analisis**: Pemahaman soal dan pendekatan pemecahan masalah.
- **Kualitas Kode**: Efisiensi, kejelasan, dan struktur kode.
- **Pemahaman Konsep Dasar**: Loops, kondisional, array, string, dll.
- **Komunikasi**: Kemampuan menjelaskan proses pemikiran dan solusi.

# Whiteboard Interview Test: System Design

## Deskripsi Test
- **Tujuan**: Mengukur pemahaman kandidat tentang desain dan arsitektur sistem skala besar.
- **Format**: Kandidat diminta untuk mendesain sistem pada whiteboard sambil menjelaskan pilihan dan pendekatan mereka.
- **Durasi**: 45-60 menit per soal.

## Soal

### Soal 1: Desain Sistem Pemesanan Tiket Online
- **Deskripsi**: Desain sistem pemesanan tiket online untuk bioskop. Sistem harus dapat menangani pemesanan simultan, pemilihan kursi, dan pembatalan tiket.
- **Fokus**: Database design, concurrency, handling transactional data.

### Soal 2: Desain Sistem Media Sosial Skala Besar
- **Deskripsi**: Desain arsitektur backend untuk sebuah platform media sosial dengan jutaan pengguna aktif. Fokus pada skalabilitas, distribusi data, dan caching.
- **Fokus**: Microservices architecture, database scalability, caching mechanisms.

### Soal 3: Desain Sistem Monitoring dan Logging untuk Cloud Infrastructure
- **Deskripsi**: Desain sistem monitoring dan logging untuk infrastruktur cloud yang menangani berbagai aplikasi dan layanan.
- **Fokus**: Data aggregation, real-time analysis, storage solutions.

### Soal 4: Desain API Gateway untuk Microservices
- **Deskripsi**: Desain API Gateway yang akan bertindak sebagai single entry point untuk serangkaian microservices.
- **Fokus**: API routing, load balancing, security, rate limiting.

### Soal 5: Desain Sistem Rekomendasi
- **Deskripsi**: Desain sistem rekomendasi yang dapat memberikan saran produk atau konten kepada pengguna berdasarkan perilaku dan preferensi mereka.
- **Fokus**: Data mining, machine learning integration, user profiling.

## Kriteria Penilaian
- **Pemahaman Konsep Arsitektur**: Kemampuan mengidentifikasi komponen sistem dan bagaimana mereka berinteraksi.
- **Skalabilitas dan Performa**: Pendekatan untuk menangani pertumbuhan pengguna dan data.
- **Keandalan dan Kesalahan Toleran**: Strategi untuk menangani kegagalan dan memastikan ketersediaan.
- **Keamanan**: Pertimbangan keamanan dalam desain.
- **Komunikasi**: Kemampuan untuk menjelaskan desain dan pilihan teknis secara efektif.

# Pair Programming Interview Test

## Deskripsi Test
- **Tujuan**: Mengukur kemampuan kandidat untuk berkolaborasi, berkomunikasi, dan menulis kode secara efisien dalam setting pair programming.
- **Format**: Dua programmer (satu pewawancara dan satu kandidat) bekerja bersama untuk menyelesaikan serangkaian tugas pemrograman.
- **Durasi**: 60-90 menit.

## Persiapan
- Siapkan sebuah lingkungan pengembangan dengan alat-alat yang diperlukan (IDE, akses ke repository, dokumentasi).
- Tentukan bahasa pemrograman dan teknologi yang akan digunakan berdasarkan persyaratan pekerjaan.
- Siapkan daftar tugas dan soal yang akan dikerjakan.

## Skenario Test

### Skenario 1: Refactoring Kode
- **Deskripsi**: Refactor sebuah blok kode yang telah ditulis sebelumnya untuk meningkatkan efisiensi dan keterbacaan.
- **Fokus**: Kualitas kode, pemahaman clean code, dan best practices.

```javascript
function processItems(items) {
    var result = [];
    for (var i = 0; i < items.length; i++) {
        if (items[i].isActive) {
            result.push(items[i].name.toUpperCase());
        }
    }
    return result;
}
```

### Skenario 2: Menambahkan Fitur Baru
- **Deskripsi**: Menambahkan fitur baru ke dalam aplikasi atau sistem yang sudah ada.
- **Fokus**: Kemampuan untuk memahami basis kode yang ada, integrasi fitur, dan testing.

```javascript
function getUser(id) {
    return database.findUserById(id); // database.findUserById adalah fungsi fiktif
}
```

### Skenario 3: Debugging dan Penyelesaian Masalah
- **Deskripsi**: Identifikasi dan perbaiki bugs dalam sebuah aplikasi atau sistem.
- **Fokus**: Kemampuan analisis, debugging, dan pemecahan masalah.
 
```javascript
function mergeArrays(arr1, arr2) {
    let merged = [];
    for (let i = 0; i < arr1.length; i++) {
        merged.push(arr1[i]);
    }
    for (let j = 0; i < arr2.length; j++) { // Notice the wrong usage of 'i' instead of 'j'
        merged.push(arr2[j]);
    }
    return merged;
}
```

### Skenario 4: Desain Algoritma
- **Deskripsi**: Kembangkan dan implementasikan algoritma untuk menyelesaikan masalah pemrograman tertentu.
- **Fokus**: Pemahaman algoritma, efisiensi kode, dan logika pemrograman.

### Skenario 5: Review Kode
- **Deskripsi**: Melakukan code review terhadap potongan kode yang ditulis oleh orang lain.
- **Fokus**: Pemahaman best practices, komunikasi feedback, dan kemampuan kolaboratif.

## Kriteria Penilaian
- **Kolaborasi**: Kemampuan bekerja dengan orang lain dan berbagi tanggung jawab.
- **Komunikasi**: Kejelasan dalam menyampaikan ide dan menerima masukan.
- **Kode**: Kualitas, keefektifan, dan kebersihan kode yang ditulis.
- **Problem Solving**: Pendekatan dan efektivitas dalam pemecahan masalah.
- **Adaptasi**: Kemampuan untuk cepat beradaptasi dengan kode dan ide baru.

## Catatan untuk Pewawancara
- Selama sesi, bergantian peran antara 'driver' yang menulis kode dan 'navigator' yang memberikan arahan.
- Pastikan untuk memberi kandidat kesempatan untuk berperan sebagai kedua-duanya.
- Berikan masukan konstruktif dan dorongan sepanjang sesi.

