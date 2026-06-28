# Eksperimen Manipulasi Citra Digital Menggunakan OpenCV

Proyek ini dibuat untuk memenuhi Tugas Individu mata kuliah **Pengolahan Sinyal Digital**. Fokus utama dari eksperimen ini adalah mengimplementasikan teknik manipulasi citra dasar menggunakan Python dan library OpenCV, serta menganalisis efek matematis dari setiap transformasi terhadap karakteristik visual citra[cite: 1].

## Identitas Mahasiswa
* **Nama:** [akhmad amin aziza]
* **NIM:** [452024611055]
* **Mata Kuliah:** Pengolahan Sinyal Digital

---

## Deskripsi Singkat Project
Project ini memuat implementasi dari 6 teknik pengolahan citra digital, yaitu:
1. Membaca dan menampilkan citra (Konversi BGR ke RGB)
2. Pengubahan ukuran citra (*Image Resize*)
3. Penggabungan dua citra (*Image Blending*)
4. Pembuatan citra negatif (*Image Negative*)
5. Transformasi Logaritmik
6. Transformasi Gamma

Selain kode program, project ini juga menyajikan analisis mendalam mengenai pengaruh perubahan nilai pixel terhadap histogram, kecerahan (*brightness*), kontras, dan detail dari citra yang dimanipulasi.

---

## Library yang Digunakan
Proyek ini berbasis Python 3 dan menggunakan library utama berikut:
* **OpenCV (`opencv-python`):** Untuk pembacaan, resize, dan pengolahan matriks citra.
* **NumPy:** Untuk komputasi array dan operasi matematika tingkat pixel.
* **Matplotlib:** Untuk visualisasi citra dan plot histogram.

---

## Citra yang Digunakan
Eksperimen ini menggunakan dua buah citra yang berbeda:
1. `image1.jpg`: [Beri penjelasan singkat, misal: Foto pemandangan / foto sendiri]
2. `image2.jpg`: [Beri penjelasan singkat, misal: Gambar tekstur / pola grafis]

---

## Struktur Folder Project
Penyusunan file dalam repository ini mengikuti standar baku berikut:
```text
manipulasi-citra-digital/
 |-- notebook/
 |    |-- image_manipulation.ipynb
 |-- images/
 |    |-- image1.jpg
 |    |-- image2.jpg
 |-- report/
 |    |-- laporan.pdf
 |-- README.md
 |-- requirements.txt