# HAEN RAG — Unduhan

Aplikasi desktop **HAEN RAG**: gerbang data HAEN AI untuk HAEN GROUP. Aplikasi ini membuka sistem HAEN RAG (`https://rag.haen.co.id`) di jendelanya sendiri, lengkap dengan ikon tray dan pembaruan otomatis. Akses hanya untuk pengguna yang diundang Owner HAEN GROUP.

## Unduh
Ambil `HAEN-RAG_<versi>_x64-setup.exe` dari **[rilis terbaru](https://github.com/sa4nha-beep/HAEN-RAG-Releases/releases/latest)**, lalu jalankan. Windows 10/11 64-bit.

**Peringatan SmartScreen:** installer belum memakai sertifikat code signing, jadi Windows bisa menampilkan "Windows protected your PC". Klik **Info selengkapnya → Tetap jalankan**.

## Cek keaslian file
Bandingkan dengan `SHA256SUMS.txt` di halaman rilis:

```powershell
Get-FileHash .\HAEN-RAG_0.1.0_x64-setup.exe -Algorithm SHA256
```

## Pembaruan
Aplikasi memeriksa versi baru saat dibuka (setelah 30 detik) dan setiap 6 jam, lalu **bertanya dulu** sebelum mengunduh. Bisa juga lewat ikon tray → *Periksa pembaruan*. Setiap pembaruan diverifikasi tanda tangannya sebelum dipasang.

## Privasi
Repo ini hanya berisi installer. Aplikasi tidak mengirim data ke pihak lain: ia hanya membuka server HAEN RAG milik HAEN GROUP dan membaca info rilis dari repo ini.
