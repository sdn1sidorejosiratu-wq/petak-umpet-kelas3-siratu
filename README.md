# Petak Umpet SDN 1 Sidorejo

Game petak umpet 2D untuk siswa kelas 3. Cari 10 teman yang bersembunyi dalam 60 detik.
Bisa dimainkan di komputer (panah/WASD + Spasi) dan HP (tombol layar).

## Cara menayangkan lewat GitHub Pages
1. Buat repositori baru di github.com (misalnya `petak-umpet`), atur ke Public.
2. Unggah file `index.html` dan `README.md` ke repositori.
3. Buka Settings, lalu Pages. Pada Source pilih "Deploy from a branch", branch `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1-2 menit. Game bisa dibuka di `https://NAMA-GITHUB.github.io/petak-umpet/`.

## Catatan papan peringkat
Di GitHub Pages, skor tersimpan di perangkat masing-masing.
Untuk papan peringkat bersama, hubungkan ke Supabase atau Firebase
dengan mengganti fungsi `saveScore` dan `loadScores` di `index.html`.
