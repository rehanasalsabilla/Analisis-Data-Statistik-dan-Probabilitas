# 📊 Praktikum Analisis Data Statistik dan Probabilitas

## 🧠 Pengertian Proyek  
Proyek ini merupakan tugas **Praktikum Modul 2 - Analisis Data Statistik dan Probabilitas**.  
Tujuan utama dari praktikum ini adalah **menerapkan konsep-konsep dasar probabilitas dan statistika menggunakan Python** untuk menyelesaikan berbagai permasalahan nyata, seperti analisis vaksinasi, pengaruh cuaca terhadap perilaku pengguna, analisis divisi pekerjaan, dan evaluasi data produksi industri.  

Setiap kasus diselesaikan dengan pendekatan matematis dan implementasi kode Python menggunakan library statistik untuk menghitung probabilitas, ekspektasi, varians, serta kovarians.

---

## 🧾 Deskripsi Proyek  
Notebook ini berisi **serangkaian studi kasus (Case A–D)** yang menggambarkan penerapan praktis dari teori probabilitas dan statistik, di antaranya:  
- Menghitung peluang menggunakan **Teorema Bayes**.  
- Menghitung **probabilitas bersyarat**.  
- Menentukan **distribusi binomial** untuk data cacat produk.  
- Menghitung **nilai harapan (mean), varians, dan kovarians** untuk analisis performa atlet.  

Setiap soal disertai langkah-langkah penyelesaian, implementasi dalam Python, dan hasil interpretasi.

---

## 📁 Dataset  
Terdapat beberapa jenis data yang digunakan dalam tiap kasus:
- **Case A:** Data jumlah orang yang terjangkit flu berdasarkan status vaksinasi.  
- **Case B:** Data jumlah pengguna *Grab-bike* dan *Grab-car* berdasarkan kondisi cuaca (hujan/cerah).  
- **Case C:** Data proporsi pekerja di dua divisi (Pengembangan & Pemasaran) berdasarkan pengalaman kerja.  
- **Case D:** Data hasil inspeksi produksi sekrup dari file CSV (`soal4_defect_test.csv`) untuk analisis kualitas produk.  
- **Case E (Soal 6):** Data skor teknikal dan artistik 25 atlet dari kompetisi internasional.

---

## ⚙️ Tools dan Teknologi  
- 🐍 **Python 3.x**  
- 📦 **Library:**
  - `numpy` → perhitungan numerik  
  - `pandas` → manajemen dan analisis data  
  - `scipy.stats` → distribusi probabilitas dan perhitungan statistik  
  - `matplotlib` / `seaborn` (opsional) → visualisasi data  

---

## 🔍 Tahapan Analisis  

### **Case A — Analisis Vaksinasi dan Flu**  
Menghitung peluang seseorang terkena flu berdasarkan status vaksin menggunakan **Teorema Bayes**.  
- P(Flu | Vaksin) = 0.0476  
- P(Flu | Tidak Vaksin) = 0.0909  
👉 Kesimpulan: Vaksinasi mengurangi peluang terkena flu hampir setengahnya.

---

### **Case B — Pengaruh Cuaca terhadap Penggunaan Transportasi Umum**  
Menganalisis hubungan antara kondisi cuaca (hujan/cerah) dengan pilihan transportasi (Grab-bike/Grab-car).  
- Peluang menggunakan Grab-bike: 0.67  
- Peluang Grab-car saat hujan: 0.98  
- Peluang Grab-car saat cerah: 0.09  
👉 Probabilitas bersyarat digunakan untuk memahami pengaruh cuaca terhadap perilaku pelanggan.

---

### **Case C — Analisis Pengalaman Kerja di Dua Divisi**  
Menghitung probabilitas pekerja berasal dari divisi tertentu berdasarkan lama pengalaman kerja.  
- P(Pengembangan | <3 tahun) = 0.30  
- Rasio Pengembangan : Pemasaran = 0.43  
👉 Mayoritas pekerja dengan pengalaman <3 tahun berasal dari Divisi Pemasaran.

---

### **Case D — Analisis Kualitas Produksi Sekrup (Distribusi Binomial)**  
Menganalisis data inspeksi kualitas untuk menentukan peluang cacat produk.  
- Peluang sekrup cacat = 0.01  
- Probabilitas kemasan perlu diganti = 0.0956  
👉 Sekitar 9.56% kemasan berpotensi cacat dan perlu diganti.

---

### **Case E — Analisis Skor Atlet (Ekspektasi, Varians, dan Kovarians)**  
Menghitung statistik deskriptif untuk data skor kompetisi atlet:  
- Nilai Harapan Skor Teknik = 91.1  
- Nilai Harapan Skor Artistik = 89.95  
- Varians Skor Teknik = 8.99  
- Varians Skor Artistik = 7.95  
- Matriks Kovarians =
  [[9.46, 4.27],
  [4.27, 8.37]]

---

👉 Kedua skor memiliki korelasi positif; semakin tinggi teknik, semakin tinggi pula nilai artistik.

---

## 📈 Hasil Akhir Analisis  

| Case | Topik | Metode | Hasil Utama |
|------|--------|---------|-------------|
| A | Probabilitas Flu & Vaksin | Teorema Bayes | Vaksin menurunkan peluang flu |
| B | Cuaca & Transportasi | Probabilitas Bersyarat | Cuaca hujan → Grab-car naik 98% |
| C | Divisi & Pengalaman | Probabilitas Total | 70% pekerja baru dari Pemasaran |
| D | Sekrup Cacat | Distribusi Binomial | 9.56% kemasan cacat |
| E | Skor Atlet | Statistik Deskriptif | Kovarians positif (teknik–artistik) |

---

## 💡 Insight dan Manfaat  
- Menunjukkan penerapan **konsep probabilitas dan statistik secara praktis** menggunakan Python.  
- Membantu memahami **relasi antar variabel** dalam data nyata (kesehatan, bisnis, industri, dan olahraga).  
- Melatih kemampuan **analisis kuantitatif dan interpretasi hasil statistik**.  
- Memberikan dasar bagi penerapan metode probabilistik lebih lanjut seperti *Bayesian inference* atau *predictive analytics*.

---

## 🏁 Kesimpulan Akhir  
1. Teorema Bayes dan probabilitas bersyarat efektif untuk memahami hubungan sebab-akibat pada data.  
2. Distribusi Binomial membantu mengestimasi kemungkinan kejadian cacat produk dalam sistem manufaktur.  
3. Nilai harapan, varians, dan kovarians memberikan wawasan tentang persebaran serta hubungan antar variabel numerik.  
4. Secara keseluruhan, proyek ini menggabungkan **konsep statistik klasik dan implementasi Python modern** untuk menjawab berbagai studi kasus data nyata.

---

👩‍💻 **Dibuat oleh:** Rehana Putri Salsabilla  
📘 **NRP:** 5027221015  
📚 **Mata Kuliah:** Praktikum Analisis Data Statistik dan Probabilitas  
🎓 **Modul 2 - Fakultas Teknologi Informasi dan Komunikasi**

