# Praktikum Desain Web - Pertemuan 7

Tugas praktikum Desain Web tentang HTML Form Dasar (input dan pengiriman data).

| | |
|---|---|
| Nama | Karel Abimanyu Ahpandi |
| NIM | 4525210031 |
| Kelas | A |
| Mata Kuliah | Desain Web |

## Deskripsi

Repo ini berisi dua halaman form yang memakai satu berkas CSS yang sama:

- **Studi Kasus** (`index.html`): prototipe form pendaftaran mahasiswa baru yang nantinya dapat diintegrasikan dengan backend. Data minimum: nama, email, password, nilai, dan tanggal lahir.
- **Individu** (`kursus.html`): form pendaftaran kursus dengan minimal lima tipe input dan tiga jenis button.

Setiap kontrol memiliki `label` yang terhubung lewat atribut `for` yang sama dengan `id`, serta atribut `name` sebagai key data saat form dikirim.

## Struktur Folder

```
.
├── index.html          # Studi Kasus: Form Pendaftaran Mahasiswa
├── kursus.html         # Individu: Form Pendaftaran Kursus
├── css/
│   └── style.css       # Styling bersama untuk kedua halaman
├── screenshots/        # Tampilan desktop dan mobile
└── README.md
```

## Fitur

1. Pendaftaran Kursus (kursus.html)
Input nama peserta (text).
Input email (email).
Input password (password).
Input jumlah sesi per minggu (number).
Input tanggal mulai kursus (date).
Pilihan program kursus menggunakan dropdown.
Catatan tambahan menggunakan textarea.
Tombol Daftar (submit), Reset (reset), dan Kembali (button).

## Cara Menggunakan
Buka halaman formulir melalui browser.
Pilih formulir yang ingin digunakan.
Isi seluruh field yang wajib diisi.
Klik tombol Daftar untuk menampilkan pesan konfirmasi.
Klik tombol Reset untuk mengosongkan isian formulir.
Klik tombol Bantuan untuk menampilkan informasi bantuan.

3. Penerimaan Mahasiswa Baru (index.html)
Input nama lengkap (text).
Input email (email).
Input password (password).
Input nilai (number, rentang 0 sampai 100).
Input tanggal lahir (date).
Pilihan program studi menggunakan dropdown.
Input alamat menggunakan textarea.
Tombol Daftar (submit), Reset (reset), dan Kembali (button).

## Screenshot

### Studi Kasus

| Desktop | Mobile |
|---|---|
| ![Studi kasus desktop](screenshots/index_desktop.png) | ![Studi kasus mobile](screenshots/index_mobile.png) |

### Individu

| Desktop | Mobile |
|---|---|
| ![Kursus desktop](screenshots/kursus_desktop.png) | ![Kursus mobile](screenshots/kursus_mobile.png) |
