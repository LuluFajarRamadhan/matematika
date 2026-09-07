# Peluang Komplemen

Pada materi sebelumnya, kita telah mempelajari peluang suatu kejadian:

$$
P(A)=\frac{n(A)}{n(S)}
$$

Dalam banyak masalah peluang, terkadang lebih mudah menghitung **kejadian yang tidak terjadi** dibandingkan menghitung kejadian yang ditanyakan secara langsung.

Konsep ini disebut **peluang komplemen**.

---

# Pengertian Komplemen Suatu Kejadian

Misalkan $A$ adalah suatu kejadian dalam ruang sampel $S$.

**Komplemen dari kejadian $A$** adalah kejadian yang berisi seluruh hasil dalam ruang sampel yang **tidak termasuk dalam $A$**.

Komplemen dari $A$ biasanya ditulis:

$$
A^c
$$

atau kadang ditulis:

$$
A'
$$

Dalam bahan ajar ini digunakan notasi:

$$
\boxed{A^c}
$$

---

## Contoh 1

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

Kejadian yang **bukan bilangan genap** adalah:

$$
A^c=\{1,3,5\}
$$

Sehingga:

$$
n(A)=3
$$

dan:

$$
n(A^c)=3
$$

---

# Hubungan Kejadian dengan Komplemennya

Setiap titik sampel pasti berada pada salah satu dari:

$$
A
$$

atau:

$$
A^c
$$

Tidak ada titik sampel yang berada pada keduanya sekaligus.

Karena itu:

$$
A\cup A^c=S
$$

dan:

$$
A\cap A^c=\varnothing
$$

Dalam bentuk peluang:

$$
P(A)+P(A^c)=1
$$

sehingga:

$$
\boxed{
P(A^c)=1-P(A)
}
$$

Demikian juga:

$$
\boxed{
P(A)=1-P(A^c)
}
$$

---

# Mengapa Jumlahnya Sama dengan 1?

Seluruh kemungkinan dalam ruang sampel mempunyai peluang total:

$$
P(S)=1
$$

Karena ruang sampel terbagi menjadi kejadian $A$ dan kejadian yang bukan $A$, maka:

$$
P(A)+P(A^c)=P(S)
$$

sehingga:

$$
P(A)+P(A^c)=1
$$

---

## Contoh 2

Peluang seorang siswa lulus ujian adalah:

$$
P(A)=0,85
$$

Tentukan peluang siswa tersebut tidak lulus.

Kejadian tidak lulus merupakan komplemen dari kejadian lulus.

Maka:

$$
\begin{aligned}
P(A^c)
&=1-P(A)\\
&=1-0,85\\
&=0,15
\end{aligned}
$$

Jadi:

$$
\boxed{P(A^c)=0,15}
$$

atau:

$$
\boxed{15\%}
$$

---

# Komplemen dalam Bentuk Pecahan

Jika:

$$
P(A)=\frac{3}{8}
$$

maka:

$$
\begin{aligned}
P(A^c)
&=1-\frac38\\
&=\frac88-\frac38\\
&=\frac58
\end{aligned}
$$

Jadi:

$$
\boxed{
P(A^c)=\frac58
}
$$

---

# Mengenali Kata yang Berkaitan dengan Komplemen

Beberapa bentuk pertanyaan sering berkaitan dengan konsep komplemen.

Contohnya:

- bukan,
- tidak,
- tidak terjadi,
- tidak ada,
- minimal satu,
- paling sedikit satu,
- sekurang-kurangnya satu.

Namun, tidak semua soal dengan kata-kata tersebut harus selalu diselesaikan dengan komplemen.

Komplemen digunakan jika cara tersebut membuat perhitungan menjadi lebih sederhana.

---

> [!important]
> Peluang komplemen bukan sekadar rumus baru.
>
> Konsep ini merupakan **strategi menghitung kejadian melalui kejadian lawannya**.

---

# Contoh Komplemen pada Pengambilan Bola

Sebuah kotak berisi:

- 5 bola merah,
- 3 bola biru,
- 2 bola hijau.

Satu bola diambil secara acak.

Tentukan peluang bola yang terambil **bukan merah**.

Jumlah seluruh bola:

$$
n(S)=10
$$

Peluang terambil bola merah:

$$
P(M)=\frac5{10}=\frac12
$$

Maka peluang bukan merah:

$$
\begin{aligned}
P(M^c)
&=1-P(M)\\
&=1-\frac12\\
&=\frac12
\end{aligned}
$$

Jadi:

$$
\boxed{\frac12}
$$

---

# Komplemen pada Percobaan Berulang

Konsep komplemen sangat berguna ketika suatu percobaan dilakukan beberapa kali.

Misalnya:

> Berapa peluang muncul **minimal satu gambar** ketika tiga koin dilempar?

Menghitung langsung berarti kita harus menghitung:

- tepat 1 gambar,
- tepat 2 gambar,
- tepat 3 gambar.

Cara tersebut dapat dilakukan, tetapi lebih panjang.

Kejadian lawan dari:

> minimal satu gambar

adalah:

> tidak muncul gambar sama sekali.

Artinya, semua koin harus menunjukkan angka.

---

## Contoh 3

Tiga koin dilempar secara bersamaan.

Tentukan peluang muncul minimal satu sisi gambar.

Misalkan $A$ adalah kejadian muncul minimal satu gambar.

Komplemennya:

$$
A^c=\text{tidak muncul gambar}
$$

Artinya:

$$
AAA
$$

Jumlah seluruh kemungkinan:

$$
n(S)=2^3=8
$$

Peluang tidak muncul gambar:

$$
P(A^c)=\frac18
$$

Maka:

$$
\begin{aligned}
P(A)
&=1-P(A^c)\\
&=1-\frac18\\
&=\frac78
\end{aligned}
$$

Jadi:

$$
\boxed{\frac78}
$$

---

# Pola "Minimal Satu"

Salah satu penggunaan komplemen yang paling penting adalah:

$$
\boxed{
P(\text{minimal satu})
=
1-P(\text{tidak ada})
}
$$

Contohnya:

$$
P(\text{minimal satu sukses})
=
1-P(\text{tidak ada sukses})
$$

atau:

$$
P(\text{minimal satu bola merah})
=
1-P(\text{tidak ada bola merah})
$$

---

# Contoh 4

Sebuah dadu dilempar dua kali.

Tentukan peluang muncul angka 6 **minimal satu kali**.

Lebih mudah menghitung komplemennya.

Komplemen dari minimal satu kali muncul 6 adalah:

> tidak muncul angka 6 pada kedua pelemparan.

Pada satu pelemparan:

$$
P(\text{bukan }6)=\frac56
$$

Untuk dua pelemparan:

$$
P(\text{tidak muncul }6)
=
\frac56\times\frac56
=
\frac{25}{36}
$$

Maka:

$$
\begin{aligned}
P(\text{minimal satu }6)
&=
1-\frac{25}{36}\\
&=
\frac{11}{36}
\end{aligned}
$$

Jadi:

$$
\boxed{\frac{11}{36}}
$$

---

> [!note]
> Pada contoh di atas digunakan aturan perkalian karena hasil pelemparan pertama tidak mengubah kemungkinan pada pelemparan kedua.
>
> Konsep kejadian seperti ini akan dibahas lebih lanjut pada materi **kejadian saling bebas**.

---

# Komplemen dengan Kombinasi

Konsep komplemen juga dapat digabungkan dengan kombinasi.

---

## Contoh 5

Sebuah kelas terdiri atas:

- 6 siswa laki-laki,
- 4 siswa perempuan.

Dipilih 3 siswa secara acak.

Tentukan peluang terpilih **minimal 1 siswa perempuan**.

### Langkah 1: Menentukan Banyak Ruang Sampel

Jumlah siswa:

$$
10
$$

Dipilih 3 siswa:

$$
n(S)={}_{10}C_3
$$

Maka:

$$
n(S)=120
$$

### Langkah 2: Menentukan Kejadian Komplemen

Komplemen dari minimal 1 siswa perempuan adalah:

> tidak ada siswa perempuan yang terpilih.

Artinya, seluruh siswa terpilih adalah laki-laki.

Maka:

$$
n(A^c)={}_6C_3
$$

$$
n(A^c)=20
$$

### Langkah 3: Menghitung Peluang Komplemen

$$
P(A^c)
=
\frac{20}{120}
=
\frac16
$$

### Langkah 4: Menghitung Peluang yang Ditanyakan

$$
\begin{aligned}
P(A)
&=1-\frac16\\
&=\frac56
\end{aligned}
$$

Jadi:

$$
\boxed{\frac56}
$$

---

# Kapan Komplemen Lebih Efisien?

Bandingkan dua cara berikut.

Misalnya diminta:

> peluang minimal satu siswa perempuan dari 3 siswa yang dipilih.

Jika dihitung langsung, kita harus mempertimbangkan:

1. tepat 1 perempuan,
2. tepat 2 perempuan,
3. tepat 3 perempuan.

Dengan komplemen, cukup menghitung satu kejadian:

> tidak ada perempuan.

Karena itu, komplemen sangat berguna ketika kejadian yang ditanyakan terdiri atas banyak kasus, tetapi kejadian lawannya jauh lebih sederhana.

---

# Komplemen Tidak Selalu Harus Digunakan

Misalnya:

> peluang muncul angka genap pada satu pelemparan dadu.

Kita dapat langsung menghitung:

$$
P(A)=\frac36=\frac12
$$

Tidak ada keuntungan berarti jika menggunakan komplemen.

Jadi, pemilihan metode bergantung pada efisiensi penyelesaian.

---

# Strategi Menyelesaikan Soal Peluang Komplemen

Gunakan langkah berikut.

### Langkah 1

Tentukan kejadian yang ditanyakan.

Misalkan:

$$
A
$$

### Langkah 2

Tentukan kejadian lawannya:

$$
A^c
$$

### Langkah 3

Bandingkan mana yang lebih mudah dihitung:

$$
A
$$

atau:

$$
A^c
$$

### Langkah 4

Jika komplemen lebih sederhana, hitung:

$$
P(A^c)
$$

### Langkah 5

Gunakan:

$$
\boxed{
P(A)=1-P(A^c)
}
$$

---

# Soal Latihan

## Soal 1

Diketahui:

$$
P(A)=\frac{3}{7}
$$

Tentukan:

$$
P(A^c)
$$

> [!success]- Klik untuk Lihat Jawaban
> Gunakan:
>
> $$
> P(A^c)=1-P(A)
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A^c)
> &=1-\frac37\\
> &=\frac47
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac47}
> $$

---

## Soal 2

Peluang sebuah mesin bekerja dengan baik adalah:

$$
0,92
$$

Tentukan peluang mesin mengalami gangguan.

> [!success]- Klik untuk Lihat Jawaban
> Kejadian mengalami gangguan merupakan komplemen dari bekerja dengan baik.
>
> Maka:
>
> $$
> \begin{aligned}
> P(A^c)
> &=1-0,92\\
> &=0,08
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{0,08}
> $$
>
> atau:
>
> $$
> \boxed{8\%}
> $$

---

## Soal 3

Sebuah dadu dilempar satu kali.

Tentukan peluang **tidak muncul bilangan prima**.

> [!success]- Klik untuk Lihat Jawaban
> Bilangan prima pada dadu adalah:
>
> $$
> 2,3,5
> $$
>
> sehingga:
>
> $$
> P(A)=\frac36=\frac12
> $$
>
> Peluang tidak muncul bilangan prima:
>
> $$
> \begin{aligned}
> P(A^c)
> &=1-\frac12\\
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

Tentukan peluang muncul **minimal satu sisi gambar**.

> [!success]- Klik untuk Lihat Jawaban
> Misalkan $A$ adalah kejadian muncul minimal satu gambar.
>
> Komplemennya adalah:
>
> > tidak muncul gambar sama sekali.
>
> Artinya:
>
> $$
> AA
> $$
>
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
> Peluang tidak muncul gambar:
>
> $$
> P(A^c)=\frac14
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A)
> &=1-\frac14\\
> &=\frac34
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac34}
> $$

---

## Soal 5

Sebuah dadu dilempar tiga kali.

Tentukan peluang angka 6 muncul **minimal satu kali**.

> [!success]- Klik untuk Lihat Jawaban
> Kejadian komplemennya adalah angka 6 tidak muncul sama sekali.
>
> Pada satu kali pelemparan:
>
> $$
> P(\text{bukan }6)=\frac56
> $$
>
> Pada tiga kali pelemparan:
>
> $$
> P(A^c)
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
> P(A)
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

## Soal 6

Sebuah kotak berisi:

- 5 bola merah,
- 4 bola biru.

Diambil 2 bola sekaligus secara acak.

Tentukan peluang **minimal satu bola merah** terambil.

> [!success]- Klik untuk Lihat Jawaban
> Kejadian komplemen dari minimal satu bola merah adalah:
>
> > kedua bola yang terambil bukan merah.
>
> Karena hanya terdapat bola merah dan biru, berarti kedua bola harus biru.
>
> Banyak seluruh cara memilih 2 bola dari 9:
>
> $$
> n(S)={}_9C_2=36
> $$
>
> Banyak cara memilih 2 bola biru dari 4:
>
> $$
> n(A^c)={}_4C_2=6
> $$
>
> Maka:
>
> $$
> P(A^c)=\frac6{36}=\frac16
> $$
>
> Sehingga:
>
> $$
> \begin{aligned}
> P(A)
> &=1-\frac16\\
> &=\frac56
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac56}
> $$

---

## Soal 7

Dalam sebuah kelas terdapat:

- 7 siswa laki-laki,
- 5 siswa perempuan.

Dipilih 4 siswa secara acak.

Tentukan peluang kelompok yang terpilih **tidak seluruhnya laki-laki**.

> [!success]- Klik untuk Lihat Jawaban
> Kejadian:
>
> > tidak seluruhnya laki-laki
>
> mempunyai komplemen:
>
> > seluruh siswa yang terpilih laki-laki.
>
> Jumlah seluruh siswa:
>
> $$
> 12
> $$
>
> Banyak seluruh kelompok:
>
> $$
> n(S)={}_{12}C_4
> $$
>
> $$
> n(S)=495
> $$
>
> Banyak kelompok yang seluruhnya laki-laki:
>
> $$
> n(A^c)={}_7C_4=35
> $$
>
> Maka:
>
> $$
> P(A^c)=\frac{35}{495}
> =\frac7{99}
> $$
>
> Sehingga:
>
> $$
> \begin{aligned}
> P(A)
> &=1-\frac7{99}\\
> &=\frac{92}{99}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{92}{99}}
> $$

---

## Soal 8

Sebuah kotak berisi:

- 6 bola merah,
- 5 bola biru,
- 4 bola hijau.

Diambil 4 bola sekaligus secara acak.

Tentukan peluang bahwa dari 4 bola yang terambil terdapat **minimal satu bola dari setiap warna**.

> [!success]- Klik untuk Lihat Jawaban
> Jumlah seluruh bola:
>
> $$
> 6+5+4=15
> $$
>
> Banyak seluruh cara mengambil 4 bola:
>
> $$
> n(S)={}_{15}C_4
> $$
>
> $$
> n(S)=1365
> $$
>
> Karena diambil 4 bola dan harus terdapat minimal satu dari setiap warna, komposisi yang mungkin adalah:
>
> $$
> (2,1,1)
> $$
>
> Artinya, salah satu warna muncul 2 kali dan dua warna lainnya masing-masing 1 kali.
>
> Kita bagi menjadi tiga kasus.
>
> ### Kasus 1: 2 Merah, 1 Biru, 1 Hijau
>
> $$
> {}_6C_2\times{}_5C_1\times{}_4C_1
> $$
>
> $$
> =15\times5\times4=300
> $$
>
> ### Kasus 2: 1 Merah, 2 Biru, 1 Hijau
>
> $$
> {}_6C_1\times{}_5C_2\times{}_4C_1
> $$
>
> $$
> =6\times10\times4=240
> $$
>
> ### Kasus 3: 1 Merah, 1 Biru, 2 Hijau
>
> $$
> {}_6C_1\times{}_5C_1\times{}_4C_2
> $$
>
> $$
> =6\times5\times6=180
> $$
>
> Jumlah kejadian yang memenuhi:
>
> $$
> n(A)=300+240+180=720
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A)
> &=\frac{720}{1365}\\
> &=\frac{48}{91}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{48}{91}}
> $$
>
> Pada soal ini, menghitung kejadian secara langsung lebih efisien daripada menggunakan komplemen karena komplemennya terdiri atas banyak kasus.

---

# Rangkuman

Komplemen dari kejadian $A$ adalah kejadian yang berisi seluruh hasil dalam ruang sampel yang tidak termasuk dalam $A$.

Ditulis:

$$
A^c
$$

Hubungan antara suatu kejadian dan komplemennya:

$$
A\cup A^c=S
$$

dan:

$$
A\cap A^c=\varnothing
$$

Dalam bentuk peluang:

$$
\boxed{
P(A)+P(A^c)=1
}
$$

sehingga:

$$
\boxed{
P(A^c)=1-P(A)
}
$$

atau:

$$
\boxed{
P(A)=1-P(A^c)
}
$$

Konsep komplemen sangat berguna untuk masalah seperti:

- bukan,
- tidak terjadi,
- minimal satu,
- paling sedikit satu.

Khusus untuk kejadian minimal satu:

$$
\boxed{
P(\text{minimal satu})
=
1-P(\text{tidak ada})
}
$$

Namun, komplemen tidak harus selalu digunakan. Pilih cara yang membuat perhitungan menjadi paling sederhana.

---

> [!important]
> Sebelum menggunakan komplemen, tanyakan:
>
> **Apa kejadian lawan dari kejadian yang diminta?**
>
> Kemudian bandingkan:
>
> $$
> \boxed{
> \text{lebih mudah menghitung kejadian langsung}
> }
> $$
>
> atau:
>
> $$
> \boxed{
> \text{lebih mudah menghitung komplemennya}
> }
> $$
>
> Gunakan metode yang lebih efisien.

---

## Konsep Terkait

- [[Kaidah Pencacahan dan Peluang/06 - Konsep Dasar Peluang]]
- [[Kaidah Pencacahan dan Peluang/08 - Peluang Kejadian Majemuk]]
- [[Kaidah Pencacahan dan Peluang/09 - Peluang Bersyarat]]
- [[Kaidah Pencacahan dan Peluang/10 - Kejadian Saling Bebas]]
- [[Kaidah Pencacahan dan Peluang/11 - Penerapan Kaidah Pencacahan dalam Peluang]]