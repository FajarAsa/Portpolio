# Portfolio Website dengan TailwindCSS

Project portfolio website yang dibuat dengan HTML, CSS vanilla, dan TailwindCSS.

## 📁 Struktur Folder

```
Fajarasa/
├── src/
│   └── style.css          # CSS file yang di-import TailwindCSS
├── dist/
│   └── style.css          # Output CSS yang sudah compiled (generated)
├── index.html             # Main HTML file
├── package.json           # NPM dependencies
├── tailwind.config.js     # Tailwind configuration
├── postcss.config.js      # PostCSS configuration
└── README.md              # File ini
```

## 🚀 Setup & Instalasi

### 1. Install Dependencies
```bash
npm install
```

### 2. Development Mode (Watch Mode)
Jalankan command ini untuk watch mode - CSS akan otomatis di-compile setiap kali Anda edit `src/style.css`:
```bash
npm run dev
```

### 3. Build untuk Production
Jalankan command ini untuk minify dan optimize CSS:
```bash
npm run build
```

## 📝 Cara Menggunakan

1. **Edit HTML**: Ubah `index.html` sesuai kebutuhan portfolio Anda
2. **Tambah CSS**: Gunakan TailwindCSS classes langsung di HTML
3. **Custom CSS**: Tambahkan custom styles di `src/style.css`
4. **Jalankan Dev Server**: 
   - Jika punya Live Server extension di VS Code, buka `index.html`
   - Atau buka file `index.html` langsung di browser

## 🎨 TailwindCSS Classes yang Sudah Tersedia

Portfolio ini sudah menggunakan TailwindCSS dengan berbagai komponen:
- Responsive Navigation
- Hero Section dengan gradient
- Card-style Projects
- Contact Form
- Footer

## 📦 Dependencies

- **tailwindcss**: ^3.4.13
- **postcss**: ^8.4.41
- **autoprefixer**: ^10.4.20

## 💡 Tips

- Jangan edit `dist/style.css` secara manual - file ini di-generate otomatis
- Semua styling menggunakan TailwindCSS - cek dokumentasi di https://tailwindcss.com
- Untuk development lebih mudah, install "Live Server" extension di VS Code

## 🔗 Links Berguna

- [TailwindCSS Documentation](https://tailwindcss.com/docs)
- [TailwindCSS Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet)

---

**Happy Coding!** 🎉
