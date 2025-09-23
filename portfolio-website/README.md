# Portfolio Website

Website portofolio profesional yang modern dan interaktif, dibangun dengan HTML5, CSS3, dan JavaScript vanilla.

## ✨ Fitur Utama

- **Design Responsif**: Tampil sempurna di semua perangkat (desktop, tablet, mobile)
- **Theme Toggle**: Mode terang dan gelap
- **Animasi Smooth**: Animasi scroll dan hover yang halus
- **Loading Screen**: Loading screen yang menarik
- **Navigation Interaktif**: Navbar dengan smooth scrolling
- **Filter Projects**: Filter proyek berdasarkan kategori
- **Contact Form**: Form kontak dengan validasi
- **Skill Progress**: Animasi progress bar untuk skills
- **Counter Animation**: Animasi counter untuk statistik
- **SEO Optimized**: Meta tags yang lengkap
- **Accessibility**: Mendukung keyboard navigation

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Struktur semantic dan modern
- **CSS3**: Grid, Flexbox, Custom Properties, Animations
- **JavaScript ES6+**: Interactive features dan DOM manipulation
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter)
- **AOS Library**: Scroll animations

## 📁 Struktur Folder

```
portfolio-website/
├── index.html          # File HTML utama
├── css/
│   └── style.css       # File CSS utama
├── js/
│   └── script.js       # File JavaScript utama
├── images/             # Folder untuk gambar
└── README.md           # Dokumentasi
```

## 🚀 Cara Menggunakan

### 1. Buka Website
Buka file `index.html` di browser Anda, atau gunakan Live Server di VS Code.

### 2. Kustomisasi Konten

#### Informasi Pribadi
Edit bagian berikut di `index.html`:

```html
<!-- Hero Section -->
<span class="name">Your Name</span>
<span class="role">Full Stack Developer</span>

<!-- About Section -->
<h3>Who Am I?</h3>
<p>I'm a passionate Full Stack Developer...</p>

<!-- Contact Section -->
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="tel:+1234567890">+1 (234) 567-890</a>
<span class="contact-value">Your City, Country</span>
```

#### Proyek
Ganti placeholder proyek dengan proyek Anda sendiri:

```html
<div class="project-card" data-category="web">
    <div class="project-image">
        <!-- Ganti dengan gambar proyek Anda -->
        <img src="images/project1.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Deskripsi proyek Anda</p>
        <!-- Update technology tags -->
        <div class="project-tech">
            <span class="tech-tag">React</span>
            <span class="tech-tag">Node.js</span>
        </div>
    </div>
</div>
```

#### Skills
Update skills dan persentase di bagian skills:

```html
<div class="skill-progress" data-width="95%"></div>
```

#### Experience
Edit timeline experience dengan pengalaman Anda:

```html
<div class="timeline-content">
    <div class="timeline-header">
        <h3>Your Job Title</h3>
        <span class="timeline-company">Company Name</span>
        <span class="timeline-date">2022 - Present</span>
    </div>
    <p class="timeline-description">
        Deskripsi pekerjaan dan pencapaian Anda
    </p>
</div>
```

### 3. Ganti Gambar
- Tambahkan foto profil Anda di `images/profile.jpg`
- Tambahkan screenshot proyek di folder `images/`
- Update referensi gambar di HTML

### 4. Kustomisasi Warna
Edit CSS variables di `css/style.css`:

```css
:root {
    --primary-color: #6366f1;        /* Warna utama */
    --primary-dark: #4f46e5;         /* Warna utama gelap */
    --primary-light: #8b5cf6;        /* Warna utama terang */
    --secondary-color: #f59e0b;      /* Warna sekunder */
    --accent-color: #06b6d4;         /* Warna aksen */
}
```

### 5. Social Media Links
Update link social media di footer dan contact section:

```html
<a href="https://linkedin.com/in/yourprofile" class="social-link">
    <i class="fab fa-linkedin"></i>
</a>
<a href="https://github.com/yourusername" class="social-link">
    <i class="fab fa-github"></i>
</a>
```

## 🎨 Kustomisasi Advanced

### Mengubah Font
```css
:root {
    --font-family: 'Your Font', sans-serif;
}
```

Jangan lupa tambahkan link font di HTML:
```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Menambah Section Baru
1. Tambahkan HTML section
2. Tambahkan link di navigation
3. Tambahkan CSS styling
4. Update JavaScript untuk scroll behavior

### Form Integration
Untuk mengintegrasikan form dengan backend:

```javascript
// Di script.js, ganti bagian form submission
// dengan endpoint API Anda
fetch('/api/contact', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify(data)
})
```

## 📱 Responsif Design

Website ini menggunakan mobile-first approach dengan breakpoints:
- Mobile: < 768px
- Tablet: 768px - 1024px  
- Desktop: > 1024px

## 🔧 Troubleshooting

### Animasi tidak berjalan
Pastikan library AOS sudah dimuat:
```html
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
```

### Icons tidak muncul
Pastikan Font Awesome sudah dimuat:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

### Theme toggle tidak berfungsi
Periksa JavaScript error di browser console (F12).

## 🌟 Tips Optimasi

1. **Kompress gambar** sebelum upload
2. **Minify CSS dan JavaScript** untuk production
3. **Gunakan WebP format** untuk gambar modern
4. **Add meta tags** untuk SEO yang lebih baik
5. **Test di berbagai browser** dan perangkat

## 📄 License

MIT License - Anda bebas menggunakan dan memodifikasi untuk keperluan pribadi atau komersial.

## 🤝 Kontribusi

Jika Anda menemukan bug atau ingin menambahkan fitur:
1. Fork repository ini
2. Buat branch baru untuk fitur Anda
3. Commit perubahan Anda
4. Push ke branch
5. Buat Pull Request

## 📞 Support

Jika Anda membutuhkan bantuan:
- Buka issue di GitHub
- Email: your.email@example.com

---

**Selamat menggunakan template portfolio Anda! 🚀**