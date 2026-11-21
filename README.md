# 🚀 Web Portofolio Profesional - Mansur

Portofolio web modern, responsif, dan interaktif yang dibangun khusus untuk **Mansur** — **Machine Learning Engineer & Data Scientist**.

---

## 🌟 Fitur Utama

1. **Desain Modern & Glassmorphism**:
   - Tampilan profesional dengan palet warna dark & light theme.
   - Ambient glow effect dan kartu glassmorphism transparan.
   - Dilengkapi foto profil formal profesional dengan floating achievement badges.

2. **Dukungan Dark / Light Theme**:
   - Tombol toggle tema yang otomatis tersimpan di `localStorage`.

3. **Proyek Unggulan Terintegrasi GitHub**:
   - Filter interaktif (Machine Learning, Computer Vision, NLP & Sentiment, Web Application).
   - Menampilkan proyek terbaik dari akun GitHub [@Mansurgayo](https://github.com/Mansurgayo):
     - **Stress Chat Detector (Capstone Project DBS Foundation x Dicoding)**
     - **Cat Skin Disease Classifier (Deep Learning / Computer Vision)**
     - **Sistem Rekomendasi Jurusan Perguruan Tinggi**
     - **Absensi KKN Management App (Next.js & Prisma ORM)**
     - **Prediksi Penyakit Ginjal Kronis (Healthcare ML)**
     - **Automated Preprocessing & MLOps Pipeline (MLflow & CI/CD)**
     - **Sistem Rekomendasi Film (Cosine Similarity)**
     - **Analisis Sentimen & Klasifikasi Teks**

4. **Sertifikasi Resmi & Verifikasi Langsung**:
   - **Spotlight Kredensial**: *Coding Camp powered by DBS Foundation 2025* (Spesialisasi Machine Learning Engineer, 289+ jam, 14 modul selesai dengan nilai memuaskan).
   - **Pencarian Live (Instant Search)**: Cari dari 15 sertifikat resmi Dicoding Indonesia secara instan.
   - Tombol verifikasi langsung ke masing-masing halaman sertifikat resmi Dicoding.

5. **Timeline Pendidikan & Pelatihan**:
   - Universitas Abulyatama.
   - DBS Foundation Coding Camp 2025.
   - Dicoding Academy Learning Path.

6. **Formulir Kontak & Social Channels**:
   - Tautan langsung ke profil GitHub dan LinkedIn.
   - Formulir pesan interaktif dengan notifikasi toast.

---

## 📁 Struktur Direktori

```text
mansur-portfolio/
├── index.html                  # Halaman utama portofolio
├── README.md                   # Dokumentasi proyek & panduan deploy
└── assets/
    ├── css/
    │   └── style.css           # Styling lengkap (Dark/Light mode, Responsive)
    ├── js/
    │   └── main.js            # Interaktivitas (Filter proyek, Live search, Theme toggle)
    └── images/
        └── mansur.jpg          # Foto profil profesional Mansur
```

---

## ⚡ Cara Menjalankan Secara Lokal

1. Buka folder `mansur-portfolio` di VS Code / file explorer.
2. Klik dua kali file `index.html` untuk langsung membukanya di browser (Chrome, Edge, Firefox, Safari).
3. Atau jalankan local server sederhana menggunakan Python:
   ```bash
   cd mansur-portfolio
   python -m http.server 8000
   ```
   Buka `http://localhost:8000` di browser.

---

## 🌐 Cara Deploy Gratis ke GitHub Pages

Agar portofolio bisa diakses publik melalui `https://mansurgayo.github.io` atau `https://mansurgayo.github.io/portfolio`:

1. Buat repository baru di GitHub dengan nama `portfolio` (atau `mansurgayo.github.io`).
2. Masukkan semua file dari folder ini:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Mansur ML Engineer Portfolio"
   git branch -M main
   git remote add origin https://github.com/Mansurgayo/portfolio.git
   git push -u origin main
   ```
3. Di GitHub: buka tab **Settings** -> **Pages** -> pilih source **Deploy from a branch** -> pilih branch `main` -> Klik **Save**.
4. Website portofolio Anda akan online dalam beberapa menit!
