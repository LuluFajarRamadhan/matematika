# Peluang Bersyarat

Pada materi sebelumnya, kita telah mempelajari kejadian majemuk, gabungan, dan irisan dua kejadian.

Sekarang kita akan mempelajari situasi ketika peluang suatu kejadian dihitung setelah kita memperoleh **informasi tambahan**.

Konsep ini disebut **peluang bersyarat**.

Misalnya:

> Berapa peluang seorang siswa menyukai Matematika jika diketahui siswa tersebut mengikuti kelas Olimpiade?

Informasi:

> siswa tersebut mengikuti kelas Olimpiade

membatasi ruang kemungkinan yang sebelumnya kita miliki.

Artinya, ruang sampel yang digunakan tidak lagi seluruh siswa, tetapi hanya siswa yang mengikuti kelas Olimpiade.

---

# Pengertian Peluang Bersyarat

Peluang bersyarat adalah peluang terjadinya kejadian $A$ dengan syarat bahwa kejadian $B$ telah terjadi.

Ditulis:

$$
\boxed{
P(A\mid B)
}
$$

dibaca:

> peluang $A$ jika diketahui $B$ terjadi.

Simbol:

$$
\mid
$$

dibaca **dengan syarat** atau **jika diketahui**.

---

## Contoh 1

Sebuah kartu bernomor 1 sampai 10 dipilih secara acak.

Diketahui kartu yang terambil merupakan bilangan genap.

Tentukan peluang kartu tersebut bernomor lebih dari 5.

---

### Langkah 1: Menggunakan Informasi yang Diketahui

Karena diketahui bilangan yang terambil genap, ruang kemungkinan sekarang hanya:

$$
\{2,4,6,8,10\}
$$

Terdapat:

$$
5
$$

kemungkinan.

---

### Langkah 2: Menentukan Kejadian yang Ditanyakan

Bilangan genap yang lebih dari 5 adalah:

$$
\{6,8,10\}
$$

Terdapat:

$$
3
$$

kemungkinan.

Maka:

$$
\boxed{
P(A\mid B)=\frac35
}
$$

---

> [!important]
> Dalam peluang bersyarat, informasi yang diketahui **mengubah atau membatasi ruang sampel yang digunakan**.

---

# Rumus Peluang Bersyarat

Peluang kejadian $A$ dengan syarat $B$ telah terjadi adalah:

$$
\boxed{
P(A\mid B)
=
\frac{P(A\cap B)}{P(B)}
}
$$

dengan:

$$
P(B)\neq0
$$

---

# Mengapa Menggunakan Irisan?

Jika diketahui bahwa $B$ telah terjadi, kita hanya memperhatikan bagian ruang sampel yang berada di dalam $B$.

Dari bagian tersebut, kejadian yang juga memenuhi $A$ adalah:

$$
A\cap B
$$

Oleh karena itu:

$$
P(A\mid B)
=
\frac{\text{peluang A dan B terjadi}}
{\text{peluang B terjadi}}
$$

atau:

$$
\boxed{
P(A\mid B)
=
\frac{P(A\cap B)}{P(B)}
}
$$

---

# Bentuk dengan Banyak Anggota

Jika semua titik sampel memiliki kesempatan yang sama, peluang bersyarat dapat ditulis sebagai:

$$
\boxed{
P(A\mid B)
=
\frac{n(A\cap B)}{n(B)}
}
$$

Perhatikan bahwa penyebutnya bukan:

$$
n(S)
$$

tetapi:

$$
n(B)
$$

karena kita sudah mengetahui bahwa kejadian $B$ terjadi.

---

## Contoh 2

Sebuah dadu dilempar satu kali.

Misalkan:

$$
A=\text{muncul bilangan lebih dari 3}
$$

dan:

$$
B=\text{muncul bilangan genap}
$$

Tentukan:

$$
P(A\mid B)
$$

---

### Langkah 1: Menentukan Kejadian B

Bilangan genap:

$$
B=\{2,4,6\}
$$

sehingga:

$$
n(B)=3
$$

---

### Langkah 2: Menentukan Irisan

Bilangan yang genap dan lebih dari 3 adalah:

$$
A\cap B=\{4,6\}
$$

sehingga:

$$
n(A\cap B)=2
$$

---

### Langkah 3: Menghitung Peluang Bersyarat

$$
\begin{aligned}
P(A\mid B)
&=
\frac{n(A\cap B)}{n(B)}\\
&=
\frac23
\end{aligned}
$$

Jadi:

$$
\boxed{\frac23}
$$

---

# Urutan Syarat Sangat Penting

Perhatikan:

$$
P(A\mid B)
$$

tidak selalu sama dengan:

$$
P(B\mid A)
$$

karena syarat yang digunakan berbeda.

---

## Contoh 3

Sebuah dadu dilempar satu kali.

Misalkan:

$$
A=\text{muncul bilangan genap}
$$

dan:

$$
B=\text{muncul bilangan lebih dari 3}
$$

Diketahui:

$$
A=\{2,4,6\}
$$

dan:

$$
B=\{4,5,6\}
$$

Irisannya:

$$
A\cap B=\{4,6\}
$$

---

### Menghitung $P(A\mid B)$

Karena diketahui $B$ terjadi:

$$
n(B)=3
$$

Maka:

$$
P(A\mid B)
=
\frac23
$$

---

### Menghitung $P(B\mid A)$

Karena diketahui $A$ terjadi:

$$
n(A)=3
$$

Maka:

$$
P(B\mid A)
=
\frac23
$$

Pada contoh ini nilainya kebetulan sama.

Namun, hal tersebut tidak berlaku secara umum.

---

## Contoh 4

Dalam sebuah kelas terdapat 20 siswa.

Sebanyak:

- 12 siswa mengikuti klub Matematika,
- 8 siswa mengikuti klub Sains,
- 5 siswa mengikuti keduanya.

Misalkan:

$$
M=\text{mengikuti klub Matematika}
$$

dan:

$$
S=\text{mengikuti klub Sains}
$$

Tentukan:

$$
P(M\mid S)
$$

Diketahui:

$$
n(M\cap S)=5
$$

dan:

$$
n(S)=8
$$

Maka:

$$
\begin{aligned}
P(M\mid S)
&=
\frac{5}{8}
\end{aligned}
$$

Jadi:

$$
\boxed{\frac58}
$$

---

# Perbedaan Peluang Biasa dan Peluang Bersyarat

Misalkan kembali data:

- 20 siswa,
- 12 mengikuti Matematika,
- 8 mengikuti Sains,
- 5 mengikuti keduanya.

Peluang siswa mengikuti Matematika:

$$
P(M)=\frac{12}{20}=\frac35
$$

Tetapi jika diketahui siswa tersebut mengikuti Sains:

$$
P(M\mid S)=\frac58
$$

Nilainya berubah karena informasi tambahan telah memperkecil ruang kemungkinan.

---

> [!note]
> Peluang biasa menggunakan seluruh ruang sampel.
>
> $$
> P(A)=\frac{n(A)}{n(S)}
> $$
>
> Peluang bersyarat menggunakan kejadian syarat sebagai ruang kemungkinan baru.
>
> $$
> P(A\mid B)=\frac{n(A\cap B)}{n(B)}
> $$

---

# Mengubah Rumus Peluang Bersyarat

Dari:

$$
P(A\mid B)
=
\frac{P(A\cap B)}{P(B)}
$$

kita dapat memperoleh:

$$
\boxed{
P(A\cap B)
=
P(B)\cdot P(A\mid B)
}
$$

Demikian juga:

$$
\boxed{
P(A\cap B)
=
P(A)\cdot P(B\mid A)
}
$$

Sehingga:

$$
\boxed{
P(A\cap B)
=
P(A)\cdot P(B\mid A)
=
P(B)\cdot P(A\mid B)
}
$$

Hubungan ini sangat penting untuk menghitung peluang beberapa kejadian yang terjadi secara berurutan.

---

# Peluang Bersyarat pada Pengambilan Tanpa Pengembalian

Misalnya terdapat sebuah kotak berisi:

- 5 bola merah,
- 3 bola biru.

Diambil dua bola satu per satu **tanpa pengembalian**.

Peluang bola kedua dipengaruhi oleh hasil pengambilan pertama karena jumlah bola dalam kotak berubah.

---

## Contoh 5

Tentukan peluang bola pertama merah dan bola kedua juga merah.

Pada pengambilan pertama:

$$
P(M_1)=\frac58
$$

Jika bola pertama merah telah terambil, tersisa:

- 4 bola merah,
- total 7 bola.

Maka:

$$
P(M_2\mid M_1)=\frac47
$$

Sehingga:

$$
\begin{aligned}
P(M_1\cap M_2)
&=
P(M_1)\cdot P(M_2\mid M_1)\\
&=
\frac58\times\frac47\\
&=
\frac{20}{56}\\
&=
\frac5{14}
\end{aligned}
$$

Jadi:

$$
\boxed{\frac5{14}}
$$

---

# Mengapa Peluang Berubah?

Sebelum pengambilan pertama:

$$
P(\text{merah})=\frac58
$$

Setelah satu bola merah diambil dan tidak dikembalikan:

$$
P(\text{merah berikutnya})=\frac47
$$

Nilainya berubah karena:

- jumlah bola merah berubah,
- jumlah seluruh bola juga berubah.

Karena itu, kejadian kedua bergantung pada informasi dari kejadian pertama.

---

# Pengambilan dengan Pengembalian

Bandingkan dengan kasus ketika bola pertama dikembalikan ke dalam kotak.

Jika terdapat:

- 5 bola merah,
- 3 bola biru,

maka setelah bola pertama dikembalikan, komposisi kotak tetap:

$$
5 \text{ merah dan }3\text{ biru}
$$

Sehingga:

$$
P(M_2\mid M_1)=\frac58
$$

Informasi bahwa bola pertama merah tidak mengubah peluang bola kedua.

Situasi ini akan dibahas lebih lanjut pada materi **kejadian saling bebas**.

---

# Peluang Bersyarat dengan Tabel

Data peluang bersyarat sering disajikan menggunakan tabel.

---

## Contoh 6

Dalam suatu kelas terdapat:

| | Laki-laki | Perempuan | Total |
|---|---:|---:|---:|
| Mengikuti Olimpiade | 8 | 12 | 20 |
| Tidak Mengikuti Olimpiade | 10 | 10 | 20 |
| Total | 18 | 22 | 40 |

Jika dipilih seorang siswa yang diketahui mengikuti Olimpiade, tentukan peluang siswa tersebut perempuan.

Karena diketahui siswa mengikuti Olimpiade, ruang kemungkinan terbatas pada:

$$
20
$$

siswa.

Dari 20 siswa tersebut, terdapat:

$$
12
$$

siswa perempuan.

Maka:

$$
P(\text{Perempuan}\mid\text{Olimpiade})
=
\frac{12}{20}
=
\frac35
$$

Jadi:

$$
\boxed{\frac35}
$$

---

# Peluang Bersyarat dengan Kombinasi

Peluang bersyarat juga dapat dihitung menggunakan kaidah pencacahan.

---

## Contoh 7

Sebuah kelas terdiri atas:

- 7 siswa laki-laki,
- 5 siswa perempuan.

Dipilih 3 siswa secara acak.

Diketahui bahwa kelompok yang terpilih memiliki **minimal satu siswa perempuan**.

Tentukan peluang kelompok tersebut terdiri atas tepat 2 siswa perempuan.

---

### Langkah 1: Menentukan Kejadian Syarat

Misalkan:

$$
B=\text{minimal satu perempuan}
$$

Jumlah seluruh kelompok:

$$
{}_{12}C_3=220
$$

Kelompok tanpa perempuan berarti seluruhnya laki-laki:

$$
{}_7C_3=35
$$

Maka:

$$
n(B)=220-35=185
$$

---

### Langkah 2: Menentukan Kejadian yang Ditanyakan

Misalkan:

$$
A=\text{tepat 2 perempuan}
$$

Untuk tepat 2 perempuan dan 1 laki-laki:

$$
n(A\cap B)
=
{}_5C_2\times{}_7C_1
$$

$$
=10\times7=70
$$

Karena kejadian tepat 2 perempuan otomatis memenuhi syarat minimal satu perempuan, maka:

$$
A\cap B=A
$$

---

### Langkah 3: Menghitung Peluang Bersyarat

$$
\begin{aligned}
P(A\mid B)
&=
\frac{70}{185}\\
&=
\frac{14}{37}
\end{aligned}
$$

Jadi:

$$
\boxed{\frac{14}{37}}
$$

---

# Strategi Menyelesaikan Peluang Bersyarat

Gunakan langkah berikut.

### Langkah 1

Identifikasi kejadian yang ditanyakan.

Misalkan:

$$
A
$$

### Langkah 2

Identifikasi informasi yang sudah diketahui.

Misalkan:

$$
B
$$

### Langkah 3

Tentukan ruang kemungkinan setelah syarat $B$ diberikan.

### Langkah 4

Tentukan bagian dari $B$ yang juga memenuhi $A$:

$$
A\cap B
$$

### Langkah 5

Gunakan:

$$
\boxed{
P(A\mid B)
=
\frac{P(A\cap B)}{P(B)}
}
$$

atau jika menggunakan banyak anggota:

$$
\boxed{
P(A\mid B)
=
\frac{n(A\cap B)}{n(B)}
}
$$

---

# Soal Latihan

## Soal 1

Sebuah dadu dilempar satu kali.

Diketahui angka yang muncul merupakan bilangan genap.

Tentukan peluang angka tersebut lebih dari 3.

> [!success]- Klik untuk Lihat Jawaban
> Karena diketahui bilangan yang muncul genap, ruang kemungkinan menjadi:
>
> $$
> \{2,4,6\}
> $$
>
> sehingga:
>
> $$
> n(B)=3
> $$
>
> Bilangan genap yang lebih dari 3:
>
> $$
> \{4,6\}
> $$
>
> sehingga:
>
> $$
> n(A\cap B)=2
> $$
>
> Maka:
>
> $$
> P(A\mid B)=\frac23
> $$
>
> Jadi:
>
> $$
> \boxed{\frac23}
> $$

---

## Soal 2

Sebuah kartu bernomor 1 sampai 20 dipilih secara acak.

Diketahui kartu tersebut memiliki nomor kelipatan 2.

Tentukan peluang nomor kartu juga merupakan kelipatan 5.

> [!success]- Klik untuk Lihat Jawaban
> Kelipatan 2 dari 1 sampai 20:
>
> $$
> 2,4,6,8,10,12,14,16,18,20
> $$
>
> sehingga:
>
> $$
> n(B)=10
> $$
>
> Bilangan yang merupakan kelipatan 2 dan 5 sekaligus adalah kelipatan 10:
>
> $$
> 10,20
> $$
>
> sehingga:
>
> $$
> n(A\cap B)=2
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A\mid B)
> &=\frac2{10}\\
> &=\frac15
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac15}
> $$

---

## Soal 3

Dalam sebuah kelas terdapat 30 siswa.

Sebanyak:

- 18 siswa menyukai Matematika,
- 15 siswa menyukai Fisika,
- 9 siswa menyukai keduanya.

Jika diketahui seorang siswa menyukai Fisika, tentukan peluang siswa tersebut juga menyukai Matematika.

> [!success]- Klik untuk Lihat Jawaban
> Misalkan:
>
> $$
> M=\text{menyukai Matematika}
> $$
>
> dan:
>
> $$
> F=\text{menyukai Fisika}
> $$
>
> Diketahui:
>
> $$
> n(M\cap F)=9
> $$
>
> dan:
>
> $$
> n(F)=15
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(M\mid F)
> &=
> \frac9{15}\\
> &=
> \frac35
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac35}
> $$

---

## Soal 4

Diketahui:

$$
P(A)=\frac12
$$

dan:

$$
P(A\cap B)=\frac15
$$

Tentukan:

$$
P(B\mid A)
$$

> [!success]- Klik untuk Lihat Jawaban
> Gunakan:
>
> $$
> P(B\mid A)
> =
> \frac{P(A\cap B)}{P(A)}
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(B\mid A)
> &=
> \frac{\frac15}{\frac12}\\
> &=
> \frac15\times2\\
> &=
> \frac25
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac25}
> $$

---

## Soal 5

Sebuah kotak berisi:

- 6 bola merah,
- 4 bola biru.

Dua bola diambil satu per satu tanpa pengembalian.

Tentukan peluang kedua bola berwarna merah.

> [!success]- Klik untuk Lihat Jawaban
> Peluang bola pertama merah:
>
> $$
> P(M_1)=\frac6{10}
> $$
>
> Setelah satu bola merah diambil, tersisa:
>
> - 5 bola merah,
> - total 9 bola.
>
> Maka:
>
> $$
> P(M_2\mid M_1)=\frac59
> $$
>
> Sehingga:
>
> $$
> \begin{aligned}
> P(M_1\cap M_2)
> &=
> \frac6{10}\times\frac59\\
> &=
> \frac{30}{90}\\
> &=
> \frac13
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac13}
> $$

---

## Soal 6

Sebuah kotak berisi:

- 5 bola merah,
- 3 bola biru,
- 2 bola hijau.

Dua bola diambil satu per satu tanpa pengembalian.

Jika diketahui bola pertama yang terambil merah, tentukan peluang bola kedua berwarna biru.

> [!success]- Klik untuk Lihat Jawaban
> Awalnya terdapat:
>
> $$
> 10
> $$
>
> bola.
>
> Karena bola pertama diketahui merah, setelah pengambilan pertama tersisa:
>
> - 4 bola merah,
> - 3 bola biru,
> - 2 bola hijau.
>
> Jumlah bola tersisa:
>
> $$
> 9
> $$
>
> Banyak bola biru tetap:
>
> $$
> 3
> $$
>
> Maka:
>
> $$
> P(B_2\mid M_1)=\frac39=\frac13
> $$
>
> Jadi:
>
> $$
> \boxed{\frac13}
> $$

---

## Soal 7

Dalam sebuah kelas terdapat:

| | Laki-laki | Perempuan | Total |
|---|---:|---:|---:|
| Mengikuti Ekskul Sains | 9 | 11 | 20 |
| Tidak Mengikuti Ekskul Sains | 6 | 4 | 10 |
| Total | 15 | 15 | 30 |

Seorang siswa dipilih secara acak.

Jika diketahui siswa tersebut perempuan, tentukan peluang siswa tersebut mengikuti Ekskul Sains.

> [!success]- Klik untuk Lihat Jawaban
> Karena diketahui siswa tersebut perempuan, ruang kemungkinan hanya seluruh siswa perempuan.
>
> Jumlah siswa perempuan:
>
> $$
> 15
> $$
>
> Siswa perempuan yang mengikuti Ekskul Sains:
>
> $$
> 11
> $$
>
> Maka:
>
> $$
> P(S\mid P)=\frac{11}{15}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{11}{15}}
> $$

---

## Soal 8

Sebuah kelas terdiri atas:

- 8 siswa laki-laki,
- 6 siswa perempuan.

Dipilih 4 siswa secara acak.

Diketahui bahwa kelompok yang terpilih memiliki **minimal 1 siswa perempuan**.

Tentukan peluang kelompok tersebut terdiri atas tepat 2 siswa perempuan.

> [!success]- Klik untuk Lihat Jawaban
> Misalkan:
>
> $$
> B=\text{minimal 1 perempuan}
> $$
>
> dan:
>
> $$
> A=\text{tepat 2 perempuan}
> $$
>
> ### Langkah 1: Menentukan Banyak Kejadian B
>
> Jumlah seluruh siswa:
>
> $$
> 14
> $$
>
> Banyak seluruh kelompok:
>
> $$
> {}_{14}C_4=1001
> $$
>
> Kelompok tanpa perempuan berarti seluruhnya laki-laki:
>
> $$
> {}_8C_4=70
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> n(B)
> &=1001-70\\
> &=931
> \end{aligned}
> $$
>
> ### Langkah 2: Menentukan Banyak Kejadian $A\cap B$
>
> Tepat 2 perempuan berarti:
>
> - memilih 2 dari 6 perempuan,
> - memilih 2 dari 8 laki-laki.
>
> Maka:
>
> $$
> \begin{aligned}
> n(A\cap B)
> &=
> {}_6C_2\times{}_8C_2\\
> &=15\times28\\
> &=420
> \end{aligned}
> $$
>
> ### Langkah 3: Menghitung Peluang Bersyarat
>
> $$
> \begin{aligned}
> P(A\mid B)
> &=
> \frac{420}{931}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{420}{931}}
> $$
>
> Pecahan tersebut sudah dalam bentuk paling sederhana.

---

# Rangkuman

Peluang bersyarat adalah peluang suatu kejadian dengan informasi bahwa kejadian lain telah terjadi.

Ditulis:

$$
\boxed{
P(A\mid B)
}
$$

dan dibaca:

> peluang $A$ jika diketahui $B$ terjadi.

Rumus utama:

$$
\boxed{
P(A\mid B)
=
\frac{P(A\cap B)}{P(B)}
}
$$

dengan:

$$
P(B)\neq0
$$

Jika semua titik sampel mempunyai peluang yang sama:

$$
\boxed{
P(A\mid B)
=
\frac{n(A\cap B)}{n(B)}
}
$$

Dari rumus tersebut diperoleh:

$$
\boxed{
P(A\cap B)
=
P(B)\cdot P(A\mid B)
}
$$

atau:

$$
\boxed{
P(A\cap B)
=
P(A)\cdot P(B\mid A)
}
$$

Peluang bersyarat sering digunakan ketika:

- terdapat informasi tambahan,
- ruang sampel menjadi lebih terbatas,
- dilakukan pengambilan tanpa pengembalian,
- suatu kejadian memengaruhi peluang kejadian berikutnya.

---

> [!important]
> Dalam peluang bersyarat, perhatikan **apa yang diketahui terlebih dahulu**.
>
> $$
> P(A\mid B)
> $$
>
> berarti ruang kemungkinan dibatasi oleh:
>
> $$
> B
> $$
>
> bukan oleh seluruh ruang sampel.
>
> Karena itu:
>
> $$
> P(A\mid B)
> $$
>
> dan:
>
> $$
> P(B\mid A)
> $$
>
> tidak boleh dianggap sama tanpa pemeriksaan.

---

# Inti Materi

Gunakan pola:

$$
\boxed{
\text{Diketahui B terjadi}
\rightarrow
\text{ruang kemungkinan menjadi B}
}
$$

kemudian:

$$
\boxed{
\text{cari bagian dari B yang juga memenuhi A}
}
$$

sehingga:

$$
\boxed{
P(A\mid B)
=
\frac{P(A\cap B)}{P(B)}
}
$$

Konsep ini menjadi dasar penting untuk memahami apakah dua kejadian **saling bebas atau tidak saling bebas** pada materi berikutnya.

---

## Konsep Terkait

- [[Kaidah Pencacahan dan Peluang/07 - Peluang Komplemen]]
- [[Kaidah Pencacahan dan Peluang/08 - Peluang Kejadian Majemuk]]
- [[Kaidah Pencacahan dan Peluang/10 - Kejadian Saling Bebas]]
- [[Kaidah Pencacahan dan Peluang/11 - Penerapan Kaidah Pencacahan dalam Peluang]]