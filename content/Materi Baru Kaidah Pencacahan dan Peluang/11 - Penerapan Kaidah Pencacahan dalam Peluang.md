# Penerapan Kaidah Pencacahan dalam Peluang

Pada materi sebelumnya, kita telah mempelajari:

- aturan penjumlahan,
- aturan perkalian,
- faktorial,
- permutasi,
- kombinasi,
- peluang,
- peluang komplemen,
- kejadian majemuk,
- peluang bersyarat,
- kejadian saling bebas.

Sekarang seluruh konsep tersebut akan digunakan secara bersama-sama.

Pada banyak soal peluang, kesulitan utamanya bukan terletak pada rumus:

$$
P(A)=\frac{n(A)}{n(S)}
$$

tetapi pada bagaimana menentukan:

$$
n(A)
$$

dan:

$$
n(S)
$$

secara tepat.

Jika ruang sampel cukup besar, kita tidak perlu menuliskan semua kemungkinan satu per satu.

Kita dapat menggunakan **kaidah pencacahan**.

---

# Hubungan Pencacahan dan Peluang

Secara umum:

$$
\boxed{
P(A)=\frac{n(A)}{n(S)}
}
$$

dengan:

- $n(S)$ = banyak seluruh kemungkinan,
- $n(A)$ = banyak kemungkinan yang memenuhi syarat.

Kaidah pencacahan digunakan untuk menghitung kedua nilai tersebut.

---

# Langkah Umum

Gunakan alur berikut.

### Langkah 1

Tentukan percobaan atau proses yang dilakukan.

### Langkah 2

Tentukan ruang sampel:

$$
S
$$

### Langkah 3

Hitung:

$$
n(S)
$$

menggunakan:

- aturan perkalian,
- permutasi,
- kombinasi.

### Langkah 4

Tentukan kejadian yang ditanyakan:

$$
A
$$

### Langkah 5

Hitung:

$$
n(A)
$$

dengan metode pencacahan yang sesuai.

### Langkah 6

Gunakan:

$$
P(A)=\frac{n(A)}{n(S)}
$$

---

# Penerapan Aturan Perkalian dalam Peluang

## Contoh 1

Sebuah bilangan dua digit dibentuk dari angka:

$$
1,2,3,4,5
$$

tanpa pengulangan angka.

Satu bilangan dipilih secara acak dari seluruh bilangan yang dapat dibentuk.

Tentukan peluang bilangan tersebut genap.

---

### Langkah 1: Menentukan Ruang Sampel

Digit pertama memiliki:

$$
5
$$

pilihan.

Digit kedua memiliki:

$$
4
$$

pilihan.

Maka:

$$
n(S)=5\times4=20
$$

---

### Langkah 2: Menentukan Kejadian

Agar bilangan genap, digit terakhir harus:

$$
2 \text{ atau }4
$$

Digit terakhir memiliki:

$$
2
$$

pilihan.

Setelah digit terakhir dipilih, digit pertama mempunyai:

$$
4
$$

pilihan.

Maka:

$$
n(A)=2\times4=8
$$

---

### Langkah 3: Menghitung Peluang

$$
\begin{aligned}
P(A)
&=\frac8{20}\\
&=\frac25
\end{aligned}
$$

Jadi:

$$
\boxed{\frac25}
$$

---

# Penerapan Permutasi dalam Peluang

Permutasi digunakan ketika ruang sampel berbentuk susunan dan **urutan diperhatikan**.

---

## Contoh 2

Lima siswa:

$$
A,B,C,D,E
$$

berdiri secara acak dalam satu baris.

Tentukan peluang $A$ berada di posisi pertama.

---

### Langkah 1: Menentukan Seluruh Susunan

Lima siswa berbeda dapat disusun:

$$
n(S)=5!
$$

sehingga:

$$
n(S)=120
$$

---

### Langkah 2: Menentukan Susunan yang Memenuhi

Jika $A$ harus berada di posisi pertama, maka 4 siswa lainnya dapat disusun pada posisi yang tersisa.

Maka:

$$
n(A)=4!
$$

sehingga:

$$
n(A)=24
$$

---

### Langkah 3: Menghitung Peluang

$$
\begin{aligned}
P(A)
&=\frac{24}{120}\\
&=\frac15
\end{aligned}
$$

Jadi:

$$
\boxed{\frac15}
$$

---

# Permutasi dengan Syarat Berdampingan

## Contoh 3

Enam siswa berdiri secara acak dalam satu baris.

Tentukan peluang Andi dan Budi berdampingan.

---

### Langkah 1: Menentukan Seluruh Susunan

$$
n(S)=6!
$$

$$
n(S)=720
$$

---

### Langkah 2: Menentukan Susunan Andi dan Budi Berdampingan

Anggap Andi dan Budi sebagai satu kelompok.

Maka terdapat:

$$
5
$$

objek yang disusun.

Banyak susunan:

$$
5!
$$

Di dalam kelompok, Andi dan Budi dapat tersusun:

$$
AB
$$

atau:

$$
BA
$$

sehingga:

$$
2!
$$

cara.

Maka:

$$
n(A)=5!\times2!
$$

$$
n(A)=120\times2=240
$$

---

### Langkah 3: Menghitung Peluang

$$
\begin{aligned}
P(A)
&=\frac{240}{720}\\
&=\frac13
\end{aligned}
$$

Jadi:

$$
\boxed{\frac13}
$$

---

# Penerapan Kombinasi dalam Peluang

Kombinasi digunakan jika suatu kejadian melibatkan pemilihan objek dengan urutan yang tidak diperhatikan.

---

## Contoh 4

Dalam sebuah kelas terdapat:

- 8 siswa laki-laki,
- 6 siswa perempuan.

Dipilih 4 siswa secara acak.

Tentukan peluang terpilih tepat:

- 2 siswa laki-laki,
- 2 siswa perempuan.

---

### Langkah 1: Menentukan Ruang Sampel

Jumlah seluruh siswa:

$$
14
$$

Banyak kelompok yang dapat dipilih:

$$
n(S)={}_{14}C_4
$$

Maka:

$$
n(S)=1001
$$

---

### Langkah 2: Menentukan Kejadian

Pilih 2 siswa laki-laki:

$$
{}_8C_2
$$

Pilih 2 siswa perempuan:

$$
{}_6C_2
$$

Maka:

$$
\begin{aligned}
n(A)
&={}_8C_2\times{}_6C_2\\
&=28\times15\\
&=420
\end{aligned}
$$

---

### Langkah 3: Menghitung Peluang

$$
\begin{aligned}
P(A)
&=\frac{420}{1001}\\
&=\frac{60}{143}
\end{aligned}
$$

Jadi:

$$
\boxed{\frac{60}{143}}
$$

---

# Peluang dengan Syarat Minimal

Untuk syarat seperti:

- minimal satu,
- paling sedikit satu,

sering kali lebih mudah menggunakan komplemen.

---

## Contoh 5

Dari:

- 7 siswa laki-laki,
- 5 siswa perempuan,

dipilih 4 siswa secara acak.

Tentukan peluang terpilih minimal 1 siswa perempuan.

---

### Langkah 1: Menentukan Ruang Sampel

Jumlah seluruh siswa:

$$
12
$$

Maka:

$$
n(S)={}_{12}C_4
$$

$$
n(S)=495
$$

---

### Langkah 2: Menggunakan Komplemen

Komplemen dari minimal 1 perempuan adalah:

> tidak ada perempuan.

Artinya, seluruh siswa yang terpilih laki-laki.

Maka:

$$
n(A^c)={}_7C_4
$$

$$
n(A^c)=35
$$

Peluang komplemennya:

$$
P(A^c)=\frac{35}{495}
$$

$$
P(A^c)=\frac7{99}
$$

---

### Langkah 3: Menghitung Peluang

$$
\begin{aligned}
P(A)
&=1-\frac7{99}\\
&=\frac{92}{99}
\end{aligned}
$$

Jadi:

$$
\boxed{\frac{92}{99}}
$$

---

# Memilih Permutasi atau Kombinasi dalam Peluang

Saat menentukan:

$$
n(S)
$$

dan:

$$
n(A)
$$

gunakan pertanyaan berikut:

> Apakah perubahan urutan menghasilkan hasil yang berbeda?

Jika:

$$
\boxed{\text{Ya}}
$$

gunakan permutasi.

Jika:

$$
\boxed{\text{Tidak}}
$$

gunakan kombinasi.

---

# Contoh Perbandingan

Dari 8 siswa akan dipilih 3 siswa.

### Kasus 1

Dipilih sebagai:

- ketua,
- sekretaris,
- bendahara.

Urutan atau posisi berbeda.

Maka:

$$
n(S)={}_8P_3
$$

---

### Kasus 2

Dipilih sebagai anggota tim.

Urutan tidak berpengaruh.

Maka:

$$
n(S)={}_8C_3
$$

---

> [!important]
> Rumus peluang tetap sama:
>
> $$
> P(A)=\frac{n(A)}{n(S)}
> $$
>
> Yang berubah adalah cara menentukan $n(A)$ dan $n(S)$.

---

# Peluang dengan Kombinasi dan Beberapa Kasus

## Contoh 6

Sebuah kotak berisi:

- 6 bola merah,
- 5 bola biru,
- 4 bola hijau.

Diambil 4 bola sekaligus.

Tentukan peluang terambil tepat 2 bola merah.

---

### Langkah 1: Menentukan Ruang Sampel

Jumlah seluruh bola:

$$
15
$$

Maka:

$$
n(S)={}_{15}C_4
$$

$$
n(S)=1365
$$

---

### Langkah 2: Menentukan Kejadian

Pilih 2 bola merah dari 6:

$$
{}_6C_2
$$

Dua bola lainnya harus bukan merah.

Jumlah bola bukan merah:

$$
5+4=9
$$

Pilih 2 dari 9:

$$
{}_9C_2
$$

Maka:

$$
\begin{aligned}
n(A)
&={}_6C_2\times{}_9C_2\\
&=15\times36\\
&=540
\end{aligned}
$$

---

### Langkah 3: Menghitung Peluang

$$
\begin{aligned}
P(A)
&=\frac{540}{1365}\\
&=\frac{36}{91}
\end{aligned}
$$

Jadi:

$$
\boxed{\frac{36}{91}}
$$

---

# Peluang dengan Susunan Huruf

## Contoh 7

Huruf-huruf:

$$
A,B,C,D,E
$$

disusun secara acak.

Tentukan peluang huruf $A$ dan $B$ berdampingan.

---

### Langkah 1: Menentukan Seluruh Susunan

$$
n(S)=5!
$$

$$
n(S)=120
$$

---

### Langkah 2: Menentukan Susunan yang Memenuhi

Anggap $A$ dan $B$ sebagai satu kelompok.

Maka terdapat:

$$
4
$$

objek:

$$
(AB),C,D,E
$$

Banyak susunannya:

$$
4!
$$

Di dalam kelompok:

$$
AB
$$

atau:

$$
BA
$$

Maka:

$$
n(A)=4!\times2
$$

$$
n(A)=48
$$

---

### Langkah 3: Menghitung Peluang

$$
\begin{aligned}
P(A)
&=\frac{48}{120}\\
&=\frac25
\end{aligned}
$$

Jadi:

$$
\boxed{\frac25}
$$

---

# Peluang dengan Beberapa Syarat

## Contoh 8

Dari:

- 6 siswa laki-laki,
- 5 siswa perempuan,

dipilih 4 siswa secara acak.

Tentukan peluang kelompok tersebut terdiri atas **minimal 2 siswa perempuan**.

Minimal 2 perempuan berarti:

1. tepat 2 perempuan,
2. tepat 3 perempuan,
3. tepat 4 perempuan.

---

### Langkah 1: Ruang Sampel

Jumlah siswa:

$$
11
$$

Maka:

$$
n(S)={}_{11}C_4
$$

$$
n(S)=330
$$

---

### Kasus 1: Tepat 2 Perempuan

$$
{}_5C_2\times{}_6C_2
$$

$$
=10\times15=150
$$

---

### Kasus 2: Tepat 3 Perempuan

$$
{}_5C_3\times{}_6C_1
$$

$$
=10\times6=60
$$

---

### Kasus 3: Tepat 4 Perempuan

$$
{}_5C_4\times{}_6C_0
$$

$$
=5
$$

---

### Langkah 2: Menentukan Banyak Kejadian

$$
\begin{aligned}
n(A)
&=150+60+5\\
&=215
\end{aligned}
$$

---

### Langkah 3: Menghitung Peluang

$$
\begin{aligned}
P(A)
&=\frac{215}{330}\\
&=\frac{43}{66}
\end{aligned}
$$

Jadi:

$$
\boxed{\frac{43}{66}}
$$

---

# Strategi Menyelesaikan Soal

Untuk setiap soal peluang berbasis pencacahan, gunakan pola:

$$
\boxed{
\text{Tentukan seluruh kemungkinan}
}
$$

$$
\downarrow
$$

$$
\boxed{
\text{Tentukan kemungkinan yang memenuhi syarat}
}
$$

$$
\downarrow
$$

$$
\boxed{
P(A)=\frac{n(A)}{n(S)}
}
$$

Kemudian tentukan metode pencacahan yang tepat.

---

# Soal Latihan

## Soal 1

Dari angka:

$$
1,2,3,4,5
$$

dibentuk bilangan dua digit tanpa pengulangan.

Satu bilangan dipilih secara acak.

Tentukan peluang bilangan tersebut lebih dari 30.

> [!success]- Klik untuk Lihat Jawaban
> Banyak seluruh bilangan:
>
> $$
> n(S)=5\times4=20
> $$
>
> Agar bilangan lebih dari 30, digit pertama harus:
>
> $$
> 3,4,\text{ atau }5
> $$
>
> sehingga terdapat:
>
> $$
> 3
> $$
>
> pilihan untuk digit pertama.
>
> Digit kedua memiliki:
>
> $$
> 4
> $$
>
> pilihan.
>
> Maka:
>
> $$
> n(A)=3\times4=12
> $$
>
> Sehingga:
>
> $$
> \begin{aligned}
> P(A)
> &=\frac{12}{20}\\
> &=\frac35
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac35}
> $$

---

## Soal 2

Enam siswa berdiri secara acak dalam satu baris.

Tentukan peluang Andi berada di salah satu ujung barisan.

> [!success]- Klik untuk Lihat Jawaban
> Banyak seluruh susunan:
>
> $$
> n(S)=6!
> $$
>
> Andi dapat berada di:
>
> - ujung kiri,
> - ujung kanan.
>
> Jadi terdapat:
>
> $$
> 2
> $$
>
> pilihan posisi untuk Andi.
>
> Lima siswa lainnya dapat disusun:
>
> $$
> 5!
> $$
>
> cara.
>
> Maka:
>
> $$
> n(A)=2\times5!
> $$
>
> Peluang:
>
> $$
> \begin{aligned}
> P(A)
> &=
> \frac{2\times5!}{6!}\\
> &=
> \frac{2}{6}\\
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

## Soal 3

Delapan siswa berdiri secara acak dalam satu baris.

Tentukan peluang Andi dan Budi berdampingan.

> [!success]- Klik untuk Lihat Jawaban
> Banyak seluruh susunan:
>
> $$
> n(S)=8!
> $$
>
> Jika Andi dan Budi berdampingan, anggap keduanya sebagai satu kelompok.
>
> Maka terdapat:
>
> $$
> 7
> $$
>
> objek.
>
> Banyak susunan:
>
> $$
> 7!
> $$
>
> Andi dan Budi dapat bertukar posisi:
>
> $$
> 2!
> $$
>
> Maka:
>
> $$
> n(A)=7!\times2
> $$
>
> Peluang:
>
> $$
> \begin{aligned}
> P(A)
> &=
> \frac{7!\times2}{8!}\\
> &=
> \frac{2}{8}\\
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

## Soal 4

Dalam sebuah kelas terdapat:

- 7 siswa laki-laki,
- 5 siswa perempuan.

Dipilih 3 siswa secara acak.

Tentukan peluang seluruh siswa yang terpilih perempuan.

> [!success]- Klik untuk Lihat Jawaban
> Jumlah seluruh siswa:
>
> $$
> 12
> $$
>
> Banyak seluruh kelompok:
>
> $$
> n(S)={}_{12}C_3
> $$
>
> $$
> n(S)=220
> $$
>
> Banyak kelompok yang seluruhnya perempuan:
>
> $$
> n(A)={}_5C_3
> $$
>
> $$
> n(A)=10
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A)
> &=
> \frac{10}{220}\\
> &=
> \frac1{22}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac1{22}}
> $$

---

## Soal 5

Sebuah kotak berisi:

- 7 bola merah,
- 5 bola biru,
- 3 bola hijau.

Diambil 4 bola sekaligus.

Tentukan peluang terambil tepat:

- 2 bola merah,
- 1 bola biru,
- 1 bola hijau.

> [!success]- Klik untuk Lihat Jawaban
> Jumlah seluruh bola:
>
> $$
> 15
> $$
>
> Banyak seluruh cara:
>
> $$
> n(S)={}_{15}C_4=1365
> $$
>
> Banyak kejadian yang memenuhi:
>
> $$
> n(A)
> =
> {}_7C_2\times{}_5C_1\times{}_3C_1
> $$
>
> $$
> =21\times5\times3
> $$
>
> $$
> =315
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A)
> &=
> \frac{315}{1365}\\
> &=
> \frac3{13}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac3{13}}
> $$

---

## Soal 6

Dari 10 siswa yang terdiri atas:

- 6 siswa laki-laki,
- 4 siswa perempuan,

dipilih 4 siswa secara acak.

Tentukan peluang kelompok yang terpilih memiliki **minimal 1 siswa perempuan**.

> [!success]- Klik untuk Lihat Jawaban
> Gunakan komplemen.
>
> Banyak seluruh kelompok:
>
> $$
> n(S)={}_{10}C_4=210
> $$
>
> Komplemen dari minimal 1 perempuan adalah seluruh anggota laki-laki.
>
> Banyak kelompok seluruh laki-laki:
>
> $$
> n(A^c)={}_6C_4=15
> $$
>
> Maka:
>
> $$
> P(A^c)=\frac{15}{210}=\frac1{14}
> $$
>
> Sehingga:
>
> $$
> \begin{aligned}
> P(A)
> &=1-\frac1{14}\\
> &=\frac{13}{14}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{13}{14}}
> $$

---

## Soal 7

Huruf-huruf pada kata:

$$
PELUANG
$$

disusun secara acak.

Tentukan peluang huruf $P$ dan $G$ berada berdampingan.

> [!success]- Klik untuk Lihat Jawaban
> Kata **PELUANG** terdiri atas:
>
> $$
> 7
> $$
>
> huruf berbeda.
>
> Banyak seluruh susunan:
>
> $$
> n(S)=7!
> $$
>
> Jika $P$ dan $G$ berdampingan, anggap keduanya sebagai satu kelompok.
>
> Maka terdapat:
>
> $$
> 6
> $$
>
> objek yang disusun.
>
> Banyak susunannya:
>
> $$
> 6!
> $$
>
> Di dalam kelompok:
>
> $$
> PG
> $$
>
> atau:
>
> $$
> GP
> $$
>
> sehingga:
>
> $$
> n(A)=6!\times2
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A)
> &=
> \frac{6!\times2}{7!}\\
> &=
> \frac27
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac27}
> $$

---

## Soal 8

Sebuah kelas terdiri atas:

- 8 siswa laki-laki,
- 6 siswa perempuan.

Dipilih 5 siswa secara acak.

Tentukan peluang kelompok yang terpilih memiliki **minimal 2 siswa perempuan dan minimal 1 siswa laki-laki**.

> [!success]- Klik untuk Lihat Jawaban
> Jumlah seluruh siswa:
>
> $$
> 14
> $$
>
> Banyak seluruh kelompok:
>
> $$
> n(S)={}_{14}C_5
> $$
>
> $$
> n(S)=2002
> $$
>
> Syarat:
>
> - minimal 2 perempuan,
> - minimal 1 laki-laki.
>
> Komposisi yang mungkin:
>
> 1. 2 perempuan dan 3 laki-laki,
> 2. 3 perempuan dan 2 laki-laki,
> 3. 4 perempuan dan 1 laki-laki.
>
> ### Kasus 1
>
> $$
> {}_6C_2\times{}_8C_3
> $$
>
> $$
> =15\times56=840
> $$
>
> ### Kasus 2
>
> $$
> {}_6C_3\times{}_8C_2
> $$
>
> $$
> =20\times28=560
> $$
>
> ### Kasus 3
>
> $$
> {}_6C_4\times{}_8C_1
> $$
>
> $$
> =15\times8=120
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> n(A)
> &=840+560+120\\
> &=1520
> \end{aligned}
> $$
>
> Peluangnya:
>
> $$
> \begin{aligned}
> P(A)
> &=
> \frac{1520}{2002}\\
> &=
> \frac{760}{1001}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{760}{1001}}
> $$

---

# Rangkuman

Kaidah pencacahan membantu menentukan:

$$
n(S)
$$

dan:

$$
n(A)
$$

dalam perhitungan peluang.

Rumus utama tetap:

$$
\boxed{
P(A)=\frac{n(A)}{n(S)}
}
$$

Gunakan **aturan perkalian** jika proses terdiri atas beberapa tahap.

Gunakan **permutasi** jika urutan diperhatikan:

$$
{}_nP_r
=
\frac{n!}{(n-r)!}
$$

Gunakan **kombinasi** jika urutan tidak diperhatikan:

$$
{}_nC_r
=
\frac{n!}{r!(n-r)!}
$$

Untuk kejadian seperti minimal satu, pertimbangkan penggunaan komplemen:

$$
P(A)=1-P(A^c)
$$

Jika terdapat beberapa komposisi yang memenuhi syarat, hitung setiap kasus kemudian jumlahkan.

---

> [!important]
> Dalam soal peluang berbasis pencacahan, jangan langsung menentukan rumus peluang.
>
> Analisis terlebih dahulu:
>
> 1. Apa seluruh kemungkinan yang dapat terjadi?
> 2. Apakah urutan diperhatikan?
> 3. Apakah terdapat pembatasan?
> 4. Apa saja kemungkinan yang memenuhi syarat?
> 5. Apakah lebih mudah menghitung langsung atau menggunakan komplemen?
>
> Setelah itu gunakan:
>
> $$
> P(A)=\frac{n(A)}{n(S)}
> $$

---

# Inti Materi

Hubungan seluruh materi dapat dirangkum menjadi:

$$
\boxed{
\text{Kaidah Pencacahan}
\rightarrow
n(S)\text{ dan }n(A)
}
$$

kemudian:

$$
\boxed{
P(A)=\frac{n(A)}{n(S)}
}
$$

Dengan demikian, kemampuan menentukan metode pencacahan yang tepat merupakan bagian penting dalam menyelesaikan permasalahan peluang yang lebih kompleks.

---

## Konsep Terkait

- [[Materi Baru Kaidah Pencacahan dan Peluang/03 - Permutasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/04 - Kombinasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/05 - Membedakan Permutasi dan Kombinasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/06 - Konsep Dasar Peluang]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/07 - Peluang Komplemen]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/12 - Latihan Terpadu Kaidah Pencacahan dan Peluang]]