# Wuzz Icons
A beautifully crafted, pixel-perfect open-source icon set for modern web projects.

> Satu set ikon open-source yang dibuat dengan indah dan presisi pixel untuk proyek web modern.

Wuzz Icons adalah koleksi ikon modern yang dirancang dengan fokus pada tiga hal: **kesederhanaan, konsistensi, dan performa**. Dibuat untuk para developer dan desainer, setiap ikon dirancang dengan cermat pada grid yang presisi untuk memastikan tampilan yang tajam dan konsisten di semua ukuran layar.

Proyek ini lahir dari kebutuhan akan ikon yang tidak hanya terlihat bagus, tetapi juga sangat ringan dan mudah diimplementasikan. Dengan lisensi MIT, Wuzz Icons sepenuhnya gratis untuk digunakan dalam proyek pribadi maupun komersial.

## ✨ Fitur Utama

*   **Presisi Pixel (Pixel-Perfect):** Setiap ikon dirancang dengan cermat untuk memastikan ketajaman maksimal di berbagai ukuran.
*   **Sangat Ringan:** Ukuran file yang dioptimalkan untuk memastikan website atau aplikasi Anda dimuat dengan cepat.
*   **Desain Konsisten:** Semua ikon memiliki gaya visual yang seragam, memberikan tampilan profesional pada antarmuka Anda.
*   **Mudah Digunakan:** Siap pakai melalui CDN jsDelivr, atau dapat diintegrasikan langsung ke proyek Anda sebagai font ikon atau SVG.
*   **Format Fleksibel:** Tersedia dalam format Font Ikon (.woff2, .ttf) dan SVG mentah untuk kustomisasi lebih lanjut.
*   **Open Source (Lisensi MIT):** Bebas digunakan, dimodifikasi, dan didistribusikan tanpa batasan.

---

# Panduan Penggunaan dengan CDN

Untuk memastikan performa dan kecepatan pemuatan aset yang optimal, kami sangat merekomendasikan untuk menggunakan Content Delivery Network (CDN). Panduan ini akan menunjukkan cara mengubah URL file dari repositori GitHub ke format URL CDN jsDelivr yang siap pakai.

jsDelivr adalah layanan CDN gratis, cepat, dan andal yang secara otomatis mengambil file dari repositori GitHub.

---

## Cara Mengubah URL GitHub ke CDN jsDelivr

Prosesnya sangat sederhana. Anda hanya perlu mengganti awalan URL GitHub dengan awalan URL jsDelivr.

### Struktur URL

Perhatikan pola transformasi URL berikut:

**URL Asli GitHub:**
> https://github.com/{nama_profil}/{nama_repositori}@{versi}/{path_ke_file}
**URL CDN jsDelivr:**
> https://cdn.jsdelivr.net/gh/{nama_profil}/{nama_repositori}@{versi}/{path_ke_file}
**Rincian Perubahan:**
*   Ganti `https://github.com/` dengan `https://cdn.jsdelivr.net/gh/`.
*   Bagian `gh` setelah `jsdelivr.net/` adalah singkatan dari "GitHub".
*   Sisa dari struktur URL (`/{nama_profil}/{nama_repositori}@{versi}/{path_ke_file}`) tetap sama.

---

### Contoh Praktis

Mari kita lihat contoh konversi menggunakan repositori `wuzz-icons`.

#### **1. URL Asli di Repositori GitHub**

Ini adalah tautan langsung ke file `icons.woff2` pada repositori GitHub dengan tag versi `v0.3.0`. URL ini tidak ideal untuk produksi karena tidak disajikan melalui CDN.
> https://github.com/medilana/wuzz-icons@v0.3.0/icons.woff2
#### **2. URL Setelah Dikonversi ke CDN jsDelivr**

Dengan menerapkan pola di atas, kita mendapatkan URL CDN yang sangat cepat dan di-cache secara global. Ini adalah format yang **direkomendasikan** untuk digunakan di website atau aplikasi Anda.
> https://cdn.jsdelivr.net/gh/medilana/wuzz-icons@v0.3.0/icons.woff2
### Menggunakan Versi Terbaru (Latest)

Jika Anda ingin selalu menggunakan versi terbaru dari file tanpa harus mengubah URL secara manual setiap ada rilis baru, Anda bisa menghilangkan tag versi dari URL.

**Contoh:**
> https://cdn.jsdelivr.net/gh/medilana/wuzz-icons/icons.woff2
**Peringatan:** Menggunakan versi terbaru tanpa tag spesifik dapat berisiko menyebabkan *breaking changes* pada proyek Anda ketika repositori diperbarui. Untuk penggunaan di lingkungan produksi, sangat disarankan untuk selalu **mengunci pada versi spesifik** (misalnya `@v0.3.0`).

---

Dengan mengikuti panduan ini, Anda dapat dengan mudah memanfaatkan kecepatan dan keandalan jsDelivr untuk menyajikan aset dari repositori ini.
