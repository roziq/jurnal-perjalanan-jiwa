# 🌿 Jurnal Perjalanan Jiwa

Aplikasi catatan harian (*mindful journaling*) dan pelacak latihan kesadaran diri yang dirancang untuk mendampingi proses transformasi dari **"Orang Lama" menjadi "Orang Baru"** berdasarkan konsep *Quantum Ikhlas* dan *Quantum Rasa*.

Aplikasi ini dibangun sebagai **Progressive Web App (PWA)** ringan berarsitektur *single-file* yang berjalan sepenuhnya di sisi klien (*client-side*), menjaga privasi data pengguna secara lokal, dan tetap berfungsi tanpa koneksi internet (*offline-first*).

---

## ✨ Fitur Utama

1. **Saklar *Think Harder* & Pemandu Koherensi Jantung (HRV)**
   * Latihan pernapasan ritmis 60 detik (tarik 5 detik – embuskan 5 detik) untuk menenangkan gelombang otak dan menyelaraskan detak jantung sebelum mengambil keputusan atau merespons situasi menekan.
2. **Penyelarasan 3R (Raga, Rasio, dan Rasa)**
   * **Raga:** Pelacak kebiasaan fisik dasar (gerak tubuh, istirahat cukup, hidrasi).
   * **Rasio:** Area fokus niat yang dilengkapi **detektor kata penghambat otomatis** (seperti kata *"tapi"*, *"susah"*, *"mustahil"*) agar kalimat niat tetap jernih dan selaras.
   * **Rasa:** Pemetaan kondisi emosional harian untuk menggeser respons dari reaktif menjadi sadar.
3. **Catatan "Ulangan" & Pemberian Makna**
   * Ruang refleksi untuk mencatat kejadian pemicu (*trigger*) sebagai bahan evaluasi pola berulang, lalu menuliskan makna baru yang lebih menenangkan dari sudut pandang hati.
4. **Ritual Sebelum Tidur & Kesadaran Bangun Pagi**
   * Pencatatan pelepasan beban pikiran sebelum tidur serta pengecekan kondisi energi saat bangun pagi.
5. **Pelacak Progres *Fermentasi Jiwa* (Siklus 40 Hari)**
   * Visualisasi konsistensi latihan kesadaran selama 40 hari beserta fitur **Ekspor & Impor JSON** untuk pencadangan (*backup*) dan pemindahan data antarperangkat.

---

## 🚀 Cara Menggunakan & Instalasi sebagai Aplikasi (PWA)

1. Buka tautan aplikasi melalui peramban (Chrome, Edge, atau Safari):  
   `https://<username-anda>.github.io/jurnal-perjalanan-jiwa/`
2. Muat halaman pertama kali dalam kondisi terhubung ke internet agar *Service Worker* menyimpan aset ke dalam *cache*.
3. **Instal ke Layar Utama:**
   * **Android (Chrome):** Ketuk menu titik tiga (`⋮`) di pojok kanan atas → pilih **Instal aplikasi** atau **Tambahkan ke Layar utama**.
   * **iOS / macOS (Safari):** Ketuk ikon **Bagikan** (*Share*) → pilih **Tambah ke Layar Utama** (*Add to Home Screen*).
   * **Desktop (Chrome / Edge):** Klik ikon **Instal** (`⊕`) di sisi kanan bilah alamat (*address bar*).

---

## 🔒 Privasi & Penyimpanan Data

* **100% Lokal (*Local-First*):** Seluruh catatan jurnal, pengaturan niat, dan progres harian disimpan secara eksklusif di dalam `localStorage` peramban perangkat Anda.
* **Tanpa Server Eksternal:** Tidak ada data pribadi yang dikirimkan, dikumpulkan, atau disimpan di server pihak ketiga mana pun.
* **Kontrol Penuh Pengguna:** Gunakan tombol **Ekspor JSON** pada tab *Fermentasi Jiwa* secara berkala untuk menyimpan salinan cadangan data Anda.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5 & Vanilla JavaScript (ES6+)** — Tanpa ketergantungan *framework* berat, cepat dimuat di berbagai spesifikasi perangkat.
* **Tailwind CSS (via CDN)** — Antarmuka bersih, responsif, dan nyaman dibaca.
* **Web Manifest & Service Worker API** — Dukungan penuh mode layar penuh (*standalone*) dan akses *offline*.

---

## 📄 Lisensi

Proyek ini dirilis di bawah lisensi [MIT License](LICENSE). Silakan digunakan, dimodifikasi, dan dikembangkan lebih lanjut untuk kebutuhan pembelajaran maupun refleksi pribadi.
