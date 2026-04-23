
---

## 🚀 Cara Menjalankan Secara Lokal

1. **Clone atau download** repository ini.
2. Buka file `index.html` dengan browser modern (Chrome, Edge, Firefox, Safari).
3. Website akan langsung berfungsi — **tidak perlu server lokal**.

> ⚠️ Jika membuka via `file://`, beberapa browser mungkin memblokir fetch JSON. Gunakan ekstensi **Live Server** di VS Code atau jalankan dengan `python -m http.server` untuk hasil terbaik.

---

## 🌍 Deploy ke GitHub Pages

1. Upload seluruh isi repository ke GitHub.
2. Masuk ke **Settings > Pages**.
3. Pilih **Source**: `Deploy from a branch` → `main` → folder `/ (root)`.
4. Klik **Save**. Website akan online dalam 1–2 menit.

---

## 📝 Sumber Data

Data kanji dan pola kalimat disusun secara manual berdasarkan kurikulum dasar bahasa Jepang (setara JLPT N5–N4). Anda dapat mengedit atau menambahkan entri baru langsung di file JSON:

- **Data Kanji.json**: setiap entri memiliki properti `kanji`, `reading`, dan `meaning`.
- **Data Pola kalimat.json**: setiap entri memiliki `pola` (string atau array), `arti`, dan `contoh` (array berisi `kalimat` & `terjemahan`).

---

## 🛠️ Teknologi

- **HTML5**, **CSS3** (desain responsif, mobile‑friendly)
- **JavaScript** (ES6, fetch API, manipulasi DOM)
- **Google Fonts** – Noto Sans JP & Quicksand
- **JSON** sebagai penyimpanan data statis

---

## 📄 Lisensi

Proyek ini bersifat **open-source** dan bebas digunakan untuk keperluan belajar maupun pengembangan lebih lanjut. Atribusi tidak diwajibkan, namun sangat dihargai.

---

## 💡 Kontribusi

Ingin menambah kosakata atau memperbaiki terjemahan?  
Silakan **fork** repository ini, lakukan perubahan, lalu ajukan **pull request**. Pastikan format JSON tetap valid.

---

## 📧 Kontak

Jika ada pertanyaan atau masukan, silakan buka **Issue** di repository GitHub ini.

---

**Selamat belajar! がんばってください！** 🇯🇵
