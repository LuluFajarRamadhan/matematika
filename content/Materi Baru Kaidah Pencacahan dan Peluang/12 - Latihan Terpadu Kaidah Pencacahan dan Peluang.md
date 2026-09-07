# Latihan Terpadu Kaidah Pencacahan dan Peluang

Pada bagian ini, seluruh konsep yang telah dipelajari akan digunakan secara terpadu.

Materi yang dapat muncul antara lain:

- aturan penjumlahan,
- aturan perkalian,
- faktorial,
- permutasi,
- kombinasi,
- peluang kejadian,
- peluang komplemen,
- kejadian majemuk,
- peluang bersyarat,
- kejadian saling bebas,
- penerapan pencacahan dalam peluang.

Pada setiap soal, tentukan terlebih dahulu **struktur masalahnya** sebelum memilih metode penyelesaian.

---

> [!important]
> Jangan langsung mencari rumus.
>
> Biasakan bertanya:
>
> 1. Apa yang diketahui?
> 2. Apa yang ditanyakan?
> 3. Apakah urutan berpengaruh?
> 4. Apakah terdapat beberapa tahap?
> 5. Apakah terdapat syarat tertentu?
> 6. Apakah lebih mudah menggunakan komplemen?
> 7. Apakah kejadian saling bebas atau bergantung?
> 8. Bagaimana menentukan $n(S)$ dan $n(A)$?

---

# Soal Latihan

## Soal 1

Dari angka:

$$
1,2,3,4,5,6
$$

akan dibentuk bilangan tiga digit tanpa pengulangan angka.

Berapa banyak bilangan yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Terdapat tiga posisi.
>
> Digit pertama:
>
> $$
> 6
> $$
>
> pilihan.
>
> Digit kedua:
>
> $$
> 5
> $$
>
> pilihan.
>
> Digit ketiga:
>
> $$
> 4
> $$
>
> pilihan.
>
> Gunakan aturan perkalian:
>
> $$
> \begin{aligned}
> n
> &=6\times5\times4\\
> &=120
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{120}
> $$

---

## Soal 2

Dari 9 siswa akan dipilih:

- seorang ketua,
- seorang wakil ketua,
- seorang sekretaris.

Berapa banyak susunan pengurus yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Ketiga jabatan berbeda, sehingga urutan atau posisi berpengaruh.
>
> Gunakan permutasi:
>
> $$
> \begin{aligned}
> {}_9P_3
> &=
> 9\times8\times7\\
> &=504
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{504}
> $$

---

## Soal 3

Dalam sebuah kelas terdapat:

- 8 siswa laki-laki,
- 7 siswa perempuan.

Dipilih 4 siswa sebagai perwakilan kelas.

Berapa banyak kelompok yang terdiri atas tepat 2 siswa laki-laki dan 2 siswa perempuan?

> [!success]- Klik untuk Lihat Jawaban
> Urutan anggota kelompok tidak berpengaruh.
>
> Pilih 2 siswa laki-laki:
>
> $$
> {}_8C_2=28
> $$
>
> Pilih 2 siswa perempuan:
>
> $$
> {}_7C_2=21
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> n
> &=28\times21\\
> &=588
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{588}
> $$

---

## Soal 4

Tujuh siswa berdiri secara acak dalam satu baris.

Tentukan peluang Andi berada pada salah satu ujung barisan.

> [!success]- Klik untuk Lihat Jawaban
> Banyak seluruh susunan:
>
> $$
> n(S)=7!
> $$
>
> Andi dapat berada pada:
>
> - ujung kiri,
> - ujung kanan.
>
> Terdapat:
>
> $$
> 2
> $$
>
> pilihan posisi untuk Andi.
>
> Enam siswa lainnya dapat disusun:
>
> $$
> 6!
> $$
>
> cara.
>
> Maka:
>
> $$
> n(A)=2\times6!
> $$
>
> Peluang:
>
> $$
> \begin{aligned}
> P(A)
> &=
> \frac{2\times6!}{7!}\\
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

## Soal 5

Sebuah kotak berisi:

- 6 bola merah,
- 5 bola biru,
- 4 bola hijau.

Diambil 3 bola sekaligus secara acak.

Tentukan peluang ketiga bola yang terambil memiliki warna yang sama.

> [!success]- Klik untuk Lihat Jawaban
> Jumlah seluruh bola:
>
> $$
> 15
> $$
>
> Banyak seluruh cara mengambil 3 bola:
>
> $$
> n(S)={}_{15}C_3
> $$
>
> $$
> n(S)=455
> $$
>
> Agar ketiga bola berwarna sama, terdapat tiga kasus.
>
> ### Kasus 1: Semua Merah
>
> $$
> {}_6C_3=20
> $$
>
> ### Kasus 2: Semua Biru
>
> $$
> {}_5C_3=10
> $$
>
> ### Kasus 3: Semua Hijau
>
> $$
> {}_4C_3=4
> $$
>
> Maka:
>
> $$
> n(A)=20+10+4=34
> $$
>
> Peluang:
>
> $$
> P(A)=\frac{34}{455}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{34}{455}}
> $$

---

## Soal 6

Sebuah dadu dilempar 4 kali.

Tentukan peluang muncul angka 6 minimal satu kali.

> [!success]- Klik untuk Lihat Jawaban
> Lebih mudah menggunakan komplemen.
>
> Komplemen dari minimal satu angka 6 adalah:
>
> > tidak muncul angka 6 sama sekali.
>
> Pada satu kali pelemparan:
>
> $$
> P(\text{bukan }6)=\frac56
> $$
>
> Karena setiap pelemparan saling bebas:
>
> $$
> P(\text{tidak ada }6)
> =
> \left(\frac56\right)^4
> =
> \frac{625}{1296}
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(\text{minimal satu }6)
> &=
> 1-\frac{625}{1296}\\
> &=
> \frac{671}{1296}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{671}{1296}}
> $$

---

## Soal 7

Dua buah dadu dilempar secara bersamaan.

Misalkan:

$$
A=\text{jumlah kedua mata dadu sama dengan 8}
$$

dan:

$$
B=\text{minimal salah satu dadu menunjukkan angka 5}
$$

Tentukan:

$$
P(A\cup B)
$$

> [!success]- Klik untuk Lihat Jawaban
> Banyak seluruh hasil:
>
> $$
> n(S)=36
> $$
>
> ### Kejadian A
>
> Pasangan dengan jumlah 8:
>
> $$
> (2,6),(3,5),(4,4),(5,3),(6,2)
> $$
>
> sehingga:
>
> $$
> n(A)=5
> $$
>
> ### Kejadian B
>
> Minimal salah satu dadu menunjukkan angka 5:
>
> $$
> (5,1),(5,2),(5,3),(5,4),(5,5),(5,6)
> $$
>
> dan:
>
> $$
> (1,5),(2,5),(3,5),(4,5),(6,5)
> $$
>
> sehingga:
>
> $$
> n(B)=11
> $$
>
> ### Irisan
>
> Pasangan yang memenuhi $A$ dan $B$:
>
> $$
> (3,5),(5,3)
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
> n(A\cup B)
> &=5+11-2\\
> &=14
> \end{aligned}
> $$
>
> Peluang:
>
> $$
> \begin{aligned}
> P(A\cup B)
> &=
> \frac{14}{36}\\
> &=
> \frac7{18}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac7{18}}
> $$

---

## Soal 8

Dalam sebuah kelas terdapat 40 siswa.

Sebanyak:

- 24 siswa menyukai Matematika,
- 20 siswa menyukai Fisika,
- 12 siswa menyukai keduanya.

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
> Ditanyakan:
>
> $$
> P(M\mid F)
> $$
>
> Gunakan:
>
> $$
> P(M\mid F)
> =
> \frac{n(M\cap F)}{n(F)}
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(M\mid F)
> &=
> \frac{12}{20}\\
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

## Soal 9

Sebuah kotak berisi:

- 7 bola merah,
- 5 bola biru.

Dua bola diambil satu per satu tanpa pengembalian.

Tentukan peluang bola pertama merah dan bola kedua biru.

> [!success]- Klik untuk Lihat Jawaban
> Peluang bola pertama merah:
>
> $$
> P(M_1)=\frac7{12}
> $$
>
> Jika bola pertama merah telah diambil, tersisa:
>
> - 6 bola merah,
> - 5 bola biru,
> - total 11 bola.
>
> Maka:
>
> $$
> P(B_2\mid M_1)=\frac5{11}
> $$
>
> Sehingga:
>
> $$
> \begin{aligned}
> P(M_1\cap B_2)
> &=
> \frac7{12}\times\frac5{11}\\
> &=
> \frac{35}{132}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{35}{132}}
> $$

---

## Soal 10

Huruf-huruf pada kata:

$$
PELUANG
$$

disusun secara acak.

Tentukan peluang huruf $P$ dan $G$ **tidak berdampingan**.

> [!success]- Klik untuk Lihat Jawaban
> Kata **PELUANG** terdiri atas 7 huruf berbeda.
>
> Banyak seluruh susunan:
>
> $$
> n(S)=7!
> $$
>
> Lebih mudah menggunakan komplemen.
>
> ### Susunan P dan G Berdampingan
>
> Anggap $P$ dan $G$ sebagai satu kelompok.
>
> Maka terdapat:
>
> $$
> 6
> $$
>
> objek.
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
> Peluang berdampingan:
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
> Maka peluang tidak berdampingan:
>
> $$
> \begin{aligned}
> P(A^c)
> &=1-\frac27\\
> &=\frac57
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac57}
> $$

---

## Soal 11

Sebuah kelas terdiri atas:

- 8 siswa laki-laki,
- 6 siswa perempuan.

Dipilih 5 siswa secara acak.

Tentukan peluang kelompok yang terpilih memiliki **tepat 3 siswa perempuan**, jika diketahui bahwa kelompok tersebut memiliki minimal 1 siswa perempuan.

> [!success]- Klik untuk Lihat Jawaban
> Misalkan:
>
> $$
> A=\text{tepat 3 perempuan}
> $$
>
> dan:
>
> $$
> B=\text{minimal 1 perempuan}
> $$
>
> Ditanyakan:
>
> $$
> P(A\mid B)
> $$
>
> ### Langkah 1: Menghitung $n(B)$
>
> Banyak seluruh kelompok:
>
> $$
> {}_{14}C_5
> =
> 2002
> $$
>
> Kelompok tanpa perempuan berarti seluruhnya laki-laki:
>
> $$
> {}_8C_5
> =
> 56
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> n(B)
> &=2002-56\\
> &=1946
> \end{aligned}
> $$
>
> ### Langkah 2: Menghitung $n(A\cap B)$
>
> Tepat 3 perempuan berarti:
>
> - pilih 3 dari 6 perempuan,
> - pilih 2 dari 8 laki-laki.
>
> Maka:
>
> $$
> \begin{aligned}
> n(A\cap B)
> &=
> {}_6C_3\times{}_8C_2\\
> &=20\times28\\
> &=560
> \end{aligned}
> $$
>
> ### Langkah 3: Peluang Bersyarat
>
> $$
> \begin{aligned}
> P(A\mid B)
> &=
> \frac{560}{1946}\\
> &=
> \frac{280}{973}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{280}{973}}
> $$

---

## Soal 12

Dari angka:

$$
0,1,2,3,4,5,6
$$

dibentuk secara acak sebuah bilangan 4 digit tanpa pengulangan angka.

Tentukan peluang bilangan yang terbentuk merupakan **bilangan genap lebih dari 3000**.

> [!success]- Klik untuk Lihat Jawaban
> Soal ini membutuhkan analisis pada ruang sampel dan kejadian.
>
> ### Langkah 1: Menentukan Banyak Ruang Sampel
>
> Bilangan harus terdiri atas 4 digit, sehingga digit pertama tidak boleh 0.
>
> Digit pertama:
>
> $$
> 6
> $$
>
> pilihan.
>
> Digit kedua:
>
> $$
> 6
> $$
>
> pilihan.
>
> Digit ketiga:
>
> $$
> 5
> $$
>
> pilihan.
>
> Digit keempat:
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
> \begin{aligned}
> n(S)
> &=6\times6\times5\times4\\
> &=720
> \end{aligned}
> $$
>
> ### Langkah 2: Menentukan Bilangan yang Memenuhi
>
> Bilangan harus:
>
> - lebih dari 3000,
> - genap.
>
> Digit pertama harus:
>
> $$
> 3,4,5,\text{ atau }6
> $$
>
> Kita bagi berdasarkan digit pertama.
>
> ### Kasus 1: Digit Pertama Ganjil
>
> Digit pertama dapat:
>
> $$
> 3 \text{ atau }5
> $$
>
> sehingga terdapat:
>
> $$
> 2
> $$
>
> pilihan.
>
> Karena digit pertama ganjil, seluruh digit genap:
>
> $$
> 0,2,4,6
> $$
>
> masih tersedia untuk digit terakhir.
>
> Maka digit terakhir mempunyai:
>
> $$
> 4
> $$
>
> pilihan.
>
> Setelah digit pertama dan terakhir dipilih, digit kedua memiliki:
>
> $$
> 5
> $$
>
> pilihan.
>
> Digit ketiga:
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
> n_1=2\times4\times5\times4=160
> $$
>
> ### Kasus 2: Digit Pertama Genap
>
> Digit pertama dapat:
>
> $$
> 4 \text{ atau }6
> $$
>
> sehingga terdapat:
>
> $$
> 2
> $$
>
> pilihan.
>
> Karena satu digit genap telah digunakan, digit genap yang tersisa untuk digit terakhir adalah:
>
> $$
> 3
> $$
>
> pilihan.
>
> Digit kedua:
>
> $$
> 5
> $$
>
> pilihan.
>
> Digit ketiga:
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
> n_2=2\times3\times5\times4=120
> $$
>
> ### Langkah 3: Menentukan Banyak Kejadian
>
> $$
> \begin{aligned}
> n(A)
> &=160+120\\
> &=280
> \end{aligned}
> $$
>
> ### Langkah 4: Menghitung Peluang
>
> $$
> \begin{aligned}
> P(A)
> &=
> \frac{280}{720}\\
> &=
> \frac7{18}
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac7{18}}
> $$

---

# Refleksi Akhir

Setelah menyelesaikan soal-soal di atas, periksa kembali kemampuanmu.

### 1. Kaidah Pencacahan

Apakah kamu dapat membedakan kapan harus menggunakan:

- aturan penjumlahan,
- aturan perkalian?

### 2. Permutasi dan Kombinasi

Apakah kamu dapat menentukan apakah urutan berpengaruh?

$$
\boxed{
\text{Urutan penting}
\rightarrow
\text{Permutasi}
}
$$

$$
\boxed{
\text{Urutan tidak penting}
\rightarrow
\text{Kombinasi}
}
$$

### 3. Peluang

Apakah kamu dapat menentukan:

$$
n(S)
$$

dan:

$$
n(A)
$$

sebelum menggunakan:

$$
P(A)=\frac{n(A)}{n(S)}
$$

### 4. Komplemen

Apakah kamu dapat mengenali ketika:

$$
P(A)=1-P(A^c)
$$

lebih efisien digunakan?

### 5. Kejadian Majemuk

Apakah kamu dapat membedakan:

$$
A\cup B
$$

dengan:

$$
A\cap B
$$

### 6. Peluang Bersyarat

Apakah kamu memahami bahwa:

$$
P(A\mid B)
$$

berarti ruang kemungkinan telah dibatasi oleh kejadian $B$?

### 7. Kejadian Saling Bebas

Apakah kamu dapat memeriksa apakah:

$$
P(A\cap B)
=
P(A)\cdot P(B)
$$

berlaku?

---

# Strategi Umum Menyelesaikan Soal

Ketika menemui soal baru, gunakan alur berikut.

```text
Baca syarat soal
      │
      ▼
Apa yang ingin dihitung?
      │
      ▼
Apakah masalah pencacahan atau peluang?
      │
      ▼
Apakah urutan berpengaruh?
      │
      ▼
Tentukan seluruh kemungkinan
      │
      ▼
Tentukan kemungkinan yang memenuhi syarat
      │
      ▼
Periksa apakah ada strategi yang lebih efisien
      │
      ▼
Lakukan perhitungan
      │
      ▼
Periksa kembali hasil
```

---

# Rangkuman Akhir Bab

## Kaidah Penjumlahan

Digunakan untuk beberapa alternatif:

$$
n=n_1+n_2+\cdots+n_k
$$

---

## Kaidah Perkalian

Digunakan untuk beberapa tahap:

$$
n=n_1\times n_2\times\cdots\times n_k
$$

---

## Faktorial

$$
n!=n(n-1)(n-2)\cdots2\cdot1
$$

---

## Permutasi

Jika urutan diperhatikan:

$$
{}_nP_r
=
\frac{n!}{(n-r)!}
$$

---

## Kombinasi

Jika urutan tidak diperhatikan:

$$
{}_nC_r
=
\frac{n!}{r!(n-r)!}
$$

---

## Peluang

$$
P(A)=\frac{n(A)}{n(S)}
$$

---

## Komplemen

$$
P(A^c)=1-P(A)
$$

---

## Gabungan

$$
P(A\cup B)
=
P(A)+P(B)-P(A\cap B)
$$

---

## Peluang Bersyarat

$$
P(A\mid B)
=
\frac{P(A\cap B)}{P(B)}
$$

---

## Kejadian Saling Bebas

$$
P(A\cap B)
=
P(A)\cdot P(B)
$$

---

> [!important]
> Inti dari kaidah pencacahan dan peluang bukan menghafal sebanyak mungkin rumus.
>
> Kemampuan yang paling penting adalah **mengenali struktur masalah**.
>
> Biasakan menentukan:
>
> $$
> \boxed{\text{apa yang mungkin terjadi}}
> $$
>
> kemudian:
>
> $$
> \boxed{\text{apa yang memenuhi syarat}}
> $$
>
> dan akhirnya memilih metode yang paling efisien untuk menghitungnya.

---

## Konsep Terkait

- [[Materi Baru Kaidah Pencacahan dan Peluang/00 - Peta Konsep Kaidah Pencacahan dan Teori Peluang]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/01 - Konsep Dasar Pencacahan]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/02 - Faktorial]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/03 - Permutasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/04 - Kombinasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/05 - Membedakan Permutasi dan Kombinasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/06 - Konsep Dasar Peluang]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/07 - Peluang Komplemen]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/08 - Peluang Kejadian Majemuk]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/09 - Peluang Bersyarat]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/10 - Kejadian Saling Bebas]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/11 - Penerapan Kaidah Pencacahan dalam Peluang]]