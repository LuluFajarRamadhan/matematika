# Peluang Kejadian Majemuk

Pada materi sebelumnya, kita telah mempelajari peluang suatu kejadian tunggal dan peluang komplemen.

Sekarang kita akan mempelajari situasi ketika terdapat **dua kejadian atau lebih** yang dianalisis secara bersamaan.

Kejadian seperti ini disebut **kejadian majemuk**.

Contohnya:

- muncul bilangan genap **atau** bilangan prima,
- terpilih siswa laki-laki **atau** siswa perempuan,
- muncul gambar pada koin **dan** bilangan genap pada dadu.

Untuk memahami kejadian majemuk, kita perlu mengenal dua konsep utama:

1. **gabungan kejadian**,
2. **irisan kejadian**.

---

# Gabungan Dua Kejadian

Gabungan kejadian $A$ dan $B$ adalah kejadian ketika:

- $A$ terjadi,
- atau $B$ terjadi,
- atau keduanya terjadi.

Gabungan $A$ dan $B$ ditulis:

$$
\boxed{A\cup B}
$$

Simbol:

$$
\cup
$$

dibaca **gabungan**.

---

## Contoh 1

Sebuah dadu dilempar satu kali.

Misalkan:

$$
A=\text{kejadian muncul bilangan genap}
$$

maka:

$$
A=\{2,4,6\}
$$

dan:

$$
B=\text{kejadian muncul bilangan prima}
$$

maka:

$$
B=\{2,3,5\}
$$

Gabungan kedua kejadian adalah:

$$
A\cup B
=
\{2,3,4,5,6\}
$$

Perhatikan bahwa angka 2 hanya ditulis satu kali meskipun termasuk dalam $A$ dan $B$.

---

# Irisan Dua Kejadian

Irisan kejadian $A$ dan $B$ adalah kejadian ketika **A dan B terjadi secara bersamaan**.

Irisan ditulis:

$$
\boxed{A\cap B}
$$

Simbol:

$$
\cap
$$

dibaca **irisan**.

---

## Contoh 2

Gunakan contoh sebelumnya:

$$
A=\{2,4,6\}
$$

dan:

$$
B=\{2,3,5\}
$$

Anggota yang terdapat pada kedua kejadian adalah:

$$
2
$$

Maka:

$$
A\cap B=\{2\}
$$

---

> [!important]
> Secara sederhana:
>
> $$
> A\cup B
> $$
>
> berarti **A atau B**.
>
> Sedangkan:
>
> $$
> A\cap B
> $$
>
> berarti **A dan B**.

---

# Peluang Gabungan Dua Kejadian

Untuk dua kejadian $A$ dan $B$, berlaku:

$$
\boxed{
P(A\cup B)
=
P(A)+P(B)-P(A\cap B)
}
$$

Mengapa dikurangi:

$$
P(A\cap B)
$$

Karena jika kita hanya menjumlahkan:

$$
P(A)+P(B)
$$

maka bagian yang termasuk dalam $A$ dan $B$ akan dihitung dua kali.

---

## Contoh 3

Sebuah dadu dilempar satu kali.

Misalkan:

$$
A=\text{muncul bilangan genap}
$$

dan:

$$
B=\text{muncul bilangan prima}
$$

Diketahui:

$$
A=\{2,4,6\}
$$

sehingga:

$$
P(A)=\frac36=\frac12
$$

Sedangkan:

$$
B=\{2,3,5\}
$$

sehingga:

$$
P(B)=\frac36=\frac12
$$

Irisannya:

$$
A\cap B=\{2\}
$$

sehingga:

$$
P(A\cap B)=\frac16
$$

Maka:

$$
\begin{aligned}
P(A\cup B)
&=
P(A)+P(B)-P(A\cap B)\\
&=
\frac12+\frac12-\frac16\\
&=
1-\frac16\\
&=
\frac56
\end{aligned}
$$

Jadi:

$$
\boxed{\frac56}
$$

---

# Kejadian Saling Lepas

Dua kejadian disebut **saling lepas** jika kedua kejadian tidak dapat terjadi secara bersamaan.

Artinya:

$$
A\cap B=\varnothing
$$

sehingga:

$$
P(A\cap B)=0
$$

Untuk dua kejadian saling lepas:

$$
\boxed{
P(A\cup B)=P(A)+P(B)
}
$$

---

## Contoh 4

Sebuah dadu dilempar satu kali.

Misalkan:

$$
A=\text{muncul angka 1}
$$

dan:

$$
B=\text{muncul angka 6}
$$

Dalam satu kali pelemparan, angka 1 dan angka 6 tidak mungkin muncul bersamaan.

Maka:

$$
A\cap B=\varnothing
$$

sehingga $A$ dan $B$ merupakan kejadian saling lepas.

Peluang muncul angka 1 atau 6:

$$
\begin{aligned}
P(A\cup B)
&=
P(A)+P(B)\\
&=
\frac16+\frac16\\
&=
\frac13
\end{aligned}
$$

Jadi:

$$
\boxed{\frac13}
$$

---

# Kejadian Tidak Saling Lepas

Dua kejadian disebut **tidak saling lepas** jika kedua kejadian dapat terjadi secara bersamaan.

Artinya:

$$
A\cap B\neq\varnothing
$$

Maka rumus yang digunakan:

$$
\boxed{
P(A\cup B)
=
P(A)+P(B)-P(A\cap B)
}
$$

---

## Contoh 5

Sebuah dadu dilempar satu kali.

Misalkan:

$$
A=\text{muncul bilangan genap}
$$

dan:

$$
B=\text{muncul bilangan lebih besar dari 3}
$$

Maka:

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

Karena:

$$
A\cap B\neq\varnothing
$$

maka $A$ dan $B$ tidak saling lepas.

---

# Membandingkan Saling Lepas dan Tidak Saling Lepas

## Saling Lepas

Tidak ada hasil yang sama.

$$
A\cap B=\varnothing
$$

Sehingga:

$$
P(A\cap B)=0
$$

dan:

$$
\boxed{
P(A\cup B)=P(A)+P(B)
}
$$

---

## Tidak Saling Lepas

Ada hasil yang termasuk dalam kedua kejadian.

$$
A\cap B\neq\varnothing
$$

Sehingga:

$$
\boxed{
P(A\cup B)
=
P(A)+P(B)-P(A\cap B)
}
$$

---

> [!note]
> Jangan langsung menggunakan:
>
> $$
> P(A\cup B)=P(A)+P(B)
> $$
>
> sebelum memeriksa apakah $A$ dan $B$ dapat terjadi secara bersamaan.

---

# Diagram Venn

Hubungan dua kejadian dapat digambarkan menggunakan diagram Venn.

Untuk dua kejadian yang tidak saling lepas:

```text
        _______       _______
       /       \_____/       \
      /    A    \   /    B    \
     |           \_/           |
      \         A∩B           /
       \_______/   \_________/
```

Bagian tengah menunjukkan:

$$
A\cap B
$$

Sedangkan seluruh daerah yang berada di dalam lingkaran $A$ atau $B$ merupakan:

$$
A\cup B
$$

---

# Menentukan Peluang dari Banyak Anggota Himpunan

Jika setiap titik sampel mempunyai peluang yang sama, maka:

$$
P(A)=\frac{n(A)}{n(S)}
$$

Untuk gabungan dua kejadian:

$$
n(A\cup B)
=
n(A)+n(B)-n(A\cap B)
$$

Sehingga:

$$
P(A\cup B)
=
\frac{n(A\cup B)}{n(S)}
$$

---

## Contoh 6

Dalam sebuah kelas terdapat 40 siswa.

Sebanyak:

- 22 siswa menyukai Matematika,
- 18 siswa menyukai Fisika,
- 8 siswa menyukai keduanya.

Jika dipilih satu siswa secara acak, tentukan peluang siswa tersebut menyukai Matematika atau Fisika.

Gunakan:

$$
n(M\cup F)
=
n(M)+n(F)-n(M\cap F)
$$

Maka:

$$
\begin{aligned}
n(M\cup F)
&=
22+18-8\\
&=
32
\end{aligned}
$$

Peluangnya:

$$
\begin{aligned}
P(M\cup F)
&=
\frac{32}{40}\\
&=
\frac45
\end{aligned}
$$

Jadi:

$$
\boxed{\frac45}
$$

---

# Peluang "Hanya A"

Selain gabungan dan irisan, terkadang soal menanyakan kejadian:

> hanya $A$

Artinya, $A$ terjadi tetapi $B$ tidak terjadi.

Banyak anggota hanya $A$:

$$
\boxed{
n(A\text{ saja})
=
n(A)-n(A\cap B)
}
$$

---

## Contoh 7

Dari 40 siswa:

- 22 menyukai Matematika,
- 18 menyukai Fisika,
- 8 menyukai keduanya.

Banyak siswa yang hanya menyukai Matematika:

$$
\begin{aligned}
n(M\text{ saja})
&=
22-8\\
&=
14
\end{aligned}
$$

Maka peluang siswa yang dipilih hanya menyukai Matematika:

$$
P(M\text{ saja})
=
\frac{14}{40}
=
\frac7{20}
$$

---

# Peluang Tidak Mengalami Keduanya

Jika ingin menentukan kejadian yang tidak termasuk dalam $A$ maupun $B$, maka gunakan komplemen dari:

$$
A\cup B
$$

Sehingga:

$$
\boxed{
P((A\cup B)^c)
=
1-P(A\cup B)
}
$$

---

## Contoh 8

Dalam sebuah kelompok:

$$
P(A\cup B)=\frac34
$$

Tentukan peluang tidak terjadi $A$ maupun $B$.

Maka:

$$
\begin{aligned}
P((A\cup B)^c)
&=
1-\frac34\\
&=
\frac14
\end{aligned}
$$

Jadi:

$$
\boxed{\frac14}
$$

---

# Kata-Kata yang Perlu Diperhatikan

Beberapa kata dalam soal sering berhubungan dengan operasi kejadian.

### "A atau B"

Biasanya berarti:

$$
A\cup B
$$

### "A dan B"

Biasanya berarti:

$$
A\cap B
$$

### "A saja"

Berarti:

$$
A-(A\cap B)
$$

### "tidak A maupun B"

Berarti:

$$
(A\cup B)^c
$$

---

> [!important]
> Kata **atau** dalam matematika umumnya bersifat inklusif.
>
> Artinya:
>
> $$
> A\cup B
> $$
>
> mencakup:
>
> - hanya $A$,
> - hanya $B$,
> - $A$ dan $B$ sekaligus.

---

# Strategi Menyelesaikan Peluang Kejadian Majemuk

Gunakan langkah berikut.

### Langkah 1

Tentukan kejadian:

$$
A
$$

dan:

$$
B
$$

### Langkah 2

Tentukan apakah soal meminta:

$$
A\cup B
$$

atau:

$$
A\cap B
$$

### Langkah 3

Periksa apakah kedua kejadian dapat terjadi bersamaan.

### Langkah 4

Jika tidak dapat terjadi bersamaan:

$$
P(A\cap B)=0
$$

dan:

$$
P(A\cup B)=P(A)+P(B)
$$

### Langkah 5

Jika dapat terjadi bersamaan:

$$
P(A\cup B)
=
P(A)+P(B)-P(A\cap B)
$$

### Langkah 6

Jika soal menanyakan tidak terjadi keduanya, gunakan komplemen jika lebih efisien.

---

# Soal Latihan

## Soal 1

Sebuah dadu dilempar satu kali.

Misalkan:

$$
A=\text{muncul angka 2}
$$

dan:

$$
B=\text{muncul angka 5}
$$

Tentukan:

1. apakah $A$ dan $B$ saling lepas,
2. peluang muncul angka 2 atau angka 5.

> [!success]- Klik untuk Lihat Jawaban
> Dalam satu kali pelemparan dadu, angka 2 dan angka 5 tidak dapat muncul secara bersamaan.
>
> Maka:
>
> $$
> A\cap B=\varnothing
> $$
>
> sehingga $A$ dan $B$ saling lepas.
>
> Gunakan:
>
> $$
> P(A\cup B)=P(A)+P(B)
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A\cup B)
> &=
> \frac16+\frac16\\
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

## Soal 2

Sebuah dadu dilempar satu kali.

Misalkan:

$$
A=\text{muncul bilangan genap}
$$

dan:

$$
B=\text{muncul bilangan prima}
$$

Tentukan peluang:

$$
A\cup B
$$

> [!success]- Klik untuk Lihat Jawaban
> Diketahui:
>
> $$
> A=\{2,4,6\}
> $$
>
> dan:
>
> $$
> B=\{2,3,5\}
> $$
>
> Irisannya:
>
> $$
> A\cap B=\{2\}
> $$
>
> sehingga:
>
> $$
> P(A)=\frac36
> $$
>
> $$
> P(B)=\frac36
> $$
>
> dan:
>
> $$
> P(A\cap B)=\frac16
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> P(A\cup B)
> &=
> \frac36+\frac36-\frac16\\
> &=
> \frac56
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac56}
> $$

---

## Soal 3

Sebuah kartu bernomor 1 sampai 20 diambil secara acak.

Misalkan:

$$
A=\text{nomor merupakan kelipatan 2}
$$

dan:

$$
B=\text{nomor merupakan kelipatan 5}
$$

Tentukan peluang nomor yang terambil merupakan kelipatan 2 atau kelipatan 5.

> [!success]- Klik untuk Lihat Jawaban
> Kelipatan 2:
>
> $$
> 2,4,6,8,10,12,14,16,18,20
> $$
>
> sehingga:
>
> $$
> n(A)=10
> $$
>
> Kelipatan 5:
>
> $$
> 5,10,15,20
> $$
>
> sehingga:
>
> $$
> n(B)=4
> $$
>
> Kelipatan 2 dan 5 sekaligus adalah kelipatan 10:
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
> n(A\cup B)
> &=
> 10+4-2\\
> &=12
> \end{aligned}
> $$
>
> Peluangnya:
>
> $$
> \begin{aligned}
> P(A\cup B)
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

## Soal 4

Dalam sebuah kelas terdapat 36 siswa.

Sebanyak:

- 20 siswa menyukai Matematika,
- 18 siswa menyukai Fisika,
- 9 siswa menyukai keduanya.

Jika dipilih satu siswa secara acak, tentukan peluang siswa tersebut menyukai Matematika atau Fisika.

> [!success]- Klik untuk Lihat Jawaban
> Gunakan:
>
> $$
> n(M\cup F)
> =
> n(M)+n(F)-n(M\cap F)
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> n(M\cup F)
> &=
> 20+18-9\\
> &=29
> \end{aligned}
> $$
>
> Peluangnya:
>
> $$
> P(M\cup F)
> =
> \frac{29}{36}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac{29}{36}}
> $$

---

## Soal 5

Dalam sebuah kelompok terdapat 50 orang.

Sebanyak:

- 28 orang menyukai sepak bola,
- 24 orang menyukai bulu tangkis,
- 12 orang menyukai keduanya.

Jika satu orang dipilih secara acak, tentukan peluang orang tersebut **hanya menyukai sepak bola**.

> [!success]- Klik untuk Lihat Jawaban
> Banyak orang yang hanya menyukai sepak bola:
>
> $$
> \begin{aligned}
> n(S\text{ saja})
> &=
> 28-12\\
> &=16
> \end{aligned}
> $$
>
> Maka:
>
> $$
> P(S\text{ saja})
> =
> \frac{16}{50}
> =
> \frac8{25}
> $$
>
> Jadi:
>
> $$
> \boxed{\frac8{25}}
> $$

---

## Soal 6

Dalam sebuah kelas terdapat 40 siswa.

Sebanyak:

- 24 siswa mengikuti klub Musik,
- 19 siswa mengikuti klub Olahraga,
- 11 siswa mengikuti kedua klub.

Jika satu siswa dipilih secara acak, tentukan peluang siswa tersebut **tidak mengikuti kedua klub tersebut**.

> [!success]- Klik untuk Lihat Jawaban
> Pertama tentukan banyak siswa yang mengikuti minimal salah satu klub.
>
> $$
> \begin{aligned}
> n(M\cup O)
> &=
> 24+19-11\\
> &=32
> \end{aligned}
> $$
>
> Maka siswa yang tidak mengikuti keduanya:
>
> $$
> 40-32=8
> $$
>
> Peluangnya:
>
> $$
> \begin{aligned}
> P
> &=
> \frac8{40}\\
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

## Soal 7

Dua buah dadu dilempar secara bersamaan.

Misalkan:

$$
A=\text{jumlah kedua mata dadu sama dengan 7}
$$

dan:

$$
B=\text{kedua mata dadu menunjukkan angka yang sama}
$$

Tentukan peluang:

$$
A\cup B
$$

> [!success]- Klik untuk Lihat Jawaban
> Jumlah seluruh hasil:
>
> $$
> n(S)=36
> $$
>
> ### Kejadian A
>
> Pasangan yang jumlahnya 7:
>
> $$
> (1,6),(2,5),(3,4),(4,3),(5,2),(6,1)
> $$
>
> sehingga:
>
> $$
> n(A)=6
> $$
>
> ### Kejadian B
>
> Pasangan dengan mata dadu sama:
>
> $$
> (1,1),(2,2),(3,3),(4,4),(5,5),(6,6)
> $$
>
> sehingga:
>
> $$
> n(B)=6
> $$
>
> Tidak ada pasangan yang sekaligus memiliki jumlah 7 dan menunjukkan angka yang sama.
>
> Maka:
>
> $$
> A\cap B=\varnothing
> $$
>
> sehingga:
>
> $$
> \begin{aligned}
> n(A\cup B)
> &=
> 6+6\\
> &=12
> \end{aligned}
> $$
>
> Peluangnya:
>
> $$
> \begin{aligned}
> P(A\cup B)
> &=
> \frac{12}{36}\\
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

## Soal 8

Dua buah dadu dilempar secara bersamaan.

Misalkan:

$$
A=\text{jumlah kedua mata dadu lebih dari 8}
$$

dan:

$$
B=\text{minimal salah satu dadu menunjukkan angka 6}
$$

Tentukan peluang:

$$
A\cup B
$$

> [!success]- Klik untuk Lihat Jawaban
> Jumlah seluruh kemungkinan:
>
> $$
> n(S)=36
> $$
>
> ### Langkah 1: Menentukan Kejadian A
>
> Jumlah lebih dari 8 berarti:
>
> $$
> 9,10,11,12
> $$
>
> Banyak pasangan masing-masing:
>
> $$
> \begin{aligned}
> \text{Jumlah }9 &: 4\\
> \text{Jumlah }10 &: 3\\
> \text{Jumlah }11 &: 2\\
> \text{Jumlah }12 &: 1
> \end{aligned}
> $$
>
> Maka:
>
> $$
> n(A)=4+3+2+1=10
> $$
>
> ### Langkah 2: Menentukan Kejadian B
>
> Minimal salah satu dadu menunjukkan angka 6.
>
> Pasangan yang memenuhi:
>
> $$
> \begin{aligned}
> &(6,1),(6,2),(6,3),(6,4),(6,5),(6,6),\\
> &(1,6),(2,6),(3,6),(4,6),(5,6)
> \end{aligned}
> $$
>
> sehingga:
>
> $$
> n(B)=11
> $$
>
> ### Langkah 3: Menentukan Irisan
>
> Pasangan yang memenuhi $A$ dan $B$ sekaligus:
>
> $$
> (6,3),(6,4),(6,5),(6,6),
> $$
>
> $$
> (3,6),(4,6),(5,6)
> $$
>
> sehingga:
>
> $$
> n(A\cap B)=7
> $$
>
> ### Langkah 4: Menentukan Gabungan
>
> $$
> \begin{aligned}
> n(A\cup B)
> &=
> n(A)+n(B)-n(A\cap B)\\
> &=
> 10+11-7\\
> &=14
> \end{aligned}
> $$
>
> Maka:
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

# Rangkuman

Kejadian majemuk melibatkan dua kejadian atau lebih.

Gabungan dua kejadian ditulis:

$$
A\cup B
$$

dan berarti:

> $A$ atau $B$ terjadi.

Irisan dua kejadian ditulis:

$$
A\cap B
$$

dan berarti:

> $A$ dan $B$ terjadi secara bersamaan.

Secara umum:

$$
\boxed{
P(A\cup B)
=
P(A)+P(B)-P(A\cap B)
}
$$

Jika $A$ dan $B$ saling lepas:

$$
A\cap B=\varnothing
$$

sehingga:

$$
\boxed{
P(A\cup B)=P(A)+P(B)
}
$$

Jika $A$ dan $B$ tidak saling lepas:

$$
A\cap B\neq\varnothing
$$

maka bagian irisan harus diperhitungkan.

Untuk menentukan kejadian yang tidak termasuk $A$ maupun $B$:

$$
\boxed{
P((A\cup B)^c)
=
1-P(A\cup B)
}
$$

---

> [!important]
> Sebelum menghitung peluang gabungan, selalu tanyakan:
>
> **Apakah kejadian $A$ dan $B$ dapat terjadi secara bersamaan?**
>
> Jika tidak:
>
> $$
> P(A\cap B)=0
> $$
>
> Jika ya:
>
> tentukan:
>
> $$
> P(A\cap B)
> $$
>
> sebelum menghitung:
>
> $$
> P(A\cup B)
> $$

---

# Inti Materi

Gunakan pola berikut:

$$
\boxed{
\text{A atau B}
\rightarrow
A\cup B
}
$$

$$
\boxed{
\text{A dan B}
\rightarrow
A\cap B
}
$$

$$
\boxed{
A\cap B=\varnothing
\rightarrow
\text{saling lepas}
}
$$

$$
\boxed{
A\cap B\neq\varnothing
\rightarrow
\text{tidak saling lepas}
}
$$

Kemampuan mengenali gabungan dan irisan ini akan sangat penting pada materi berikutnya, yaitu **peluang bersyarat** dan **kejadian saling bebas**.

---

## Konsep Terkait

- [[Kaidah Pencacahan dan Peluang/06 - Konsep Dasar Peluang]]
- [[Kaidah Pencacahan dan Peluang/07 - Peluang Komplemen]]
- [[Kaidah Pencacahan dan Peluang/09 - Peluang Bersyarat]]
- [[Kaidah Pencacahan dan Peluang/10 - Kejadian Saling Bebas]]
- [[Kaidah Pencacahan dan Peluang/11 - Penerapan Kaidah Pencacahan dalam Peluang]]