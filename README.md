# Outlier-Detection-Kelompok-1
Proyek ini bertujuan untuk mendeteksi penipuan kartu credit yang dilihat dari anomali pada tiap transaksi.
<br>Proyek ini dibuat oleh **Kelompok 1** dalam rangka tugas Data Mining.

## Visualisasi Data Class Distribution
![image](https://github.com/user-attachments/assets/f6d989ef-854f-4fd2-b22c-021a2a8b6303)
Grafik yang di tampilkan menunjukkan distribusi kelas pada dataset credi tcard, di mana terlihat ketimpangan kelas yang sangat besar antara transaksi normal dan fraud (penipuan).

## Visualisasi Amount per Transaction by Class
![image](https://github.com/user-attachments/assets/fe91e807-815b-498c-ad2e-0377e21a866b)
Jika dilihat dari gambar diatas, menegaskan bahwa transaksi fraud cenderung menggunakan nilai kecil untuk menghindari deteksi, sedangkan transaksi normal lebih bervariasi nilainya.

## Evaluasi Model
Pada Proyek kali ini, kami memakai 3 model Algoritma Detection Outlier yaitu : 
1. Isolation Forest
   <br>Algoritma berbasis pohon keputusan yang mengisolasi observasi.
2. Local Outlier Factor (LOF)
   <br>Algoritma berbasis kepadatan lokal.
3. One-Class SVM
   <br>Algoritma berbasis Support Vector Machine untuk deteksi outlier.
   <br>
  <br> ![image](https://github.com/user-attachments/assets/62dc98a0-f80d-44df-a683-07419f065f7f)
   <br>
    <br>

## Visualisasi   
**Visualisasi Data Outlier Menggunakan Isolation Forest**
![image](https://github.com/user-attachments/assets/309f8ee4-37cd-40d8-b7b4-1736cad78e68)
 <br>
    <br>
**Visualisasi Data Outlier Menggunakan Local Outlier Factor (LOF)**
![image](https://github.com/user-attachments/assets/61e35605-a1ba-4328-9865-01b1af237ce5)
 <br>
    <br>
**Visualisasi Data Outlier Menggunakan One-Class SVM**
![image](https://github.com/user-attachments/assets/0d660ba5-2f0b-4818-83a2-dde379052b5b)
 <br>
    <br>

## Analisis
  - Isolation Forest mendeteksi 73 kesalahan, dibandingkan dengan Local Outlier Factor (LOF) yang mendeteksi 97 kesalahan,        dan SVM yang mendeteksi 8.516 kesalahan.
  - Isolation Forest memiliki akurasi sebesar 99,74%, lebih tinggi dibandingkan LOF yang memiliki akurasi 99,65%, dan SVM         yang hanya 70,09%.
  - Ketika membandingkan presisi dan recall dari kesalahan pada ketiga model, Isolation Forest memberikan hasil yang jauh         lebih baik dibandingkan LOF. Hal ini terlihat dari tingkat deteksi kasus penipuan sebesar sekitar 27%, dibandingkan LOF       yang hanya mendeteksi sekitar 2%, dan SVM sebesar 0%.
  - Secara keseluruhan, metode Isolation Forest memberikan performa yang jauh lebih baik dalam menentukan kasus penipuan,         yaitu sekitar 30%.

## Kontributor
Proyek ini dikerjakan oleh **Kelompok 1** dalam rangka penyelesaian tugas data mining:
 - Evelyn Eunike Aritonang (G1A022024)
 - Damianus Christopher Samosir (G1A022028)
 - Sinta Ezra Wati Gulo (G1A022040)
 - Torang Four Yones Manullang (G1A022052)
 - Wahyu Ozorah Manurung (G1A022060)
