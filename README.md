# Atelier Curated Portfolio — Arya Danurdara, S.Kom

Website portofolio rekayasa perangkat lunak (*Software Engineering*) dan desain produk (*Product Design*) yang dibangun sesuai dengan spesifikasi desain pada folder `Tamplate Desain` (**DESIGN.md**, **code.html**, dan **screen.png**).

---

## 🎨 Karakteristik & Sistem Desain

Website ini menerapkan perpaduan **Contemporary Editorial Minimalism** dengan struktur arsitektur modular (*Architectural Grid*), memberikan impresi monograf akademik yang profesional, elegan, dan berbobot.

### 1. Palet Warna (*Harmonized Palette*)
- **Neutral Canvas (`#FBF9F5`)**: Latar belakang krem hangat (*warm alabaster*), memberikan kesan kertas monograf premium dan ramah untuk mata.
- **Primary Ink (`#0F172A`)**: Slate Navy gelap untuk tipografi utama, aturan struktural, dan tombol prioritas tertinggi.
- **Secondary Accent (`#904D00` / `#D97706`)**: Aksen Warm Amber untuk badge penanda kronologi, milestone, dan status ketersediaan.
- **Tertiary Interactive (`#4338CA`)**: Electric Indigo untuk efek fokus input formulir, interaksi aktif, dan tautan kredensial.
- **Borders & Surfaces (`#EAEDE4` / `#FFFFFF`)**: Kontur *hairline border* 1px yang presisi dan bersih tanpa bayangan berlebihan.

### 2. Triad Tipografi
1. **Newsreader** (*Display & Headlines*): Tipografi berkarakter editorial klasik berbobot akademik, diperkaya aksen miring (*italic*) pada kata hubung.
2. **Plus Jakarta Sans** (*Body & Structural UI*): Tingkat keterbacaan modern (*clean readability*) untuk deskripsi, rekam jejak, dan teks navigasi.
3. **JetBrains Mono** (*Labels, Badges, & Chronology*): Tipografi monospace untuk angka indeks, tag teknologi, tanggal, dan hash verifikasi ijazah/kredensial.

---

## 🚀 Fitur Interaktif yang Diimplementasikan

- **Navigasi Responsif & Scroll-Spy**: Indikator menu navigasi secara otomatis menyorot posisi seksi yang sedang dilihat saat pengguna menggulir (*scroll*).
- **Mobile Navigation Drawer**: Menu navigasi fleksibel untuk tampilan layar smartphone dan tablet.
- **Filter Interaktif Galeri Proyek**: Tombol filter dinamis (*Semua, Fintech, Healthtech, Point of Sale, CLI & Systems*) untuk memilah proyek karya unggulan.
- **Modal Detail Proyek**: Pratinjau lengkap arsitektur sistem, sorotan hasil, metrik penggunaan, dan tautan repositori/demo.
- **Modal Verifikasi Kredensial**: Dialog detail verifikasi sertifikat AWS, Google, Meta, dan Scrum Alliance lengkap dengan ID kredensial.
- **Salin Alamat Email Cepat**: Satu klik untuk menyalin alamat email ke clipboard dengan notifikasi toast elegan.
- **Modal Jadwalkan Diskusi 15 Menit**: Formulir interaktif untuk konsultasi arsitektur atau peluang rekayasa.
- **Modal & Unduh CV**: Pratinjau resume ATS-friendly dengan pemicu cetak / simpan dokumen PDF.
- **Image Fallback System**: Tampilan tetap rapi dan konsisten dengan placeholder berbasis gradien CSS jika koneksi internet sedang lambat atau offline.

---

## 📂 Struktur Berkas

```
portofolio/
├── index.html              # Halaman utama portofolio yang lengkap & siap pakai
├── README.md               # Dokumentasi sistem desain dan panduan penggunaan
└── Tamplate Desain/        # Aset & referensi desain awal
    ├── DESIGN.md           # Spesifikasi token, tipografi, dan panduan gaya
    ├── code.html           # Starter code referensi Tailwind
    └── screen.png          # Tangkapan layar referensi visual
```

---

## 💻 Cara Menjalankan Website

### Opsi 1: Langsung Buka di Browser (Paling Mudah)
Cukup klik dua kali (atau klik kanan > *Open with*) berkas `index.html` menggunakan Google Chrome, Microsoft Edge, Mozilla Firefox, atau browser favorit Anda.

### Opsi 2: Menggunakan Local Web Server
Jika Anda ingin menjalankannya melalui server lokal:

**Dengan Python:**
```bash
python -m http.server 3000
```
Lalu buka browser di `http://localhost:3000`.

**Dengan Node.js (npx serve):**
```bash
npx serve .
```

---

## 🛠️ Kustomisasi Konten

Anda dapat memperbarui informasi pribadi atau karya Anda dengan mengedit `index.html`:
- **Data Diri & Hero Section**: Cari bagian `<!-- SECTION 1: PERKENALAN DIRI & TENTANG -->`.
- **Riwayat Pendidikan**: Cari bagian `<!-- SECTION 2: RIWAYAT PENDIDIKAN & AKADEMIK -->`.
- **Pengalaman Kerja**: Cari bagian `<!-- SECTION 3: PENGALAMAN KERJA & MAGANG -->`.
- **Daftar Proyek & Detail Modal**: Cari objek data JavaScript `projectData` di bagian bawah untuk mengubah rincian proyek.
- **Sertifikasi**: Perbarui objek data `certData` dan elemen di `<!-- SECTION 5: SERTIFIKASI & KREDENSIAL -->`.

