# Kejadian Saling Bebas

Pada materi sebelumnya, kita telah mempelajari **peluang bersyarat**, yaitu peluang suatu kejadian setelah diketahui kejadian lain telah terjadi.

Sekarang kita akan mempelajari dua kejadian yang tidak saling memengaruhi.

Dua kejadian seperti ini disebut **kejadian saling bebas**.

Contohnya:

- hasil pelemparan koin pertama dan kedua,
- hasil pelemparan dua dadu,
- pengambilan bola dengan pengembalian.

Pada kejadian saling bebas, informasi bahwa kejadian pertama terjadi **tidak mengubah peluang kejadian kedua**.

---

# Pengertian Kejadian Saling Bebas

Dua kejadian $A$ dan $B$ disebut **saling bebas** jika terjadinya kejadian $A$ tidak memengaruhi peluang kejadian $B$, dan sebaliknya.

Artinya:

$$
P(B\mid A)=P(B)
$$

dan:

$$
P(A\mid B)=P(A)
$$

Dengan kata lain, mengetahui bahwa salah satu kejadian telah terjadi tidak memberikan perubahan pada peluang kejadian lainnya.

---

## Contoh 1

Sebuah koin dilempar dua kali.

Misalkan:

$$
A=\text{muncul gambar pada pelemparan pertama}
$$

dan:

$$
B=\text{muncul gambar pada pelemparan kedua}
$$

Peluang muncul gambar pada pelemparan kedua adalah:

$$
P(B)=\frac12
$$

Jika diketahui bahwa pelemparan pertama menghasilkan gambar, peluang pelemparan kedua tetap:

$$
P(B\mid A)=\frac12
$$

Karena:

$$
P(B\mid A)=P(B)
$$

maka $A$ dan $B$ merupakan kejadian saling bebas.

---

# Rumus Kejadian Saling Bebas

Dari rumus peluang bersyarat:

$$
P(A\mid B)
=
\frac{P(A\cap B)}{P(B)}
$$

Jika $A$ dan $B$ saling bebas:

$$
P(A\mid B)=P(A)
$$

Maka:

$$
P(A)
=
\frac{P(A\cap B)}{P(B)}
$$

sehingga:

$$
\boxed{
P(A\cap B)
=
P(A)\cdot P(B)
}
$$

Rumus ini merupakan ciri utama dua kejadian saling bebas.

---

> [!important]
> Jika $A$ dan $B$ saling bebas:
>
> $$
> \boxed{
> P(A\cap B)=P(A)\cdot P(B)
> }
> $$

---

# Contoh 2

Sebuah koin dan sebuah dadu dilempar secara bersamaan.

Misalkan:

$$
A=\text{koin menunjukkan gambar}
$$

dan:

$$
B=\text{dadu menunjukkan bilangan genap}
$$

Peluang kejadian $A$:

$$
P(A)=\frac12
$$

Peluang kejadian $B$:

$$
P(B)=\frac36=\frac12
$$

Karena hasil koin tidak memengaruhi hasil dadu, kedua kejadian saling bebas.

Maka:

$$
\begin{aligned}
P(A\cap B)
&=
P(A)\cdot P(B)\\
&=
\frac12\times\frac12\\
&=
\frac14
\end{aligned}
$$

Jadi:

$$
\boxed{\frac14}
$$

---

# Kejadian Tidak Saling Bebas

Dua kejadian disebut **tidak saling bebas** apabila terjadinya salah satu kejadian mengubah peluang kejadian lainnya.

Artinya:

$$
P(A\mid B)\neq P(A)
$$

atau:

$$
P(B\mid A)\neq P(B)
$$

---

## Contoh 3

Sebuah kotak berisi:

- 5 bola merah,
- 3 bola biru.

Dua bola diambil satu per satu tanpa pengembalian.

Misalkan:

$$
A=\text{bola pertama merah}
$$

dan:

$$
B=\text{bola kedua merah}
$$

Sebelum pengambilan pertama:

$$
P(B)=\frac58
$$

Namun, jika diketahui bola pertama merah, tersisa:

- 4 bola merah,
- total 7 bola.

Sehingga:

$$
P(B\mid A)=\frac47
$$

Karena:

$$
\frac47\neq\frac58
$$

maka kedua kejadian tersebut **tidak saling bebas**.

---

# Pengambilan dengan Pengembalian

Sekarang perhatikan situasi yang sama, tetapi bola pertama **dikembalikan** ke dalam kotak.

Setelah bola pertama diambil, jumlah bola kembali menjadi:

- 5 merah,
- 3 biru.

Maka peluang bola kedua merah tetap:

$$
\frac58
$$

Jadi:

$$
P(B\mid A)=P(B)
$$

Sehingga kejadian pertama dan kedua menjadi **saling bebas**.

---

> [!note]
> Dalam soal pengambilan bola:
>
> **dengan pengembalian** biasanya menghasilkan kejadian saling bebas.
>
> **tanpa pengembalian** biasanya menghasilkan kejadian tidak saling bebas.
>
> Namun, tetap periksa apakah peluang kejadian kedua berubah atau tidak.

---

# Perbedaan Saling Bebas dan Saling Lepas

Dua istilah ini sering tertukar.

Padahal keduanya memiliki makna yang berbeda.

---

## Kejadian Saling Lepas

Dua kejadian saling lepas jika **tidak dapat terjadi secara bersamaan**.

$$
A\cap B=\varnothing
$$

sehingga:

$$
P(A\cap B)=0
$$

---

## Kejadian Saling Bebas

Dua kejadian saling bebas jika terjadinya salah satu kejadian **tidak memengaruhi peluang kejadian lainnya**.

$$
P(A\cap B)=P(A)\cdot P(B)
$$

---

# Contoh Perbandingan

Sebuah dadu dilempar satu kali.

Misalkan:

$$
A=\text{muncul angka 2}
$$

dan:

$$
B=\text{muncul angka 5}
$$

Kedua kejadian tidak mungkin terjadi bersamaan.

Maka:

$$
A\cap B=\varnothing
$$

sehingga $A$ dan $B$ saling lepas.

Namun:

$$
P(A)=\frac16
$$

dan:

$$
P(B)=\frac16
$$

Jika keduanya saling bebas, seharusnya:

$$
P(A\cap B)
=
\frac16\times\frac16
=
\frac1{36}
$$

Padahal:

$$
P(A\cap B)=0
$$

Maka $A$ dan $B$ **tidak saling bebas**.

---

> [!important]
> Jika dua kejadian mempunyai peluang positif dan saling lepas, maka kedua kejadian tersebut tidak saling bebas.

---

# Ringkasan Perbedaan

| Saling Lepas | Saling Bebas |
|---|---|
| Tidak dapat terjadi bersamaan | Dapat terjadi bersamaan |
| $A\cap B=\varnothing$ | $A\cap B$ dapat memiliki anggota |
| $P(A\cap B)=0$ | $P(A\cap B)=P(A)P(B)$ |
| Berkaitan dengan kemungkinan terjadi bersamaan | Berkaitan dengan pengaruh antar kejadian |

---

# Menguji Apakah Dua Kejadian Saling Bebas

Untuk memeriksa apakah $A$ dan $B$ saling bebas, bandingkan:

$$
P(A\cap B)
$$

dengan:

$$
P(A)\cdot P(B)
$$

Jika:

$$
P(A\cap B)
=
P(A)\cdot P(B)
$$

maka:

$$
\boxed{\text{$A$ dan $B$ saling bebas}}
$$

Jika tidak sama, maka:

$$
\boxed{\text{$A$ dan $B$ tidak saling bebas}}
$$

---

## Contoh 4

Diketahui:

$$
P(A)=\frac12
$$

$$
P(B)=\frac35
$$

dan:

$$
P(A\cap B)=\frac3{10}
$$

Periksa apakah $A$ dan $B$ saling bebas.

Hitung:

$$
P(A)\cdot P(B)
=
\frac12\times\frac35
=
\frac3{10}
$$

Karena:

$$
P(A\cap B)=P(A)\cdot P(B)
$$

maka:

$$
\boxed{\text{$A$ dan $B$ saling bebas}}
$$

---

# Percobaan Berulang

Jika sebuah percobaan dilakukan berulang dan setiap percobaan saling bebas, maka peluang beberapa hasil tertentu dapat dihitung dengan aturan perkalian.

---

## Contoh 5

Sebuah koin dilempar 3 kali.

Tentukan peluang muncul gambar pada ketiga pelemparan.

Peluang gambar pada setiap pelemparan:

$$
\frac12
$$

Karena hasil setiap pelemparan saling bebas:

$$
\begin{aligned}
P(GGG)
&=
\frac12\times\frac12\times\frac12\\
&=
\frac18
\end{aligned}
$$

Jadi:

$$
\boxed{\frac18}
$$

---

# Tepat Sejumlah Keberhasilan

Dalam percobaan berulang, kita juga dapat menentukan peluang tepat beberapa kejadian terjadi.

---

## Contoh 6

Sebuah koin dilempar 3 kali.

Tentukan peluang muncul tepat 2 gambar.

Kemungkinan yang memenuhi:

$$
GGA,\ GAG,\ AGG
$$

Setiap susunan mempunyai peluang:

$$
\frac12\times\frac12\times\frac12
=
\frac18
$$

Terdapat:

$$
3
$$

susunan.

Maka:

$$
\begin{aligned}
P(\text{tepat 2 gambar})
&=
3\times\frac18\\
&=
\frac38
\end{aligned}
$$

Jadi:

$$
\boxed{\frac38}
$$

---

# Kombinasi pada Percobaan Berulang

Pada contoh sebelumnya, posisi dua sisi gambar dapat dipilih dari 3 pelemparan.

Banyak cara memilih posisi gambar adalah:

$$
{}_3C_2=3
$$

Sehingga:

$$
P(\text{tepat 2 gambar})
=
{}_3C_2
\left(\frac12\right)^2
\left(\frac12\right)^1
$$

Maka:

$$
P(\text{tepat 2 gambar})
=
\frac38
$$

Konsep ini menunjukkan hubungan antara **kombinasi** dan **peluang percobaan berulang**.

---

# Minimal Satu Keberhasilan

Komplemen juga dapat digunakan pada kejadian saling bebas.

---

## Contoh 7

Sebuah dadu dilempar 4 kali.

Tentukan peluang muncul angka 6 minimal satu kali.

Peluang tidak muncul angka 6 pada satu pelemparan:

$$
\frac56
$$

Karena setiap pelemparan saling bebas:

$$
P(\text{tidak muncul 6 sama sekali})
=
\left(\frac56\right)^4
$$

Maka:

$$
\begin{aligned}
P(\text{minimal satu 6})
&=
1-\left(\frac56\right)^4\\
&=
1-\frac{625}{1296}\\
&=
\frac{671}{1296}
\end{aligned}
$$

Jadi:

$$
\boxed{\frac{671}{1296}}
$$

---

# Lebih dari Dua Kejadian Saling Bebas

Jika kejadian:

$$
A_1,A_2,A_3,\ldots,A_n
$$

saling bebas, maka peluang semuanya terjadi adalah:

$$
\boxed{
P(A_1\cap A_2\cap\cdots\cap A_n)
=
P(A_1)P(A_2)\cdots P(A_n)
}
$$

---

## Contoh 8

Sebuah koin, sebuah dadu, dan sebuah kartu bernomor 1 sampai 5 digunakan secara bersamaan.

Tentukan peluang:

- koin menunjukkan gambar,
- dadu menunjukkan bilangan genap,
- kartu menunjukkan angka lebih dari 3.

Peluang koin menunjukkan gambar:

$$
\frac12
$$

Peluang dadu menunjukkan genap:

$$
\frac36=\frac12
$$

Peluang kartu menunjukkan angka lebih dari 3:

$$
\frac25
$$

Ketiga percobaan tidak saling memengaruhi.

Maka:

$$
\begin{aligned}
P
&=
\frac12\times\frac12\times\frac25\\
&=
\frac1{10}
\end{aligned}
$$

Jadi:

$$
\boxed{\frac1{10}}
$$

---

# Strategi Menyelesaikan Masalah Kejadian Saling Bebas

Gunakan langkah berikut.

### Langkah 1

Identifikasi kejadian:

$$
A
$$

dan:

$$
B
$$

### Langkah 2

Tanyakan:

> Apakah terjadinya $A$ mengubah peluang $B$?

### Langkah 3

Jika tidak berubah:

$$
P(B\mid A)=P(B)
$$

maka kejadian saling bebas.

### Langkah 4

Gunakan:

$$
P(A\cap B)=P(A)\cdot P(B)
$$

### Langkah 5

Jika percobaan dilakukan berulang, kalikan peluang setiap tahap jika masing-masing percobaan saling bebas.

---

# Soal Latihan

## Soal 1

Sebuah koin dilempar dan sebuah dadu dilempar secara bersamaan.

Tentukan peluang muncul sisi gambar pada koin dan angka 5 pada dadu.

> [!success]- Klik untuk Lihat Jawaban
> Hasil koin tidak memengaruhi hasil dadu, sehingga kedua kejadian saling bebas.
>
> Peluang gambar:
>
> $$
> P(G)=\frac12
> $$
>
> Peluang angka 5:
>
> $$
> P(5)=\frac16
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(G\cap5)
> &=
> \frac12\times\frac16\\
> &=
> \frac1{12}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac1{12}}
> $$

---

## Soal 2

Dua buah dadu dilempar secara bersamaan.

Tentukan peluang dadu pertama menunjukkan bilangan genap dan dadu kedua menunjukkan bilangan lebih dari 4.

> [!success]- Klik untuk Lihat Jawaban
> Peluang dadu pertama genap:
>
> $$
> \frac36=\frac12
> $$
>
> Peluang dadu kedua lebih dari 4:
>
> $$
> \frac26=\frac13
> $$
>
> Kedua hasil saling bebas.
>
> Maka:
>
> $$
> \begin{aligned}
> P
> &=
> \frac12\times\frac13\\
> &=
> \frac16
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac16}
> $$

---

## Soal 3

Diketahui:

$$
P(A)=\frac25
$$

$$
P(B)=\frac12
$$

dan $A$ serta $B$ saling bebas.

Tentukan:

$$
P(A\cap B)
$$

> [!success]- Klik untuk Lihat Jawaban
> Karena $A$ dan $B$ saling bebas:
>
> $$
> P(A\cap B)=P(A)P(B)
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A\cap B)
> &=
> \frac25\times\frac12\\
> &=
> \frac15
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac15}
> $$

---

## Soal 4

Diketahui:

$$
P(A)=\frac34
$$

$$
P(B)=\frac25
$$

dan:

$$
P(A\cap B)=\frac3{10}
$$

Tentukan apakah $A$ dan $B$ saling bebas.

> [!success]- Klik untuk Lihat Jawaban
> Hitung:
>
> $$
> \begin{aligned}
> P(A)\cdot P(B)
> &=
> \frac34\times\frac25\\
> &=
> \frac6{20}\\
> &=
> \frac3{10}
> \end{aligned}
> $$
>
> Karena:
>
> $$
> P(A\cap B)
> =
> P(A)\cdot P(B)
> $$
>
> maka:
>
> $$
> \boxed{\text{$A$ dan $B$ saling bebas}}
> $$

---

## Soal 5

Sebuah kotak berisi:

- 4 bola merah,
- 6 bola biru.

Satu bola diambil, dicatat warnanya, kemudian dikembalikan ke dalam kotak.

Proses dilakukan dua kali.

Tentukan peluang kedua bola yang terambil berwarna merah.

> [!success]- Klik untuk Lihat Jawaban
> Karena bola pertama dikembalikan, komposisi kotak tidak berubah.
>
> Maka kedua pengambilan saling bebas.
>
> Peluang merah pada setiap pengambilan:
>
> $$
> \frac4{10}=\frac25
> $$
>
> Sehingga:
>
> $$
> \begin{aligned}
> P(MM)
> &=
> \frac25\times\frac25\\
> &=
> \frac4{25}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac4{25}}
> $$

---

## Soal 6

Sebuah koin dilempar 4 kali.

Tentukan peluang muncul tepat 3 sisi gambar.

> [!success]- Klik untuk Lihat Jawaban
> Kita memilih 3 dari 4 posisi untuk ditempati gambar.
>
> Banyak caranya:
>
> $$
> {}_4C_3=4
> $$
>
> Peluang setiap susunan yang terdiri atas 3 gambar dan 1 angka:
>
> $$
> \left(\frac12\right)^3
> \left(\frac12\right)
> =
> \frac1{16}
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(\text{tepat 3 gambar})
> &=
> 4\times\frac1{16}\\
> &=
> \frac14
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac14}
> $$

---

## Soal 7

Sebuah dadu dilempar 3 kali.

Tentukan peluang muncul angka 6 minimal satu kali.

> [!success]- Klik untuk Lihat Jawaban
> Gunakan komplemen.
>
> Peluang tidak muncul angka 6 dalam satu pelemparan:
>
> $$
> \frac56
> $$
>
> Karena setiap pelemparan saling bebas:
>
> $$
> P(\text{tidak ada 6})
> =
> \left(\frac56\right)^3
> =
> \frac{125}{216}
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(\text{minimal satu 6})
> &=
> 1-\frac{125}{216}\\
> &=
> \frac{91}{216}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{91}{216}}
> $$

---

## Soal 8

Diketahui dua kejadian $A$ dan $B$ dengan:

$$
P(A)=\frac35
$$

$$
P(B)=\frac12
$$

dan:

$$
P(A\cup B)=\frac45
$$

Tentukan apakah $A$ dan $B$ saling bebas.

> [!success]- Klik untuk Lihat Jawaban
> Kita belum mengetahui:
>
> $$
> P(A\cap B)
> $$
>
> Gunakan rumus gabungan:
>
> $$
> P(A\cup B)
> =
> P(A)+P(B)-P(A\cap B)
> $$
>
> Substitusi:
>
> $$
> \frac45
> =
> \frac35+\frac12-P(A\cap B)
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A\cap B)
> &=
> \frac35+\frac12-\frac45\\
> &=
> \frac6{10}+\frac5{10}-\frac8{10}\\
> &=
> \frac3{10}
> \end{aligned}
> $$
>
> Selanjutnya periksa:
>
> $$
> P(A)\cdot P(B)
> $$
>
> $$
> \begin{aligned}
> P(A)\cdot P(B)
> &=
> \frac35\times\frac12\\
> &=
> \frac3{10}
> \end{aligned}
> $$
>
> Karena:
>
> $$
> P(A\cap B)
> =
> P(A)\cdot P(B)
> $$
>
> maka:
>
> $$
> \boxed{\text{$A$ dan $B$ saling bebas}}
> $$

---

# Rangkuman

Dua kejadian $A$ dan $B$ disebut **saling bebas** jika terjadinya salah satu kejadian tidak mengubah peluang kejadian lainnya.

Secara peluang bersyarat:

$$
\boxed{
P(A\mid B)=P(A)
}
$$

atau:

$$
\boxed{
P(B\mid A)=P(B)
}
$$

Untuk kejadian saling bebas:

$$
\boxed{
P(A\cap B)=P(A)\cdot P(B)
}
$$

Untuk menguji kebebasan dua kejadian, bandingkan:

$$
P(A\cap B)
$$

dengan:

$$
P(A)P(B)
$$

Jika sama, kedua kejadian saling bebas.

---

## Saling Bebas dan Saling Lepas

Saling lepas berarti:

$$
A\cap B=\varnothing
$$

Sedangkan saling bebas berarti:

$$
P(A\cap B)=P(A)P(B)
$$

Kedua konsep tersebut berbeda.

---

## Percobaan Berulang

Jika percobaan dilakukan beberapa kali secara saling bebas, peluang hasil tertentu dapat diperoleh dengan mengalikan peluang pada setiap tahap.

Untuk kejadian minimal satu:

$$
\boxed{
P(\text{minimal satu})
=
1-P(\text{tidak ada})
}
$$

---

> [!important]
> Jangan menentukan kejadian saling bebas hanya karena dua kejadian terlihat berbeda.
>
> Pertanyaan utamanya adalah:
>
> **Apakah informasi bahwa satu kejadian terjadi mengubah peluang kejadian lainnya?**
>
> Jika tidak:
>
> $$
> \boxed{\text{saling bebas}}
> $$
>
> Jika berubah:
>
> $$
> \boxed{\text{tidak saling bebas}}
> $$

---

# Inti Materi

Gunakan hubungan berikut:

$$
\boxed{
\text{Saling bebas}
\Rightarrow
P(A\cap B)=P(A)P(B)
}
$$

$$
\boxed{
\text{Tidak saling bebas}
\Rightarrow
P(A\cap B)=P(A)P(B\mid A)
}
$$

dan jangan tertukar dengan:

$$
\boxed{
\text{Saling lepas}
\Rightarrow
P(A\cap B)=0
}
$$

Kemampuan membedakan ketiga situasi tersebut sangat penting sebelum masuk ke penerapan gabungan kaidah pencacahan dan peluang.

---

## Konsep Terkait

- [[Materi Baru Kaidah Pencacahan dan Peluang/07 - Peluang Komplemen]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/08 - Peluang Kejadian Majemuk]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/09 - Peluang Bersyarat]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/11 - Penerapan Kaidah Pencacahan dalam Peluang]]