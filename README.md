# Website HMI Komisariat Adiwangsa Cabang Jambi

Website modern dan responsif untuk HMI Komisariat Adiwangsa Cabang Jambi yang terinspirasi dari website HIMASI UNJA.

## 🌟 Fitur Utama

- **Homepage yang Menarik**: Desain modern dengan gradient colors yang eye-catching
- **Profil Organisasi**: Halaman tentang HMI dengan visi, misi, dan nilai-nilai inti
- **Struktur Organisasi**: Daftar pengurus dan 15 divisi kerja dengan deskripsi lengkap
- **Berita & Informasi**: Sistem publikasi berita dan buletin organisasi
- **Galeri Foto**: Album kegiatan dari berbagai tahun
- **Halaman Kontak**: Formulir kontak dan informasi lengkap
- **Responsive Design**: Kompatibel dengan desktop, tablet, dan mobile
- **Modern UI/UX**: Menggunakan Poppins font dan Font Awesome icons
- **Navigation Bar Sticky**: Menu yang selalu terlihat saat scroll
- **Hamburger Menu**: Menu mobile yang user-friendly

## 📁 Struktur Folder

```
hmi.website/
├── index.html
├── assets/
│   ├── css/
│   │   ├── style.css       # Stylesheet utama
│   │   └── pages.css       # Stylesheet untuk halaman internal
│   └── js/
│       └── script.js       # JavaScript untuk interaktivitas
└── pages/
    ├── tentang.html        # Tentang HMI
    ├── struktur.html       # Struktur Organisasi
    ├── berita.html         # Berita & Informasi
    ├── galeri.html         # Galeri Foto
    └── kontak.html         # Halaman Kontak
```

## 🎨 Warna & Desain

- **Primary Gradient**: #667eea (Blue) → #764ba2 (Purple)
- **Secondary Color**: #1e3c72 (Dark Blue)
- **Accent Color**: #ffd700 (Gold)
- **Background**: #f8f9fa (Light Gray)
- **Font**: Poppins (Google Fonts)

## 🔧 Teknologi yang Digunakan

- **HTML5**: Struktur semantik
- **CSS3**: Responsive Grid & Flexbox
- **JavaScript (Vanilla)**: Tanpa dependencies
- **Font Awesome 6.4**: Icon library
- **Google Fonts**: Poppins font family

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## 🚀 Cara Menggunakan

### 1. Buka Website
Buka file `index.html` di browser untuk melihat homepage.

### 2. Navigasi
- Gunakan menu navbar untuk navigasi ke halaman lain
- Klik logo untuk kembali ke homepage
- Gunakan hamburger menu di mobile untuk akses menu

### 3. Responsive Testing
- Buka DevTools (F12) di browser
- Pilih "Toggle device toolbar" untuk test di berbagai ukuran layar

## 📝 Customization

### Mengubah Informasi Kontak
Edit bagian kontak di footer atau halaman kontak:
```html
<p><i class="fas fa-phone"></i> +62 xxx-xxxx-xxxx</p>
<p><i class="fas fa-envelope"></i> info@hmi-adiwangsa.ac.id</p>
```

### Mengganti Warna
Edit variabel warna di `assets/css/style.css`:
```css
/* Primary Gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Secondary Color */
color: #1e3c72;

/* Accent */
color: #ffd700;
```

### Menambah Konten Berita
Duplikasi `.news-card` di halaman berita dan sesuaikan konten:
```html
<article class="news-card">
    <div class="news-image">
        <i class="fas fa-book"></i>
    </div>
    <div class="news-body">
        <span class="news-date">Tanggal</span>
        <h3>Judul Berita</h3>
        <p>Deskripsi singkat...</p>
        <a href="#" class="btn btn-primary">Baca Selengkapnya</a>
    </div>
</article>
```

## ✨ Fitur JavaScript

### 1. Mobile Menu Toggle
- Hamburger menu yang responsif
- Auto close saat memilih menu item

### 2. Smooth Scroll Animation
- Scroll animation untuk elemen yang muncul
- Counter animation untuk statistik

### 3. Active Navigation
- Highlight menu yang aktif sesuai halaman
- Automatic based on current URL

## 🎯 Best Practices

1. **SEO Optimization**: Setiap halaman memiliki title dan meta description yang unik
2. **Accessibility**: Menggunakan semantic HTML dan proper heading hierarchy
3. **Performance**: Minimal external dependencies, fast loading
4. **Mobile First**: Design dimulai dari mobile kemudian desktop
5. **Clean Code**: Well-organized dan mudah di-maintain

## 📞 Dukungan Kontak

Halaman kontak memiliki fitur:
- Formulir kontak interaktif
- Integrasi WhatsApp untuk langsung chat
- Social media links
- Jam operasional

## 🔐 Security Tips

1. Jangan share kontak pribadi di public repository
2. Gunakan form handler server-side untuk keamanan
3. Validate semua form input di backend
4. Gunakan HTTPS saat deploy

## 📊 Fitur Statistik

Homepage menampilkan:
- 250+ Anggota Aktif
- 15+ Divisi Kerja
- 50+ Program Tahunan
- 100% Dedikasi

## 🎬 Animasi & Interaktif

- Hover effects pada cards
- Fade-in animations saat scroll
- Smooth transitions pada tombol
- Loading effects pada counter

## 📦 Dependencies

- Font Awesome 6.4.0 (CDN)
- Google Fonts - Poppins (CDN)
- Vanilla JavaScript (No jQuery needed)

## 🔄 Browser Support

- Chrome/Edge: ✅
- Firefox: ✅
- Safari: ✅
- IE 11: ⚠️ (Limited support)

## 💡 Tips Pengembangan

1. Gunakan DevTools untuk debug CSS & JavaScript
2. Test responsiveness di berbagai device
3. Monitor performance dengan Lighthouse
4. Update konten berita secara berkala
5. Backup files sebelum membuat perubahan besar

## 📄 Lisensi

Website ini dapat digunakan untuk keperluan HMI Komisariat Adiwangsa Cabang Jambi.

---

**Dibuat dengan ❤️ untuk HMI Komisariat Adiwangsa Cabang Jambi**

Terakhir diupdate: Januari 31, 2024
