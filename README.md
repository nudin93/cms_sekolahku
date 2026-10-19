# CMS Sekolahku v2.4.13

CMS (Content Management System) website sekolah berbasis CodeIgniter + MySQL.
Dikembangkan oleh [sekolahku.web.id](https://sekolahku.web.id) — CMS Sekolahku.

## Kegunaan singkat

Satu aplikasi untuk **website profil sekolah + administrasi data + PPDB online**:
admin/operator mengelola berita, halaman, galeri foto, slider, data siswa,
data pegawai, alumni, prestasi, beasiswa, dan penerimaan peserta didik baru
(PPDB) — semua tampil otomatis di website sekolah yang bisa diganti temanya.

## Fitur utama

- **Website**: tema yang bisa diganti, menu dinamis, slider gambar, halaman
  statis, berita + kategori + tag + komentar, galeri album & foto, jajak
  pendapat (polling), kata mutiara, sambutan kepala sekolah, tautan, پرونده
  unduhan, pesan/kontak masuk, pelanggan berita (subscriber).
- **PPDB online**: gelombang & jenis pendaftaran, kuota, formulir pendaftar,
  seleksi, status lulus/tidak, pendaftar disetujui/belum.
- **Data siswa**: biodata, rombongan belajar (rombel), status, tempat tinggal,
  transportasi, penghasilan orang tua, impor Excel, alumni + impor alumni.
- **Data pegawai**: biodata, status/jenis kepegawaian, pangkat, keterampilan
  lab, sumber gaji, pengangkat.
- **Prestasi & beasiswa**: data prestasi siswa dan beasiswa.
- **Lainnya**: tahun ajaran, jurusan, dashboard statistik, multi-pengguna.

## Instalasi (cPanel)

1. Upload semua file ke hosting (mis. `public_html/`), buat database kosong.
2. Buka `https://domain-anda/install` → isi database, info sekolah,
   dan **buat akun admin sendiri** → proses.
3. **HAPUS folder `install/`** setelah selesai, lalu login di
   `https://domain-anda/login`.
4. Alternatif manual: import `db_cms_sekolahku.sql` via phpMyAdmin, sesuaikan
   `application/config/database.php` (login bawaan: `administrator` /
   `administrator` — segera diganti).

> Catatan: `application/config/database.php` di repo ini berisi placeholder
> (`ISI_*_CMS`), bukan kredensial asli. Kredensial diisi saat instalasi.

## Keamanan

- Hapus folder `install/` setelah dipakai. Ganti password bawaan bila pakai
  import manual. Batasi hak tulis folder upload. Detail kegunaan lengkap baca
  [DESKRIPSI-APLIKASI.md](DESKRIPSI-APLIKASI.md).
