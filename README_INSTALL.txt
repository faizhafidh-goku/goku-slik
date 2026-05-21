SLIK Angsuran Presisi - Mobile/PWA

Isi paket:
- index.html
- manifest.webmanifest
- service-worker.js
- html2pdf.bundle.min.js
- folder icons
- KTP_3208011311980002.txt sebagai data contoh

Cara paling stabil untuk iOS dan Android:
1. Upload semua isi folder ini ke hosting HTTPS statis, misalnya Netlify Drop, Vercel, GitHub Pages, atau hosting kantor.
2. Buka URL HTTPS tersebut di HP.
3. iPhone/iPad: buka Safari > Share > Add to Home Screen.
4. Android: buka Chrome > menu titik tiga > Install app atau Add to Home screen.

Catatan:
- PWA/offline install penuh memerlukan HTTPS. Jika dibuka dari file lokal atau IP lokal HTTP, aplikasi tetap bisa dicoba, tetapi fitur install/offline bisa dibatasi browser.
- APK Android dan IPA iOS native memerlukan build tool serta signing. Android perlu JDK + Android Studio/SDK. iOS perlu Xcode dan akun Apple Developer/TestFlight/App Store.
