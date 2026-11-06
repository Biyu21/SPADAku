# SPADAku

SPADAku adalah aplikasi Android pendamping **SPADA UM Metro** (e-learning Universitas Muhammadiyah Metro). Cek tugas, absen dari notifikasi, kumpulkan tugas lewat scan, dan atur jadwal kuliah dalam satu genggaman.

## Unduh

**[⬇️ SPADAku-v1.0.0.apk](release/SPADAku-v1.0.0.apk)** (± 92 MB)

| | |
|---|---|
| Versi | 1.0.0 (build 1) |
| Android minimal | 7.0 (Nougat) |
| Arsitektur | Universal (arm64-v8a, armeabi-v7a, x86_64) |
| SHA-256 | `9a259235af26776f411c7d15112157271356d8fc933eaeaec39a1fb522c80dac` |

## Fitur

- **Absen dari notifikasi.** Saat dosen membuka presensi, HP kamu bunyi. Tekan "Hadir" langsung dari notifikasi. Kalau dosen memasang password, ketik di notifikasi itu juga.
- **Rekap & riwayat kehadiran.** Persentase kehadiran per matkul, riwayat per pertemuan, termasuk pertemuan yang terlewat dan belum tercatat.
- **Tugas & deadline.** Semua tugas dari semua matkul dalam satu daftar, urut dari yang paling mepet. Pengingat H-3, H-1, dan 3 jam sebelum deadline (bisa diatur).
- **Kumpulkan tugas pakai scan.** Foto kertas jawaban, pinggiran kertas terdeteksi otomatis, lalu langsung jadi PDF dan terkirim ke SPADA.
- **Jadwal & agenda.** Kuliah, deadline, dan agenda pribadi (rapat organisasi, kerja kelompok) dalam satu linimasa, lengkap dengan pengingat.
- **Materi & nilai.** Materi per pertemuan bisa dibaca offline, plus rekap nilai tiap matkul.
- **Forum diskusi** matkul langsung dari aplikasi.
- **Widget layar utama** dan **kunci sidik jari / PIN HP**.

## Cara memasang

1. Unduh file APK di atas ke HP Android kamu.
2. Buka file tersebut. Jika muncul peringatan, izinkan **"Instal aplikasi tidak dikenal"** untuk browser atau file manager yang kamu pakai.
3. Tekan **Instal**, lalu buka SPADAku dan masuk dengan **NPM dan password SPADA** kamu.

Sudah pernah memasang versi sebelumnya? Cukup pasang APK baru di atasnya. Data dan login kamu tetap tersimpan.

## Agar notifikasi absen & tugas selalu muncul

SPADAku mengecek SPADA di latar belakang, termasuk saat aplikasi sudah ditutup dari daftar aplikasi terbaru. Beberapa HP (terutama Xiaomi/Redmi/POCO, Oppo, Vivo, dan Realme) membatasi aplikasi di latar belakang, jadi atur sekali di **Setelan → Aplikasi → SPADAku**:

- **Baterai / Penghemat baterai:** pilih **Tidak dibatasi**.
- **Mulai otomatis (Autostart):** **aktifkan**.
- (Opsional) Kunci SPADAku di daftar aplikasi terbaru.

Untuk mengetes, buka **Akun → Pengingat deadline → Kirim notifikasi tes (1 menit)**.

## Privasi

- Login memakai akun SPADA kamu sendiri.
- Password disimpan **terenkripsi hanya di HP kamu** dan dikirim langsung ke server SPADA (`spada.ummetro.ac.id`), tidak ke server lain.
- Foto profil dan agenda pribadi hanya tersimpan di HP kamu.

## Pembuat

**Abbiyu Hashfi Dzakwan**
Mahasiswa S1 Ilmu Komputer, Universitas Muhammadiyah Metro

Ada kendala atau saran? Hubungi pembuat lewat menu **Akun → Bantuan** di aplikasi.
