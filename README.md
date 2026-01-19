# Senyum Dental Care - Template Klinik Dokter Gigi

Template landing page klinik dokter gigi modern, responsif, dan kreatif menggunakan HTML, Tailwind CSS, dan JavaScript.

## Demo

Lihat demo langsung: [Senyum Dental Care Demo](https://demo.bitnesia.com/klinik-gigi)

## Fitur

- **Responsif** - Tampilan optimal di desktop, tablet, dan mobile
- **Modern Design** - Desain bersih dan profesional dengan warna biru segar
- **Single Page** - Navigasi smooth scroll ke semua section
- **Animasi** - Efek hover dan animasi scroll yang smooth
- **Booking Form** - Formulir booking konsultasi dengan validasi
- **Floating WhatsApp** - Button WhatsApp untuk chat langsung
- **SEO Friendly** - Struktur HTML yang baik untuk mesin pencari
- **Local Assets** - Semua aset tersimpan lokal (tidak perlu CDN eksternal)

## Struktur File

```
klinik-gigi/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   ├── style.css      # Custom CSS untuk animasi
    │   └── output.css     # Tailwind output (jika diperlukan)
    ├── js/
    │   └── main.js        # JavaScript untuk interaksi
    └── images/
        ├── hero-image.jpg
        ├── about1-4.jpg
        ├── doctor1-4.jpg
        └── avatar1-3.jpg
```

## 🎨 Kustomisasi

### Mengganti Warna
Ubah konfigurasi Tailwind di bagian `<script>` di `index.html`:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                'primary': '#00B4D8',       // Warna utama
                'primary-dark': '#0077B6',  // Warna utama gelap
                'secondary': '#90E0EF',     // Warna sekunder
                'accent': '#CAF0F8',        // Warna aksen
                'dark': '#03045E'           // Warna gelap
            }
        }
    }
}
```

### Mengganti Gambar
Replace file gambar di `assets/images/` dengan gambar baru dengan nama yang sama.

### Mengubah Informasi Kontak
Cari dan ubah teks berikut di `index.html`:
- Nama klinik
- Alamat
- Nomor telepon
- Jam operasional
- Informasi dokter

## Section yang Tersedia

1. **Navbar** - Navigation dengan logo dan menu
2. **Hero** - Section utama dengan call-to-action
3. **About** - Informasi tentang klinik
4. **Services** - Layanan yang tersedia (6 layanan)
5. **Doctors** - Tim dokter (4 dokter)
6. **Testimonials** - Testimoni pasien (3 testimoni)
7. **Contact** - Form booking dan informasi kontak
8. **Footer** - Links, jam buka, dan credit

## Dependencies

- **Tailwind CSS** - Via CDN (bisa di-install locally jika diperlukan)
- **Google Fonts** - Poppins font
- **Phosphor Icons** - Icon library
- **Unsplash** - Gambar royalty-free

