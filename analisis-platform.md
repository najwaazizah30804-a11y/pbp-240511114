# Analisis Komparatif Platform

## Tabel Perbandingan Platform

| Aspek | Web | Desktop | Mobile |
| :--- | :--- | :--- | :--- |
| **Bahasa Utama** | HTML, CSS, JavaScript, TypeScript | C++, C#, Java, Python, Electron (JS/TS) | Java, Kotlin (Android), Swift (iOS), Dart (Flutter) |
| **Arsitektur** | Client-Server / Monolithic / Microservices (REST API/GraphQL) | Standalone (Monolithic) / Client-Server | Client-Server / Mobile Architecture (MVVM, MVP, VIPER) |
| **Cara Distribusi** | Hosting di Web Server (Akses via URL/Browser) | File Installer (.exe, .msi, .dmg, .deb) / App Store platform | App Store (Google Play Store, Apple App Store, APK) |
| **Keunggulan** | *Cross-platform* tanpa install, pembaruan aplikasi instan, mudah diakses dari perangkat apa saja | Performa sangat tinggi, akses penuh ke hardware/OS lokal, dapat berjalan *offline* penuh | Sangat portable, memanfaatkan sensor perangkat (GPS, Kamera, NFC), *user engagement* tinggi (Notifikasi) |
| **Keterbatasan** | Keterbatasan akses ke hardware lokal, sangat bergantung pada koneksi internet | Instalasi manual & pembaruan cukup rumit, keterbatasan kompatibilitas antar OS | Resource terbatas (baterai, memori, layar kecil), proses kelulusan/review aplikasi yang ketat di App Store |
| **Contoh Aplikasi** | Trello, Canva, Google Docs | Visual Studio Code, Adobe Photoshop, Spotify Desktop | WhatsApp Mobile, Gojek, Instagram App |

---

## Daftar Referensi
1. **Mozilla Developer Network (MDN).** *Introduction to Web Development & Web Architecture*. Terintegrasi secara online pada: https://developer.mozilla.org/
2. **Android Developers.** *Guide to App Architecture*. Google, 2024. Tersedia pada: https://developer.android.com/topic/architecture
3. **Microsoft Learn.** *Desktop Application Development Documentation*. Microsoft, 2024. Tersedia pada: https://learn.microsoft.com/en-us/windows/apps/
## Refleksi Pengalaman Setup Environment

Di antara ketiga platform yang dipelajari, platform **Web** merupakan platform yang paling menarik bagi saya. Hal ini dikarenakan kemudahan dalam hal aksesibilitas dan proses distribusinya. Pengembangan aplikasi Web memungkinkan aplikasi untuk langsung diakses oleh pengguna global hanya melalui peramban (browser) tanpa mengharuskan pengguna melakukan instalasi perangkat lunak terlebih dahulu. Selain itu, ekosistem teknologi Web saat ini berkembang sangat cepat dengan berbagai kerangka kerja (*framework*) modern yang sangat fleksibel.

Tantangan terbesar yang saya hadapi selama proses *setup environment* adalah ketika melakukan unduhan dan konfigurasi **Android Studio** beserta Java JDK. Ukuran berkas Android Studio dan SDK-nya yang sangat besar membutuhkan koneksi internet yang stabil serta ruang penyimpanan disk yang cukup lapang. Selain itu, menyelaraskan variabel lingkungan (*environment variables*) seperti `JAVA_HOME` dan `PATH` di sistem operasi lokal sempat menimbulkan sedikit kendala saat dipanggil melalui terminal.

Untuk mengatasi tantangan tersebut, rencana saya adalah melakukan manajemen ruang penyimpanan dengan membersihkan berkas yang tidak terpakai serta mengunduh SDK secara bertahap saat koneksi internet stabil. Saya juga secara aktif membaca dokumentasi resmi instalasi dan memanfaatkan pustaka pustaka komunitas serta forum diskusi untuk memastikan seluruh konfigurasi *path* dan *tools* pengembangan terpasang dengan benar dan terintegrasi tanpa error.