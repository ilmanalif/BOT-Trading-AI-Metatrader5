<div align="center">
  <h1>🤖 Auto Trade AI</h1>
  <p><strong>Bot Trading Otomatis berbasis AI untuk MetaTrader 5</strong></p>
</div>

---

## ✨ Fitur

| Fitur | Deskripsi |
|-------|-----------|
| **Analisis AI Multi-Provider** | Google Gemini, OpenAI, DeepSeek, Claude — auto failover jika salah satu error |
| **Dashboard Web Real-Time** | Monitoring harga, equity, posisi terbuka, grafik TradingView, log AI |
| **Trading Otomatis** | Eksekusi BUY/SELL berdasarkan sinyal AI tanpa campur tangan manual |
| **Chart Mapping** | Analisis teknikal dengan gambar chart multi-timeframe (M15, H1, H4, D1) |
| **Risk Management** | Target harian, max loss, lot size otomatis/manual, SL/TP |
| **Multi-Session** | Indikator sesi Sydney, Tokyo, London, New York |
| **Akses dari HP** | Dashboard bisa dibuka dari perangkat mobile di jaringan yang sama |
| **Dark/Light Mode** | Tampilan nyaman di berbagai kondisi cahaya |
| **Sistem Aktivasi HWID** | Lisensi terikat perangkat untuk keamanan maksimal |
| **Ekspor PDF** | Riwayat trading bisa diekspor ke PDF |

---

## 📦 Persyaratan Sistem

| Komponen | Keterangan |
|----------|------------|
| **OS** | Windows 10 / 11 (64-bit) |
| **MetaTrader 5** | Sudah terinstall dan memiliki akun trading |
---

## 🚀 Cara Menjalankan

1. **Ekstrak** folder `AutoTradeAI` ke lokasi mana saja (disarankan di drive C: atau D:)
2. **Jalankan** `AutoTradeAI.exe` — klik dua kali
3. **Dashboard** akan terbuka otomatis di browser: **http://localhost:8000**

> ⚠️ Jika tidak terbuka otomatis, buka manual `http://localhost:8000` di browser.

---

## 🔧 Pengaturan Awal

### 1. Konfigurasi MetaTrader 5

Sebelum menjalankan, pastikan:
- MetaTrader 5 sudah terinstall dan **login** ke akun trading Anda
- Jalankan MetaTrader 5 **sebagai Administrator** (klik kanan → Run as Administrator)

### 2. Atur API Key di Dashboard

1. Buka menu **Pengaturan** di dashboard
2. Isi **Gemini API Key** (wajib) — daftar gratis di Google AI Studio
3. Isi **MT5 Path** sesuai lokasi MetaTrader 5 broker Anda
4. Atur **Symbol** (pair trading) dan **Timeframe** sesuai keinginan
5. Klik **Simpan**

### 3. Aktivasi Lisensi

1. Buka dashboard — modal aktivasi akan muncul
2. **Copy HWID** yang tampil
3. Klik paket sewa (1, 3, 6, 12 bulan, atau lifetime)
4. Hubungi **Telegram: [@ilmanalif](https://t.me/ilmanalif)** — kirimkan HWID Anda
5. Setelah pembayaran, masukkan **kode aktivasi** yang dikirim developer
6. Klik **Aktifkan** — bot siap digunakan

### 4. Mulai Bot

1. Klik tombol **Connect** di dashboard untuk menghubungkan ke MT5
2. Klik tombol **Start Bot** — bot akan mulai menganalisa dan trading otomatis

---

## 🖥️ Tampilan Dashboard

| Menu | Fungsi |
|------|--------|
| **Dasbor Analisa** | Grafik TradingView, posisi terbuka, analisa market, sinyal AI, log terminal |
| **Pengaturan** | Konfigurasi strategi, pair, timeframe, risk management, API Keys, MT5 Path |
| **Riwayat** | History trading dengan grafik performa, filter periode, ekspor PDF |

---

## ⚙️ Parameter Penting

| Parameter | Default | Keterangan |
|-----------|---------|------------|
| Symbol | XAUUSD | Pair trading (EURUSD, GBPUSD, dll) |
| Timeframe | H1 | M5, M15, H1, H4, D1 |
| Target Harian | 10% | Bot berhenti jika target tercapai |
| Max Loss Harian | 5% | Bot berhenti jika loss mencapai batas |
| Lot Mode | Auto Safe | Menyesuaikan lot berdasarkan equity |
| Volume | 0.01 | Lot tetap (jika mode Fixed) |
| Stop Loss | 50 pip | SL otomatis dari AI atau manual |
| Take Profit | 100 pip | TP otomatis dari AI atau manual |

---

## 🔐 Status Lisensi

Sidebar menampilkan sisa masa aktivasi dengan indikator warna:
- 🟢 **Hijau** — Lisensi aktif (≥7 hari)
- 🟡 **Kuning** — Lisensi akan habis (<7 hari)
- 🔴 **Merah** — Lisensi akan segera habis (<3 hari)

> Bot akan berhenti otomatis jika lisensi kedaluwarsa.

---

## ❓ Troubleshooting

| Masalah | Solusi |
|---------|--------|
| **MT5 tidak terhubung** | Pastikan MT5 sudah login dan jalankan sebagai Administrator. Cek MT5 Path di pengaturan dashboard. |
| **API Key error** | Pastikan API key valid. Aktifkan Generative Language API di Google Cloud Console. |
| **Aktivasi gagal** | Pastikan kode 64 karakter. HWID harus sama dengan saat pembuatan kode. |
| **Port 8000 dipakai** | Matikan aplikasi lain yang menggunakan port 8000. |
| **Error saat startup** | Jalankan `AutoTradeAI.exe` sebagai Administrator. |
| **Bot tidak trading** | Cek apakah target harian sudah tercapai. Cek koneksi MT5 dan API Key. |

---

## 📱 Kontak

- **Telegram**: [@ilmanalif](https://t.me/ilmanalif)
- **Website**: [saya.ilmanalif.my.id](https://saya.ilmanalif.my.id)

---

<div align="center">
  <p>
    <strong>Auto Trade AI</strong> — © 2024 ilmanalif. All rights reserved.<br>
    <sub>Proprietary software. Unauthorized copying, modification, or distribution prohibited.</sub>
  </p>
</div>
