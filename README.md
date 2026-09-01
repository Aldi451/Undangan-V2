# 💌 Website Undangan Pernikahan Digital

Undangan pernikahan digital berbasis *web* modern, elegan, dan interaktif dengan tema putih berornamen batik tradisional Indonesia. Dirancang ringan tanpa membutuhkan *database* server yang rumit, sehingga sangat optimal dan cepat diakses melalui perangkat seluler (*mobile-friendly*).

---

## 🌟 Fitur Lengkap Website

* **🔗 Sistem Link Tamu Dinamis (URL Parameter):** 
  Satu halaman utama dapat digunakan untuk ribuan tamu tanpa membuat file baru. Nama tamu dibaca secara otomatis langsung dari tautan (contoh: `?to=Nama+Tamu`).
* **🛠️ Halaman Generator Link Terpisah (`generator.html`):** 
  Mempermudah pengirim undangan untuk membuat dan menyalin pesan WhatsApp lengkap dengan nama dan tautan unik masing-masing tamu secara instan tanpa menghapus riwayat sebelumnya.
* **🎵 Backsound Musik Otomatis:** 
  Dilengkapi pemutar audio latar belakang yang akan mengalun lembut secara otomatis tepat setelah tamu mengklik tombol "Buka Undangan".
* **🌸 Animasi Kelopak Bunga Gugur:** 
  Efek visual visual interaktif berupa kelopak bunga bernuansa emas yang jatuh perlahan saat undangan dibuka untuk memberikan kesan romantis.
* **📖 Kisah Cinta (Love Story Timeline):** 
  Bagian lini masa vertikal yang estetik untuk merangkum perjalanan hubungan pasangan dari awal bertemu hingga menuju hari pernikahan.
* **📸 Galeri Prewedding (Our Moments):** 
  Wadah khusus untuk memajang foto-foto pra-nikah terbaik dengan bingkai kartu modern yang elegan.
* **⏳ Hitung Mundur Acara (Countdown Timer):** 
  Penghitung waktu interaktif secara *real-time* menuju hari pelaksanaan akad dan resepsi tanpa elemen detik agar tetap rapi di layar HP.
* **🎁 Amplop Digital (Wedding Gift):** 
  Fitur informasi rekening bank lengkap dengan tombol salin otomatis (*copy to clipboard*) untuk memudahkan tamu memberikan tanda kasih.
* **✉️ RSVP & Konfirmasi Kehadiran via WhatsApp:** 
  Tombol interaktif yang mengarahkan tamu secara otomatis ke aplikasi WhatsApp pengantin untuk melakukan konfirmasi kehadiran.
* **🎨 Desain Responsif & Tema Batik Eksklusif:** 
  Menggunakan latar belakang bernuansa batik tradisional khas Indonesia yang dipadukan dengan tipografi mewah bergradien warna emas.

---

## 📁 Struktur File Proyek

* `index.html` — Halaman utama undangan digital yang diakses oleh para tamu.
* `generator.html` — Alat bantu admin/pengantin untuk *generate* tautan undangan per nama tamu.
* `lagu-pernikahan.mp3` — Berkas audio latar belakang musik pernikahan.
* `foto-pria.jpg` & `foto-wanita.jpg` — Berkas foto profil calon mempelai.
* `prewed1.jpg` & `prewed2.jpg` — Berkas foto galeri pra-nikah.

---

## 🚀 Panduan Publikasi (Deployment)

1. Buat *repository* publik baru di **GitHub**.
2. Unggah seluruh file proyek (`index.html`, `generator.html`, aset foto, dan lagu `.mp3`) ke dalam *repository* tersebut.
3. Buka menu **Settings** > **Pages** di GitHub.
4. Pada bagian *Build and deployment*, ubah *Source* dari *None* menjadi cabang `main`, lalu klik **Save**.
5. Undangan digital siap diakses melalui tautan GitHub Pages yang diberikan!
