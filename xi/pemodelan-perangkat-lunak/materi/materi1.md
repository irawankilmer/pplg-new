## 📘 **Modul 1: Konsep Pemodelan & SDLC**

---

### 🎯 Tujuan Pembelajaran

Setelah mempelajari modul ini, kamu akan:

* Memahami apa itu pemodelan sistem dan mengapa penting.
* Mengetahui langkah-langkah umum dalam pengembangan perangkat lunak (SDLC).
* Mengenali berbagai metode SDLC (Waterfall, Incremental, Spiral, Agile).
* Menentukan metode mana yang cocok digunakan dalam proyekmu.

---

### 🧩 A. Mengapa Modul Ini Penting?

Bayangkan kamu ingin membuat sebuah aplikasi jual beli online (marketplace). Apa langkah pertama yang kamu ambil? Apakah langsung buka laptop dan mulai ngoding?

Kalau iya, kemungkinan besar kamu akan kebingungan di tengah jalan:

* Fitur mana yang harus dikerjakan dulu?
* Desainnya seperti apa?
* Siapa yang pakai aplikasi ini?
* Alurnya gimana?

Nah, **modul ini adalah pondasi**.
Di sini kamu akan belajar **bagaimana menyusun rencana sistem secara tertib dan logis sebelum membuat program**, mulai dari mengenal apa itu pemodelan sampai mengenal berbagai metode kerja dalam proyek perangkat lunak.

---

### 📐 B. Apa Itu Pemodelan Sistem?

Pemodelan sistem adalah **cara menggambarkan atau merancang sistem sebelum dibuat**, agar:

* Mudah dipahami semua orang,
* Bisa didiskusikan,
* Dan meminimalkan kesalahan saat pembuatan aplikasi.

> 🔍 **Analogi gampang:**
> Kamu mau bikin motor custom. Kamu pasti gambar dulu bentuknya, ukurannya, warna, dan komponennya.
> Gak mungkin langsung ambil mesin dan mulai ngelas bodi tanpa rencana, kan?

---

#### 🔧 Fungsi Pemodelan Sistem

1. **Memudahkan komunikasi antar tim (developer, klien, tester).**
2. **Menjadi panduan saat membangun aplikasi.**
3. **Mendeteksi kesalahan sejak awal sebelum keluar biaya besar.**

---

### 🔁 C. Apa Itu SDLC?

**SDLC (Software Development Life Cycle)** adalah urutan langkah-langkah yang digunakan untuk mengembangkan sistem perangkat lunak.

---

#### 🧭 6 Tahapan Umum SDLC:

| Tahap                        | Penjelasan                                      |
| ---------------------------- | ----------------------------------------------- |
| 1. **Perencanaan**           | Menentukan tujuan proyek.                       |
| 2. **Analisis Kebutuhan**    | Mengumpulkan apa yang dibutuhkan pengguna.      |
| 3. **Perancangan (Desain)**  | Membuat model: use case, ERD, UI mockup, dll.   |
| 4. **Implementasi (Coding)** | Mulai membuat program sesuai model.             |
| 5. **Pengujian (Testing)**   | Mengecek apakah sistem berjalan sesuai harapan. |
| 6. **Pemeliharaan**          | Memperbaiki bug dan memperbarui sistem.         |

> 📌 **Catatan penting:** Di tahap desain inilah semua **pemodelan sistem** terjadi.

---

### 🚧 D. Metode SDLC: Gaya Kerja dalam Proyek

Ada banyak "gaya" dalam menerapkan SDLC. Kita bahas 4 metode yang paling umum.

---

#### 1. **Waterfall (Air Terjun)**

Langkah-langkah SDLC dikerjakan secara berurutan, satu tahap selesai baru lanjut ke tahap berikutnya.

🟩 **Cocok Jika:**

* Proyek kecil, kebutuhan sudah jelas sejak awal.
* Tidak banyak perubahan selama proses.

🔻 **Kelemahan:**

* Sulit mundur ke tahap sebelumnya kalau ada kesalahan.
* Tidak fleksibel terhadap perubahan.

---

#### 2. **Incremental**

Aplikasi dibangun secara bertahap per bagian. Misalnya: minggu ini buat login, minggu depan katalog, lalu checkout.

🟦 **Cocok Jika:**

* Ingin punya sistem awal yang bisa langsung dipakai meski belum lengkap.
* Bisa menyelesaikan proyek sambil mengembangkan lebih lanjut.

🔻 **Kelemahan:**

* Desain awal harus cukup kuat untuk mendukung penambahan.
* Bisa jadi tidak konsisten antar bagian jika kurang direncanakan.

---

#### 3. **Spiral**

Menggabungkan unsur desain berulang (iterasi) dan penilaian risiko. Fokus pada evaluasi tiap tahap.

🟨 **Cocok Jika:**

* Proyek kompleks, melibatkan risiko tinggi.
* Perlu banyak percobaan dan pengujian desain.

🔻 **Kelemahan:**

* Rumit dan mahal untuk proyek kecil.
* Butuh tim yang berpengalaman.

---

#### 4. **Agile**

Proyek dibagi menjadi sprint (1–2 minggu), tim membuat bagian kecil sistem secara cepat dan terus dievaluasi.

🟥 **Cocok Jika:**

* Kebutuhan sering berubah.
* Tim bisa komunikasi cepat dan kerja bareng.

🔻 **Kelemahan:**

* Butuh disiplin dan koordinasi tinggi.
* Tidak cocok jika klien ingin semua terstruktur dari awal.

---

### 🧾 Tabel Perbandingan Singkat

| Metode      | Cocok Untuk                 | Kelebihan                        | Kekurangan                 |
| ----------- | --------------------------- | -------------------------------- | -------------------------- |
| Waterfall   | Proyek kecil, stabil        | Rapi, terstruktur                | Tidak fleksibel            |
| Incremental | Proyek bertahap             | Bisa dipakai sambil dikembangkan | Bisa tidak konsisten       |
| Spiral      | Proyek besar & kompleks     | Minim risiko                     | Mahal dan rumit            |
| Agile       | Proyek dinamis, kolaboratif | Fleksibel, cepat adaptasi        | Butuh tim solid & disiplin |

---

### 📦 E. Studi Kasus Mini: Marketplace Kelas

> **Proyek:** Tim kalian ingin membuat aplikasi marketplace sekolah (jual beli barang siswa).

Bagaimana SDLC bisa diterapkan?

| Tahap           | Contoh Aplikasi Marketplace                                       |
| --------------- | ----------------------------------------------------------------- |
| 1. Perencanaan  | Mau ada katalog produk dan fitur bayar.                           |
| 2. Analisis     | Siswa bisa jual & beli, harus ada sistem login, notifikasi order. |
| 3. Desain       | Buat use case, class diagram, ERD, UI mockup.                     |
| 4. Implementasi | Coding halaman login, katalog, keranjang.                         |
| 5. Pengujian    | Uji alur beli & bayar. Cek validasi dan error.                    |
| 6. Pemeliharaan | Tambah fitur tracking atau rating.                                |

Kamu bisa pilih metode:

* **Waterfall** jika kamu yakin desainnya sudah final.
* **Incremental** kalau kamu ingin pelan-pelan membangun.
* **Agile** kalau timmu fleksibel dan suka kerja dinamis.

---

### 📝 Latihan

1. Jelaskan dengan bahasa sendiri apa itu **pemodelan sistem**.
2. Bandingkan metode **Waterfall vs Agile**: kapan kamu pakai salah satu?
3. Pilih 1 metode SDLC yang kamu sukai. Ceritakan kenapa kamu memilih itu.

---

### 🧠 Refleksi

Diskusi ringan:

> “Kalian lebih suka kerja rapi dari awal, atau suka nyoba-nyoba sambil jalan?”

Simulasi kecil: 

siswa dibagi jadi 4 kelompok, masing-masing merancang sistem sederhana dengan pendekatan SDLC yang berbeda.

Lalu presentasi dan bandingkan pendekatan tiap kelompok.

---

### 📌 Catatan Akhir

* Modul ini adalah fondasi sebelum masuk ke **analisis kebutuhan dan pemodelan diagram**.
* Pastikan kalian **memahami peran setiap tahap SDLC**, karena ini akan terus digunakan di proyek semester genap nanti.
