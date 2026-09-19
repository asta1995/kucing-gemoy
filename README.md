# 🐱 Kucing Gemoy Catch! 🐾

> *Bantu Meow makan ikan sebanyak-banyaknya, hindari bom, dan jadilah sultan koin di game web kasual yang super nagih ini!*

[![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-UI-38bDF8?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

---

## 🎮 Tentang Game
**Kucing Gemoy Catch!** adalah game web kasual berbasis HTML5 Canvas & TailwindCSS yang dirancang ringan, responsif untuk perangkat seluler (*mobile-friendly*), dan sangat adiktif. Pemain bertugas menggerakkan seekor kucing yang semakin lama semakin "gemoy" (membesar) karena kekenyangan makan ikan sambil menghindari rintangan bom berbahaya.

---

## ✨ Fitur Unggulan
- 🐟 **Dynamic Gameplay:** Semakin tinggi skor, kecepatan jatuh item akan bertambah dan ukuran kucing akan ikut mengembang!
- 🪙 **Sistem Koin & Toko (Shop):** Kumpulkan koin dari permainan untuk membuka fitur belanja, skin spesial, dan gacha.
- 🎁 **Gacha Kotak Misteri:** Buka kotak misterius untuk mendapatkan bonus koin instan, *Shield*, atau *Magnet*.
- ⚡ **Skill Spesial:**
  - 🛡️ **Shield:** Melindungi kucing dari ledakan bom.
  - 🧲 **Magnet:** Menarik ikan dan koin secara otomatis ke arah kucing.
- 🔄 **Fitur Revive Dinamis:** Hidup lagi saat Game Over dengan menonton iklan atau menggunakan koin dengan kenaikan harga bertahap (`+25 Koin` tiap revive).
- 🎡 **Lucky Coin Multiplier (Spin Wheel):** Putar jarum meter di akhir game untuk menggandakan koin sesi permainan hingga 10x!
- 🚫 **No-Ads Pass:** Sistem langganan bebas iklan sementara yang terintegrasi dengan `localStorage`.
- 💳 **Simulasi Payment Gateway:** Simulasi top-up koin instan ala Midtrans (QRIS/E-Wallet).

---

## 🕹️ Cara Bermain
1. **Kontrol Pergerakan:**
   - Gunakan tombol panah **Kiri (`⬅️`) / Kanan (`➡️`)** di layar sentuh atau *keyboard* (`A` / `D` / *Arrow Keys*).
   - Bisa juga dengan melakukan *Tap* atau *Swipe* langsung di area kanvas game.
2. **Kumpulkan Poin:**
   - 🐟 **Ikan / Sushi:** Menambah skor dan ukuran kucing.
   - 🪙 **Koin:** Menambah pundi-pundi mata uang untuk belanja di Toko.
   - 💣 **Bom:** Mengurangi nyawa (❤️). Jangan disentuh kecuali *Shield* aktif!

---

## 🛠️ Teknologi yang Digunakan
- **HTML5 Canvas** (Rendering Game 2D & Partikel)
- **TailwindCSS** (Desain Antarmuka/UI Responsif)
- **Web Audio API** (Efek suara murni tanpa file eksternal)
- **Vanilla JavaScript (ES6)** (Logika permainan & state management)
- **Local Storage** (Penyimpanan data *highscore*, *koin*, *skin*, dan *pass* lokal)

---

## 🚀 Cara Menjalankan (Run Locally)
Kamu tidak memerlukan instalasi *dependency* yang rumit (seperti Node.js/npm) karena game ini dibuat *pure* dalam satu file tunggal (`index.html`).

1. *Clone* repository ini atau *Download* sebagai ZIP:
   ```bash
   git clone [https://github.com/username-kamu/kucing-gemoy-catch.git](https://github.com/username-kamu/kucing-gemoy-catch.git)
