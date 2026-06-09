# Belajar Hero Section - Tailwind CSS

Proyek belajar membuat hero section sederhana menggunakan Tailwind CSS.

## Preview

Halaman terdiri dari:
- Navbar dengan logo dan link navigasi (Home, About, Service, Portfolio, Contact)
- Hero section dengan judul, deskripsi, tombol CTA, dan ilustrasi SVG

## Tech Stack

- [Tailwind CSS](https://tailwindcss.com/) v2.2.7
- Nodemon (auto-rebuild CSS saat ada perubahan)
- HTML murni (tanpa framework JS)

## Struktur Folder

```
├── dist/
│   ├── index.html   # File HTML utama
│   ├── style.css    # CSS Tailwind hasil build
│   ├── hero.svg     # Ilustrasi hero
│   └── logo.png     # Logo navbar
├── src/
│   └── style.css    # Source CSS (input Tailwind)
└── package.json
```

## Cara Menjalankan

### Install dependencies

```bash
npm install
```

### Build CSS sekali

```bash
npm run build:css
```

### Mode development (auto-rebuild saat CSS berubah)

```bash
npm run serve
```

Setelah build, buka `dist/index.html` di browser.
