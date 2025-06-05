# 📊 Capstone Project: Understanding Attrition – Who’s Leaving and Why

## 📁 Proyek Modul 3 – Data Analyst Bootcamp

Dalam proyek ini, saya berperan sebagai seorang *Data Analyst* untuk menganalisis penyebab dan karakteristik karyawan yang mengundurkan diri (attrition) dari perusahaan. Dengan menggunakan dataset fiktif dari IBM, analisis ini bertujuan untuk memberikan *insight berbasis data* yang dapat digunakan untuk meningkatkan strategi retensi karyawan.

---

## 📝 Latar Belakang

Attrition atau pengunduran diri karyawan menjadi salah satu isu penting yang dihadapi tim manajemen SDM di perusahaan. Jika attrition terus terjadi, perusahaan akan menghadapi penurunan produktivitas, meningkatnya biaya rekrutmen dan pelatihan, serta hilangnya pengetahuan dan pengalaman penting dalam organisasi.

Saat ini, jumlah karyawan yang resign tercatat sebanyak 237 orang (16,12% dari total karyawan), sehingga hanya tersisa 1.233 karyawan aktif. Analisis attrition diperlukan untuk memahami penyebab utama dan merumuskan strategi retensi yang efektif.

---

## 👥 Stakeholder

Pihak-pihak yang berkepentingan dan berwenang menindaklanjuti hasil analisis attrition:

1. **HR Manager / HR Business Partner**: Bertanggung jawab atas operasional manajemen SDM, menyusun dan mengeksekusi program retensi, onboarding, mentoring, serta kebijakan lembur.
2. **HR Director / Chief Human Capital Officer (CHCO)**: Menetapkan arah strategis kebijakan SDM, menyetujui kebijakan baru, mengalokasikan anggaran, dan membawa temuan ke level direksi.
3. **Department Head (misal: Head of Sales)**: Memimpin departemen dengan attrition tinggi, melakukan intervensi langsung seperti redistribusi kerja, pelatihan tim, dan pemantauan kepuasan kerja.

---

## 🧭 Metodologi Analisis

Analisis dilakukan melalui tiga pendekatan utama:

1. **Eksplorasi Data (EDA)**: Menampilkan pola dan tren pengunduran diri secara visual, seperti membandingkan persentase resign berdasarkan usia, gender, atau departemen.
2. **Uji Statistik (Inferensial)**: Menggunakan teknik statistik (Mann-Whitney U test, Chi-Square Test, Kruskal-Wallis) untuk mengetahui signifikansi hubungan antar variabel.
3. **Interpretasi Berbasis Data**: Semua insight diambil dari hasil analisis statistik, bukan asumsi atau opini pribadi.

**Tools:** Python (Pandas, Seaborn, Matplotlib, Scipy)

---

## 🎯 Tujuan Bisnis

- Mengurangi tingkat resign yang merugikan perusahaan.  
- Menekan biaya rekrutmen dan pelatihan akibat turnover tinggi.  
- Mempertahankan talenta muda yang potensial.  
- Meningkatkan efektivitas strategi retensi karyawan.  
- Mendukung pengambilan keputusan manajerial berbasis data.

---

## ❓ Pertanyaan Bisnis

1. Bagaimana demografi karyawan yang resign?  
2. Bagaimana karakteristik karyawan dari kelompok usia rentan resign?  
3. Departemen atau job role mana yang memiliki tingkat attrition tinggi?  
4. Apa karakteristik dari departemen dengan attrition tertinggi?  
5. Bagaimana attrition rate berdasarkan durasi kerja karyawan?  

---

## 📄 Dataset

- **Sumber**: IBM HR Analytics – [Kaggle Link](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  
- **Jumlah entri**: 1.470 baris  
- **Kolom penting**: `Age`, `Attrition`, `Department`, `JobRole`, `MonthlyIncome`, `DistanceFromHome`, `YearsAtCompany`, dll.

---

## 🧪 Proses Analisis

1. **Data Understanding**  
   Memahami kolom, distribusi, dan konteks bisnis dari data HR.

2. **Data Cleaning**  
   Dataset tidak memiliki missing values; dilakukan deteksi duplikasi.

3. **Exploratory Data Analysis (EDA)**  
   Visualisasi attrition berdasarkan usia, jenis kelamin, status pernikahan, dan pendapatan.  
   Identifikasi departemen dengan tingkat attrition tinggi.

4. **Statistical Summary**  
   Statistik deskriptif untuk membandingkan karyawan yang bertahan vs resign.

5. **Insight & Recommendation**  
   Insight disampaikan secara runut, didukung visualisasi, dan disertai rekomendasi.

---

## 📈 Insight Utama

- Attrition tertinggi terjadi pada karyawan *usia muda (≤ 30 tahun)*.
- *Sales Department* dan *Human Resources* memiliki tingkat attrition yang relatif tinggi.
- Karyawan yang tinggal jauh dari kantor cenderung lebih mudah resign.
- Kepuasan kerja dan gaji juga menjadi faktor penting penyebab resign.

---

## ✅ Rekomendasi

- Perlu strategi retensi untuk usia muda dan karyawan awal karier.
- Evaluasi beban kerja serta lakukan rotasi di departemen dengan tingkat attrition tinggi.
- Pertimbangkan kompensasi berbasis kinerja dan fleksibilitas lokasi kerja.
- Perkuat program engagement dan pelatihan bagi karyawan baru.

---

## 🛠 Teknologi yang Digunakan

- **Python** (Pandas, Matplotlib, Seaborn)  
- **Jupyter Notebook**  
- **Looker Studio** (untuk dashboard interaktif)  
- **Canva / Google Slides** (untuk presentasi)

---

## 🔗 File & Dokumentasi

- **data-analyst-attrition.ipynb** – Notebook analisis utama  
- **WA_Fn-UseC_-HR-Employee-Attrition.csv** – Dataset asli  
- [Dashboard Looker Studio](https://lookerstudio.google.com/reporting/89b4df9b-ea99-4586-827c-9d7c6c4e1f89)  
- [Slide Presentasi](https://drive.google.com/file/d/1J4bKyix2w_i6hc8gZ957NGl3E3pTaK8G/view?usp=sharing)

---

## 📌 Catatan

Proyek ini merupakan bagian dari evaluasi Capstone Project Modul 3 dan dibuat untuk tujuan edukasi. Semua data digunakan secara etis dan hanya untuk keperluan pembelajaran.