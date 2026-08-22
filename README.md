<div align="center">

<img src="https://raw.githubusercontent.com/intisariapps-com/Intisari-AutoCut-Android/main/assets/ic_launcher_web.png" width="120" alt="Intisari AutoCut Logo"/>

# ✂️ Intisari AutoCut Android

### Aplikasi Pemotong Video Otomatis Bertenaga AI

[![Release](https://img.shields.io/github/v/release/intisariapps-com/Intisari-AutoCut-Android?style=for-the-badge&color=6366f1&label=Versi%20Terbaru)](https://github.com/intisariapps-com/Intisari-AutoCut-Android/releases/latest)
[![Download](https://img.shields.io/github/downloads/intisariapps-com/Intisari-AutoCut-Android/total?style=for-the-badge&color=a855f7&label=Total%20Unduhan)](https://github.com/intisariapps-com/Intisari-AutoCut-Android/releases/latest/download/IntisariAutoCut.apk)
[![Android](https://img.shields.io/badge/Android-7.0%2B-brightgreen?style=for-the-badge&logo=android)](https://github.com/intisariapps-com/Intisari-AutoCut-Android/releases/latest/download/IntisariAutoCut.apk)
[![License](https://img.shields.io/badge/Lisensi-Berbayar-orange?style=for-the-badge)](https://intisariapps.com)

**[⬇️ UNDUH APK SEKARANG](https://github.com/intisariapps-com/Intisari-AutoCut-Android/releases/latest/download/IntisariAutoCut.apk)**

*Unduhan langsung — tidak perlu buat akun GitHub*

</div>

---

## 🎯 Apa itu Intisari AutoCut?

**Intisari AutoCut** adalah aplikasi Android bertenaga AI yang dirancang khusus untuk membantu kreator konten secara otomatis mengunduh video dari YouTube, menganalisis poin-poin penting menggunakan model bahasa besar (LLM), dan memotong klip terbaik secara cerdas — langsung dari genggaman tangan Anda.

Tidak perlu laptop, tidak perlu software editing mahal. Cukup masukkan URL video atau resep `.txt`, biarkan AI bekerja, dan ekspor klip siap pakai dalam hitungan menit.

---

## ⬇️ Cara Mengunduh & Menginstal

### Metode 1 — Direct Download (Direkomendasikan)

1. Klik tautan di bawah untuk langsung mengunduh APK:

   **[➡️ Download IntisariAutoCut.apk](https://github.com/intisariapps-com/Intisari-AutoCut-Android/releases/latest/download/IntisariAutoCut.apk)**

2. Buka file `.apk` yang sudah diunduh di HP Anda
3. Jika muncul dialog "Sumber Tidak Dikenal", pilih **Izinkan dari Sumber Ini**
4. Ikuti instruksi instalasi

### 🎥 Video Panduan Uji Coba Trial

Bagi Anda yang ingin melakukan uji coba trial fitur aplikasi secara gratis, silakan tonton panduan video aktivasi dan uji coba di bawah ini:

**[▶️ Video Tutorial Uji Coba Trial AutoCut](https://youtu.be/PEZi_Jt1xK4)**

---

### Metode 2 — Halaman Releases GitHub

Kunjungi [Halaman Releases](https://github.com/intisariapps-com/Intisari-AutoCut-Android/releases/latest) untuk melihat semua versi yang tersedia beserta catatan perubahan.

> **Persyaratan Minimum:** Android 7.0 (API Level 24) ke atas

---

## ✨ Fitur Lengkap v1.0.0

### 🎬 1. Video Downloader Terintegrasi
- Unduh video YouTube langsung dari dalam aplikasi menggunakan **yt-dlp**
- Mendukung berbagai format dan kualitas video
- **Smart Cache Hit**: Video master yang sudah diunduh disimpan secara permanen di `/sdcard/Download/Intisari_AutoCut_Masters/` — tidak perlu diunduh ulang jika diproses kembali
- Antarmuka pencarian dan input URL yang bersih

### 🤖 2. AI Video Analyzer — Multi-Provider
Analisis konten video menggunakan **7 pilihan provider AI** yang dapat diganti sewaktu-waktu:

| Provider | Model |
|---|---|
| 🌟 **Google Gemini** *(default)* | Gemini 2.5 Flash |
| 🔵 **DeepSeek** | DeepSeek Chat (R1) |
| ⚡ **Groq** | Llama 3.3 |
| 🔶 **SambaNova** | Qwen 2.5 |
| 🧠 **Cerebras** | Fast AI |
| 🌊 **Cohere** | Command R+ |
| 🌐 **OpenRouter** | Universal (akses ratusan model) |

### ✂️ 3. Auto Cut Engine
- Otomatis mengidentifikasi dan memotong bagian terbaik dari video berdasarkan hasil analisis AI
- Menghasilkan file resep potongan (`.txt`) yang dapat disimpan dan digunakan ulang
- Dukungan mode reframe video (portrait/landscape/square)

### 📂 4. Ekspor Klip Cerdas dengan Subfolder Dinamis
- Hasil potongan video diekspor ke folder yang **terorganisir otomatis** berdasarkan 3 kata pertama judul video
- Contoh: video berjudul *"Tips Memasak Ayam Goreng"* → klip disimpan di `/sdcard/Movies/Intisari_AutoCut/Tips_Memasak_Ayam/`
- Tidak ada lagi klip video yang berantakan di satu folder yang sama

### 📄 5. Berbagi Resep Potongan (.txt)
- Ekspor **resep potongan** dari setiap proyek dalam format `.txt`
- Resep dapat dibagikan ke pengguna lain atau diproses ulang tanpa mengunduh video lagi
- Format kompatibel dengan sistem AutoCut generasi sebelumnya (Termux)

### 🔑 6. Sistem Lisensi & Aktivasi
- Sistem lisensi berbasis token untuk akses premium
- Input token aktivasi melalui layar Pengaturan yang aman
- Validasi lisensi secara real-time dengan server API

### 🔄 7. Forced Update System
- Sistem pendeteksi versi otomatis yang membaca `version_android.json` dari repositori ini
- Jika versi aplikasi di HP lebih rendah dari versi minimum yang ditetapkan, pengguna akan diminta memperbarui sebelum dapat menggunakan aplikasi
- Tombol unduh langsung mengarah ke APK terbaru tanpa harus membuka browser

### ⚙️ 8. Pengaturan Global Pipeline
- Konfigurasi model AI yang aktif
- Manajemen API Key dengan penyimpanan aman (SharedPreferences)
- Toggle auto cleanup file sementara
- Pilihan mode reframe: 4:3, 9:16, 16:9, 1:1

### 📊 9. Dashboard Proyek
- Tampilan statistik potongan hari ini dan total potongan keseluruhan
- Riwayat proyek terbaru dengan akses cepat
- Monitor penggunaan penyimpanan

---

## 🛠️ Stack Teknologi

| Komponen | Teknologi |
|---|---|
| Bahasa | Kotlin |
| UI Framework | Jetpack Compose (Material 3) |
| Video Processing | FFmpeg-Kit Android (v6.0.6) |
| Python Engine | Chaquopy (Python 3.10 di dalam APK) |
| Video Download | yt-dlp |
| AI Integration | REST API multi-provider |
| Min SDK | Android 7.0 (API 24) |
| Target SDK | Android 14 (API 34) |
| Arsitektur | ARM64 + ARM32 |

---

## 📂 Struktur Penyimpanan

```
/sdcard/
├── Download/
│   └── Intisari_AutoCut_Masters/     ← Video master (unduhan YouTube)
│       ├── video_judul_1.mp4
│       └── video_judul_2.mp4
│
└── Movies/
    └── Intisari_AutoCut/              ← Klip hasil ekspor
        ├── Tips_Memasak_Ayam/         ← Subfolder otomatis (3 kata judul)
        │   ├── klip_01.mp4
        │   └── klip_02.mp4
        └── Review_Produk_Terbaik/
            └── klip_01.mp4
```

---

## 🔄 Riwayat Versi

### v1.0.0 — 5 Agustus 2026 *(Rilis Perdana)*
- 🎉 Rilis perdana aplikasi Android Native Intisari AutoCut
- ✅ Video Downloader terintegrasi (yt-dlp via Chaquopy)
- ✅ AI Analyzer dengan 7 provider (Gemini, DeepSeek, Groq, SambaNova, Cerebras, Cohere, OpenRouter)
- ✅ Auto Cut Engine dengan ekspor klip
- ✅ Subfolder dinamis berdasarkan 3 kata judul master
- ✅ Penyimpanan master video permanen (Smart Cache)
- ✅ Sistem Forced Update otomatis
- ✅ Ekspor resep potongan (.txt)
- ✅ Antarmuka glassmorphism premium dark mode

---

## ❓ Pertanyaan Umum (FAQ)

**Q: Apakah aplikasi ini gratis?**
A: Aplikasi dapat diunduh gratis, namun memerlukan token lisensi aktivasi untuk menggunakan fitur penuh. Hubungi tim IntisariApps untuk informasi pembelian lisensi.

**Q: Apa yang terjadi jika versi aplikasi saya lebih lama dari yang di GitHub?**
A: Aplikasi akan menampilkan notifikasi pembaruan wajib (*forced update*). Anda perlu mengunduh versi terbaru sebelum dapat melanjutkan penggunaan.

**Q: Di mana hasil potongan video disimpan?**
A: Di `/sdcard/Movies/Intisari_AutoCut/[Nama_Subfolder]/` yang diorganisir secara otomatis berdasarkan judul video.

**Q: Apakah data saya aman?**
A: Semua pemrosesan video dilakukan secara lokal di HP Anda. Hanya permintaan analisis teks yang dikirim ke server AI pihak ketiga yang Anda pilih.

---

## 📞 Dukungan

- **Website:** [intisariapps.com](https://intisariapps.com)
- **Email Dukungan:** support@intisariapps.com
- **Laporkan Bug:** [GitHub Issues](https://github.com/intisariapps-com/Intisari-AutoCut-Android/issues)

---

<div align="center">

Dibuat dengan ❤️ oleh **IntisariApps**

*Khusus untuk kreator konten Indonesia yang cerdas dan efisien*

</div>
