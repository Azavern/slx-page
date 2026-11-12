# slx-page — Landing page sailox.my.id

Landing page untuk game **CONNECTION** (simulasi hacker Android, oleh
RFL-KSPULLX) yang di-host di https://sailox.my.id/.

- `index.html` — draf landing page v1 (dibuat Ryn atas permintaan Veo,
  sudah direview Veo: "udah pas"). Hero "BANGUN PC. JALANKAN MISI. JADI
  LEGENDA.", tombol unduh APK v0.1.5 ke
  https://sailox.my.id/connection-latest.apk.
- `privacy.html`, `terms.html` — Privacy Policy + Terms of Service yang
  sedang live (tidak diubah).
- `index.html` mengikuti aturan visual game: hitam solid, biru `#3b82f6`,
  panel flat tanpa gradien/glow/shadow, tanpa emoji.

## Deploy

Deploy dilakukan Eriri (root di VPS) ke `/var/www/sailox/` — ganti
`index.html` saja, `privacy.html` + `terms.html` jangan disentuh — dan
hanya atas perintah Shizu dengan pengumuman jam + durasi dulu.

## Catatan

- Label versi di draf masih `v0.1.5`, sementara game sudah `0.2.0` live.
  Tautan `connection-latest.apk` selalu menunjuk versi terbaru, tapi label
  ini dicek dan diatur sendiri oleh Shizu/Eriri sebelum deploy.
- Source code game/server TIDAK ada di repo ini (sengaja).
