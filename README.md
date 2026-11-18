# 101daily

Atlas interaktif 101daily untuk mahasiswa kedokteran hewan. Satu file (`index.html`), tanpa build.

## Isi
- **Anatomi & Otot 3D**: sapi, kambing/domba, kuda, anjing, kucing, ayam, kura-kura, ular. Putar 360°, klik otot untuk nama, fungsi, protein, dan lokasi injeksi. Ada mode **Kuis otot**.
- **Mata 3D**: 8 hewan, bentuk pupil dan tapetum berbeda, potongan bola mata, otot luar mata.
- **Mikroskop Parasit**: 8 preparat (feses, apus darah, kerokan kulit), lensa 4×–100×, fokus, geser preparat.
- **Histopatologi**: hati, usus, kulit, otot, paru (normal vs patologi).
- **Embriologi**: zigot sampai organogenesis, lapisan germinal, tabel perkembangan ayam.
- **Reproduksi**: betina dan jantan 9 hewan, tabel perbandingan.
- **Ulas Darah**: apus darah 6 hewan (anjing, kucing, sapi, kuda, kambing, ayam) dengan sel-sel darah, kondisi normal/anemia/parasit darah, kuis sel, dan latihan hitung diferensial leukosit.

## Menjalankan
Buka `index.html` di browser (perlu internet untuk memuat Three.js dari unpkg).

## GitHub Pages
1. Buat repo `101daily.github.io` di akun/organisasi `101daily`, unggah `index.html` dan `README.md`.
2. Settings → Pages → Branch `main` / root → Save.
3. Alamat: `https://101daily.github.io/`

## Foto atlas sendiri
Taruh foto yang kamu punya hak pakainya di `assets/repro/` dengan nama `sapi-betina.jpg`, `anjing-jantan.jpg`, dst (kunci: sapi, kambing, kuda, babi, anjing, kucing, ayam, kura, ular). Tampil otomatis di tab Reproduksi.

## Catatan
Semua model dan gambar dibuat dengan kode (skematis), bukan foto asli. Nilai (protein, gestasi, dll) berupa perkiraan; cocokkan dengan atlas dan buku rujukan. Info injeksi hanya untuk belajar anatomi, bukan petunjuk dosis.
