# Analisis Komparatif Platform: Web, Desktop, dan Mobile

**Mata Kuliah:** Pemrograman Berbasis Platform
**Nama:** [ABI RAFI FIRDAUS AL GHOZALI]
**NIM:** [240511016]

## Tabel Perbandingan

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| Bahasa utama | HTML, CSS, JavaScript/TypeScript (front-end); PHP, Python, Java, Node.js, Go (back-end) | C#/.NET, C++, Java, Python; Electron memakai JavaScript | Kotlin dan Java (Android); Swift (iOS); Dart/Flutter, JavaScript/React Native (lintas platform) |
| Arsitektur | Client-server: browser (client) berkomunikasi lewat HTTP/HTTPS dengan server dan database; sering memakai pola MVC atau REST API | Aplikasi berjalan langsung di sistem operasi, memakai sumber daya lokal (file, CPU, GPU); umumnya monolitik atau berlapis (UI, logika, data) | Aplikasi di perangkat dengan SDK OS (Android/iOS), siklus hidup (lifecycle) ketat, sering terhubung ke backend/API cloud; pola MVVM/MVC |
| Cara distribusi | Di-deploy ke server/hosting dan diakses lewat URL; pembaruan langsung tanpa instal ulang | Installer (.exe, .msi, .dmg, .deb), portable app, atau toko aplikasi (Microsoft Store, Mac App Store) | Toko aplikasi resmi (Google Play, App Store) melalui proses review, atau APK untuk sideload di Android |
| Keunggulan | Lintas platform lewat browser, tanpa instalasi, pembaruan terpusat, jangkauan luas | Performa tinggi, akses penuh ke perangkat keras dan sistem file, bisa bekerja offline, cocok untuk aplikasi berat | Portabel, akses sensor (kamera, GPS, notifikasi push), dekat dengan pengguna, pengalaman sentuh yang natural |
| Keterbatasan | Bergantung pada koneksi internet dan kompatibilitas browser, akses perangkat keras terbatas, performa di bawah aplikasi native | Harus diinstal per perangkat, pengembangan per OS (kecuali memakai framework lintas platform), pembaruan tersebar | Layar kecil, baterai dan memori terbatas, fragmentasi perangkat (Android), aturan dan review toko aplikasi |
| Contoh aplikasi | Google Docs, Tokopedia (web), Wikipedia, GitHub | Microsoft Word, Visual Studio Code, Adobe Photoshop, Spotify Desktop | WhatsApp, Gojek, Instagram, Google Maps |

## Referensi

1. Mozilla Developer Network. *Learn Web Development*. https://developer.mozilla.org/en-US/docs/Learn_web_development
2. Electron. *Electron Documentation*. https://www.electronjs.org/docs/latest/
3. Microsoft. *Desktop Guide (.NET)*. https://learn.microsoft.com/en-us/dotnet/desktop/
4. Android Developers. *Android Developer Guides*. https://developer.android.com/guide

## Refleksi

[DRAF: sesuaikan dengan pengalaman Anda sendiri sebelum dikumpulkan]

Dari ketiga platform, saya paling tertarik mempelajari platform **mobile**. Alasannya, hampir semua orang membawa smartphone ke mana pun, sehingga aplikasi mobile terasa paling dekat dengan kebutuhan sehari-hari. Selain itu, aplikasi mobile bisa memanfaatkan kamera, GPS, dan notifikasi, yang membuat kemungkinan ide aplikasinya sangat luas.

Tantangan terbesar saat setup environment adalah **[pilih/ubah sesuai pengalaman: ukuran file Android Studio yang besar dan koneksi internet yang lambat / mengatur PATH untuk Java dan Node.js / spesifikasi laptop yang terbatas / bingung membuat repository dan melakukan clone]**. Hal ini membuat proses instalasi memakan waktu lebih lama dari perkiraan dan sempat membuat saya ragu apakah langkah yang saya lakukan sudah benar.

Rencana saya untuk mengatasinya adalah mengunduh installer saat koneksi stabil, mengikuti dokumentasi resmi setiap tools, dan memeriksa hasil instalasi memakai perintah versi di terminal setelah tiap langkah selesai. Jika masih bermasalah, saya akan mencari solusinya di dokumentasi atau forum seperti Stack Overflow, lalu bertanya kepada dosen atau teman sekelas. Saya juga akan mencatat setiap kendala dan solusinya agar mudah diulang jika harus menginstal ulang di kemudian hari.

*(± 190 kata)*
