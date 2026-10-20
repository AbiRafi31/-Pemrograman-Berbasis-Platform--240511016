# Analisis Komparatif Platform: Web, Desktop, dan Mobile

- **Mata Kuliah:** Pemrograman Berbasis Platform
- **Nama:** ABI RAFI FIRDAUS AL GHOZALI
- **NIM:** 240511016

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

Dari ketiga platform, saya paling tertarik mempelajari platform mobile. Hampir semua aktivitas saya sehari-hari dilakukan lewat HP, jadi saya penasaran bagaimana aplikasi yang sering saya pakai itu dibuat. Saya juga ingin suatu hari bisa membuat aplikasi sendiri yang berguna bagi orang lain.

Tantangan terbesar saat setup environment ada dua. Pertama, ukuran Android Studio dan SDK-nya besar, sehingga proses unduh dan instalasinya cukup lama, apalagi ada banyak lisensi yang harus disetujui satu per satu di setup wizard. Kedua, saya masih belum terbiasa dengan Git. Saya sempat mendapat error "not a git repository" karena menjalankan git add di folder yang belum berisi repository. Nama repository saya juga awalnya belum sesuai ketentuan, sehingga harus diganti. Selain itu, file analisis saya sempat belum ikut ter-push ke GitHub karena salah memasukkannya ke folder repo.

Untuk mengatasinya, saya akan mengunduh tools saat koneksi stabil dan membaca pesan error dengan teliti sebelum mencari solusinya. Saya juga akan membiasakan menjalankan git status sebelum commit dan push untuk memastikan posisi folder dan file sudah benar. Jika masih ada kendala, saya akan bertanya kepada teman atau dosen, lalu mencatat solusinya agar tidak terulang.
