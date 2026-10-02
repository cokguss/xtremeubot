# DOKUMEN INTEGRASI KHUSUS: LISENSI PERANGKAT LUNAK & KETENTUAN LAYANAN XTREMEBOT

**Masa Berlaku Terintegrasi: Sejak 17 Februari 2023 hingga Saat Ini (Diperbarui secara Berkala)**

Selamat datang di **XtremeBot**. Dokumen ini merupakan kesatuan hukum yang mengikat secara sah antara Anda (selaku "Pengguna", "Pemasang", atau "Penerima Lisensi") dengan **BloodsKiL** (selaku "Pencipta", "Pemilik Hak Cipta", dan "Pengembang Utama"). 

Dengan mengunduh, menyalin, menginstal, menjalankan, atau menggunakan perangkat lunak XtremeBot (termasuk seluruh modul Python, hot-path engine Cython/Rust/Nim/Zig/Elixir, WhatsApp IPC Bridge, dan aset digital pendukungnya), Anda menyatakan secara sadar bahwa Anda telah membaca, memahami, dan menyetujui seluruh isi dari Lisensi dan Ketentuan Layanan ini.

Jika Anda tidak menyetujui salah satu atau seluruh poin dalam dokumen ini, Anda tidak diperkenankan untuk menginstal atau menggunakan XtremeBot, dan diwajibkan untuk menghapus seluruh salinan kode sumber dari penyimpanan Anda.

---

## BAGIAN I: LISENSI PENGGUNAAN PERANGKAT LUNAK (SOFTWARE LICENSE)

### Pasal 1: Kepemilikan Hak Cipta & Hak Kekayaan Intelektual
1. Seluruh kode sumber, arsitektur sistem, modul khusus (seperti modul OSINT, Cyber Shield, Aegis Proxy, Islamic Module, Stalker Pro, dll.), dokumentasi, dan desain visual dari XtremeBot adalah milik eksklusif **BloodsKiL**.
2. Perlindungan hak cipta atas XtremeBot terhitung secara resmi sejak rilis perdana kode dasar pada tanggal **17 Februari 2023** dan tetap dilindungi undang-undang yang berlaku hingga saat ini.
3. Hak kepemilikan ini tidak dialihkan kepada Pengguna dalam bentuk apa pun. Pengguna hanya mendapatkan hak pakai terbatas yang tunduk pada ketentuan dokumen ini.

### Pasal 2: Hibah Lisensi Terbatas (Grant of License)
1. BloodsKiL memberikan lisensi non-eksklusif, tidak dapat dipindahtangankan, dapat ditarik kembali, dan terbatas kepada Pengguna untuk mengoperasikan XtremeBot pada server pribadi (self-hosted / VPS) milik Pengguna sendiri.
2. Lisensi ini diberikan khusus untuk penggunaan pribadi dan non-komersial, kecuali jika Pengguna telah terdaftar sebagai Reseller resmi atau memiliki kesepakatan tertulis khusus dengan BloodsKiL.
3. Lisensi penggunaan ini dibatasi berdasarkan jumlah akun/node Telegram yang aktif sesuai dengan paket langganan (Premium/VIP/Ultra) yang dibeli secara sah melalui BloodsKiL.

### Pasal 3: Batasan dan Larangan Penggunaan (Restrictions)
Sebagai penerima lisensi, Anda **dilarang keras** untuk:
1. Mendistribusikan ulang kode sumber XtremeBot kepada pihak ketiga tanpa izin tertulis dari BloodsKiL.
2. Melakukan dekripsi, dekompilasi, atau reverse-engineering terhadap modul-modul inti XtremeBot yang telah dienkripsi atau dikompilasi (seperti Cython `.so` / `.pyd` binaries atau modul Rust/Nim/Zig/Elixir hot-path).
3. Menghapus, menyamarkan, atau memodifikasi watermark, atribusi pembuat, tautan Telegram `@bloodskil3`, atau kredit "BloodsKiL" yang tertanam di dalam bot maupun landing page.
4. Menggunakan kode sumber atau memotong bagian kode XtremeBot untuk dijadikan proyek userbot baru dengan nama lain untuk tujuan komersialisasi mandiri tanpa persetujuan.

---

## BAGIAN II: KETENTUAN LAYANAN & PENGGUNAAN (TERMS OF SERVICE)

### Pasal 4: Kepatuhan Terhadap Pihak Ketiga (Telegram & WhatsApp)
1. XtremeBot beroperasi dengan berinteraksi langsung pada Application Programming Interface (API) resmi dan protokol MTProto milik Telegram, serta menggunakan Baileys Library untuk menjembatani protokol WhatsApp secara lokal.
2. Pengguna memahami sepenuhnya bahwa Telegram melarang keras penggunaan akun untuk aktivitas spamming, manipulasi sistem, atau pelanggaran Ketentuan Layanan Telegram lainnya.
3. Segala bentuk tindakan disipliner dari pihak Telegram atau WhatsApp, termasuk namun tidak terbatas pada:
   - Pembatasan akun (spambot/read-only).
   - Pemblokiran nomor secara permanen (ban).
   - Penghapusan grup/saluran akibat aktivitas bot.
   Adalah **tanggung jawab penuh Pengguna**. BloodsKiL tidak bertanggung jawab atas kerugian akun tersebut.

### Pasal 5: Kebijakan Fitur Broadcast (Auto-Gcast / Spam / Promosi)
1. Fitur broadcast otomatis (`.gcast`, `.promosi`, `.spam`) dirancang untuk mempermudah manajemen informasi. Namun, penggunaannya wajib mematuhi etika berkomunikasi online dan regulasi anti-spam yang berlaku.
2. Pengguna dilarang menyalahgunakan fitur broadcast untuk:
   - Menyebarkan konten pornografi, perjudian online, perdagangan ilegal, atau penipuan finansial.
   - Melakukan spamming massal yang mengganggu kenyamanan pengguna grup lain secara ekstrim.
3. Pengembang menyediakan fitur "Anti-Spam Adaptive" dan "Blacklist Chat" untuk meminimalisir risiko ban. Pengguna sangat disarankan untuk mengaktifkan fitur perlindungan ini.

### Pasal 6: Sistem Berlangganan Premium & VIP
1. Layanan tambahan, fitur mutakhir, dan kapasitas bot ekstra didapatkan melalui skema berlangganan Premium atau VIP yang dikelola langsung oleh BloodsKiL.
2. Pembayaran biaya langganan bersifat final dan non-refundable (tidak dapat dikembalikan).
3. Status Premium, VIP, atau Ultra dapat dicabut secara sepihak dan seketika oleh BloodsKiL tanpa pengembalian dana apabila Pengguna terbukti melakukan pelanggaran berat terhadap lisensi ini (seperti mencoba merusak server autentikasi, menyebarkan file crack, atau menghina pengembang).

### Pasal 7: Privasi Data dan Keamanan Sesi
1. XtremeBot membutuhkan kredensial sensitif seperti `API_ID`, `API_HASH`, `BOT_TOKEN`, dan Session String Telegram untuk berfungsi.
2. Seluruh kredensial tersebut disimpan dalam database MongoDB lokal milik Pengguna atau server database yang dikonfigurasi secara pribadi oleh Pengguna melalui file `.env`.
3. BloodsKiL tidak mengumpulkan, menyalin, atau memperjualbelikan kredensial sesi Telegram Pengguna ke server pihak ketiga manapun. Keamanan file konfigurasi `.env` dan akses server VPS sepenuhnya berada di bawah kendali dan tanggung jawab Pengguna.

---

## BAGIAN III: BATASAN TANGGUNG JAWAB & GARANSI (DISCLAIMER)

### Pasal 8: Pernyataan "As Is" (Apa Adanya)
PERANGKAT LUNAK INI DISEDIAKAN OLEH PEMEGANG HAK CIPTA DAN KONTRIBUTOR "SEBAGAIMANA ADANYA" (AS IS) DAN "SEBAGAIMANA TERSEDIA" (AS AVAILABLE). SEGALA JAMINAN YANG TERSIRAT ATAU TERSURAT, TERMASUK NAMUN TIDAK TERBATAS PADA JAMINAN KELAYAKAN JUAL DAN KESESUAIAN UNTUK TUJUAN TERTENTU, DITOLAK SEPENUHNYA.

### Pasal 9: Batasan Tanggung Jawab Kerusakan
DALAM KEADAAN APA PUN, BLOODSKIL TIDAK BERTANGGUNG JAWAB ATAS SEGALA KERUSAKAN LANGSUNG, TIDAK LANGSUNG, INSIDENTAL, KHUSUS, ATAU KONSEKUENSIAL YANG TIMBUL DARI PENGGUNAAN ATAU KETIDAKMAMPUAN UNTUK MENGGUNAKAN PERANGKAT LUNAK INI, TERMASUK NAMUN TIDAK TERBATAS PADA:
1. Kehilangan data penting, kerusakan database MongoDB, atau kegagalan sistem VPS.
2. Kerugian finansial akibat terhentinya operasional bisnis atau penarikan status premium.
3. Kebocoran data yang disebabkan oleh kelalaian keamanan pada server pengguna (misalnya port database terbuka umum, kata sandi VPS lemah, dll.).

---

## BAGIAN IV: AMENDEMEN & HUKUM YANG BERLAKU

### Pasal 10: Perubahan Dokumen
BloodsKiL berhak untuk memperbarui, mengubah, atau mengganti bagian mana pun dari Lisensi dan Ketentuan Layanan ini sewaktu-waktu. Perubahan akan diumumkan melalui saluran Telegram resmi XtremeBot atau diperbarui langsung dalam berkas repositori ini. Penggunaan bot yang berkelanjutan setelah perubahan tersebut dipublikasikan merupakan bentuk persetujuan eksplisit terhadap versi terbaru.

### Pasal 11: Hukum Terintegrasi
Dokumen ini diatur dan ditafsirkan berdasarkan asas keadilan, etika pengembangan perangkat lunak terbuka-tertutup (hybrid proprietary), serta hukum perlindungan hak cipta digital. Segala perselisihan yang timbul akan diselesaikan secara kekeluargaan melalui diskusi langsung bersama BloodsKiL selaku pencipta platform.

---

**DITETAPKAN DI: JAKARTA, INDONESIA**  
**BERLAKU SEJAK: 17 FEBRUARI 2023**  
**VERSI TERAKHIR: 2026 (BERLAKU HINGGA SAAT INI)**  
**PENGEMBANG UTAMA: BloodsKiL**  
*Tautan Kontak Resmi: https://t.me/bloodskil3*
