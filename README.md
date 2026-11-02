# Pemburu Bintang Nebula — modifikasi dari Star Catcher
Game HTML5/Canvas/JavaScript murni, bukan Phaser. Tidak memakai CDN, npm, atau aset berbayar. Semua aset contoh dibuat untuk materi ini.

## Menjalankan
Ekstrak ZIP. Buka folder di VS Code lalu jalankan index.html dengan Live Server. Alternatif: `python -m http.server 8000` lalu buka http://localhost:8000. index.html juga dapat dibuka langsung untuk contoh ini.

## Kontrol
Panah kiri/kanan atau A/D; tombol layar untuk sentuh. Tangkap bintang +15 poin, meteor mengurangi nyawa. Durasi 45 detik, nyawa 3. Enter atau tombol Mulai ulang mengulang permainan.

## itch.io
Unggah ZIP ini sebagai proyek HTML. Aktifkan “This file will be played in the browser”. Pilih ukuran embed yang sesuai, periksa pratinjau sebelum publikasi. index.html berada di akar ZIP.

## GitHub Pages
Unggah ISI folder ini ke akar repository public milik Anda. Jangan unggah ZIP saja. Settings > Pages > Deploy from a branch > main > /(root) > Save. Tunggu deployment selesai dan buka URL yang GitHub tampilkan.

## Modifikasi
CONFIG pada game.js mengatur durasi, kecepatan, interval kemunculan, peluang meteor, dan poin bintang. Ubah judul pada index.html. Uji lagi setelah perubahan. Untuk game Phaser/webpack, unggah HASIL build, bukan folder src saja.

## Hak penggunaan
Kode dan aset contoh ini boleh dipakai, dimodifikasi dan dipublikasikan untuk pembelajaran. Jangan mengaku sebagai pembuat tunggal jika ketentuan tugas meminta pengungkapan bantuan. Cantumkan perubahan Anda di README.

## Catatan perubahan (modifikasi saya)
- **Judul:** "Star Catcher" menjadi "Pemburu Bintang Nebula" (title tab, heading, dan deskripsi di index.html).
- **Unsur 1 – Gameplay (CONFIG di game.js):** durasi 60 → 45 detik, kecepatan pemain 430 → 480, interval kemunculan 0,60 → 0,45 detik, peluang meteor 24% → 30%, poin bintang 10 → 15.
- **Unsur 2 – Tampilan:** tema warna biru tua/cyan diganti nebula ungu-pink (latar halaman, kanvas, bintang latar, tanah, kapal pemain, tombol, dan teks) di style.css dan game.js.
