# 🎮 Game Batu Gunting Kertas

Game sederhana **Batu, Gunting, Kertas** berbasis **HTML, CSS, dan JavaScript**.
Pemain dapat melawan komputer dengan sistem skor otomatis dan tampilan interaktif menggunakan ikon dari Font Awesome.

## 📌 Fitur

* ✊ Pilihan Batu
* ✋ Pilihan Kertas
* ✌️ Pilihan Gunting
* 🤖 Komputer memilih secara random
* 📊 Sistem skor pemain dan komputer
* 🎨 Tampilan sederhana dan responsif
* ⚡ Dibuat menggunakan JavaScript vanilla (tanpa framework)

---

## 🛠️ Teknologi yang Digunakan

* **HTML5**
* **CSS3**
* **JavaScript**
* **Font Awesome** (untuk ikon tangan)

---

## 📂 Struktur Project

```bash
📁 batu-gunting-kertas
│── index.html
│── style.css
│── app.js
└── README.md
```

---

## 🚀 Cara Menjalankan Project

1. Download atau clone repository ini

```bash
git clone https://github.com/username/nama-repository.git
```

2. Masuk ke folder project

```bash
cd nama-repository
```

3. Buka file `index.html` di browser

---

## 🎮 Cara Bermain

1. Pilih salah satu tombol:

   * Batu
   * Kertas
   * Gunting

2. Komputer akan memilih secara otomatis.

3. Hasil pertandingan akan muncul:

   * Menang 🟢
   * Kalah 🔴
   * Seri 🟠

4. Skor akan bertambah sesuai hasil permainan.

---

## 📸 Tampilan Game

Game memiliki tampilan sederhana dengan:

* Area skor pemain dan komputer
* Ikon pilihan pemain dan komputer
* Tombol interaktif untuk memilih aksi

---

## 🧠 Logika Permainan

Aturan dasar:

* Batu mengalahkan Gunting
* Gunting mengalahkan Kertas
* Kertas mengalahkan Batu

Komputer memilih secara acak menggunakan:

```javascript
Math.floor(Math.random() * randomClasses.length)
```

---

## 📈 Pengembangan Selanjutnya

Beberapa fitur yang bisa ditambahkan:

* 🔊 Efek suara
* 🌙 Dark mode
* 🏆 Sistem best of 3 / best of 5
* 📱 Responsive mobile version
* 💾 Penyimpanan skor menggunakan Local Storage
* 🎞️ Animasi saat bermain

---

## 👨‍💻 Author

Dibuat oleh **Bayu**

---

## 📄 License

Project ini bebas digunakan untuk belajar dan pengembangan pribadi.
