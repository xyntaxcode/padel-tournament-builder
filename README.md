# Rally Draw — Padel Tournament Builder

Alat penyusun turnamen padel berbasis web, satu file HTML tanpa dependensi backend.

## Fitur

- **Info turnamen** — nama acara, tanggal, lokasi, jumlah lapangan
- **Pilihan format**
  - Round Robin — semua pasangan saling bertanding
  - Gugur Langsung (single elimination) — bagan menyusut tiap babak
  - Grup + Gugur — round robin per grup, fase gugur disusun manual setelahnya
  - Mexicano — format dinamis khas padel; babak pertama dihasilkan otomatis, babak berikutnya menyesuaikan skor live
- **Peserta** — tambah/hapus pasangan ganda beserta kategori (Terbuka/Pemula/Menengah/Lanjutan)
- **Pengaturan skor** — jumlah set, game per set, golden point, super tiebreak
- **Jadwal otomatis** — penjadwalan round-robin (circle method) dengan pembagian lapangan per babak, dan generator bagan gugur dengan bye otomatis untuk jumlah peserta ganjil/bukan pangkat dua

## Menjalankan

Buka `index.html` langsung di browser — tidak perlu server atau instalasi apa pun.

## Batasan yang diketahui

- State hanya tersimpan di memori halaman (tidak ada localStorage/backend); refresh halaman akan mengembalikan ke data contoh.
- Format Mexicano dan Grup+Gugur memerlukan penyusunan manual untuk babak lanjutan, karena bergantung pada hasil pertandingan sebelumnya.
- Ini adalah desain dan implementasi orisinal, dibuat dari konsep umum penjadwalan turnamen padel — bukan hasil menyalin produk komersial mana pun.

---

Co-Authored-By: Claude Sonnet 5 <noreply@anthropic.com>
