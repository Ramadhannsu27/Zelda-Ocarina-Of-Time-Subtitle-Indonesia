# The Legend of Zelda: Ocarina of Time - Subtitle & Teks Bahasa Indonesia

![License](https://img.shields.io/badge/License-CC--BY--NC--SA--4.0-blue.svg)
![Status](https://img.shields.io/badge/Status-100%25%20Completed-brightgreen.svg)
![Game](https://img.shields.io/badge/Game-The%20Legend%20of%20Zelda%3A%20Ocarina%20of%20Time-gold.svg)
![Platform](https://img.shields.io/badge/Platform-PC%20Native%20%7C%20Switch%20%7C%20Emulator-orange.svg)

Mod terjemahan menyeluruh (100% selesai) untuk game **The Legend of Zelda: Ocarina of Time** ke dalam **Bahasa Indonesia**. Kompatibel untuk **Ocarina Reborn (PC Native Port / Hookshot)**, konsol **Nintendo Switch (Atmosphere)**, dan **Emulator (Ryujinx, Yuzu, Suyu, Sudachi)**.

Dilengkapi dengan penyesuaian alokasi memori **ResourceSizeTable (RESTBL)** resmi sehingga **100% stabil dan bebas crash**.

---

## 🌟 Fitur Utama

- **100% Penerjemahan Dialog & Teks (21.138 Baris):**
  - **Alur Cerita & Cutscene:** Prolog Kokiri Forest, Pohon Deku, Pertemuan Putri Zelda, Kuil Waktu, Kebangkitan 6 Sage, hingga Pertempuran Akhir melawan Ganondorf.
  - **Seluruh Dialog NPC Hyrule:** Penduduk Desa Kokiri, Pasar Kastel Hyrule, Desa Kakariko, Kota Goron, Domain Zora, Peternakan Lon Lon, Danau Hylia, Lembah Gerudo, dan Gurun Hantu.
  - **Petunjuk & Lore:** Seluruh petunjuk peri Navi, Batu Berbisik (*Gossip Stones*), serta papan rambu penunjuk jalan.
  - **Antarmuka & Menu (UI):** Menu sistem, peta dunia, inventaris, status quest, dan jendela dialog konfirmasi.
  - **Mini-Game & Aktivitas Sampingan:** Panahan Kuda, Bowling Bombchu, Galeri Tembak Slingshot, Kolam Pancing, Rumah Harta Karun, Balapan Kuda Malon/Ingo, dan Kuburan Kakariko.
  - **Item & Perlengkapan:** Seluruh deskripsi senjata, perisai, tunik/pakaian, sepatu bot, topeng (*masks*), dan upgrade perlengkapan.
- **RESTBL Pre-patched (Anti-Crash):**
  Ukuran memori buffer teks bahasa Indonesia sudah dihitung ulang dan ditingkatkan ke batas aman (2.550.000 byte) di RESTBL multi-versi (`1.0.0`, `1.1.0`, `1.1.1`, `1.1.2`, `1.2.0`, `1.2.1`), sehingga mencegah crash *null-pointer* (`0xc0000005`).
- **Kompatibilitas Prompt Controller:**
  Mendukung layout kontroler DualSense/PS4/PS5, Xbox, Nintendo Switch Pro Controller, Steam Deck, dan Keyboard/Mouse tanpa teks bentrok.

---

## ⚠️ Syarat Penting

> [!IMPORTANT]
> **Bahasa Game Wajib Disetel ke "English (US)" atau "English (UK)"!**  
> Mod ini menggantikan berkas bahasa Inggris (`USen` dan `EUen`). Jika bahasa pada game atau emulator disetel ke bahasa lain (seperti Jepang atau Prancis), subtitle bahasa Indonesia tidak akan tampil.

---

## 📥 Panduan Instalasi

### 1. Ocarina Reborn / PC Native Port (Hookshot Engine)
1. Unduh paket rilis [`The_Legend_of_Zelda_Subtitle_Indonesia_v1.0.0.zip`](../../releases).
2. Buka folder instalasi game PC Anda (folder tempat `hookshot.exe` atau `ocarina_reborn.exe` berada).
3. Masuk ke folder `mods/` (jika belum ada, buat folder baru bernama `mods`).
4. Ekstrak folder `Subtitle Bahasa Indonesia` ke dalam folder `mods/`.
   Struktur direktori yang benar:
   ```text
   <Folder Game>/
   ├── hookshot.exe
   └── mods/
       └── Subtitle Bahasa Indonesia/
           └── romfs/
               ├── Mals/
               └── System/Resource/
   ```
5. Buka game, dan teks bahasa Indonesia akan langsung otomatis aktif!

---

### 2. Emulator PC & Android (Ryujinx / Yuzu / Suyu / Sudachi)
1. Buka emulator favorit Anda di PC/Android.
2. Klik kanan pada game **The Legend of Zelda** di daftar game:
   - **Ryujinx:** Pilih **Open Mod Directory**.
   - **Yuzu / Suyu / Sudachi:** Pilih **Open Mod Data Location**.
3. Buat folder baru, misalnya bernama `Subtitle Bahasa Indonesia`.
4. Salin folder `romfs/` dari rilis ini ke dalam folder tersebut:
   ```text
   .../load/<TitleID>/Subtitle Bahasa Indonesia/romfs/
   ```
5. Pastikan mod tercentang di menu Properties emulator, lalu jalankan gamenya.

---

### 3. Nintendo Switch Asli (CFW Atmosphere)
1. Matikan Nintendo Switch Anda dan masukkan kartu MicroSD ke PC.
2. Salin folder `romfs/` dari mod ini ke direktori Atmosphere:
   ```text
   sdmc:/atmosphere/contents/<TitleID_Game>/romfs/
   ```
3. Pasang kembali MicroSD ke Switch, boot ke CFW Atmosphere, dan nikmati gamenya!

---

## 📁 Struktur Berkas Mod

```text
Subtitle Bahasa Indonesia/
├── README.md
├── translations_id.json                                       <-- Kamus sumber terjemahan (21.138 baris)
└── romfs/
    ├── Mals/
    │   ├── EUen.Product.100.sarc.zs
    │   ├── EUen.Product.110.sarc.zs
    │   ├── USen.Product.100.sarc.zs
    │   └── USen.Product.110.sarc.zs
    └── System/Resource/
        ├── ResourceSizeTable.Product.100.Nin_Ounce_NVN2.rsizetable.zs
        ├── ResourceSizeTable.Product.100.rsizetable.zs
        ├── ResourceSizeTable.Product.110.Nin_Ounce_NVN2.rsizetable.zs
        ├── ResourceSizeTable.Product.110.rsizetable.zs
        ├── ResourceSizeTable.Product.111.Nin_Ounce_NVN2.rsizetable.zs
        ├── ResourceSizeTable.Product.111.rsizetable.zs
        ├── ResourceSizeTable.Product.112.rsizetable.zs
        ├── ResourceSizeTable.Product.120.rsizetable.zs
        └── ResourceSizeTable.Product.121.rsizetable.zs
```

---

## 👥 Kredit & Kontribusi

- **Penerjemah & Modder:** Ramadhannsu
- **Game Developer:** Nintendo
- **PC Port Engine:** Ocarina Reborn / Hookshot Team & Nintendo Recompilation Community
- Jika Anda menemukan kesalahan ketik (*typo*) atau terjemahan yang kurang pas, silakan buka **Issue** atau kirimkan **Pull Request**.

---

## ⚖️ Lisensi & Penafian (*Disclaimer*)

Mod ini didistribusikan secara gratis di bawah lisensi [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).  
Dilarang memperjualbelikan mod ini dalam bentuk apa pun. Hak cipta karakter, aset, dan cerita The Legend of Zelda sepenuhnya adalah milik Nintendo.
