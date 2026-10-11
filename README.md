# 📰 Vynz News

Website portal berita teknologi berbasis **HTML, CSS, dan JavaScript** murni (tanpa framework). Vynz News menyajikan artikel seputar teknologi, kecerdasan buatan, startup, pengembangan web, edukasi digital, dan keamanan siber, lengkap dengan mode gelap dan tampilan responsif.

> 🔗 **Demo:** _(isi dengan link GitHub Pages / hosting kamu)_

<!-- Tambahkan screenshot di sini
![Preview Vynz News](assets/preview.png)
-->

---

## ✨ Fitur

- **Dark / Light Mode**: tombol toggle, pilihan tersimpan di `localStorage` dan mengikuti preferensi sistem saat pertama kali dibuka.
- **Desain Responsif**: tampilan menyesuaikan desktop, tablet, dan mobile, dengan menu hamburger di layar kecil.
- **Halaman Kategori dengan Tab Filter**: telusuri artikel berdasarkan topik (Web Development, AI, Startup & Bisnis, Edukasi, Teknologi, Keamanan Siber).
- **Detail Berita**: 6 artikel lengkap dengan penulis, tanggal, estimasi waktu baca, kutipan, tombol bagikan, dan rekomendasi "Baca Juga".
- **Galeri Jurnalistik**: kumpulan foto bertema teknologi dalam layout grid.
- **Formulir Kontak**: validasi bawaan HTML5 dengan notifikasi saat pesan dikirim (front-end only).
- **Halaman Informasi & Legal**: Tentang Kami, Kebijakan Privasi, Syarat & Ketentuan, dan Pedoman Media Siber.
- **SEO Dasar**: meta description dan title unik di setiap halaman, `lang="id"`.

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Kegunaan |
| --- | --- |
| HTML5 | Struktur halaman & semantic markup |
| CSS3 | Styling, CSS Variables (tema), Flexbox & Grid |
| JavaScript (Vanilla) | Dark mode, menu mobile, tab kategori |
| Google Fonts | Font **Inter** & **Outfit** |
| Unsplash | Sumber gambar ilustrasi |

---

## 📁 Struktur Folder

```
vynz-news/
├── index.html
├── kategori.html
├── galeri.html
├── tentang.html
├── kontak.html
├── detail-berita-1.html
├── detail-berita-2.html
├── detail-berita-3.html
├── detail-berita-4.html
├── detail-berita-5.html
├── detail-berita-6.html
├── kebijakan-privasi.html
├── syarat-ketentuan.html
├── pedoman-media-siber.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

---

## 📄 Daftar Halaman

| Halaman | File | Deskripsi |
| --- | --- | --- |
| Beranda | `index.html` | Halaman utama berisi berita terbaru |
| Kategori | `kategori.html` | Daftar artikel per topik dengan tab filter |
| Galeri | `galeri.html` | Galeri foto jurnalistik |
| Tentang Kami | `tentang.html` | Visi, misi, dan nilai editorial |
| Kontak | `kontak.html` | Formulir kontak & info redaksi |
| Detail Berita 1–6 | `detail-berita-*.html` | Halaman artikel lengkap |
| Kebijakan Privasi | `kebijakan-privasi.html` | Kebijakan pengelolaan data pengguna |
| Syarat & Ketentuan | `syarat-ketentuan.html` | Aturan penggunaan website |
| Pedoman Media Siber | `pedoman-media-siber.html` | Pedoman pemberitaan media siber |

### 📚 Artikel

1. Masa Depan AI dalam Pengembangan Web: Otomatisasi dan Kreativitas
2. Strategi Startup Melewati Tech Winter di Asia Tenggara
3. Framework JavaScript Terbaik untuk Skalabilitas Enterprise di 2026
4. Transformasi Digital di Sektor Pendidikan: Membangun Kelas Tanpa Batas
5. Memahami Web Accessibility: Mengapa Desain Inklusif adalah Keharusan
6. Ancaman Ransomware Meningkat, Bagaimana Perusahaan Harus Bersiap?

---

## 🚀 Cara Menjalankan

Tidak perlu instalasi apa pun, cukup:

1. **Clone repository**
   ```bash
   git clone https://github.com/username/vynz-news.git
   cd vynz-news
   ```
2. **Buka `index.html`** langsung di browser, atau gunakan ekstensi **Live Server** di VS Code agar otomatis reload saat ada perubahan.

### Deploy ke GitHub Pages

1. Push project ke repository GitHub.
2. Buka **Settings → Pages**.
3. Pada **Source**, pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
4. Website akan aktif di `https://username.github.io/vynz-news/`.

---

## 🎨 Kustomisasi

- **Warna & tema**: ubah CSS Variables di `css/style.css` (variabel tema terang dan gelap diatur lewat atribut `data-theme` pada `<html>`).
- **Menambah artikel**: duplikat salah satu file `detail-berita-*.html`, ubah isinya, lalu tambahkan kartu artikel baru di `index.html` dan `kategori.html`.
- **Font**: ganti link Google Fonts di bagian `<head>` setiap halaman.

---

## 🗺️ Rencana Pengembangan

- [ ] Fitur pencarian artikel
- [ ] Integrasi formulir kontak ke backend / layanan seperti Formspree
- [ ] Pagination pada halaman kategori
- [ ] Lightbox untuk galeri
- [ ] Fungsi tombol bagikan ke media sosial

---

## 👤 Author

**Nama Kamu**
- GitHub: [@username](https://github.com/username)
- Email: email@example.com

---

## 📜 Lisensi

Project ini dibuat untuk keperluan pembelajaran. Gambar bersumber dari [Unsplash](https://unsplash.com) dan hak ciptanya dimiliki masing-masing fotografer.

Kamu bisa menambahkan lisensi sendiri (misalnya [MIT](https://choosealicense.com/licenses/mit/)) sesuai kebutuhan.
