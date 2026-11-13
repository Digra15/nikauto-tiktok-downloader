# NikAuto TikTok Downloader

Web sederhana untuk download video TikTok tanpa watermark. Tempel link TikTok, lalu unduh HD / SD tanpa watermark, versi asli dengan watermark, atau audio MP3. Mendukung juga postingan foto (slideshow).

Tema sama seperti NikAuto TTS: navbar hitam, aksen lime, modern.

## Cara pakai
1. Tempel link TikTok (tiktok.com, vt.tiktok.com, vm.tiktok.com, atau teks bagikan)
2. Klik Ambil Video
3. Pilih kualitas unduhan

## Deploy di Cloudflare Pages
- Connect to Git repo ini, preset None/static, build command kosong, output root `/`
- Atau Direct Upload folder ini

## Catatan
- Mesin utama: API TikWM, cadangan otomatis: Cobalt API
- Web statis tanpa backend, tanpa API key
- Download end-to-end perlu dites di jaringan normal (di lingkungan build, fetch eksternal diblokir)
