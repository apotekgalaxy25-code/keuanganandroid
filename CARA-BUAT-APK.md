# Keuangan Keluarga - Cara membuat APK

## Cara 1 - Tanpa Android Studio (GitHub, gratis)
1. Buat repository baru di github.com, unggah SELURUH isi folder ini.
2. Buka tab Actions > "Build APK" > Run workflow.
3. Tunggu +-5 menit, unduh "Keuangan-Keluarga-APK" > app-debug.apk, pasang di HP.

## Cara 2 - Android Studio
1. Install Node.js, jalankan: npm install lalu npx cap sync android
2. Buka folder "android" di Android Studio > Build > Build APK(s).

## Cara 3 - Tanpa APK (PWA)
Unggah isi folder "www" ke hosting HTTPS, buka di Chrome Android > menu > "Instal aplikasi".

Ikon aplikasi: gambar kucing (sudah terpasang di semua ukuran).
Paket: 1 Bulan Rp15.000 - 1 Tahun Rp150.000 - Selamanya Rp250.000. Trial 15 hari.
Untuk APK rilis Play Store, ganti ke assembleRelease dan tanda tangani dengan keystore Anda.
