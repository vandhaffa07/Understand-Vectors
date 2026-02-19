# DEFINISI DASAR DAN REPRESENTASI VEKTOR

## POSISI VEKTOR DALAM MATEMATIKA DAN FISIKA
Sebelum vektor menjadi alat utama dalam fisika modern, matematika terlebih dahulu memperkenalkan gagasan tentang besaran yang tidak cukup direpresentasikan oleh angka semata. Dalam kehidupan sehari-hari, banyak besaran cukup dinyatakan dengan satu nilai numerik, seperti massa, suhu, atau waktu. Namun, ketika kita mulai berbicara tentang perpindahan, gaya, kecepatan, atau medan, satu angka saja tidak lagi memadai. Dibutuhkan informasi tambahan yang bersifat geometris, yakni arah. Dari kebutuhan inilah lahir konsep vektor. Secara historis, perkembangan vektor tidak langsung berbentuk seperti yang kita kenal sekarang. Gagasan awal tentang arah dan besaran berkembang melalui geometri analitik oleh René Descartes, kemudian diformalkan lebih lanjut dalam bentuk aljabar vektor oleh William Rowan Hamilton dan Josiah Willard Gibbs. Seiring waktu, vektor menjadi bahasa universal dalam mekanika klasik, teori medan, hingga elektromagnetisme.

## DEFINISI FORMAL VEKTOR
Vektor secara matematis didefinisikan sebagai besaran yang memiliki nilai panjang dan arah tertentu. Berbeda dengan skalar yang hanya memiliki nilai, vektor direpresentasikan sebagai ruas garis berarah/panah, di mana panjang panah menunjukkan besaran vektor dan ujung panah menunjukkan arahnya. Vektor memiliki 2 bagian uatama yakni titik pangkal dan titik ujung. Titik pangkal vektor adalah titik tempat dimulainya sebuah vektor sedangkan titik ujung adalah titik akhir atau tujuan yang ditunjukkan oleh anak panah vektor yang menandakan arah dan posisi akhir perpindahan. Vektor sendiri dapat ditulis menggunakan beberapa cara, seperti menggunakan huruf kecil bertanda panah di atasnya ($\vec{a}$), huruf kecil bercetak tebal (**a**), huruf kecil bergaris bawah ($\underline{a}$), atau menggunakan elemen titik pangkal dan titik ujung yang bertanda panah diatasnya($\vec{AB}$)

| <img width="444" height="451" alt="Cuplikan layar 2026-02-19 134250" src="https://github.com/user-attachments/assets/64f3d3c0-7382-4336-98e3-5c1f77bc840e" /> | Pada gambar tersebut terlihat sebuah panah yang berawal dari titik A dan berakhir di titik B. Panah tersebut merepresentasikan sebuah vektor sederhana di bidang dua dimensi, dengan $A$ sebagai titik pangkalnya dan $B$ sebagai titik ujungnya. Secara notasi, vektor pada gambar tersebut dapat dituliskan dalam dua cara yang ekuivalen yakni $\vec{AB}$ atau $\vec{a}$ |
| :--- | :--- |


## VEKTOR BARIS DAN VEKTOR KOLOM
Secara notasi, vektor dapat dituliskan dalam dua bentuk umum:

#### **1. Bentuk Baris**

$$
\begin{aligned}
\text{Dalam ruang 3 dimensi:} \quad & \vec{v} = (v_1, v_2, v_3) \\
\text{Dalam ruang 2 dimensi:} \quad & \vec{v} = (v_1, v_2)
\end{aligned}
$$

#### **2. Bentuk Kolom**

$$
\text{Dalam ruang 3 dimensi:} \quad 
\vec{v} =
\begin{pmatrix}
v_1 \\
v_2 \\
v_3
\end{pmatrix}
$$

$$
\text{Dalam ruang 2 dimensi:} \quad 
\vec{v} =
\begin{pmatrix}
v_1 \\
v_2
\end{pmatrix}
$$

Perbedaan ini bukan sekadar estetika penulisan. Dalam aljabar linear, bentuk kolom sering digunakan karena lebih konsisten dengan operasi matriks dan transformasi linear. Namun, pada tahap awal ini, keduanya merepresentasikan objek matematis yang sama.

![Image](https://github.com/user-attachments/assets/0cc69227-6857-42f7-bac7-fbe2cbf68a33)


