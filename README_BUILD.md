# Ibu AI - Android APK

Project ini membungkus Google Apps Script Web App menjadi aplikasi Android.

URL aplikasi:
https://script.google.com/macros/s/AKfycbyJozXO6dyNntUm8ex1NvRXD090WuVy0EJYZpcf037n4Y7SdziYBe3ZnFnAhe7cwPv_1Q/exec

## Build di Android Studio
1. Buka folder project ini.
2. Tunggu Gradle selesai sinkronisasi.
3. Pilih Build > Generate App Bundles or APKs > Generate APKs.
4. APK debug akan berada di:
   app/build/outputs/apk/debug/app-debug.apk

## Catatan
Aplikasi membutuhkan internet.
WebView sudah mengaktifkan JavaScript dan DOM Storage.
Tombol Back Android akan kembali ke halaman WebView sebelumnya.
