# 🌊 Prediksi Kondisi Aman Berlayar

## 📖 Project Overview

Proyek ini merupakan aplikasi berbasis web yang dikembangkan untuk membantu memprediksi tingkat keamanan pelayaran berdasarkan kondisi cuaca laut. Sistem menggunakan **Matriks Risiko BMKG** sebagai dasar pengambilan keputusan dengan mempertimbangkan **kecepatan angin**, **tinggi gelombang**, dan **jenis kapal**. Seluruh logika aplikasi dibangun menggunakan **JavaScript**, sehingga hasil evaluasi dapat ditampilkan secara langsung melalui antarmuka web yang interaktif.

---

## 🛠️ Project Workflow

| Tahapan | Tools | Deskripsi |
|---------|-------|-----------|
| User Input | HTML | Pengguna memasukkan nilai kecepatan angin, tinggi gelombang, dan memilih jenis kapal. |
| Input Validation | JavaScript | Memastikan seluruh data yang dimasukkan valid sebelum diproses. |
| Risk Evaluation | JavaScript | Mengevaluasi kondisi pelayaran menggunakan logika berdasarkan Matriks Risiko BMKG. |
| Recommendation | JavaScript | Menentukan tingkat keamanan pelayaran dan memberikan rekomendasi sesuai hasil evaluasi. |
| User Interface | HTML & CSS | Menampilkan hasil prediksi secara interaktif dan mudah dipahami. |

---

## 📌 Business Problem

Kondisi cuaca laut yang berubah-ubah dapat meningkatkan risiko kecelakaan pelayaran. Nelayan maupun operator kapal memerlukan informasi yang mudah dipahami untuk menentukan apakah kondisi saat ini aman untuk berlayar.

Tanpa sistem pendukung keputusan, pengguna harus menafsirkan data cuaca secara manual sehingga berpotensi menghasilkan keputusan yang kurang tepat.

---

## 🎯 Project Objectives

Proyek ini dikembangkan untuk:

- Mengevaluasi keamanan pelayaran berdasarkan parameter cuaca laut.
- Membantu pengguna menentukan apakah kondisi saat ini aman untuk berlayar.
- Menyajikan hasil evaluasi secara sederhana dan mudah dipahami.
- Mendukung pengambilan keputusan sebelum melakukan aktivitas pelayaran.

---

## 📊 Application Features

Aplikasi menyediakan beberapa fitur utama, antara lain:

- Input Kecepatan Angin (knot)
- Input Tinggi Gelombang (meter)
- Pemilihan Jenis Kapal
- Validasi Input
- Evaluasi Risiko Berdasarkan Matriks BMKG
- Status Keamanan Pelayaran
- Rekomendasi Keselamatan

---

## 📈 Decision Logic

Sistem melakukan evaluasi berdasarkan tiga parameter utama:

- 🌬️ Kecepatan Angin
- 🌊 Tinggi Gelombang
- 🚢 Jenis Kapal

Logika aplikasi dibangun menggunakan **JavaScript** dengan mengacu pada **Matriks Risiko BMKG** untuk menentukan tingkat keamanan pelayaran.

Hasil evaluasi diklasifikasikan menjadi:

- 🟢 Aman
- 🟡 Waspada
- 🔴 Berbahaya

---

## 💡 Recommendations

Berdasarkan hasil evaluasi, sistem memberikan rekomendasi sebagai berikut:

- **Aman** → Aktivitas pelayaran dapat dilakukan.
- **Waspada** → Disarankan meningkatkan kewaspadaan dan terus memantau perkembangan cuaca.
- **Berbahaya** → Aktivitas pelayaran sebaiknya ditunda hingga kondisi cuaca membaik.

---

## 🛠️ Tools & Technologies

- HTML
- CSS
- JavaScript
- BMKG Risk Matrix

---

## 📂 Reference

Referensi penentuan tingkat keamanan pelayaran menggunakan **Matriks Risiko BMKG** berdasarkan:

- Kecepatan Angin
- Tinggi Gelombang
- Jenis Kapal

---

## 📷 Application Preview

<img width="2876" height="1538" alt="image" src="https://github.com/user-attachments/assets/a10e72cc-1138-4be2-8f67-d918fd382692" />



