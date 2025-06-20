<!-- Gambar -->
<!-- assets/img/DropYourTask-Home.png -->

[![DropYourTask](https://raw.githubusercontent.com/Urproject/DropYourTask/main/assets/img/DropYourTask-Home.png)](https://raw.githubusercontent.com/Urproject/DropYourTask/main/assets/img/DropYourTask-Home.png)

# 📚 DropYourTask

**DropYourTask** adalah sistem pengumpulan dan penilaian tugas berbasis web, dirancang khusus untuk guru dan sekolah yang ingin alternatif dari Google Classroom — ringan, fleksibel, dan bisa di-host sendiri.

> 🎯 Dibuat oleh [@zoelabbb](https://github.com/zoelabbb)

---

## ✨ Fitur Utama

- 🔐 Role: Super Admin & Teacher
- 📂 Pengumpulan tugas dengan validasi Kode Kelas + NIM
- 🧾 Penilaian & Feedback submission siswa
- 🔄 Log aktivitas lengkap
- 📤 Upload file aman (PDF, DOCX, dll)
- 📊 Export nilai ke Excel
- ⏳ Atur deadline kelas & arsip kelas
- 📉 Tampilan ringan & mobile-friendly
- 🖥️ Bisa di-host sendiri (Self-hosted Laravel)

## 👨‍🏫 Untuk Guru

- ✅ Manajemen kelas dengan kode unik
- ✅ Tambah/hapus mahasiswa
- ✅ Lihat dan nilai submission
- ✅ Download bulk submission per kelas
- ✅ Manajemen deadline tugas
- ✅ Activity logging

## 👨‍🎓 Untuk Mahasiswa/Murid

- ✅ Submit tugas dengan verifikasi NIM + Kode Kelas
- ✅ Lihat status submission
- ✅ Download file submission

## 🔐 Untuk Super Admin

- ✅ Manajemen user dan role
- ✅ Activity log monitoring
- ✅ Akses ke semua fitur dan data

---

## 🚀 Demo

> Belum tersedia online.

---

## ⚙️ Tech Stack

- Laravel 11
- UUID-based model (kecuali user)
- TailwindCSS
- Livewire
- MySQL
- Jetstream (untuk autentikasi)
- LogActivity (untuk log aktivitas)

---

## 🔐 Login Akun Demo

| Role        | Email          | Password     |
| ----------- | -------------- | ------------ |
| Super Admin | admin@demo.com | pswadmindemo |
| Teacher     | guru@demo.com  | pswgurudemo  |

---

## 🔎 Kenapa Bukan Google Classroom?

| Fitur                                              | DropYourTask | Google Classroom |
| -------------------------------------------------- | ------------ | ---------------- |
| Tanpa login Gmail                                  | ✅ Ya        | ❌ Tidak bisa    |
| Bisa Self-hosted                                   | ✅ Ya        | ❌ Tidak bisa    |
| Custom branding sekolah                            | ✅ Bisa      | ❌ Tidak bisa    |
| Upload submission via NIM & Kode Kelas tanpa login | ✅ Bisa      | ❌ Tidak ada     |
| Ringan & bisa LAN-only                             | ✅ Bisa      | ❌ Tidak bisa    |
| Tampilan mobile-friendly                           | ✅ Ya        | ✅ Ya            |
| Customisasi fitur sesuai kebutuhan sekolah         | ✅ Bisa      | ❌ Terbatas      |
| Integrasi dengan sistem lain                       | ✅ Bisa      | ❌ Terbatas      |

---

## 📦 Fitur Mendatang

- 🔔 Notifikasi tugas via Telegram/WA/Email
- 📤 Impor siswa via Excel
- 📄 Preview file (PDF) langsung di browser
