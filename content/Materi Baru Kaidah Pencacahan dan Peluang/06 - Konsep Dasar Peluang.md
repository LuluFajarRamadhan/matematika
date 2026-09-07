# Konsep Dasar Peluang

Pada materi sebelumnya, kita telah mempelajari bagaimana menentukan **banyak kemungkinan** menggunakan:

- aturan penjumlahan,
- aturan perkalian,
- permutasi,
- kombinasi.

Sekarang kita akan menggunakan banyak kemungkinan tersebut untuk menjawab pertanyaan yang berbeda:

> **Seberapa besar kemungkinan suatu kejadian akan terjadi?**

Konsep yang digunakan untuk mengukur kemungkinan terjadinya suatu kejadian disebut **peluang** atau **probabilitas**.

---

# Percobaan Acak

**Percobaan acak** adalah suatu percobaan yang hasil akhirnya belum dapat diketahui dengan pasti sebelum percobaan dilakukan, meskipun semua kemungkinan hasilnya dapat ditentukan.

Contohnya:

1. melempar sebuah koin;
2. melempar sebuah dadu;
3. mengambil sebuah kartu secara acak;
4. mengambil sebuah bola dari dalam kotak;
5. memilih seorang siswa secara acak dari sebuah kelas.

---

## Contoh 1

Sebuah dadu dilempar satu kali.

Sebelum dadu dilempar, kita tidak dapat memastikan apakah akan muncul:

$$
1,\ 2,\ 3,\ 4,\ 5,\text{ atau }6
$$

Namun, kita mengetahui seluruh hasil yang mungkin.

Karena hasil akhirnya belum dapat dipastikan, pelemparan dadu merupakan **percobaan acak**.

---

# Ruang Sampel

**Ruang sampel** adalah himpunan seluruh hasil yang mungkin terjadi dari suatu percobaan acak.

Ruang sampel biasanya dilambangkan dengan:

$$
S
$$

Banyak anggota ruang sampel ditulis:

$$
n(S)
$$

---

## Contoh 2

Sebuah koin dilempar satu kali.

Misalkan:

- $A$ menyatakan sisi angka,
- $G$ menyatakan sisi gambar.

Maka ruang sampelnya:

$$
S=\{A,G\}
$$

sehingga:

$$
n(S)=2
$$

---

## Contoh 3

Sebuah dadu dilempar satu kali.

Ruang sampelnya:

$$
S=\{1,2,3,4,5,6\}
$$

sehingga:

$$
n(S)=6
$$

---

# Titik Sampel

**Titik sampel** adalah setiap hasil individual yang terdapat dalam ruang sampel.

Misalnya:

$$
S=\{1,2,3,4,5,6\}
$$

Maka:

$$
1,\ 2,\ 3,\ 4,\ 5,\ 6
$$

masing-masing merupakan titik sampel.

---

> [!note]
> Perbedaan ruang sampel dan titik sampel:
>
> **Ruang sampel** adalah kumpulan seluruh kemungkinan hasil.
>
> **Titik sampel** adalah satu hasil tertentu di dalam ruang sampel.

---

# Menentukan Ruang Sampel

Ruang sampel dapat ditentukan dengan beberapa cara:

1. mendaftar seluruh kemungkinan;
2. menggunakan diagram pohon;
3. menggunakan tabel;
4. menggunakan kaidah pencacahan.

---

# Ruang Sampel Dua Koin

Dua buah koin dilempar secara bersamaan.

Misalkan:

- $A$ = angka,
- $G$ = gambar.

Ruang sampelnya:

$$
S=\{AA,AG,GA,GG\}
$$

sehingga:

$$
n(S)=4
$$

Perhatikan bahwa:

$$
AG\neq GA
$$

karena koin pertama dan koin kedua merupakan dua objek yang berbeda.

---

# Ruang Sampel Dua Dadu

Dua buah dadu dilempar secara bersamaan.

Setiap dadu memiliki:

$$
6
$$

kemungkinan hasil.

Dengan aturan perkalian:

$$
n(S)=6\times6
$$

sehingga:

$$
\boxed{n(S)=36}
$$

Dalam hal ini, kita tidak harus selalu menuliskan seluruh 36 pasangan satu per satu.

Kaidah pencacahan membantu menentukan ukuran ruang sampel secara lebih efisien.

---

> [!important]
> Inilah hubungan antara **kaidah pencacahan** dan **peluang**.
>
> Kaidah pencacahan dapat digunakan untuk menentukan:
>
> $$
> n(S)
> $$
>
> ketika ruang sampel terlalu besar untuk dituliskan satu per satu.

---

# Kejadian

**Kejadian** adalah himpunan satu atau beberapa titik sampel yang memenuhi suatu kondisi tertentu.

Kejadian biasanya dilambangkan dengan huruf kapital, misalnya:

$$
A,\ B,\ C,\ldots
$$

---

## Contoh 4

Sebuah dadu dilempar satu kali.

Ruang sampelnya:

$$
S=\{1,2,3,4,5,6\}
$$

Misalkan $A$ adalah kejadian muncul bilangan genap.

Maka:

$$
A=\{2,4,6\}
$$

sehingga:

$$
n(A)=3
$$

Karena seluruh anggota $A$ merupakan anggota ruang sampel $S$, maka:

$$
A\subseteq S
$$

---

# Kejadian Tunggal dan Kejadian Majemuk

## Kejadian Tunggal

Kejadian yang hanya terdiri atas satu titik sampel.

Misalnya:

> muncul angka 5 ketika sebuah dadu dilempar.

Maka:

$$
A=\{5\}
$$

---

## Kejadian Majemuk

Kejadian yang terdiri atas lebih dari satu titik sampel.

Misalnya:

> muncul bilangan ganjil ketika sebuah dadu dilempar.

Maka:

$$
B=\{1,3,5\}
$$

---

# Peluang Suatu Kejadian

Jika setiap titik sampel memiliki kesempatan yang sama untuk terjadi, peluang kejadian $A$ dapat dihitung dengan:

$$
\boxed{
P(A)=\frac{n(A)}{n(S)}
}
$$

dengan:

- $P(A)$ = peluang kejadian $A$,
- $n(A)$ = banyak hasil yang memenuhi kejadian $A$,
- $n(S)$ = banyak seluruh hasil yang mungkin.

---

## Contoh 5

Sebuah dadu dilempar satu kali.

Tentukan peluang muncul bilangan genap.

Ruang sampel:

$$
S=\{1,2,3,4,5,6\}
$$

sehingga:

$$
n(S)=6
$$

Kejadian muncul bilangan genap:

$$
A=\{2,4,6\}
$$

sehingga:

$$
n(A)=3
$$

Maka:

$$
\begin{aligned}
P(A)
&=\frac{n(A)}{n(S)}\\
&=\frac36\\
&=\frac12
\end{aligned}
$$

Jadi:

$$
\boxed{P(A)=\frac12}
$$

---

# Makna Nilai Peluang

Nilai peluang selalu berada pada interval:

$$
\boxed{
0\leq P(A)\leq1
}
$$

Nilai tersebut dapat digunakan untuk menggambarkan seberapa mungkin suatu kejadian terjadi.

---

## Kejadian Mustahil

Kejadian yang tidak mungkin terjadi mempunyai peluang:

$$
\boxed{P(A)=0}
$$

### Contoh

Muncul angka 8 ketika sebuah dadu bersisi enam dilempar.

Tidak terdapat angka 8 pada dadu.

Maka:

$$
P(A)=0
$$

---

## Kejadian Pasti

Kejadian yang selalu terjadi mempunyai peluang:

$$
\boxed{P(A)=1}
$$

### Contoh

Muncul angka kurang dari 7 ketika sebuah dadu bersisi enam dilempar.

Semua titik sampel:

$$
1,2,3,4,5,6
$$

memenuhi syarat tersebut.

Maka:

$$
P(A)=1
$$

---

## Kejadian Mungkin

Jika suatu kejadian dapat terjadi tetapi tidak selalu terjadi, maka:

$$
\boxed{
0<P(A)<1
}
$$

Contohnya, muncul bilangan genap pada pelemparan satu dadu:

$$
P(A)=\frac12
$$

---

# Peluang dalam Bentuk Pecahan, Desimal, dan Persen

Nilai peluang dapat dinyatakan dalam beberapa bentuk.

Misalnya:

$$
P(A)=\frac14
$$

Dalam bentuk desimal:

$$
P(A)=0,25
$$

Dalam bentuk persen:

$$
P(A)=25\%
$$

Ketiganya menyatakan peluang yang sama.

---

# Contoh 6

Sebuah kotak berisi:

- 5 bola merah,
- 3 bola biru,
- 2 bola hijau.

Satu bola diambil secara acak.

Tentukan peluang terambil bola biru.

Jumlah seluruh bola:

$$
5+3+2=10
$$

sehingga:

$$
n(S)=10
$$

Jumlah bola biru:

$$
n(A)=3
$$

Maka:

$$
P(A)=\frac3{10}
$$

atau:

$$
P(A)=0,3
$$

atau:

$$
P(A)=30\%
$$

---

# Peluang dan Kaidah Pencacahan

Pada contoh sederhana, nilai:

$$
n(A)
$$

dan:

$$
n(S)
$$

masih mudah ditentukan dengan mendaftar seluruh kemungkinan.

Namun, pada masalah yang lebih besar, kita dapat menggunakan kaidah pencacahan.

---

## Contoh 7

Dari 6 siswa akan dipilih 2 siswa secara acak.

Tentukan peluang Andi terpilih.

### Langkah 1: Menentukan Banyak Ruang Sampel

Banyak cara memilih 2 siswa dari 6:

$$
n(S)={}_6C_2
$$

sehingga:

$$
n(S)=15
$$

### Langkah 2: Menentukan Banyak Kejadian

Agar Andi terpilih, Andi sudah pasti menjadi salah satu anggota.

Kita hanya perlu memilih 1 siswa lagi dari 5 siswa lainnya.

Maka:

$$
n(A)={}_5C_1=5
$$

### Langkah 3: Menghitung Peluang

$$
\begin{aligned}
P(A)
&=\frac5{15}\\
&=\frac13
\end{aligned}
$$

Jadi:

$$
\boxed{\frac13}
$$

---

> [!important]
> Dalam soal peluang yang melibatkan pemilihan atau penyusunan objek:
>
> $$
> \boxed{
> P(A)=\frac{\text{banyak kemungkinan yang memenuhi syarat}}
> {\text{banyak seluruh kemungkinan}}
> }
> $$
>
> Permutasi atau kombinasi dapat digunakan untuk menentukan pembilang maupun penyebutnya.

---

# Strategi Menyelesaikan Masalah Peluang

Gunakan langkah berikut.

### Langkah 1

Tentukan percobaan yang dilakukan.

### Langkah 2

Tentukan ruang sampel:

$$
S
$$

### Langkah 3

Tentukan banyak anggota ruang sampel:

$$
n(S)
$$

### Langkah 4

Tentukan kejadian yang ditanyakan:

$$
A
$$

### Langkah 5

Tentukan banyak anggota kejadian:

$$
n(A)
$$

### Langkah 6

Gunakan:

$$
P(A)=\frac{n(A)}{n(S)}
$$

### Langkah 7

Sederhanakan hasil jika diperlukan.

---

# Soal Latihan

## Soal 1

Sebuah koin dilempar satu kali.

Tentukan:

1. ruang sampel,
2. banyak anggota ruang sampel,
3. peluang muncul sisi gambar.

> [!success]- Klik untuk Lihat Jawaban
> Misalkan:
>
> - $A$ = angka,
> - $G$ = gambar.
>
> Ruang sampel:
>
> $$
> S=\{A,G\}
> $$
>
> sehingga:
>
> $$
> n(S)=2
> $$
>
> Misalkan $B$ adalah kejadian muncul gambar.
>
> $$
> B=\{G\}
> $$
>
> sehingga:
>
> $$
> n(B)=1
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(B)
> &=\frac{n(B)}{n(S)}\\
> &=\frac12
> \end{aligned}
> $$
>
> Jadi, peluang muncul sisi gambar adalah:
>
> $$
> \boxed{\frac12}
> $$

---

## Soal 2

Sebuah dadu dilempar satu kali.

Tentukan peluang muncul bilangan yang lebih besar dari 4.

> [!success]- Klik untuk Lihat Jawaban
> Ruang sampel:
>
> $$
> S=\{1,2,3,4,5,6\}
> $$
>
> sehingga:
>
> $$
> n(S)=6
> $$
>
> Bilangan yang lebih besar dari 4 adalah:
>
> $$
> A=\{5,6\}
> $$
>
> sehingga:
>
> $$
> n(A)=2
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A)
> &=\frac26\\
> &=\frac13
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac13}
> $$

---

## Soal 3

Sebuah dadu dilempar satu kali.

Tentukan peluang muncul bilangan prima.

> [!success]- Klik untuk Lihat Jawaban
> Ruang sampel:
>
> $$
> S=\{1,2,3,4,5,6\}
> $$
>
> Bilangan prima pada dadu adalah:
>
> $$
> 2,3,5
> $$
>
> sehingga:
>
> $$
> A=\{2,3,5\}
> $$
>
> Maka:
>
> $$
> n(A)=3
> $$
>
> dan:
>
> $$
> n(S)=6
> $$
>
> Sehingga:
>
> $$
> \begin{aligned}
> P(A)
> &=\frac36\\
> &=\frac12
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac12}
> $$

---

## Soal 4

Dua buah koin dilempar secara bersamaan.

Tentukan peluang muncul tepat satu sisi gambar.

> [!success]- Klik untuk Lihat Jawaban
> Ruang sampel:
>
> $$
> S=\{AA,AG,GA,GG\}
> $$
>
> sehingga:
>
> $$
> n(S)=4
> $$
>
> Kejadian muncul tepat satu gambar:
>
> $$
> B=\{AG,GA\}
> $$
>
> sehingga:
>
> $$
> n(B)=2
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(B)
> &=\frac24\\
> &=\frac12
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac12}
> $$

---

## Soal 5

Di dalam sebuah kotak terdapat kartu bernomor 1 sampai dengan 12.

Satu kartu diambil secara acak.

Tentukan peluang terambil kartu yang nomornya merupakan kelipatan 3.

> [!success]- Klik untuk Lihat Jawaban
> Banyak seluruh kartu:
>
> $$
> n(S)=12
> $$
>
> Kelipatan 3 antara 1 sampai 12 adalah:
>
> $$
> 3,6,9,12
> $$
>
> sehingga:
>
> $$
> n(A)=4
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A)
> &=\frac4{12}\\
> &=\frac13
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

Tiga buah koin dilempar secara bersamaan.

Tentukan peluang muncul tepat dua sisi gambar.

> [!success]- Klik untuk Lihat Jawaban
> Ruang sampel:
>
> $$
> \begin{aligned}
> S=\{&
> AAA,AAG,AGA,AGG,\\
> &GAA,GAG,GGA,GGG
> \}
> \end{aligned}
> $$
>
> sehingga:
>
> $$
> n(S)=8
> $$
>
> Kejadian muncul tepat dua sisi gambar:
>
> $$
> B=\{AGG,GAG,GGA\}
> $$
>
> sehingga:
>
> $$
> n(B)=3
> $$
>
> Maka:
>
> $$
> P(B)=\frac38
> $$
>
> Jadi:
>
> $$
> \boxed{\frac38}
> $$

---

## Soal 7

Sebuah koin dan sebuah dadu dilempar secara bersamaan.

Tentukan peluang muncul sisi gambar pada koin dan bilangan genap pada dadu.

> [!success]- Klik untuk Lihat Jawaban
> Koin mempunyai:
>
> $$
> 2
> $$
>
> kemungkinan hasil.
>
> Dadu mempunyai:
>
> $$
> 6
> $$
>
> kemungkinan hasil.
>
> Maka:
>
> $$
> n(S)=2\times6=12
> $$
>
> Agar memenuhi syarat:
>
> - koin harus menunjukkan gambar,
> - dadu harus menunjukkan $2$, $4$, atau $6$.
>
> Kemungkinan yang memenuhi:
>
> $$
> \{(G,2),(G,4),(G,6)\}
> $$
>
> sehingga:
>
> $$
> n(A)=3
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A)
> &=\frac3{12}\\
> &=\frac14
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac14}
> $$

---

## Soal 8

Dua buah dadu dilempar secara bersamaan.

Tentukan peluang jumlah kedua mata dadu merupakan bilangan prima.

> [!success]- Klik untuk Lihat Jawaban
> Setiap dadu mempunyai:
>
> $$
> 6
> $$
>
> kemungkinan hasil.
>
> Maka:
>
> $$
> n(S)=6\times6=36
> $$
>
> Jumlah dua mata dadu berada antara:
>
> $$
> 2
> $$
>
> sampai:
>
> $$
> 12
> $$
>
> Bilangan prima dalam rentang tersebut adalah:
>
> $$
> 2,3,5,7,11
> $$
>
> Banyak pasangan untuk setiap jumlah:
>
> $$
> \begin{aligned}
> \text{Jumlah }2 &: 1\\
> \text{Jumlah }3 &: 2\\
> \text{Jumlah }5 &: 4\\
> \text{Jumlah }7 &: 6\\
> \text{Jumlah }11 &: 2
> \end{aligned}
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> n(A)
> &=1+2+4+6+2\\
> &=15
> \end{aligned}
> $$
>
> Sehingga:
>
> $$
> \begin{aligned}
> P(A)
> &=\frac{15}{36}\\
> &=\frac5{12}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac5{12}}
> $$

---

# Rangkuman

Peluang digunakan untuk mengukur seberapa besar kemungkinan suatu kejadian terjadi.

**Percobaan acak** adalah percobaan yang hasil akhirnya belum dapat diketahui dengan pasti sebelum dilakukan.

**Ruang sampel** adalah himpunan seluruh kemungkinan hasil:

$$
S
$$

Banyak anggota ruang sampel ditulis:

$$
n(S)
$$

**Titik sampel** adalah setiap hasil individual dalam ruang sampel.

**Kejadian** adalah satu atau beberapa titik sampel yang memenuhi syarat tertentu.

Jika setiap titik sampel mempunyai kesempatan yang sama untuk terjadi:

$$
\boxed{
P(A)=\frac{n(A)}{n(S)}
}
$$

Nilai peluang selalu memenuhi:

$$
\boxed{
0\leq P(A)\leq1
}
$$

Kejadian mustahil:

$$
P(A)=0
$$

Kejadian pasti:

$$
P(A)=1
$$

Kaidah pencacahan dapat digunakan untuk menentukan $n(S)$ maupun $n(A)$ jika banyak kemungkinan terlalu besar untuk didaftarkan satu per satu.

---

> [!important]
> Saat mengerjakan soal peluang, jangan langsung mencari rumus.
>
> Tentukan secara berurutan:
>
> $$
> \boxed{
> \text{Percobaan}
> \rightarrow
> S
> \rightarrow
> n(S)
> \rightarrow
> A
> \rightarrow
> n(A)
> \rightarrow
> P(A)
> }
> $$
>
> Dengan alur ini, kesalahan dalam menentukan pembilang dan penyebut peluang dapat dikurangi.

---

## Konsep Terkait

- [[Materi Baru Kaidah Pencacahan dan Peluang/04 - Kombinasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/05 - Membedakan Permutasi dan Kombinasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/07 - Peluang Komplemen]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/08 - Peluang Kejadian Majemuk]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/11 - Penerapan Kaidah Pencacahan dalam Peluang]]