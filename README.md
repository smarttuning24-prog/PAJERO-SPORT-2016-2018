# Mitsubishi Pajero Sport (2016-2018)

Koleksi manual servis, technical information, dan body repair untuk Mitsubishi Pajero Sport (MY 2016-2018).

Tujuan repo ini: menyimpan versi situs/manual yang bisa diakses oleh tim bengkel internal untuk referensi teknis.

Penting - Hak Cipta
- Pastikan Anda memiliki izin untuk membagikan atau mempublikasikan manual pabrikan. Banyak manual pabrikan dilindungi hak cipta; jika ragu, simpan repo sebagai *private* atau host pada server internal.

Preview lokal
- Untuk melihat situs secara lokal dari root repo:

```bash
# jika situs berada di `docs/` (direkomendasikan for GitHub Pages)
cd docs
python3 -m http.server 8000
# buka http://localhost:8000
```

Hosting
- Untuk GitHub Pages: letakkan semua file situs di folder `docs/` pada branch `main`, lalu aktifkan Pages pada repository settings (Branch: `main`, Folder: `/docs`).
- Untuk private/internal hosting: simpan repo sebagai private dan deploy ke webserver internal (nginx/apache) dengan proteksi jaringan.

Struktur yang direkomendasikan
- `docs/` — semua file situs (HTML/CSS/JS/assets).
- `docs/index.html` — halaman utama (sudah dibuat redirect ke `main.html` jika diperlukan).
- `README.md` — panduan singkat ini.
- `CONTRIBUTING.md` — petunjuk menambah/merapikan manual.

Cara menambah manual baru
1. Tambahkan file HTML ke folder yang sesuai di `docs/` (mis. `docs/00`, `docs/01`, dst.).
2. Ikuti penamaan konsisten: `M<chapter>_<id>...ENG.html`.
3. Commit dan buka PR (atau push langsung jika repo private dan tim sudah sepakat).

Kontak
- Untuk masalah teknis terkait struktur atau hosting, hubungi admin repo.

---
_Generated/updated by repository assistant on behalf of workshop._

