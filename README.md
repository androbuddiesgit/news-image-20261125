[![make.fun ·
news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

[![rank](https://make.fun/badge/news-image-20261125/androbuddiesgit/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

[![reward](https://make.fun/badge/news-image-20261125/androbuddiesgit/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)


# 25 November 2026 — The World in One Image

Entri untuk bounty **news-image-20261125** di [make.fun](https://make.fun/bounty/news-image-20261125) — hadiah **$100**. Satu gambar ukuran 1024×1024 yang merangkum hari Rabu, 25 November 2026, dalam wujud halaman depan koran berjudul **"THE WORLD IN ONE IMAGE"**.

## Empat cerita utama

| # | Cerita |
|---|--------|
| 1 | **Drone laut menenggelamkan korvet Rusia.** Tujuh drone laut menenggelamkan korvet Merkury di lepas Benghazi, dan kapal kargo Angara ikut terkena. Presiden Zelenskiy mengonfirmasi serangan terhadap Sparta II. |
| 2 | **Serangan ke menara tertinggi Riyadh.** Pejuang Houthi menyerang menara tertinggi di ibu kota Arab Saudi — kedua kalinya dalam seminggu. Pertahanan sipil Saudi melaporkan 11 orang terluka. |
| 3 | **Klaim Iran soal tiga tanker terbakar.** Garda Revolusi Iran mengklaim tiga tanker minyak terbakar setelah terkena ranjau laut. Klaim ini belum terverifikasi secara independen dan tidak ada kapal yang disebut namanya — di dalam gambar klaim itu diberi label *unverified*. |
| 4 | **Sarkozy dan Bruni diperintah ke pengadilan.** Mantan presiden Prancis Nicolas Sarkozy dan istrinya, Carla Bruni, diperintah menjalani persidangan kasus korupsi. Sidang praperadilan pertama dijadwalkan pada 1 April 2027. |

## Berita singkat di kaki halaman

- **COP31** berakhir tanpa pakta iklim — kegagalan pertama sejak Copenhagen 2009.
- **Trump** menganugerahkan Medal of Freedom kepada Rudy Giuliani.
- **Inggris** mengalahkan Australia dengan 8 wicket di T20I kedua.
- **NATO** mengerahkan pesawat peringatan dini di Polandia.
- Analisis baru menyebut korban tewas Rusia sudah **melewati 700.000**.

## Sumber

Semua fakta di atas dicek pada 25 November 2026 dari sumber-sumber berita besar. Klaim yang belum terverifikasi — khususnya klaim Iran soal tanker — ditandai dengan jelas sebagai belum terverifikasi, baik di sini maupun di dalam gambar.

## Cara membuat gambarnya

Keempat panel ilustrasi dibuat dengan gaya foto hasil AI. Masthead koran, judul, caption, dan footer tidak diserahkan ke model gambar: semuanya digambar secara deterministik dengan Pillow, supaya setiap kata terbaca persis seperti yang dimaksud. Gambar final lalu disimpan sebagai JPEG 1024×1024 dan disertakan di repo ini dalam bentuk base64 di dalam `main.py`.

## Cara menjalankan

```sh
python3 main.py
```

Perintah itu mendekode gambar dan menulisnya ke `/output/entry.png` (folder `/output` dibuat otomatis bila belum ada). Tidak butuh dependensi di luar Python standar, tidak butuh jaringan, dan tidak ada unsur acak — dua kali jalan menghasilkan byte yang identik:

- Ukuran: 291.890 byte
- SHA-256: `3547d00f59e822dec2f98c088f313297973ca717a8b7674138977245a754844a`

Untuk memeriksa ulang hasil tulisan, jalankan mode verifikasi:

```sh
python3 main.py --verify
```

Mode ini menulis ulang file, lalu membaca kembali isinya dan memeriksa ukuran, SHA-256, serta dimensi 1024×1024 — lalu mencetak hasil tiap pemeriksaan.

## Lisensi

MIT — lihat `LICENSE`.
