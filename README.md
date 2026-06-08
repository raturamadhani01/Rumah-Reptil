<div align="center">

# 🦖 Rumah Reptile

### Pusat Reptil Dunia — Temukan, Jelajahi, dan Kelola Koleksi Reptilmu!

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

</div>

---

## Tentang Proyek

**Rumah Reptile** adalah aplikasi web katalog reptil yang memungkinkan pengguna untuk menjelajahi, mencari, menambahkan, mengedit, dan menghapus koleksi reptil. Data disimpan secara lokal menggunakan **localStorage**, sehingga perubahan tetap tersimpan meski halaman di-refresh.

> Ini adalah **proyek pertama kami** sebagai kolaborasi tim — dibuat dengan penuh semangat dan dedikasi sebagai bagian dari seleksi Hacktiv8 Phase 0.

---

## Fitur Utama

- **Autentikasi** — Halaman login sederhana untuk mengamankan akses
- **Katalog Reptil** — Tampilan kartu untuk semua koleksi reptil yang tersedia
- **Pencarian Real-time** — Cari reptil berdasarkan nama secara langsung
- **Tambah Item** — Tambahkan reptil baru ke dalam katalog
- **Edit Item** — Perbarui informasi reptil yang sudah ada
- **Hapus Item** — Hapus reptil dari katalog
- **Persistensi Data** — Semua perubahan tersimpan otomatis via localStorage
- **Carousel Banner** — Tampilan banner dinamis di halaman utama
- **Responsif** — Tampilan yang nyaman di berbagai ukuran layar

---

## Koleksi Reptil

| Nama | Harga |
|------|-------|
| Gecko | Rp 200.000 |
| Iguana | Rp 6.000.000 |
| Ular Python | Rp 200.000 |
| Kura-kura | Rp 6.500.000 |
| Kadal Gurun | Rp 4.500.000 |
| Komodo | Rp 256.000 |
| Bunglon | Rp 20.000 |
| Tokek | Rp 6.000 |
| Dinosaurus | Rp 450.000.000.000 |

---

## Cara Menggunakan

1. **Login** menggunakan akun berikut:
   - Email: `admin123@gmail.com`
   - Password: `12345678`

2. Setelah login, kamu akan diarahkan ke halaman **Home** dengan daftar seluruh reptil.

3. Gunakan kolom **pencarian** untuk menemukan reptil tertentu.

4. Klik tombol **Tambah** untuk menambahkan reptil baru.

5. Klik **Edit** atau **Hapus** pada kartu reptil untuk mengelola data.

---

## Struktur Proyek

```
Rumah-Reptil/
├── index.html              # Halaman login
├── pages/
│   ├── home.html           # Halaman utama (katalog)
│   ├── add_item.html       # Halaman tambah reptil
│   └── edit-item.html      # Halaman edit reptil
├── components/
│   ├── database.js         # Data default & localStorage
│   ├── login.js            # Logika autentikasi
│   ├── index.js            # Render katalog & pencarian
│   ├── add-item.js         # Logika tambah item
│   ├── edit-item.js        # Logika edit item
│   ├── unload.js           # Guard autentikasi
│   ├── navbar.html         # Komponen navbar
│   └── footer.html         # Komponen footer
├── style/
│   ├── style.css           # Gaya utama
│   ├── page-item.css       # Gaya halaman item
│   └── login.css           # Gaya halaman login
└── images/                 # Aset gambar reptil & banner
```

---

## Tim Pengembang

Proyek ini merupakan **kolaborasi pertama** kami berdua.

| Developer | GitHub |
|-----------|--------|
| Ratu Ramadhani | [@raturamadhani01](https://github.com/raturamadhani01) |
| Rekan 1 | [@baiapa10](https://github.com/baiapa10) |
| Rekan 2 | [@erwindW99](https://github.com/erwindW99) |
| Rekan 3 | [@archiesuyono](https://github.com/archiesuyono) |

---

<div align="center">

Dibuat dengan semangat oleh tim **Rumah Reptile** — Hacktiv8 Phase 0 Selection

</div>
