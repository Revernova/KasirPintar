# KasirPintar & Stock Flow AI
**Aplikasi Web Point of Sales (POS) & Manajemen Mutasi Inventaris Berbasis AI**

Aplikasi ini dikembangkan untuk memenuhi penugasan **Final Project Track AI (Batch 2) - Topik 2 (AI untuk Pembuatan Apps/Website / Vibe Coding)**.

---

## Fitur Utama

1. **Point of Sales (POS) Kasir:**
   - Pencarian produk cepat & filter kategori dinamis.
   - Keranjang belanja real-time, validasi ketersediaan stok fisik.
   - Kalkulasi otomatis: subtotal, diskon fleksibel, kalkulasi uang kembalian tunai.
   - Modal cetak struk belanja (*print preview*) ramah cetak thermal/A4.

2. **Pencatatan Mutasi Barang (Keluar / Masuk):**
   - **Barang Masuk (Restock):** Pencatatan pasokan dari supplier dengan penambahan saldo stok instan.
   - **Barang Keluar (Non-Penjualan):** Pencatatan barang rusak, kadaluwarsa, atau sampel.
   - **Pemotongan Otomatis:** Setiap transaksi kasir otomatis memotong stok dan mencatat riwayat mutasi keluar.

3. **Riwayat Transaksi Penjualan:**
   - Log seluruh nota kasir lengkap dengan detail produk, waktu transaksi, dan total nominal.
   - Fitur ekspor riwayat penjualan ke format CSV untuk pembukuan.

4. **Konsultan AI Pintar (Gemini API):**
   - **Audit Risiko Stok:** Menganalisis produk yang berada di bawah ambang batas minimum dan merekomendasikan jumlah restock beserta estimasi modal.
   - **Strategi Promo Bundling:** Menyusun rekomendasi paket diskon dan strategi kenaikan margin laba.
   - Dilengkapi fallback simulasi lokal otomatis jika penguji belum memasukkan Gemini API Key.
1. Buat repository baru di GitHub dan upload file `index.html`.
2. Masuk ke **Settings > Pages**, pilih branch `main`, lalu klik **Save**.
3. Tautan publik GitHub Pages akan aktif dalam 1-2 menit.
