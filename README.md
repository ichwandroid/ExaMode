
# ExaMode

Proyek ini terdiri dari:

- `pwa/` — Progressive Web App yang dibuka melalui WebView
- `kiosk_wrapper/` — Aplikasi Flutter untuk membungkus PWA dan menjalankannya dalam mode kiosk

## Cara Build APK di Windows

1. Install Flutter SDK dan Android Command Line Tools
2. Jalankan `flutter doctor` dan pastikan semuanya hijau
3. Masuk ke folder `kiosk_wrapper` dan jalankan:

```bash
flutter build apk --release
```

File APK akan muncul di `build/app/outputs/flutter-apk/app-release.apk`
