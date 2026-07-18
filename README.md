# 🚀 Sodium App - Share VPN Fast

A completely free, ad-free Android utility to share a VPN or proxy connection over a hotspot (HTTP, SOCKS5, Shadowsocks). This repository contains the releases (APK artifacts), documentation, and distribution metadata so users can safely download and install the app.


---

## Quick links
- Releases (APK downloads): https://github.com/davisJq07/Sodium-App.ShereVpnFast/releases/tag/Sodium
- Latest release: Sodium-Alpha-version.apk (prerelease)


---

## Quickstart — تثبيت سريع

1. على جهاز Android المستضيف (Phone A) شغّل الهوتسبوت وافتح تطبيق Sodium ثم اضغط Start.
2. على الجهاز المستقبل (Phone B) اتصل بشبكة الهوتسبوت الخاصة بـ Phone A.
3. لتحميل التطبيق: نزّل الملف APK من صفحة Releases عبر الرابط أعلاه.
4. تفعيل تثبيت التطبيقات من مصادر غير معروفة (Settings → Security) — اتبع تعليمات نظام Android.
5. تأكد من ال��حقق من الشيك‑سوم للتحقق من صحة الملف قبل التثبيت (انظر CHECKSUMS.txt).

Quickstart (EN):
1. Enable hotspot on Phone A, open Sodium, press Start.
2. On Phone B connect to the hotspot network.
3. Download the APK from Releases and sideload it (enable "Install unknown apps").
4. Verify the SHA256 checksum (see CHECKSUMS.txt) before installing.

---

## Important safety & trust notes
- Current APKs attached to this repository are debug builds. For production use you should install a signed release build (AAB/APK) from a trusted channel (Google Play, F‑Droid, or a signed Release attached here). Debug APKs are intended for testing only.
- Always verify the SHA256 checksum before installing. Example command on Linux/macOS:

  curl -L -o Sodium-debug.apk "https://github.com/davisJq07/Sodium-App.ShereVpnFast/releases/download/Sodium/Sodium-debug-0x071.apk"
  sha256sum Sodium-debug.apk

- If you need a signed production build, open an issue or follow the CONTRIBUTING.md to request a release with a signed APK/AAB.

---

## What this release provides
- SOCKS5 (UDP-capable via compatible clients)
- HTTP proxy sharing via hotspot (port 8080)
- Shadowsocks support
- No ads, no subscriptions, no tracking on device

---

## How you can help
- Report bugs using the template in Issues.
- Share the project link and a short explanation on Reddit/Telegram/Discord.
- Star the repo if you find it useful.

---

## Links and metadata
- Repository: https://github.com/davisJq07/Sodium-App.ShereVpnFast
- Releases: https://github.com/davisJq07/Sodium-App.ShereVpnFast/releases

---

## License
This project is licensed under the MIT License — see LICENSE.

