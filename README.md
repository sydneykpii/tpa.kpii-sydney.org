# TPA Khairu Ummah

Website TPA Khairu Ummah (KPII Sydney) beserta materi ajar interaktif.

## Isi folder

| File | Fungsi |
| --- | --- |
| `index.html` | Halaman utama TPA |
| `images/islamic-calendar-thumbnail.jpg` | Gambar untuk bagian Islamic Calendar |
| `images/hero.jpg` | Foto banner atas (tambahkan sendiri) |
| `images/logo.png` | Logo di pojok kiri atas (tambahkan sendiri) |
| `lessons/index.html` | Halaman Islamic Calendar berisi empat pelajaran |
| `lessons/islamic-new-year.html` | Pelajaran Islamic New Year |
| `lessons/asyura.html` | Pelajaran The Day of 'Asyura |
| `lessons/maulid-nabi.html` | Pelajaran Maulid Nabi |
| `lessons/isra-miraj.html` | Pelajaran The Night Journey (Isra Mi'raj) |

## Cara menayangkan di GitHub Pages

1. Buat repository baru di GitHub, misalnya `tpa`.
2. Upload semua isi folder ini (bukan foldernya) ke repository tersebut, lewat tombol **Add file** lalu **Upload files**.
3. Buka **Settings**, pilih **Pages**. Pada **Source** pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu sekitar satu menit. Alamatnya akan menjadi `https://NAMA-AKUN.github.io/tpa/`.

## Foto banner dan logo

Halaman tetap tampil rapi tanpa keduanya (banner memakai motif hijau). Untuk memakai foto anak anak seperti di Google Sites, simpan fotonya sebagai `images/hero.jpg`. Untuk logo, simpan sebagai `images/logo.png`. Nama file harus persis sama.

## Menambah materi baru

Di `index.html`, cari bagian `<article class="item">`. Salin satu blok itu, lalu ganti gambar, judul, keterangan, dan link tombolnya.

## Catatan

Font dimuat dari Google Fonts, jadi perlu koneksi internet. Tanpa internet, halaman tetap berjalan dengan font bawaan.
