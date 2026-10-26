# Praktikum Desain Web – Pertemuan 6: Mockup Halaman Web

Tugas pengembangan **Contoh 1** (halaman Program Studi Teknik Informatika) menjadi wireframe dan mockup high fidelity, dalam versi desktop dan mobile.

| | |
|---|---|
| **Nama** | _(Larasati Dewi)_ |
| **NIM** | _(4525210037)_ |
| **Kelas** | _(A)_ |
| **Mata Kuliah** | Desain Web |
| **Pertemuan** | 6 – Mockup Halaman Web |

---

## Deskripsi

Halaman ini adalah landing page Program Studi Teknik Informatika (Universitas ABC). Desain dikembangkan dari Contoh 1 pada modul, dengan tambahan section dan penyesuaian tampilan mobile. Hasilnya dibuat dalam dua tahap:

1. **Wireframe**: kerangka tata letak berwarna abu-abu, tanpa warna dan gaya visual.
2. **Mockup high fidelity**: tampilan akhir dengan palet warna, tipografi, tombol, dan card.

## Daftar File

| File | Isi |
|---|---|
| `wireframe-desktop.html` / `.pdf` | Wireframe desktop (lebar 1180px) |
| `mockup-desktop.html` / `.pdf` | Mockup desktop high fidelity |
| `wireframe-mobile.html` / `.pdf` | Wireframe mobile (lebar 390px) |
| `mockup-mobile.html` / `.pdf` | Mockup mobile high fidelity |
| `README.md` | Dokumentasi tugas ini |

## Struktur Folder

```
desain-web/
└── pertemuan-06/
    ├── README.md
    ├── wireframe-desktop.pdf
    ├── mockup-desktop.pdf
    ├── wireframe-mobile.pdf
    ├── mockup-mobile.pdf
    └── dokumentasi/
```

## Struktur Halaman

| No | Section | Keterangan |
|---|---|---|
| 1 | Header | Logo, nama prodi, menu navigasi, tombol "Daftar" |
| 2 | Hero | Judul, deskripsi, dua tombol aksi, dan visual utama |
| 3 | Statistik | **Baru.** Mahasiswa, dosen, mitra industri, akreditasi |
| 4 | Tentang | Tiga feature card: Web, Software, Data |
| 5 | Fasilitas | Tiga facility card |
| 6 | Prospek Karier | **Baru.** Empat profesi lulusan |
| 7 | Call to Action | Ajakan menghubungi prodi |
| 8 | Footer | **Dikembangkan** menjadi tiga kolom: profil, menu, kontak |

## Design System

### Warna

| Token | Hex | Fungsi |
|---|---|---|
| `--primary` | `#173f73` | Tombol utama, logo, section CTA |
| `--primary-dark` | `#0f2d54` | Hover tombol, footer |
| `--accent` | `#e7a72d` | Tombol aksen, angka statistik, label di atas latar gelap |
| `--neutral-50` | `#f8f9fb` | Latar section terang |
| `--neutral-100` | `#eef1f5` | Garis pemisah dan border card |
| `--neutral-300` | `#ccd3dc` | Border tombol sekunder |
| `--neutral-600` | `#606b7a` | Teks paragraf |
| `--neutral-900` | `#202833` | Teks utama |

### Tipografi (type scale)

Font: Arial, Helvetica, sans-serif.

| Elemen | Desktop | Mobile |
|---|---|---|
| H1 | 52px | 32px |
| H2 | 36px | 26px |
| H3 | 21px | 18px |
| Paragraf | 16–18px | 14–16px |
| Label | 13px, bold, letter-spacing 1.5px | sama |

### Tombol

| Gaya | Penggunaan |
|---|---|
| Primary (biru) | Aksi utama: "Pelajari Program", "Daftar" |
| Secondary (outline abu-abu) | Aksi pendukung: "Hubungi Kami" di hero |
| Accent (kuning) | Aksi di atas latar biru (section CTA) |

### Card

- **Feature card:** ikon di dalam kotak, judul, dan deskripsi. Radius 12px, shadow ringan.
- **Facility card:** area gambar di atas dan teks di bawah. Radius 12px dengan `overflow: hidden`.

### Radius, shadow, dan spacing

- Radius: 6px, 12px, 20px
- Shadow: `0 4px 10px rgba(0,0,0,.08)` dan `0 10px 30px rgba(0,0,0,.12)`
- Spacing: kelipatan 8px (8, 16, 24, 32, 48, 64)

## Perbedaan Desktop dan Mobile

| Aspek | Desktop | Mobile |
|---|---|---|
| Navigasi | Menu horizontal | Ikon hamburger |
| Hero | Dua kolom (teks dan gambar) | Satu kolom, tombol penuh lebar |
| Statistik | 4 kolom | 2 × 2 |
| Tentang | 3 kolom | Ditumpuk 1 kolom |
| Fasilitas | 3 kolom | Geser horizontal (scroll snap) |
| Karier | 4 kolom | 2 kolom |
| CTA | Teks dan tombol sejajar | Ditumpuk, tombol penuh lebar |
| Footer | 3 kolom | 1 kolom |
| Tambahan | – | Tombol "Daftar Sekarang" menempel di bawah layar |

## Cara Melihat

1. Buka file `.pdf` untuk melihat hasil akhir.

## Catatan

- Seluruh isi (nama kampus, angka statistik, dan kontak) adalah data contoh.
- Desain berpedoman pada design tokens dari Contoh 1 pada modul Pertemuan 6.
