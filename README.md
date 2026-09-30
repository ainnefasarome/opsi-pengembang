<p align="center">
  <img src="icon.png" alt="Opsi Pengembang" width="140">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-4.2%2B%20sampai%2014-green" alt="Android">
  <img src="https://img.shields.io/badge/Version-v1000-blue" alt="Version">
  <img src="https://img.shields.io/badge/Platform-Universal-orange" alt="Platform">
  <img src="https://img.shields.io/badge/License-Bebas%20digunakan-lightgrey" alt="License">
</p>

<p align="center">
  <a href="https://github.com/ainnefasarome/opsi-pengembang/releases/latest">
    <img src="https://img.shields.io/badge/%E2%AC%87%20Download%20APK%20v1000-success?style=for-the-badge" alt="Download APK">
  </a>
</p>

# Opsi Pengembang

Aplikasi Android ringan tanpa tampilan (non-UI) yang berfungsi sebagai **jembatan pintar** menuju halaman **Build Number** di pengaturan HP, supaya pengguna tinggal mengetuk **7 kali** untuk mengaktifkan **Opsi Pengembang** - tanpa harus bingung mencari sendiri.

## Fitur

- **Non-UI** - ikon diklik, langsung bekerja. Tidak ada layar yang mengganggu.
- **Cerdas & adaptif** - mendeteksi merek/ROM HP dan mengarahkan ke halaman Build Number yang tepat.
- **Multi-merek & multi-bahasa** - mendukung 90+ variasi istilah Build Number (Indonesia, Inggris, Mandarin, Jepang, Korea, Arab, Hindi, dll).
- **Auto submenu** - otomatis menap submenu seperti Versi (ColorOS), Semua Spesifikasi (MIUI), Informasi Perangkat Lunak (One UI), jika Build Number berada di dalamnya.
- **Auto tap 7x** - menggunakan Accessibility Service untuk mengetuk Build Number 7 kali secara otomatis.

## Tentang Opsi Pengembang

**Opsi Pengembang (Developer Options)** adalah menu tersembunyi di Android yang ditujukan untuk pengembang aplikasi, teknisi, dan pengguna tingkat lanjut. Menu ini disembunyikan secara default agar tidak sembarangan diubah oleh pengguna awam, karena berisi pengaturan teknis yang bisa mempengaruhi performa dan stabilitas sistem.

### Mulai Android Berapa?

Menu Developer Options sudah ada sejak era awal Android, namun **disembunyikan di balik tap 7x Build Number sejak Android 4.2 (Jelly Bean, 2012)**. Sejak saat itu, setiap versi Android (4.2 hingga 14) menggunakan cara yang sama: buka Tentang Ponsel, lalu tap Build Number 7 kali.

### Kelebihan & Fungsi Opsi Pengembang

- **USB Debugging** - menghubungkan HP ke komputer via ADB (untuk flashing, root, development, backup, dsb).
- **Wireless Debugging** - ADB tanpa kabel (Android 11+).
- **Mock Location** - mensimulasikan lokasi GPS palsu (untuk pengujian aplikasi).
- **Animation Scale** - mempercepat / memperlambat animasi sistem.
- **Force GPU Rendering** - memaksa rendering 2D lewat GPU, bisa meningkatkan performa game ringan.
- **Background Process Limit** - membatasi jumlah proses latar belakang (hemat RAM/baterai).
- **Show Taps / Pointer Location** - menampilkan sentuhan jari di layar (untuk demo/tutorial).
- **Don't Keep Activities** - menghancurkan activity saat ditinggalkan (untuk uji coba developer).
- **OEM Unlocking** - membuka bootloader (untuk install custom ROM / recovery).
- **Bug Report / Logger** - mengambil log sistem untuk diagnosa masalah.
- **Dan puluhan fitur teknis lainnya** - tergantung versi Android dan merek HP.

## Izin yang Dibutuhkan

Aplikasi ini membutuhkan **satu izin** saja, yaitu **Aksesibilitas (Accessibility Service)**.

**Kenapa butuh aksesibilitas?**
Aksesibilitas adalah satu-satunya cara yang disediakan Android untuk aplikasi bisa membaca isi layar dan melakukan ketukan otomatis. Tanpa izin ini, aplikasi hanya bisa membuka halaman Tentang Ponsel, tetapi tidak bisa mencari Build Number atau mengetuknya 7x secara otomatis.

**Apakah aman?**
- Tidak ada data yang dikumpulkan.
- Tidak ada data yang dikirim ke server mana pun.
- Tidak ada koneksi internet yang dibuka.
- Aplikasi bekerja sepenuhnya offline dan lokal di HP kamu.
- Kode sumber dapat diperiksa sendiri karena aplikasi ini bebas digunakan.

**Bisa dimatikan kapan saja?**
Bisa. Matikan toggle di **Settings - Aksesibilitas - Opsi Pengembang Otomatis** kapan pun kamu mau.

## Kompatibilitas

| Item | Keterangan |
|------|------------|
| Minimum Android | 4.2 (Jelly Bean, API 17) |
| Target Android | 14 (API 34) |
| Arsitektur | Universal (semua) |

**Mendukung otomatis sebagian besar HP Android:**
Samsung One UI, Xiaomi MIUI/HyperOS, Oppo/Realme ColorOS, Vivo FuntouchOS, Huawei/Honor EMUI, OnePlus OxygenOS, Google Pixel, Nokia, Sony, Asus ZenUI, dan lainnya.

Beberapa HP dengan proteksi khusus (Xiaomi HyperOS terbaru, Samsung Knox enterprise) mungkin tidak mendukung mode otomatis. Kalau gagal, silakan laporkan dengan screenshot halaman Tentang Ponsel agar istilahnya bisa ditambahkan di versi berikutnya.

## Cara Pakai

1. Install APK dari halaman Releases.
2. Klik ikon Opsi Pengembang.
3. Saat pertama kali, kamu akan diarahkan ke halaman Aksesibilitas - aktifkan "Opsi Pengembang Otomatis".
4. Klik ikon sekali lagi, aplikasi akan otomatis:
   - Membuka Tentang Ponsel
   - Masuk ke submenu yang benar (jika perlu)
   - Mengetuk Build Number 7x
5. Selesai! Buka Settings - Sistem - Opsi Pengembang.

## FAQ

**Apakah aplikasi ini butuh root?**
Tidak. Aplikasi berjalan sepenuhnya tanpa root.

**Apakah ada data yang dikirim ke internet?**
Tidak ada. Aplikasi bekerja offline dan tidak membuka koneksi internet sama sekali.

**Kenapa harus aktifkan aksesibilitas?**
Karena Android hanya mengizinkan aplikasi membaca layar dan mengetuk otomatis lewat izin aksesibilitas. Ini aturan keamanan dari Android, tidak bisa dilewati.

**Kalau di HP saya gagal, bagaimana?**
Buka Issue di halaman GitHub ini dengan menyertakan merek, tipe HP, versi Android, dan screenshot halaman Tentang Ponsel. Istilah Build Number yang berbeda akan ditambahkan di update berikutnya.

**Apakah aman untuk HP saya?**
Aman. Aplikasi hanya membuka pengaturan dan mengetuk Build Number 7 kali. Tidak mengubah data, tidak menghapus apapun, tidak mengakses file pribadi.

**Apakah bisa dipakai di semua HP?**
Mendukung otomatis sebagian besar merek Android. Beberapa HP dengan proteksi sistem khusus mungkin perlu mengetuk Build Number secara manual setelah aplikasi membuka halamannya.

## Kontribusi

Kalau aplikasi ini gagal di HP kamu, buka Issue dengan menyertakan:
- Merek + tipe HP
- Versi Android
- Screenshot halaman Tentang Ponsel

Kontribusi keyword baru sangat diterima demi cakupan yang lebih luas.
