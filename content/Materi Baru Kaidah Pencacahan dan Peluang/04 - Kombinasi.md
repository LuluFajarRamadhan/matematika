# Kombinasi

Pada materi sebelumnya, kita telah mempelajari **permutasi**, yaitu penyusunan objek dengan memperhatikan urutan.

Sekarang kita akan mempelajari situasi yang berbeda.

Misalnya, dari 5 siswa:

$$
A,\ B,\ C,\ D,\ E
$$

akan dipilih 2 siswa sebagai perwakilan kelas.

Jika yang terpilih adalah:

$$
A \text{ dan } B
$$

maka kelompok tersebut sama dengan:

$$
B \text{ dan } A
$$

karena dalam pemilihan anggota kelompok, urutan tidak menghasilkan kelompok baru.

Masalah seperti ini disebut **kombinasi**.

---

# Pengertian Kombinasi

**Kombinasi** adalah pemilihan sejumlah objek dari beberapa objek yang tersedia dengan **tidak memperhatikan urutan**.

Sebagai contoh, dari tiga siswa:

$$
A,\ B,\ C
$$

akan dipilih 2 siswa.

Kelompok yang dapat dibentuk adalah:

$$
AB,\ AC,\ BC
$$

Perhatikan bahwa:

$$
AB=BA
$$

dalam konteks pemilihan kelompok.

Artinya, pasangan $A$ dan $B$ tidak dianggap berbeda dengan pasangan $B$ dan $A$.

---

> [!important]
> Pertanyaan utama untuk mengenali kombinasi adalah:
>
> **Apakah perubahan urutan menghasilkan pilihan yang berbeda?**
>
> Jika jawabannya **tidak**, maka masalah tersebut berkaitan dengan kombinasi.

---

# Rumus Kombinasi

Banyak cara memilih $r$ objek dari $n$ objek berbeda adalah:

$$
\boxed{
{}_nC_r
=
\frac{n!}{r!(n-r)!}
}
$$

dengan:

- $n$ = banyak seluruh objek,
- $r$ = banyak objek yang dipilih.

Notasi kombinasi juga dapat ditulis:

$$
\binom{n}{r}
$$

Sehingga:

$$
{}_nC_r=\binom{n}{r}
$$

---

# Mengapa Rumus Kombinasi Dibagi dengan $r!$?

Misalkan dari 5 siswa akan dipilih 3 siswa.

Jika menggunakan permutasi:

$$
{}_5P_3
$$

maka kelompok:

$$
ABC
$$

akan dihitung berbeda dengan:

$$
ACB,\ BAC,\ BCA,\ CAB,\ CBA
$$

Padahal, dalam kombinasi, keenam susunan tersebut merupakan **kelompok yang sama**, yaitu kelompok yang terdiri atas:

$$
A,\ B,\ C
$$

Setiap kelompok yang terdiri atas 3 orang telah dihitung sebanyak:

$$
3!
$$

kali oleh permutasi.

Karena itu:

$$
{}_5C_3
=
\frac{{}_5P_3}{3!}
$$

Secara umum:

$$
{}_nC_r
=
\frac{{}_nP_r}{r!}
$$

Karena:

$$
{}_nP_r
=
\frac{n!}{(n-r)!}
$$

maka:

$$
{}_nC_r
=
\frac{n!}{r!(n-r)!}
$$

---

# Contoh 1

Dari 6 siswa akan dipilih 2 siswa sebagai perwakilan kelas.

Berapa banyak kelompok yang dapat dibentuk?

Diketahui:

$$
n=6
$$

dan:

$$
r=2
$$

Gunakan kombinasi:

$$
\begin{aligned}
{}_6C_2
&=
\frac{6!}{2!4!}\\
&=
\frac{6\times5}{2\times1}\\
&=15
\end{aligned}
$$

Jadi:

$$
\boxed{15}
$$

kelompok dapat dibentuk.

---

# Contoh 2

Dari 10 siswa akan dipilih 4 siswa untuk mengikuti lomba.

Berapa banyak kelompok yang dapat dibentuk?

Gunakan:

$$
{}_ {10}C_4
$$

Maka:

$$
\begin{aligned}
{}_{10}C_4
&=
\frac{10!}{4!6!}\\
&=
\frac{10\times9\times8\times7}
{4\times3\times2\times1}\\
&=210
\end{aligned}
$$

Jadi:

$$
\boxed{210}
$$

kelompok dapat dibentuk.

---

# Hubungan Permutasi dan Kombinasi

Permutasi dan kombinasi sama-sama digunakan untuk memilih objek.

Perbedaannya terletak pada **urutan**.

## Permutasi

Urutan diperhatikan.

Contoh:

Dari 8 siswa dipilih:

- ketua,
- sekretaris,
- bendahara.

Karena jabatannya berbeda, susunan orang yang dipilih juga berbeda.

Gunakan:

$$
{}_8P_3
$$

---

## Kombinasi

Urutan tidak diperhatikan.

Contoh:

Dari 8 siswa dipilih 3 siswa sebagai anggota tim.

Ketiga siswa memiliki kedudukan yang sama.

Gunakan:

$$
{}_8C_3
$$

---

> [!note]
> Jangan hanya melihat kata **dipilih**.
>
> Kata tersebut dapat muncul pada permutasi maupun kombinasi.
>
> Yang perlu diperiksa adalah:
>
> **Apakah posisi atau urutan orang yang dipilih menghasilkan hasil yang berbeda?**

---

# Sifat-Sifat Kombinasi

Kombinasi memiliki beberapa sifat penting.

---

## 1. Memilih Tidak Ada Objek

Dari $n$ objek, banyak cara memilih 0 objek adalah:

$$
\boxed{{}_nC_0=1}
$$

Hanya terdapat satu cara, yaitu tidak memilih apa pun.

---

## 2. Memilih Seluruh Objek

Dari $n$ objek, banyak cara memilih seluruh $n$ objek adalah:

$$
\boxed{{}_nC_n=1}
$$

Karena hanya terdapat satu kelompok yang berisi seluruh objek.

---

## 3. Sifat Simetri

Berlaku:

$$
\boxed{{}_nC_r={}_nC_{n-r}}
$$

---

## Mengapa?

Misalnya, dari 8 siswa akan dipilih 3 siswa.

Memilih 3 siswa untuk masuk kelompok secara otomatis menentukan 5 siswa yang tidak masuk kelompok.

Karena itu:

$$
{}_8C_3={}_8C_5
$$

Secara perhitungan:

$$
{}_8C_3=56
$$

dan:

$$
{}_8C_5=56
$$

---

# Kombinasi dengan Beberapa Kelompok

Dalam beberapa soal, objek berasal dari kelompok yang berbeda.

Misalnya:

- siswa laki-laki dan perempuan,
- bola merah dan biru,
- buku matematika dan fisika.

Untuk membentuk satu kelompok dengan syarat tertentu, kombinasi dari setiap kelompok dapat dikalikan.

---

## Contoh 3

Sebuah kelas terdiri atas:

- 6 siswa laki-laki,
- 5 siswa perempuan.

Akan dipilih 3 siswa yang terdiri atas:

- 2 siswa laki-laki,
- 1 siswa perempuan.

Banyak cara memilih 2 siswa laki-laki:

$$
{}_6C_2
$$

Banyak cara memilih 1 siswa perempuan:

$$
{}_5C_1
$$

Karena kedua pemilihan harus dilakukan, gunakan aturan perkalian:

$$
{}_6C_2\times{}_5C_1
$$

Maka:

$$
\begin{aligned}
n
&=15\times5\\
&=75
\end{aligned}
$$

Jadi:

$$
\boxed{75}
$$

kelompok dapat dibentuk.

---

# Kombinasi dengan Syarat Minimal

Kata-kata seperti:

- minimal,
- paling sedikit,
- paling banyak,
- sekurang-kurangnya,

sering membuat suatu masalah memiliki beberapa kemungkinan kasus.

---

## Contoh 4

Sebuah kelompok terdiri atas:

- 5 siswa laki-laki,
- 4 siswa perempuan.

Akan dipilih 3 siswa dengan syarat **minimal 2 siswa perempuan**.

Minimal 2 siswa perempuan berarti terdapat dua kemungkinan:

### Kasus 1

Dipilih:

- 2 perempuan,
- 1 laki-laki.

Banyak cara:

$$
{}_4C_2\times{}_5C_1
$$

$$
=6\times5=30
$$

### Kasus 2

Dipilih:

- 3 perempuan,
- 0 laki-laki.

Banyak cara:

$$
{}_4C_3\times{}_5C_0
$$

$$
=4\times1=4
$$

Karena kedua kasus merupakan alternatif, gunakan aturan penjumlahan:

$$
30+4=34
$$

Jadi:

$$
\boxed{34}
$$

kelompok dapat dibentuk.

---

> [!important]
> Jika sebuah syarat menghasilkan beberapa **kasus alternatif**, hitung setiap kasus secara terpisah lalu jumlahkan hasilnya.

---

# Kombinasi dengan Syarat Orang Tertentu

Pada beberapa soal, terdapat seseorang yang:

- harus dipilih,
- tidak boleh dipilih.

---

## Contoh 5

Dari 9 siswa akan dipilih 4 siswa sebagai anggota tim.

Jika Andi harus menjadi anggota tim, berapa banyak kelompok yang dapat dibentuk?

Karena Andi sudah pasti dipilih, kita hanya perlu memilih:

$$
3
$$

siswa lagi dari:

$$
8
$$

siswa lainnya.

Maka:

$$
{}_8C_3
$$

sehingga:

$$
\begin{aligned}
{}_8C_3
&=
\frac{8!}{3!5!}\\
&=56
\end{aligned}
$$

Jadi:

$$
\boxed{56}
$$

kelompok dapat dibentuk.

---

## Contoh 6

Dari 9 siswa akan dipilih 4 siswa sebagai anggota tim.

Jika Andi tidak boleh menjadi anggota tim, maka hanya tersedia:

$$
8
$$

siswa yang dapat dipilih.

Maka:

$$
{}_8C_4
$$

sehingga:

$$
\boxed{70}
$$

kelompok dapat dibentuk.

---

# Kombinasi dan Metode Komplemen

Dalam beberapa masalah, lebih mudah menghitung seluruh kemungkinan kemudian mengurangi kemungkinan yang tidak diinginkan.

---

## Contoh 7

Dari 7 siswa laki-laki dan 5 siswa perempuan akan dipilih 4 siswa.

Berapa banyak kelompok yang dapat dibentuk jika **minimal terdapat 1 siswa perempuan**?

Menghitung langsung berarti kita harus mempertimbangkan:

- 1 perempuan,
- 2 perempuan,
- 3 perempuan,
- 4 perempuan.

Cara yang lebih sederhana adalah:

$$
\text{seluruh kelompok}
-
\text{kelompok tanpa perempuan}
$$

Jumlah seluruh siswa:

$$
7+5=12
$$

Banyak seluruh kelompok:

$$
{}_{12}C_4
$$

Kelompok tanpa perempuan berarti seluruh anggotanya laki-laki:

$$
{}_7C_4
$$

Maka:

$$
\begin{aligned}
n
&={}_{12}C_4-{}_7C_4\\
&=495-35\\
&=460
\end{aligned}
$$

Jadi:

$$
\boxed{460}
$$

kelompok dapat dibentuk.

---

> [!note]
> Untuk syarat seperti **minimal satu**, sering kali metode:
>
> $$
> \boxed{
> \text{seluruh kemungkinan}
> -
> \text{tidak ada sama sekali}
> }
> $$
>
> lebih efisien.

Konsep ini nantinya juga sangat berguna pada materi **peluang komplemen**.

---

# Kombinasi dalam Masalah Geometri

Konsep kombinasi tidak hanya digunakan untuk memilih orang.

Kombinasi juga dapat digunakan ketika suatu objek terbentuk dengan memilih beberapa unsur.

---

## Contoh 8

Terdapat 8 titik berbeda dan tidak ada 3 titik yang segaris.

Berapa banyak garis yang dapat dibuat melalui dua titik tersebut?

Sebuah garis ditentukan oleh:

$$
2
$$

titik.

Karena urutan kedua titik tidak berpengaruh:

$$
AB=BA
$$

maka digunakan kombinasi:

$$
{}_8C_2
$$

Maka:

$$
\begin{aligned}
{}_8C_2
&=
\frac{8\times7}{2}\\
&=28
\end{aligned}
$$

Jadi:

$$
\boxed{28}
$$

garis dapat dibuat.

---

# Strategi Menyelesaikan Masalah Kombinasi

Gunakan langkah berikut sebelum melakukan perhitungan.

### Langkah 1

Tentukan apa yang sedang dipilih.

### Langkah 2

Tanyakan:

> Apakah perubahan urutan menghasilkan pilihan yang berbeda?

Jika **tidak**, gunakan kombinasi.

### Langkah 3

Tentukan:

$$
n
$$

yaitu banyak seluruh objek.

### Langkah 4

Tentukan:

$$
r
$$

yaitu banyak objek yang dipilih.

### Langkah 5

Periksa syarat seperti:

- harus dipilih,
- tidak boleh dipilih,
- tepat,
- minimal,
- maksimal.

### Langkah 6

Jika terdapat beberapa kasus, hitung setiap kasus secara terpisah.

---

# Soal Latihan

## Soal 1

Dari 7 siswa akan dipilih 2 siswa sebagai perwakilan kelas.

Berapa banyak kelompok yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Urutan tidak diperhatikan karena kedua siswa memiliki kedudukan yang sama.
>
> Gunakan kombinasi:
>
> $$
> \begin{aligned}
> {}_7C_2
> &=
> \frac{7!}{2!5!}\\
> &=
> \frac{7\times6}{2}\\
> &=21
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{21}
> $$
>
> kelompok dapat dibentuk.

---

## Soal 2

Dari 10 pemain basket akan dipilih 5 pemain untuk bermain di lapangan.

Berapa banyak susunan tim yang dapat dipilih?

> [!success]- Klik untuk Lihat Jawaban
> Kita hanya memilih siapa yang menjadi anggota tim.
>
> Urutan pemain tidak diperhatikan.
>
> Maka:
>
> $$
> \begin{aligned}
> {}_{10}C_5
> &=
> \frac{10!}{5!5!}\\
> &=252
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{252}
> $$
>
> kelompok pemain dapat dipilih.

---

## Soal 3

Dalam sebuah kelas terdapat:

- 8 siswa laki-laki,
- 6 siswa perempuan.

Akan dipilih 4 siswa yang terdiri atas tepat:

- 2 siswa laki-laki,
- 2 siswa perempuan.

Berapa banyak kelompok yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Pilih 2 siswa laki-laki:
>
> $$
> {}_8C_2=28
> $$
>
> Pilih 2 siswa perempuan:
>
> $$
> {}_6C_2=15
> $$
>
> Kedua proses harus dilakukan, sehingga:
>
> $$
> \begin{aligned}
> n
> &=28\times15\\
> &=420
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{420}
> $$
>
> kelompok dapat dibentuk.

---

## Soal 4

Dari 9 siswa akan dipilih 4 siswa sebagai anggota tim.

Jika Andi harus terpilih, berapa banyak kelompok yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Andi sudah pasti menjadi anggota.
>
> Berarti masih diperlukan:
>
> $$
> 3
> $$
>
> siswa dari 8 siswa lainnya.
>
> Maka:
>
> $$
> \begin{aligned}
> n
> &={}_8C_3\\
> &=56
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{56}
> $$
>
> kelompok dapat dibentuk.

---

## Soal 5

Dari 10 siswa akan dipilih 4 siswa sebagai anggota tim.

Andi dan Budi **tidak boleh terpilih secara bersamaan**.

Berapa banyak kelompok yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Gunakan:
>
> $$
> \text{seluruh kelompok}
> -
> \text{kelompok yang memuat Andi dan Budi}
> $$
>
> ### Langkah 1: Seluruh Kelompok
>
> $$
> {}_{10}C_4=210
> $$
>
> ### Langkah 2: Andi dan Budi Terpilih Bersamaan
>
> Andi dan Budi sudah dipilih.
>
> Masih perlu dipilih:
>
> $$
> 2
> $$
>
> siswa dari 8 siswa lainnya.
>
> Maka:
>
> $$
> {}_8C_2=28
> $$
>
> ### Langkah 3: Mengurangi
>
> $$
> \begin{aligned}
> n
> &=210-28\\
> &=182
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{182}
> $$
>
> kelompok dapat dibentuk.

---

## Soal 6

Sebuah kelas terdiri atas:

- 6 siswa laki-laki,
- 5 siswa perempuan.

Akan dipilih 4 siswa dengan syarat **minimal 2 siswa perempuan**.

Berapa banyak kelompok yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Minimal 2 siswa perempuan menghasilkan tiga kasus.
>
> ### Kasus 1: 2 Perempuan dan 2 Laki-Laki
>
> $$
> {}_5C_2\times{}_6C_2
> $$
>
> $$
> =10\times15=150
> $$
>
> ### Kasus 2: 3 Perempuan dan 1 Laki-Laki
>
> $$
> {}_5C_3\times{}_6C_1
> $$
>
> $$
> =10\times6=60
> $$
>
> ### Kasus 3: 4 Perempuan
>
> $$
> {}_5C_4\times{}_6C_0
> $$
>
> $$
> =5\times1=5
> $$
>
> Jumlah:
>
> $$
> \begin{aligned}
> n
> &=150+60+5\\
> &=215
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{215}
> $$
>
> kelompok dapat dibentuk.

---

## Soal 7

Terdapat 10 titik berbeda dan tidak ada tiga titik yang segaris.

Berapa banyak segitiga yang dapat dibentuk dengan menggunakan titik-titik tersebut sebagai titik sudut?

> [!success]- Klik untuk Lihat Jawaban
> Sebuah segitiga ditentukan oleh:
>
> $$
> 3
> $$
>
> titik.
>
> Karena tidak ada tiga titik yang segaris, setiap pemilihan 3 titik akan menghasilkan sebuah segitiga.
>
> Urutan titik tidak diperhatikan.
>
> Maka:
>
> $$
> \begin{aligned}
> n
> &={}_{10}C_3\\
> &=
> \frac{10\times9\times8}{3\times2\times1}\\
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
> segitiga dapat dibentuk.

---

## Soal 8

Sebuah kelompok terdiri atas:

- 7 siswa laki-laki,
- 5 siswa perempuan.

Akan dipilih 5 siswa sebagai perwakilan.

Tentukan banyak kelompok yang dapat dibentuk jika terdapat **minimal 1 siswa perempuan dan minimal 1 siswa laki-laki**.

> [!success]- Klik untuk Lihat Jawaban
> Kita dapat menghitung menggunakan metode komplemen.
>
> ### Langkah 1: Menghitung Seluruh Kelompok
>
> Jumlah seluruh siswa:
>
> $$
> 7+5=12
> $$
>
> Maka:
>
> $$
> {}_{12}C_5=792
> $$
>
> ### Langkah 2: Mengurangi Kelompok yang Seluruhnya Laki-Laki
>
> $$
> {}_7C_5=21
> $$
>
> ### Langkah 3: Mengurangi Kelompok yang Seluruhnya Perempuan
>
> Karena terdapat tepat 5 siswa perempuan:
>
> $$
> {}_5C_5=1
> $$
>
> ### Langkah 4: Menghitung Kelompok yang Memenuhi Syarat
>
> $$
> \begin{aligned}
> n
> &=792-21-1\\
> &=770
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{770}
> $$
>
> kelompok dapat dibentuk.

---

# Rangkuman

Kombinasi digunakan ketika kita memilih sejumlah objek dengan **tidak memperhatikan urutan**.

Rumus kombinasi:

$$
\boxed{
{}_nC_r=
\frac{n!}{r!(n-r)!}
}
$$

Hubungan kombinasi dan permutasi:

$$
\boxed{
{}_nC_r=
\frac{{}_nP_r}{r!}
}
$$

Sifat penting kombinasi:

$$
{}_nC_0=1
$$

$$
{}_nC_n=1
$$

dan:

$$
{}_nC_r={}_nC_{n-r}
$$

Jika pemilihan melibatkan beberapa kelompok, kombinasi dari masing-masing kelompok dapat dikalikan.

Jika syarat menghasilkan beberapa kasus yang berbeda, jumlahkan hasil setiap kasus.

Untuk syarat seperti **minimal satu**, metode komplemen sering lebih efisien:

$$
\boxed{
\text{seluruh kemungkinan}
-
\text{kemungkinan tanpa objek yang dimaksud}
}
$$

---

> [!important]
> Perbedaan utama permutasi dan kombinasi dapat diringkas sebagai:
>
> **Permutasi**
>
> $$
> AB\neq BA
> $$
>
> karena urutan berpengaruh.
>
> **Kombinasi**
>
> $$
> AB=BA
> $$
>
> karena urutan tidak berpengaruh.
>
> Jangan menghafal rumus terlebih dahulu. Tentukan dahulu apakah perubahan urutan menghasilkan hasil yang berbeda.

---

## Konsep Terkait

- [[Materi Baru Kaidah Pencacahan dan Peluang/02 - Faktorial]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/03 - Permutasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/05 - Membedakan Permutasi dan Kombinasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/06 - Konsep Dasar Peluang]]