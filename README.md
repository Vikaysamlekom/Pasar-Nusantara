# Pasar Nusantara - Belajar Kegiatan Ekonomi

**Pasar Nusantara** adalah aplikasi pembelajaran interaktif berbasis web untuk mata pelajaran **IPAS kelas V SD**. Melalui delapan kios materi, siswa dapat mempelajari kegiatan ekonomi dengan latihan yang dekat dengan kehidupan sehari-hari.

Aplikasi ini dapat dibuka langsung di browser dan tidak memerlukan proses instalasi atau build.

## Daftar Isi

- [Fitur](#fitur)
- [Materi Pembelajaran](#materi-pembelajaran)
- [Cara Menjalankan](#cara-menjalankan)
- [Deploy ke GitHub Pages](#deploy-ke-github-pages)
- [Struktur Proyek](#struktur-proyek)
- [Teknologi](#teknologi)
- [Lisensi](#lisensi)

## Fitur

- Delapan kios pembelajaran dengan materi IPAS yang berbeda
- Soal pilihan ganda dan tantangan menyusun urutan rantai ekonomi
- Simulasi sederhana sebagai penjual dan pembeli di warung
- Sistem poin dan penilaian bintang untuk setiap kios
- Kuis campuran "Juragan Pasar"
- Tampilan responsif untuk perangkat desktop dan mobile
- Dukungan mode gelap berdasarkan pengaturan perangkat
- Navigasi yang mendukung penggunaan keyboard
- Dukungan pengurangan animasi bagi pengguna yang membutuhkan

## Materi Pembelajaran

1. Kegiatan ekonomi di sekitar kita
2. Pengertian kegiatan ekonomi
3. Produksi, distribusi, dan konsumsi
4. Pekerjaan masyarakat berdasarkan lingkungan
5. Jual beli di warung
6. Menjaga sumber daya alam
7. Rantai produksi hingga konsumsi
8. Manfaat kegiatan ekonomi

Materi juga memperkenalkan kegiatan ekonomi, kebutuhan pokok, alat pembayaran, barter, pelestarian sumber daya alam, serta hubungan antarpelaku ekonomi.

## Cara Menjalankan

### Membuka langsung

1. Unduh atau clone repositori ini.
2. Buka file `Pasar Nusantara – IPAS Kelas V.html` menggunakan browser.
3. Pilih satu kios untuk mulai belajar.

### Menjalankan melalui server lokal

Menggunakan Python:

```bash
python -m http.server 8000
```

Buka `http://localhost:8000` di browser, kemudian pilih file halaman aplikasi.

Menggunakan Visual Studio Code:

1. Install ekstensi **Live Server**.
2. Klik kanan file `Pasar Nusantara – IPAS Kelas V.html`.
3. Pilih **Open with Live Server**.

## Deploy ke GitHub Pages

1. Pastikan file HTML sudah berada di branch utama, misalnya `main`.
2. Buka halaman **Settings** pada repositori GitHub.
3. Pilih menu **Pages**.
4. Pada **Source**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`.
6. Klik **Save**.
7. Setelah deployment selesai, buka URL GitHub Pages yang ditampilkan pada halaman Pages.

## Struktur Proyek

```text
.
├── Pasar Nusantara – IPAS Kelas V.html
└── README.md
```

## Teknologi

- HTML5
- CSS3
- JavaScript tanpa framework
- Google Fonts
  - Baloo 2
  - Nunito

Aplikasi hanya membutuhkan browser modern. Font akan menggunakan font bawaan sistem jika koneksi Google Fonts tidak tersedia.

## Lisensi

Tambahkan informasi lisensi proyek di sini, misalnya MIT, jika ingin repositori ini dapat digunakan kembali oleh orang lain.
