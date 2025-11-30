# Contributing

Panduan singkat untuk menambah atau merapikan konten manual di repo ini.

1. Struktur dan penempatan
   - Semua file situs disimpan di folder `docs/`.
   - Manual dikelompokkan per folder numerik (`docs/00`, `docs/01`, dst.).
   - Ikuti penamaan file yang sudah ada (mis. `M100100010362500ENG.html`).

2. Menambah file
   - Masukkan file HTML dan aset terkait (gambar, CSS, JS) ke folder yang sesuai.
   - Jika menambahkan banyak file gambar, compress dahulu untuk menghemat ruang.

3. Preview lokal
   - Jalankan `cd docs && python3 -m http.server 8000` lalu buka `http://localhost:8000`.

4. Commit dan workflow
   - Jika repo **public**, gunakan branch terpisah per perubahan dan buat Pull Request.
   - Jika repo **private/internal**, tim dapat push langsung ke `main` setelah koordinasi.
   - Gunakan pesan commit singkat dan jelas, mis. `Add: manual M1001000XXXXX (Electrical)`.

5. Perhatian hak cipta
   - Jangan tambahkan materi yang Anda tidak punya izin untuk mendistribusikan secara publik.
   - Jika materi berlisensi pihak ketiga, beri catatan pada file atau `NOTICE.md`.

6. Kontak
   - Jika ragu terkait struktur atau lisensi, hubungi admin repo sebelum publish.
