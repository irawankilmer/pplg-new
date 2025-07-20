## 📘 **Modul 2: Analisis Kebutuhan Sistem**

---

### 🎯 Tujuan Pembelajaran

Setelah mempelajari modul ini, kamu akan bisa:

* Menjelaskan apa itu kebutuhan sistem: fungsional dan non-fungsional.
* Menyusun kebutuhan sistem dari studi kasus marketplace sekolah.
* Menentukan kebutuhan berdasarkan hasil wawancara, observasi, atau kuesioner.
* Menganalisis kebutuhan pengguna (user) dengan pendekatan alami, bukan hanya teknis.

---

### 📍 A. Kenapa Harus Menganalisis Kebutuhan?

> **Pertanyaan sederhana:**
> "Kalau kamu diminta buat aplikasi, kamu tau harus bikin apa aja?"

Mungkin banyak dari kalin langsung jawab:

* “Ya bikin fitur login.”
* “Fitur beli barang.”
* “Bisa bayar pakai e-wallet.”

Tapi… pertanyaan yang benar seharusnya bukan **"fitur apa yang mau kamu buat?"**, tapi **"masalah apa yang mau kamu selesaikan?"**

> 🔍 **Contoh Kasus:**
> Di sekolah kita, banyak siswa jualan lewat IG/WA. Tapi sering terjadi:
>
> * Barang udah dibeli, tapi gak dikirim.
> * Temanmu udah bayar, tapi gak ada sistem bukti pembayaran.
> * Siswa bingung cari barang atau toko terpercaya.

Nah! Di sinilah **analisis kebutuhan sistem** dibutuhkan. Kita tidak boleh langsung membuat fitur — kita harus tahu **apa yang dibutuhkan pengguna** agar sistemnya benar-benar berguna.

---

### 📖 B. Apa Itu Kebutuhan Sistem?

Dalam dunia rekayasa perangkat lunak, **kebutuhan sistem** dibagi menjadi dua:

---

#### 1. **Kebutuhan Fungsional**

Ini adalah **apa saja yang sistem *harus bisa lakukan*.**
Bisa dilihat sebagai *fitur* atau *fungsi utama sistem*.

> Contoh:
>
> * Sistem harus menyediakan fitur login.
> * Pengguna bisa menambahkan produk ke keranjang.
> * Admin bisa mengelola data pengguna.

**Sederhananya:** ini adalah **apa yang terjadi ketika tombol diklik.**

---

#### 2. **Kebutuhan Non-Fungsional**

Ini adalah hal-hal yang tidak berhubungan langsung dengan aksi pengguna, tapi penting dalam kualitas sistem.

> Contoh:
>
> * Sistem bisa diakses dari HP dan laptop (responsif).
> * Waktu loading halaman maksimal 3 detik.
> * Data pengguna disimpan dengan aman (enkripsi).
> * Aplikasi tersedia 24 jam tanpa error.

**Sederhananya:** ini adalah **syarat "gak kelihatan" tapi sangat penting.**

---

### 🧰 C. Teknik Mengumpulkan Kebutuhan

Kamu gak bisa menebak-nebak kebutuhan.
Kamu harus **mengumpulkan data langsung dari pengguna / klien**. Ada beberapa cara:

---

#### 1. **Wawancara**

> Bertanya langsung ke calon pengguna:
> “Apa masalahmu sekarang?”
> “Kalau ada aplikasi, kamu pengin fitur apa?”

🟩 Cocok untuk:

* Proyek kecil.
* Sistem yang dibuat untuk klien tertentu (misalnya koperasi sekolah).

---

#### 2. **Observasi**

> Kamu melihat langsung cara kerja mereka sekarang.
> Contoh: kamu lihat anak-anak antri beli barang di koperasi → kamu tahu mereka butuh sistem order online.

🟦 Cocok untuk:

* Menemukan masalah yang tidak disadari pengguna.
* Proyek berbasis kebiasaan nyata.

---

#### 3. **Kuesioner**

> Kamu buat pertanyaan tertulis yang disebar ke banyak pengguna.
> “Menurut kamu, fitur apa yang paling penting?”
> “Seberapa sering kamu belanja di sekolah?”

🟨 Cocok untuk:

* Jumlah responden besar.
* Analisis kebutuhan sistem yang melibatkan banyak siswa/guru.

---

#### 4. **Studi Dokumen**

> Kamu mempelajari dokumen lama atau sistem sebelumnya.
> Misalnya: catatan penjualan koperasi manual, file Excel, buku nota.

🟥 Cocok untuk:

* Sistem yang menggantikan sistem lama.
* Mengetahui alur bisnis yang sudah berjalan.

---

### 📦 D. Studi Kasus: Analisis Kebutuhan Marketplace Sekolah

---

**Konteks Proyek:**
Aplikasi marketplace sekolah untuk siswa jual beli online.

---

#### 📝 Contoh Kebutuhan Fungsional(F):

| Kode | Deskripsi                                                         |
| ---- | ----------------------------------------------------------------- |
| F1   | Siswa dapat mendaftar dan login.                                  |
| F2   | Penjual dapat menambahkan produk.                                 |
| F3   | Pembeli dapat menambahkan barang ke keranjang.                    |
| F4   | Pembeli dapat melakukan checkout dan mengunggah bukti pembayaran. |
| F5   | Sistem mengirim notifikasi ke penjual.                            |
| F6   | Admin dapat mengelola pengguna dan transaksi.                     |

---

#### 🔐 Contoh Kebutuhan Non-Fungsional(NF):

| Kode | Deskripsi                                     |
| ---- | --------------------------------------------- |
| NF1  | Sistem dapat diakses 24 jam.                  |
| NF2  | Waktu respons halaman kurang dari 3 detik.    |
| NF3  | Data pengguna dienkripsi.                     |
| NF4  | Tampilan mendukung mobile dan desktop.        |
| NF5  | Tidak ada bug fatal saat transaksi dilakukan. |

---

#### 📊 Contoh Teknik Pengumpulan Data yang Digunakan:

| Teknik        | Contoh Praktis di Sekolah                                   |
| ------------- | ----------------------------------------------------------- |
| Wawancara     | Tanya ke teman yang sering jualan: “Apa kendalanya?”        |
| Observasi     | Lihat proses jual beli manual di koperasi / grup WA.        |
| Kuesioner     | Sebar Google Form ke siswa: “Fitur apa yang kamu butuhkan?” |
| Studi Dokumen | Minta file Excel penjualan koperasi.                        |

---

### 📝 Latihan Mandiri

1. Buat 5 contoh kebutuhan fungsional dan 3 non-fungsional dari aplikasi "Kantin Online".
2. Cari 1 teman yang sering jualan atau beli barang di sekolah, dan wawancarai 5 menit. Catat 3 kebutuhannya.
3. Coba pikirkan: fitur apa yang menurutmu penting tapi *gak keliatan*? (non-fungsional)

---

### 🎙️ Refleksi

**latihan wawancara langsung**.

Simulasi:

* 1 siswa sebagai "klien" (penjual di sekolah),
* 2 siswa lain sebagai "tim pengembang".
  
Dengan latihan ini diharapkan kalian bisa berpikir seperti profesional.

> “Jangan langsung ngoding. Tanyakan dulu: sebenarnya yang dibutuhkan itu apa?”

Susun daftar kebutuhan sistem kalian, lalu dipresentasikan dan direvisi bersama.

---

### 📌 Penutup

* **Jangan pernah menebak-nebak fitur.**
* Semua sistem yang baik dimulai dari **analisis kebutuhan yang tepat**.
* Kalau kamu salah dari awal, semua diagram setelah ini juga akan ikut salah.

Modul berikutnya kita akan belajar **mengubah kebutuhan tadi menjadi model visual** — mulai dari **Use Case Diagram**.

---
