# Tugas Sub CPMK-3 - Penalaran Komputer

## 📋 Deskripsi Proyek

Repositori ini berisi hasil tugas **Tugas Sub CPMK-3** yang dikerjakan dengan pendekatan case-based reasoning. Materi dikembangkan dari repositori kakak tingkat sebelumnya dan sekarang disesuaikan untuk memenuhi CPMK-3.

> 🎯 **Fokus tugas**: membangun representasi kasus dari dokumen putusan, melakukan retrieval kasus, reuse solusi, dan evaluasi model pada data hukum.

## 🧑‍🤝‍🧑 Anggota Tim

- Dino Ibnu Zein — NIM 202310370311107
- Marcellio Maulana Cholik — NIM 202310370311152

## 📂 Struktur Proyek

```
UAS_PK/
├── Data/
│   ├── raw/                  # dokumen putusan teks mentah
│   └── processed/            # dataset terstruktur untuk analisis
│       └── cases.csv
├── Notebook/
│   ├── PK_Tahap_1_(Case_Base).ipynb
│   ├── PK_Tahap_2_(Case_Representation).ipynb
│   ├── PK_Tahap_3_(Case_Retrieval).ipynb
│   ├── PK_Tahap_4_(Solution_Reuse).ipynb
│   └── PK_Tahap_5_(Model_Evaluation).ipynb
├── requirements.txt
└── README.md
```

## 📖 Komponen Utama

- `Data/raw/` : file putusan Pengadilan Negeri mentah.
- `Data/processed/cases.csv` : dataset yang sudah diproses menjadi tabel kasus untuk representasi dan evaluasi.
- `Notebook/` : notebook Jupyter untuk setiap tahapan CPMK-3.
- `requirements.txt` : daftar paket Python yang diperlukan.

## 🚀 Cara Instalasi

1. Buat virtual environment dan aktifkan:
   ```bash
   python -m venv env
   env\Scripts\activate    # Windows
   source env/bin/activate  # Linux/Mac
   ```

2. Install dependency dari `requirements.txt`:
   ```bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

3. Jalankan Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📌 Pipeline End-to-End

Karena proyek ini berbentuk notebook, pipeline end-to-end dijalankan dengan membuka dan mengeksekusi notebook secara berurutan.

1. Buka `Notebook/PK_Tahap_1_(Case_Base).ipynb`
   - Membangun basis kasus dan membersihkan dokumen putusan.
2. Buka `Notebook/PK_Tahap_2_(Case_Representation).ipynb`
   - Membuat representasi kasus dari data yang sudah diproses.
3. Buka `Notebook/PK_Tahap_3_(Case_Retrieval).ipynb`
   - Menguji pencarian kasus dan retrieval berdasarkan representasi.
4. Buka `Notebook/PK_Tahap_4_(Solution_Reuse).ipynb`
   - Menyusun ulang solusi yang relevan dari kasus yang ada.
5. Buka `Notebook/PK_Tahap_5_(Model_Evaluation).ipynb`
   - Mengevaluasi performa model retrieval dan hasil akhir.

> Catatan: Jalankan setiap notebook dari atas ke bawah untuk memastikan variabel dan data tersedia.

## 💻 Contoh Perintah

### Instalasi
```bash
python -m venv env
env\Scripts\activate
pip install --upgrade pip
pip install -r requirements.txt
```

### Menjalankan Notebook
```bash
jupyter notebook
```

### Menjalankan notebook dari terminal (opsional)
```bash
jupyter nbconvert --to notebook --execute Notebook/PK_Tahap_1_(Case_Base).ipynb --output Notebook/PK_Tahap_1_(Case_Base)_run.ipynb
```

## 🔧 Tujuan Tugas

- Membangun basis kasus dari dokumen putusan.
- Mengembangkan representasi kasus yang dapat diinput ke sistem retrieval.
- Menerapkan metode case-based reasoning untuk reuse solusi.
- Mengevaluasi performa model retrieval dan klasifikasi.

## 📝 Catatan Adaptasi

Proyek ini berasal dari repositori kakak tingkat yang awalnya untuk tugas UAS Penalaran Komputer. Konten sekarang disusun ulang untuk kebutuhan **Tugas Sub CPMK-3** dan dilengkapi dengan nama anggota tim.

## 💡 Rekomendasi Perubahan Lainnya

- Pastikan setiap notebook mencantumkan judul tugas saat ini dan nama anggota tim.
- Hapus semua badge atau dokumentasi placeholder yang tidak sesuai dengan isi repo.
- Tambahkan ringkasan peran untuk setiap anggota jika diminta oleh dosen.


