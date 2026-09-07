# Permutasi

Pada materi sebelumnya, kita telah mempelajari faktorial dan aturan perkalian.

Misalnya, terdapat 5 siswa yang akan berdiri berjajar.

Untuk posisi pertama tersedia:

$$
5
$$

pilihan.

Setelah satu siswa menempati posisi pertama, posisi kedua memiliki:

$$
4
$$

pilihan.

Kemudian:

$$
3,\ 2,\ 1
$$

pilihan untuk posisi berikutnya.

Maka banyak susunan yang dapat dibuat adalah:

$$
5\times4\times3\times2\times1
$$

atau:

$$
5!
$$

Konsep penyusunan seperti ini disebut **permutasi**.

---

# Pengertian Permutasi

**Permutasi** adalah penyusunan sejumlah objek dengan **memperhatikan urutan**.

Dalam permutasi, perubahan posisi objek menghasilkan susunan yang berbeda.

Sebagai contoh, tiga huruf:

$$
A,\ B,\ C
$$

dapat disusun menjadi:

$$
ABC,\ ACB,\ BAC,\ BCA,\ CAB,\ CBA
$$

Terdapat:

$$
6
$$

susunan berbeda.

Perhatikan bahwa:

$$
ABC\neq BAC
$$

meskipun keduanya menggunakan huruf yang sama.

Hal ini terjadi karena **urutannya berbeda**.

---

> [!important]
> Pertanyaan utama dalam menentukan apakah suatu masalah menggunakan permutasi adalah:
>
> **Apakah perubahan urutan menghasilkan hasil yang berbeda?**
>
> Jika jawabannya **ya**, maka masalah tersebut berkaitan dengan permutasi.

---

# Permutasi Seluruh Unsur Berbeda

Jika terdapat $n$ objek berbeda dan seluruh objek tersebut akan disusun, banyak susunannya adalah:

$$
\boxed{n!}
$$

---

## Contoh 1

Berapa banyak cara menyusun 4 buku berbeda dalam satu baris?

Untuk posisi pertama terdapat:

$$
4
$$

pilihan.

Posisi kedua:

$$
3
$$

pilihan.

Posisi ketiga:

$$
2
$$

pilihan.

Posisi keempat:

$$
1
$$

pilihan.

Maka:

$$
\begin{aligned}
n
&=4\times3\times2\times1\\
&=4!\\
&=24
\end{aligned}
$$

Jadi:

$$
\boxed{24}
$$

susunan berbeda dapat dibuat.

---

# Permutasi Sebagian Unsur

Tidak semua objek harus selalu digunakan.

Misalnya, dari 6 siswa akan dipilih 3 siswa untuk menempati posisi:

- ketua,
- sekretaris,
- bendahara.

Karena ketiga posisi tersebut berbeda, urutan atau jabatan yang diperoleh siswa juga berbeda.

Jika Andi menjadi ketua dan Budi menjadi sekretaris, hasilnya berbeda dengan Budi menjadi ketua dan Andi menjadi sekretaris.

Karena urutan diperhatikan, digunakan permutasi.

---

## Rumus Permutasi Sebagian Unsur

Banyak permutasi $r$ unsur yang dipilih dari $n$ unsur berbeda adalah:

$$
\boxed{{}_nP_r=\frac{n!}{(n-r)!}}
$$

dengan:

- $n$ = banyak seluruh objek,
- $r$ = banyak objek yang disusun.

---

## Mengapa Rumusnya Demikian?

Misalkan terdapat $n$ objek dan akan diisi sebanyak $r$ posisi.

Untuk posisi pertama:

$$
n
$$

pilihan.

Untuk posisi kedua:

$$
n-1
$$

pilihan.

Posisi ketiga:

$$
n-2
$$

pilihan.

Dilanjutkan sampai sebanyak $r$ posisi.

Sehingga:

$$
{}_nP_r
=
n(n-1)(n-2)\cdots(n-r+1)
$$

Bentuk tersebut dapat ditulis sebagai:

$$
{}_nP_r
=
\frac{n!}{(n-r)!}
$$

---

## Contoh 2

Dari 7 siswa akan dipilih ketua, sekretaris, dan bendahara.

Berapa banyak susunan pengurus yang dapat dibentuk?

Karena terdapat:

$$
n=7
$$

dan:

$$
r=3
$$

maka:

$$
\begin{aligned}
{}_7P_3
&=
\frac{7!}{(7-3)!}\\
&=
\frac{7!}{4!}\\
&=
7\times6\times5\\
&=210
\end{aligned}
$$

Jadi:

$$
\boxed{210}
$$

susunan pengurus dapat dibentuk.

---

# Permutasi dan Aturan Perkalian

Permutasi sebenarnya merupakan bentuk khusus dari aturan perkalian.

Pada contoh sebelumnya:

$$
{}_7P_3
$$

dapat langsung dihitung sebagai:

$$
7\times6\times5
$$

karena:

- ketua memiliki 7 pilihan,
- sekretaris memiliki 6 pilihan,
- bendahara memiliki 5 pilihan.

Maka:

$$
{}_7P_3
=
7\times6\times5
=
210
$$

---

> [!note]
> Untuk nilai $r$ yang kecil, sering kali lebih cepat menggunakan aturan perkalian daripada menuliskan faktorial secara lengkap.
>
> Contoh:
>
> $$
> {}_{10}P_3
> =
> 10\times9\times8
> $$

---

# Permutasi dengan Pembatasan

Pada beberapa soal, susunan yang dibuat harus memenuhi syarat tertentu.

Dalam kasus seperti ini, kita perlu memperhatikan posisi yang memiliki pembatasan terlebih dahulu.

---

## Contoh 3

Lima siswa, yaitu:

$$
A,\ B,\ C,\ D,\ E
$$

akan berdiri berjajar.

Berapa banyak susunan jika $A$ harus berada di posisi pertama?

Karena posisi pertama sudah ditempati $A$, kita hanya perlu menyusun:

$$
B,\ C,\ D,\ E
$$

pada 4 posisi yang tersisa.

Maka:

$$
4!=24
$$

Jadi:

$$
\boxed{24}
$$

susunan dapat dibuat.

---

## Contoh 4

Enam siswa akan berdiri berjajar. Andi dan Budi harus selalu berdampingan.

Berapa banyak susunan yang dapat dibuat?

Anggap Andi dan Budi sebagai satu kelompok:

$$
(AB)
$$

Maka objek yang disusun menjadi:

$$
(AB),C,D,E,F
$$

Terdapat:

$$
5
$$

objek.

Banyak susunan kelima objek tersebut:

$$
5!
$$

Namun, di dalam kelompok, Andi dan Budi dapat tersusun:

$$
AB
$$

atau:

$$
BA
$$

sehingga terdapat:

$$
2!
$$

susunan.

Maka:

$$
\begin{aligned}
n
&=5!\times2!\\
&=120\times2\\
&=240
\end{aligned}
$$

Jadi:

$$
\boxed{240}
$$

susunan dapat dibuat.

---

# Permutasi dengan Beberapa Unsur Sama

Tidak semua objek yang disusun selalu berbeda.

Misalnya, kita ingin menyusun huruf-huruf pada kata:

$$
MAMA
$$

Jika semua huruf dianggap berbeda, kita memperoleh:

$$
4!
$$

susunan.

Namun, terdapat:

- 2 huruf $M$ yang sama,
- 2 huruf $A$ yang sama.

Menukar posisi kedua huruf $M$ tidak menghasilkan susunan baru.

Demikian juga dengan kedua huruf $A$.

Oleh karena itu, kita harus membagi hasil faktorial dengan faktorial banyak unsur yang sama.

---

## Rumus Permutasi dengan Unsur Sama

Jika terdapat $n$ objek dengan:

- $n_1$ objek jenis pertama yang sama,
- $n_2$ objek jenis kedua yang sama,
- dan seterusnya,

maka banyak susunan berbeda adalah:

$$
\boxed{
P=
\frac{n!}
{n_1!n_2!\cdots n_k!}
}
$$

dengan:

$$
n_1+n_2+\cdots+n_k=n
$$

---

## Contoh 5

Berapa banyak susunan berbeda dari huruf-huruf pada kata:

$$
MAMA
$$

Jumlah seluruh huruf:

$$
4
$$

Terdapat:

- 2 huruf $M$,
- 2 huruf $A$.

Maka:

$$
\begin{aligned}
P
&=
\frac{4!}{2!2!}\\
&=
\frac{24}{4}\\
&=6
\end{aligned}
$$

Jadi:

$$
\boxed{6}
$$

susunan berbeda dapat dibuat.

---

## Contoh 6

Berapa banyak susunan berbeda dari huruf-huruf pada kata:

$$
MATEMATIKA
$$

Jumlah seluruh huruf:

$$
10
$$

Perhatikan huruf yang berulang:

- $A$ muncul 3 kali,
- $M$ muncul 2 kali,
- $T$ muncul 2 kali,
- $E$, $I$, dan $K$ masing-masing muncul 1 kali.

Maka:

$$
P=
\frac{10!}{3!2!2!}
$$

sehingga:

$$
\begin{aligned}
P
&=
\frac{3628800}{6\times2\times2}\\
&=
\frac{3628800}{24}\\
&=151200
\end{aligned}
$$

Jadi:

$$
\boxed{151200}
$$

susunan berbeda dapat dibuat.

---

# Permutasi Siklis

Permutasi siklis digunakan ketika objek disusun **melingkar**.

Misalnya:

- duduk mengelilingi meja bundar,
- menyusun orang dalam sebuah lingkaran.

Pada susunan melingkar, dua susunan yang hanya berbeda karena seluruh objek diputar dianggap sebagai susunan yang sama.

---

## Mengapa Berbeda dengan Susunan Berjajar?

Misalkan tiga orang:

$$
A,\ B,\ C
$$

duduk mengelilingi sebuah meja bundar.

Susunan:

$$
A-B-C
$$

jika seluruh posisi diputar menjadi:

$$
B-C-A
$$

atau:

$$
C-A-B
$$

sebenarnya tidak menghasilkan susunan relatif yang baru.

Karena itu, salah satu objek dapat dianggap tetap sebagai titik acuan.

---

## Rumus Permutasi Siklis

Banyak susunan melingkar dari $n$ objek berbeda adalah:

$$
\boxed{(n-1)!}
$$

---

## Contoh 7

Enam orang duduk mengelilingi sebuah meja bundar.

Berapa banyak susunan tempat duduk yang berbeda?

Gunakan:

$$
(n-1)!
$$

Maka:

$$
\begin{aligned}
P
&=(6-1)!\\
&=5!\\
&=120
\end{aligned}
$$

Jadi:

$$
\boxed{120}
$$

susunan berbeda dapat dibuat.

---

> [!important]
> Susunan berjajar:
>
> $$
> n!
> $$
>
> Susunan melingkar:
>
> $$
> (n-1)!
> $$
>
> Perbedaannya muncul karena pada susunan melingkar, hasil yang hanya berbeda akibat perputaran dianggap sama.

---

# Permutasi Siklis dengan Pembatasan

Pembatasan juga dapat muncul pada susunan melingkar.

---

## Contoh 8

Enam orang duduk mengelilingi meja bundar. Andi dan Budi harus duduk berdampingan.

Berapa banyak susunan yang dapat dibuat?

Anggap Andi dan Budi sebagai satu kelompok.

Maka terdapat:

$$
5
$$

objek yang disusun melingkar.

Banyak susunan melingkar:

$$
(5-1)!=4!
$$

Andi dan Budi dapat bertukar posisi:

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

kemungkinan.

Maka:

$$
\begin{aligned}
n
&=4!\times2!\\
&=24\times2\\
&=48
\end{aligned}
$$

Jadi:

$$
\boxed{48}
$$

susunan dapat dibuat.

---

# Membedakan Jenis Permutasi

Sebelum menggunakan rumus, tentukan terlebih dahulu jenis masalahnya.

## 1. Seluruh objek berbeda disusun

Gunakan:

$$
\boxed{n!}
$$

## 2. Sebagian objek dipilih dan disusun

Gunakan:

$$
\boxed{{}_nP_r=\frac{n!}{(n-r)!}}
$$

## 3. Terdapat beberapa objek yang sama

Gunakan:

$$
\boxed{
\frac{n!}{n_1!n_2!\cdots n_k!}
}
$$

## 4. Objek disusun melingkar

Gunakan:

$$
\boxed{(n-1)!}
$$

---

# Strategi Menyelesaikan Masalah Permutasi

Sebelum melakukan perhitungan, tanyakan:

### Langkah 1

Apakah **urutan berpengaruh**?

Jika tidak, kemungkinan besar masalah tersebut bukan permutasi.

### Langkah 2

Apakah seluruh objek digunakan?

Jika ya, pertimbangkan:

$$
n!
$$

### Langkah 3

Apakah hanya sebagian objek digunakan?

Pertimbangkan:

$$
{}_nP_r
$$

### Langkah 4

Apakah terdapat objek yang sama?

Jika ada, perhatikan banyak pengulangan setiap objek.

### Langkah 5

Apakah susunannya melingkar?

Jika ya, gunakan konsep permutasi siklis.

### Langkah 6

Periksa apakah terdapat syarat khusus seperti:

- harus berdampingan,
- tidak boleh berdampingan,
- harus berada pada posisi tertentu.

---

# Soal Latihan

## Soal 1

Lima buku berbeda akan disusun berjajar pada sebuah rak.

Berapa banyak susunan yang dapat dibuat?

> [!success]- Klik untuk Lihat Jawaban
> Seluruh 5 buku berbeda digunakan dan urutannya diperhatikan.
>
> Maka:
>
> $$
> \begin{aligned}
> P
> &=5!\\
> &=5\times4\times3\times2\times1\\
> &=120
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{120}
> $$
>
> susunan dapat dibuat.

---

## Soal 2

Dari 8 siswa akan dipilih seorang ketua, seorang sekretaris, dan seorang bendahara.

Berapa banyak susunan pengurus yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Karena jabatan ketua, sekretaris, dan bendahara berbeda, urutan atau posisi siswa diperhatikan.
>
> Gunakan permutasi:
>
> $$
> \begin{aligned}
> {}_8P_3
> &=
> \frac{8!}{5!}\\
> &=8\times7\times6\\
> &=336
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{336}
> $$
>
> susunan pengurus dapat dibentuk.

---

## Soal 3

Terdapat 9 peserta lomba. Akan ditentukan juara 1, juara 2, dan juara 3.

Berapa banyak kemungkinan susunan pemenang?

> [!success]- Klik untuk Lihat Jawaban
> Urutan pemenang diperhatikan karena juara 1, 2, dan 3 merupakan posisi yang berbeda.
>
> Maka:
>
> $$
> \begin{aligned}
> {}_9P_3
> &=9\times8\times7\\
> &=504
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{504}
> $$
>
> kemungkinan susunan pemenang.

---

## Soal 4

Enam siswa akan berdiri berjajar.

Berapa banyak susunan yang dapat dibuat jika Andi harus selalu berada di posisi paling kiri?

> [!success]- Klik untuk Lihat Jawaban
> Posisi paling kiri sudah ditempati Andi.
>
> Lima siswa lainnya dapat disusun pada 5 posisi yang tersisa.
>
> Maka:
>
> $$
> \begin{aligned}
> n
> &=5!\\
> &=120
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{120}
> $$
>
> susunan dapat dibuat.

---

## Soal 5

Tujuh siswa akan berdiri berjajar. Andi dan Budi harus selalu berdampingan.

Berapa banyak susunan yang dapat dibuat?

> [!success]- Klik untuk Lihat Jawaban
> Andi dan Budi dianggap sebagai satu kelompok.
>
> Maka objek yang disusun adalah:
>
> $$
> (AB),C,D,E,F,G
> $$
>
> sehingga terdapat:
>
> $$
> 6
> $$
>
> objek.
>
> Banyak susunan keenam objek:
>
> $$
> 6!
> $$
>
> Di dalam kelompok, Andi dan Budi dapat tersusun:
>
> $$
> AB
> $$
>
> atau:
>
> $$
> BA
> $$
>
> sehingga:
>
> $$
> 2!
> $$
>
> cara.
>
> Maka:
>
> $$
> \begin{aligned}
> n
> &=6!\times2!\\
> &=720\times2\\
> &=1440
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{1440}
> $$
>
> susunan dapat dibuat.

---

## Soal 6

Berapa banyak susunan berbeda yang dapat dibuat dari seluruh huruf pada kata:

$$
STATISTIK
$$

> [!success]- Klik untuk Lihat Jawaban
> Kata **STATISTIK** terdiri atas:
>
> $$
> 9
> $$
>
> huruf.
>
> Huruf yang berulang:
>
> - $T$ sebanyak 3 kali,
> - $S$ sebanyak 2 kali,
> - $I$ sebanyak 2 kali.
>
> Huruf $A$ dan $K$ masing-masing muncul satu kali.
>
> Maka:
>
> $$
> P=
> \frac{9!}{3!2!2!}
> $$
>
> sehingga:
>
> $$
> \begin{aligned}
> P
> &=
> \frac{362880}{6\times2\times2}\\
> &=
> \frac{362880}{24}\\
> &=15120
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{15120}
> $$
>
> susunan berbeda dapat dibuat.

---

## Soal 7

Delapan orang duduk mengelilingi sebuah meja bundar.

Berapa banyak susunan tempat duduk yang berbeda?

> [!success]- Klik untuk Lihat Jawaban
> Karena susunan berbentuk melingkar, gunakan permutasi siklis:
>
> $$
> (n-1)!
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P
> &=(8-1)!\\
> &=7!\\
> &=5040
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{5040}
> $$
>
> susunan tempat duduk berbeda.

---

## Soal 8

Delapan siswa yang terdiri atas Andi, Budi, dan 6 siswa lainnya akan berdiri berjajar.

Tentukan banyak susunan yang dapat dibuat jika **Andi dan Budi tidak boleh berdampingan**.

> [!success]- Klik untuk Lihat Jawaban
> Cara yang lebih efisien adalah menggunakan:
>
> $$
> \text{seluruh susunan}
> -
> \text{susunan ketika Andi dan Budi berdampingan}
> $$
>
> ### Langkah 1: Menghitung Seluruh Susunan
>
> Delapan siswa berbeda dapat disusun:
>
> $$
> 8!
> $$
>
> sehingga:
>
> $$
> 8!=40320
> $$
>
> ### Langkah 2: Menghitung Susunan Andi dan Budi Berdampingan
>
> Anggap Andi dan Budi sebagai satu kelompok.
>
> Maka terdapat:
>
> $$
> 7
> $$
>
> objek yang disusun.
>
> Banyak susunannya:
>
> $$
> 7!
> $$
>
> Di dalam kelompok, Andi dan Budi dapat tersusun:
>
> $$
> AB
> $$
>
> atau:
>
> $$
> BA
> $$
>
> sehingga terdapat:
>
> $$
> 2!
> $$
>
> susunan.
>
> Maka:
>
> $$
> \begin{aligned}
> n(\text{berdampingan})
> &=7!\times2!\\
> &=5040\times2\\
> &=10080
> \end{aligned}
> $$
>
> ### Langkah 3: Menghitung Susunan Tidak Berdampingan
>
> $$
> \begin{aligned}
> n
> &=40320-10080\\
> &=30240
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{30240}
> $$
>
> susunan dapat dibuat jika Andi dan Budi tidak berdampingan.

---

# Rangkuman

Permutasi digunakan untuk menghitung banyak susunan ketika **urutan objek diperhatikan**.

Jika seluruh $n$ objek berbeda disusun:

$$
\boxed{n!}
$$

Jika $r$ objek dipilih dan disusun dari $n$ objek berbeda:

$$
\boxed{
{}_nP_r
=
\frac{n!}{(n-r)!}
}
$$

Jika terdapat beberapa unsur yang sama:

$$
\boxed{
P=
\frac{n!}{n_1!n_2!\cdots n_k!}
}
$$

Jika $n$ objek disusun secara melingkar:

$$
\boxed{(n-1)!}
$$

Pada soal dengan pembatasan, struktur masalah perlu dianalisis sebelum menggunakan rumus.

Untuk objek yang harus berdampingan, objek tersebut dapat dipandang sebagai **satu kelompok**.

Untuk objek yang tidak boleh berdampingan, salah satu strategi yang dapat digunakan adalah:

$$
\boxed{
\text{seluruh kemungkinan}
-
\text{kemungkinan yang tidak diinginkan}
}
$$

---

> [!important]
> Jangan menentukan permutasi hanya karena soal menggunakan kata **menyusun** atau **memilih**.
>
> Periksa terlebih dahulu:
>
> **Apakah perubahan urutan menghasilkan hasil yang berbeda?**
>
> Jika:
>
> $$
> ABC\neq BAC
> $$
>
> dalam konteks masalah tersebut, maka urutan berpengaruh dan konsep permutasi dapat digunakan.

---

## Konsep Terkait

- [[Materi Baru Kaidah Pencacahan dan Peluang/01 - Konsep Dasar Pencacahan]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/02 - Faktorial]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/04 - Kombinasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/05 - Membedakan Permutasi dan Kombinasi]]