# SATRIA 360

Sistem Monitoring K3 & Lingkungan Hidup (EHS) berbasis web satu halaman (single-file).

## Fitur
- Dashboard ringkasan, modul K3, Lingkungan, Kebakaran (peta hotspot)
- Perizinan (status masa berlaku otomatis), Pelatihan, Sertifikasi, Agenda
- Anggaran & Realisasi (serapan otomatis), CAPA, Laporan Instansi, Pengaturan akun
- Ekspor Excel, penyimpanan otomatis di browser, Backup/Pulihkan data (JSON)

## Menjalankan
Buka `index.html` di browser (butuh internet untuk memuat Tailwind, Chart.js, Leaflet, dan ikon dari CDN).

## Menayangkan lewat GitHub Pages
1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**, branch `main`, folder `/ (root)`
3. Buka `https://<username>.github.io/<nama-repo>/`

## Catatan penting
- Data disimpan di `localStorage` browser masing-masing pengguna, bukan di server. Gunakan tombol Backup secara berkala.
- Halaman login masih simulasi (belum ada autentikasi nyata). Jangan menaruh data sensitif di repositori publik.
- Data awal di `index.html` adalah contoh. Ganti sebelum dipakai nyata.
