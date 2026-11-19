# PR Pintra — Proyek Android

Aplikasi sederhana untuk mencatat pekerjaan rumah (PR), mata pelajaran, deadline, dan status selesai. Data disimpan secara lokal di perangkat menggunakan SharedPreferences.

## Cara membuka dan membuat APK
1. Instal **Android Studio** di komputer/laptop.
2. Ekstrak folder `PR_Pintra.zip`.
3. Android Studio → **Open** → pilih folder `PR_Pintra` (folder yang berisi `settings.gradle`).
4. Tunggu proses **Gradle Sync** selesai. Jika diminta, instal Android SDK Platform 35 dan Android Gradle Plugin yang diperlukan.
5. Untuk mencoba di HP: aktifkan Developer Options dan USB debugging, sambungkan HP, lalu tekan **Run ▶**.
6. Untuk membuat APK: pilih **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
7. Setelah selesai, tekan **locate** pada notifikasi. APK debug biasanya berada di `app/build/outputs/apk/debug/app-debug.apk`.
8. Pindahkan APK ke HP dan buka file tersebut. Jika diminta, izinkan instalasi dari sumber yang digunakan.

## Fitur
- Menambah PR dengan nama tugas, mata pelajaran, dan deadline.
- Menandai tugas sebagai selesai.
- Menghapus tugas dengan konfirmasi.
- Ringkasan jumlah tugas dan tugas selesai.
- Data tetap tersimpan setelah aplikasi ditutup.

## Catatan
- Dibutuhkan Android Studio dan koneksi internet pertama kali untuk mengunduh komponen Gradle/SDK.
- Proyek ini menghasilkan APK debug untuk uji coba. Untuk distribusi publik, buat signed release APK melalui **Build → Generate Signed Bundle / APK**.
- Package: `com.prpintra.app`
