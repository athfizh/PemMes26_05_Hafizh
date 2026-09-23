<div align="center">

```
██████╗ ███████╗███╗   ███╗███╗   ███╗███████╗███████╗
██╔══██╗██╔════╝████╗ ████║████╗ ████║██╔════╝██╔════╝
██████╔╝█████╗  ██╔████╔██║██╔████╔██║█████╗  ███████╗
██╔═══╝ ██╔══╝  ██║╚██╔╝██║██║╚██╔╝██║██╔══╝  ╚════██║
██║     ███████╗██║ ╚═╝ ██║██║ ╚═╝ ██║███████╗███████║
╚═╝     ╚══════╝╚═╝     ╚═╝╚═╝     ╚═╝╚══════╝╚══════╝
```

# Pembelajaran Mesin

### *Machine Learning — Semester 5 Repository*

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

<br/>

[![GitHub commits](https://img.shields.io/github/commit-activity/m/athfizh/PemMes26_05_Hafizh?style=flat-square&color=4ade80&label=Commits)](https://github.com/athfizh/PemMes26_05_Hafizh/commits)
[![GitHub repo size](https://img.shields.io/github/repo-size/athfizh/PemMes26_05_Hafizh?style=flat-square&color=60a5fa&label=Repo%20Size)](https://github.com/athfizh/PemMes26_05_Hafizh)
[![GitHub last commit](https://img.shields.io/github/last-commit/athfizh/PemMes26_05_Hafizh?style=flat-square&color=f472b6&label=Last%20Update)](https://github.com/athfizh/PemMes26_05_Hafizh)

</div>

---

## 👤 Identitas Mahasiswa

<table>
  <tr>
    <td><b>Nama</b></td>
    <td>Athaulla Hafizh</td>
  </tr>
  <tr>
    <td><b>NIM</b></td>
    <td>244107020030</td>
  </tr>
  <tr>
    <td><b>Kelas</b></td>
    <td><a>TI-3F</a></td>
  </tr>
  <tr>
    <td><b>Mata Kuliah</b></td>
    <td>Pembelajaran Mesin (PemMes)</td>
  </tr>
  <tr>
    <td><b>Program Studi</b></td>
    <td>D-IV Teknik Informatika</td>
  </tr>
  <tr>
    <td><b>Jurusan</b></td>
    <td>Teknologi Informasi, Politeknik Negeri Malang</td>
  </tr>
</table>

---

## 📖 Tentang Repository

Repository ini berisi modul praktikum berbasis codelab untuk mata kuliah **Pembelajaran Mesin (Machine Learning)**. Mengacu pada [modul resmi praktikum JTI](https://polinema.gitbook.io/jti-modul-praktikum-pembelajaran-mesin-mah), materinya mencakup pengenalan pembelajaran mesin, pemahaman & pra pengolahan data, ekstraksi fitur, model regresi, model klaster, *approximate nearest neighbors*, model klasifikasi, *artificial neural network*, *convolutional neural network*, hingga evaluasi dan penyajian (*deployment*) model. Sebagian besar pengerjaan lab dan tugas dilakukan menggunakan **Google Colab**.

> ℹ️ Penomoran folder `JS0X` pada repository ini mengikuti urutan sesi perkuliahan aktual (mingguan) sebagaimana disampaikan oleh Team Teaching, sehingga urutan topiknya bisa saja berbeda dari urutan penomoran pada situs modul referensi di atas.

---

## 📂 Struktur Repository

```text
PemMes26_05_Hafizh/
│
├── 📁 JS01/
├── 📁 JS02/
├── 📁 JS03/
├── 📁 JS04/
├── 📁 JS05/
├── 📁 JS06/
├── 📁 JS07/
├── 📁 JS08/
├── 📁 JS09/
├── 📁 JS10/
├── 📁 JS11/
├── 📁 JS12/
├── 📄 KUIS1_244107020030_ATHAULLA_HAFIZH.ipynb
└── 📄 README.md
```

Setiap folder `JS0X` berisi notebook `.ipynb` (dikerjakan/dijalankan di Google Colab) dengan format penamaan:

```text
JS0X-0Y.ipynb        → notebook Lab ke-Y pada modul JS0X
JS0X-TugasLab.ipynb  → notebook Tugas Lab pada modul JS0X
```

**Contoh:**
```text
JS02/JS02-01.ipynb
JS02/JS02-TugasLab.ipynb
JS04/JS04-01.ipynb
JS04/JS04-TugasLab.ipynb
```

---

## 📋 Daftar Modul Praktikum

| No | Topik Praktikum | Sub-materi | Direktori | Status |
|:--:|---|---|:---:|:---:|
| JS01 | Pengenalan Pembelajaran Mesin | Konsep Dasar, Etika dan Tantangan, Lab 1, Tugas Lab 1, Tugas Pendahuluan JS02 | [JS01](./JS01) | ✅ Selesai |
| JS02 | Pemahaman Data dan Pra Pengolahan Data | Rekognisi & Pola, Jenis-Jenis Data, EDA, Pra Pengolahan Data, Lab 1–4, Tugas Lab (Wisconsin Breast Cancer) | [JS02](./JS02) | ✅ Selesai |
| JS03 | Ekstraksi Fitur | Fitur & Ekstraksi Fitur, Proses Ekstraksi Fitur, Seleksi Fitur, Lab 1–3, Tugas Lab (Wisconsin Breast Cancer) | [JS03](./JS03) | ✅ Selesai |
| JS04 | Regresi | Dasar Regresi, Simple/Multiple/Polynomial/Support Vector Regression, Data Latih-Validasi-Uji, Lab 0–2, Tugas Lab (Medical Insurance Charges) | [JS04](./JS04) | ✅ Selesai |
| JS05 | Klasterisasi | K-Means, DBSCAN, Lab 1–3, Tugas Lab | [JS05](./JS05) | Coming Soon |
| JS06 | Hierarchical Clustering | Konsep Dasar, HDBSCAN, Lab 1–3, Tugas Lab 1–2 | [JS06](./JS06) | Coming Soon |
| JS07 | Approximate Nearest Neighbors (ANN) | Dasar ANN, ANNOY, FAISS, HNSW, Lab 1–5, Tugas Lab 1–2 | [JS07](./JS07) | Coming Soon |
| JS08 | Klasifikasi 1 | k-Nearest Neighbors (kNN), Naive Bayes, Lab 1–3, Tugas Lab 1–2 | [JS08](./JS08) | Coming Soon |
| JS09 | Klasifikasi 2 | Support Vector Machine, Dasar Teori, Lab 1–5, Tugas Lab | [JS09](./JS09) | Coming Soon |
| JS10 | Artificial Neural Network | Perceptron, Artificial Neural Network, Lab 1–4, Tugas Lab | [JS10](./JS10) | Coming Soon |
| JS11 | Convolutional Neural Network | CNN, Lab 1–2, Tugas Lab | [JS11](./JS11) | Coming Soon |
| JS12 | Machine Learning Pipeline & Deployment | ML Pipeline, Lab 1–2, Tugas Lab | [JS12](./JS12) | Coming Soon |

> Referensi lengkap sub-materi tiap modul dapat dilihat pada [modul praktikum resmi JTI](https://polinema.gitbook.io/jti-modul-praktikum-pembelajaran-mesin-mah).

---

## 🛠️ Tech Stack & Tools

<div align="center">

| Kategori | Teknologi / Pustaka |
|---|---|
| **Programming Language** | Python |
| **Environment** | Google Colab, Jupyter Notebook |
| **Data Handling** | Pandas, NumPy |
| **Machine Learning** | scikit-learn |
| **Deep Learning** | TensorFlow / Keras |
| **Approximate Nearest Neighbors** | ANNOY, FAISS, HNSW |
| **Visualisasi** | Matplotlib, Seaborn |
| **Version Control** | Git & GitHub |

</div>

---

## 🎯 Capaian Pembelajaran

- [x] Memahami konsep dasar, etika, dan tantangan dalam pembelajaran mesin.
- [x] Melakukan pemahaman data dan pra pengolahan data (EDA, cleaning, preprocessing).
- [x] Melakukan ekstraksi dan seleksi fitur.
- [x] Menerapkan berbagai teknik regresi (linear, multiple, polynomial, SVR).
- [ ] Menerapkan algoritma klasterisasi (K-Means, DBSCAN, Hierarchical Clustering).
- [ ] Menerapkan Approximate Nearest Neighbors (ANNOY, FAISS, HNSW).
- [ ] Menerapkan algoritma klasifikasi (kNN, Naive Bayes, SVM, dan lainnya).
- [ ] Membangun Artificial Neural Network (Perceptron & ANN).
- [ ] Membangun Convolutional Neural Network (CNN).
- [ ] Menyusun ML Pipeline dan memahami dasar deployment model.

---

## 📚 Referensi

| Referensi | Tautan |
|---|:---:|
| Modul Praktikum JTI - Pembelajaran Mesin | [Akses Modul](https://polinema.gitbook.io/jti-modul-praktikum-pembelajaran-mesin-mah) |
| Python Documentation | [Akses Docs](https://docs.python.org/3/) |
| Google Colab | [Akses Colab](https://colab.research.google.com/) |
| scikit-learn Documentation | [Akses Docs](https://scikit-learn.org/stable/) |
| Pandas Documentation | [Akses Docs](https://pandas.pydata.org/docs/) |
| TensorFlow Documentation | [Akses Docs](https://www.tensorflow.org/guide) |
| FAISS Documentation | [Akses Docs](https://faiss.ai/) |

---

## 📬 Kontak

<div align="center">

**Athaulla Hafizh**

[![GitHub](https://img.shields.io/badge/GitHub-athfizh-181717?style=for-the-badge&logo=github)](https://github.com/athfizh)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/athaullahafizh/)

</div>

---

<div align="center">

<sub>⭐ Repository ini disusun untuk memenuhi tugas praktikum mata kuliah Pembelajaran Mesin</sub>

<br/>

</div>
