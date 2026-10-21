# 🐍 Snake Game Ultimate Edition

> **A Modern, Retro-Arcade Snake Game Built with HTML5 Canvas, Tailwind CSS, and Web Audio API.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)

**Snake Game Ultimate Edition** adalah rekayasa ulang modern dari game Snake klasik retro. Dibuat murni menggunakan satu file web mandiri (*standalone single-file*) tanpa bantuan *framework* berat atau file *asset* eksternal. Game ini menyajikan visual neon *dark-mode*, animasi 2D Canvas kustom, efek suara sintetis, serta berbagai fitur interaktif modern.

---

## ✨ Fitur Utama (Features)

### 🎨 Visual & Grafis Kustom
* **Desain Objek Detail:** Bukan sekadar kotak/lingkaran! Makanan digambar realistis (Apel berdaun, Bintang Emas, Berlian, Pizza Slice, Koin Emas, dan Jamur Beracun).
* **Anatomi Ular Dinamis:** Kepala ular dilengkapi mata bercahaya dan lidah bercabang animasi, segmen tubuh membulat (*tapering tail*), dan efek tekstur sisik.
* **Sistem Kustomisasi Skin:** 
  * **6 Skin Ular:** *Emerald Neon, Cyber Cyan, Inferno Red, Galaxy Purple, Golden Glow,* dan *Rainbow Party*.
  * **4 Skin Makanan:** *Classic Apple, Golden Star, Cyan Diamond,* dan *Pizza Slice*.
  * Unlock skin baru dengan mencapai target High Score tertentu!

### 🕹️ Mode Permainan Bervariasi
1. **Classic Mode:** Ular dapat menembus batas layar (*wraparound*).
2. **Hardcore Mode:** Menabrak dinding menyebabkan Game Over.
3. **Maze Mode:** Map berisi rintangan tembok bata futuristik.
4. **Time Attack:** Batas waktu 60 detik (memakan makanan memberikan tamabahan +2 detik).

### ⚡ Power-Up & Item Spesial
* ⚡ **Speed Boost:** Kecepatan ekstra selama 7 detik.
* 🛡️ **Shield:** Perlindungan 1x dari tabrakan dinding atau tubuh sendiri.
* 🧲 **Food Magnet:** Menarik makanan ke arah kepala ular secara otomatis.
* ✂️ **Tail Shrinker:** Memotong panjang ekor ular secara instan.
* 👾 **Target Boss:** Serangga neon melompat yang memberikan bonus **+50 Poin**.
* 🍄 **Bad Food (Jamur Beracun):** Mengurangi poin (-15) jika termakan.

### 🎵 Audio & Efek Visual (Juice)
* **Web Audio API Sound Engine:** Efek suara (SFX) sintetis & Musik Latar (BGM) 8-Bit tanpa butuh file `.mp3` eksternal.
* **Particle System & Floating Text:** Animasi ledakan partikel saat makan & angka poin melayang.
* **Screen Shake:** Layar bergetar saat mendapat bonus atau menggunakan perisai.

### 🏆 Sistem Progresi & Kontrol
* **Combo Multiplier (x1 - x5):** Memakan makanan berturut-turut meningkatkan multiplier poin.
* **Badges / Achievements:** Buka piala pencapaian (*First Bite, Combo Master, Boss Hunter, Snake King*, dll).
* **Kontrol Responsif:** Dukungan **Keyboard** (Arrow Keys / WASD), **Touch Swipe**, dan **Virtual D-Pad** untuk perangkat Mobile/HP.
* **Penyimpanan Otomatis:** High Score, Skin Terbuka, dan Badges tersimpan di `localStorage`.

---

## 🚀 Cara Menjalankan (How to Run)

Proyek ini dibuat sebagai **Single File Web App**, sehingga sangat mudah dijalankan tanpa perlu proses kompilasi (*build process*) atau instalasi Node.js.

### Metode 1: Jalankan Langsung
1. Clone repositori ini atau unduh file zip-nya:
   ```bash
   git clone [https://github.com/USERNAME/snake-game-ultimate.git](https://github.com/USERNAME/snake-game-ultimate.git)
