
# Faktorial

Pada materi sebelumnya, kita telah menggunakan aturan perkalian untuk menentukan banyak kemungkinan.

Sebagai contoh, dari 5 orang akan dipilih dan disusun 3 orang secara berurutan.

Banyak kemungkinan dapat dihitung dengan:

$$
5\times4\times3
$$

Jika seluruh 5 orang disusun, perhitungannya menjadi:

$$
5\times4\times3\times2\times1
$$

Perkalian berurutan seperti ini sering muncul dalam masalah pencacahan. Agar penulisannya lebih sederhana, digunakan **notasi faktorial**.

---

# Pengertian Faktorial

Untuk bilangan bulat positif $n$, faktorial dari $n$ ditulis:

$$
n!
$$

dan didefinisikan sebagai:

$$
n!=n(n-1)(n-2)\cdots3\cdot2\cdot1
$$

Dengan kata lain, $n!$ adalah hasil kali semua bilangan bulat positif dari $n$ sampai 1.

---

## Contoh 1

Tentukan nilai:

$$
5!
$$

Berdasarkan definisi:

$$
\begin{aligned}
5!
&=5\times4\times3\times2\times1\\
&=120
\end{aligned}
$$

Jadi:

$$
\boxed{5!=120}
$$

---

## Contoh 2

Tentukan nilai:

$$
7!
$$

Maka:

$$
\begin{aligned}
7!
&=7\times6\times5\times4\times3\times2\times1\\
&=5040
\end{aligned}
$$

Jadi:

$$
\boxed{7!=5040}
$$

---

# Nilai-Nilai Faktorial

Beberapa nilai faktorial yang sering digunakan adalah:

| $n$ | $n!$ |
|---:|---:|
| $0$ | $1$ |
| $1$ | $1$ |
| $2$ | $2$ |
| $3$ | $6$ |
| $4$ | $24$ |
| $5$ | $120$ |
| $6$ | $720$ |
| $7$ | $5040$ |
| $8$ | $40320$ |

---

> [!important]
> Secara khusus:
>
> $$
> 0!=1
> $$
>
> Nilai ini didefinisikan demikian agar berbagai rumus dalam kombinatorika tetap berlaku secara konsisten.

---

# Hubungan Antar-Faktorial

Perhatikan:

$$
5!=5\times4\times3\times2\times1
$$

Sedangkan:

$$
4!=4\times3\times2\times1
$$

Maka:

$$
5!=5\times4!
$$

Secara umum:

$$
\boxed{n!=n(n-1)!}
$$

Hubungan ini sangat berguna untuk menyederhanakan bentuk yang melibatkan faktorial.

---

## Contoh 3

Sederhanakan:

$$
\frac{8!}{7!}
$$

Karena:

$$
8!=8\times7!
$$

maka:

$$
\begin{aligned}
\frac{8!}{7!}
&=\frac{8\times7!}{7!}\\
&=8
\end{aligned}
$$

Jadi:

$$
\boxed{8}
$$

---

# Menyederhanakan Bentuk Faktorial

Ketika terdapat pembagian dua faktorial, kita tidak perlu selalu menghitung nilai faktorial secara penuh.

Perhatikan contoh berikut.

## Contoh 4

Sederhanakan:

$$
\frac{10!}{7!}
$$

Tuliskan $10!$ sampai muncul $7!$:

$$
10!=10\times9\times8\times7!
$$

Sehingga:

$$
\begin{aligned}
\frac{10!}{7!}
&=
\frac{10\times9\times8\times7!}{7!}\\
&=10\times9\times8\\
&=720
\end{aligned}
$$

Jadi:

$$
\boxed{720}
$$

---

> [!note]
> Dalam pembagian faktorial, cukup uraikan faktorial yang lebih besar sampai muncul faktorial yang terdapat pada penyebut.
>
> Cara ini jauh lebih efisien daripada menghitung nilai faktorial secara penuh.

---

# Bentuk Umum Pembagian Faktorial

Jika $n>r$, maka:

$$
\frac{n!}{r!}
$$

dapat ditulis:

$$
\frac{n!}{r!}
=
n(n-1)(n-2)\cdots(r+1)
$$

Misalnya:

$$
\frac{9!}{5!}
$$

maka:

$$
\begin{aligned}
\frac{9!}{5!}
&=9\times8\times7\times6\\
&=3024
\end{aligned}
$$

---

# Faktorial dengan Operasi Perkalian

Faktorial juga dapat muncul bersama operasi lain.

## Contoh 5

Sederhanakan:

$$
\frac{7!}{5!\times2!}
$$

Uraikan:

$$
7!=7\times6\times5!
$$

Maka:

$$
\begin{aligned}
\frac{7!}{5!\times2!}
&=
\frac{7\times6\times5!}{5!\times2\times1}\\
&=
\frac{7\times6}{2}\\
&=21
\end{aligned}
$$

Jadi:

$$
\boxed{21}
$$

Bentuk seperti ini nantinya banyak digunakan dalam rumus **kombinasi**.

---

# Menentukan Nilai $n$

Pada beberapa soal, nilai faktorial diketahui dan kita diminta menentukan nilai $n$.

## Contoh 6

Jika:

$$
n!=120
$$

tentukan nilai $n$.

Kita mengetahui:

$$
5!=120
$$

maka:

$$
\boxed{n=5}
$$

---

## Contoh 7

Jika:

$$
\frac{n!}{(n-2)!}=20
$$

tentukan nilai $n$.

Uraikan:

$$
n!=n(n-1)(n-2)!
$$

Maka:

$$
\begin{aligned}
\frac{n!}{(n-2)!}
&=
\frac{n(n-1)(n-2)!}{(n-2)!}\\
&=n(n-1)
\end{aligned}
$$

Sehingga:

$$
n(n-1)=20
$$

Kita cari dua bilangan berurutan yang hasil kalinya 20:

$$
5\times4=20
$$

maka:

$$
\boxed{n=5}
$$

---

# Hubungan Faktorial dengan Kaidah Pencacahan

Faktorial muncul secara alami ketika kita menyusun sejumlah objek berbeda.

Misalnya, terdapat 4 buku berbeda yang akan disusun berjajar.

Untuk posisi pertama tersedia:

$$
4
$$

pilihan.

Setelah satu buku ditempatkan, posisi kedua memiliki:

$$
3
$$

pilihan.

Posisi ketiga memiliki:

$$
2
$$

pilihan.

Posisi terakhir memiliki:

$$
1
$$

pilihan.

Maka banyak susunannya:

$$
4\times3\times2\times1
$$

atau:

$$
4!
$$

sehingga:

$$
4!=24
$$

Jadi, terdapat:

$$
\boxed{24}
$$

susunan berbeda.

---

> [!important]
> Faktorial dapat dipandang sebagai bentuk ringkas dari aturan perkalian ketika jumlah pilihan berkurang satu demi satu.
>
> Polanya:
>
> $$
> n\times(n-1)\times(n-2)\times\cdots\times1
> $$
>
> ditulis:
>
> $$
> n!
> $$

---

# Hubungan dengan Permutasi

Misalkan terdapat 6 orang dan seluruhnya akan disusun dalam satu baris.

Banyak susunan:

$$
6\times5\times4\times3\times2\times1
$$

atau:

$$
6!
$$

Konsep inilah yang akan menjadi dasar pada materi berikutnya, yaitu **permutasi**.

Permutasi digunakan ketika kita ingin menghitung banyak susunan dan **urutan objek diperhatikan**.

---

# Strategi Menyelesaikan Bentuk Faktorial

Saat menghadapi bentuk faktorial, gunakan langkah berikut.

### Langkah 1

Perhatikan faktorial terbesar.

### Langkah 2

Uraikan hanya sampai muncul faktorial yang dapat dicoret.

### Langkah 3

Sederhanakan terlebih dahulu.

### Langkah 4

Lakukan perhitungan setelah bentuknya sederhana.

---

## Contoh 8

Hitung:

$$
\frac{12!}{10!\times2!}
$$

Uraikan:

$$
12!=12\times11\times10!
$$

Maka:

$$
\begin{aligned}
\frac{12!}{10!\times2!}
&=
\frac{12\times11\times10!}{10!\times2}\\
&=
\frac{12\times11}{2}\\
&=66
\end{aligned}
$$

Jadi:

$$
\boxed{66}
$$

---

# Soal Latihan

## Soal 1

Hitung nilai:

$$
6!
$$

> [!success]- Klik untuk Lihat Jawaban
> Berdasarkan definisi faktorial:
>
> $$
> \begin{aligned}
> 6!
> &=6\times5\times4\times3\times2\times1\\
> &=720
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{720}
> $$

---

## Soal 2

Hitung nilai:

$$
\frac{8!}{6!}
$$

> [!success]- Klik untuk Lihat Jawaban
> Uraikan $8!$ sampai muncul $6!$:
>
> $$
> 8!=8\times7\times6!
> $$
>
> sehingga:
>
> $$
> \begin{aligned}
> \frac{8!}{6!}
> &=
> \frac{8\times7\times6!}{6!}\\
> &=8\times7\\
> &=56
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{56}
> $$

---

## Soal 3

Sederhanakan:

$$
\frac{10!}{8!}
$$

> [!success]- Klik untuk Lihat Jawaban
> Karena:
>
> $$
> 10!=10\times9\times8!
> $$
>
> maka:
>
> $$
> \begin{aligned}
> \frac{10!}{8!}
> &=10\times9\\
> &=90
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{90}
> $$

---

## Soal 4

Hitung nilai:

$$
\frac{9!}{7!\times2!}
$$

> [!success]- Klik untuk Lihat Jawaban
> Uraikan:
>
> $$
> 9!=9\times8\times7!
> $$
>
> sehingga:
>
> $$
> \begin{aligned}
> \frac{9!}{7!\times2!}
> &=
> \frac{9\times8\times7!}{7!\times2}\\
> &=
> \frac{72}{2}\\
> &=36
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{36}
> $$

---

## Soal 5

Tentukan nilai $n$ jika:

$$
n!=720
$$

> [!success]- Klik untuk Lihat Jawaban
> Kita mencari bilangan yang faktorialnya sama dengan 720.
>
> $$
> \begin{aligned}
> 6!
> &=6\times5\times4\times3\times2\times1\\
> &=720
> \end{aligned}
> $$
>
> Maka:
>
> $$
> \boxed{n=6}
> $$

---

## Soal 6

Tentukan nilai $n$ jika:

$$
\frac{n!}{(n-1)!}=9
$$

> [!success]- Klik untuk Lihat Jawaban
> Gunakan:
>
> $$
> n!=n(n-1)!
> $$
>
> maka:
>
> $$
> \begin{aligned}
> \frac{n!}{(n-1)!}
> &=
> \frac{n(n-1)!}{(n-1)!}\\
> &=n
> \end{aligned}
> $$
>
> Karena:
>
> $$
> n=9
> $$
>
> maka:
>
> $$
> \boxed{n=9}
> $$

---

## Soal 7

Tentukan nilai $n$ jika:

$$
\frac{n!}{(n-2)!}=42
$$

> [!success]- Klik untuk Lihat Jawaban
> Uraikan:
>
> $$
> n!=n(n-1)(n-2)!
> $$
>
> sehingga:
>
> $$
> \begin{aligned}
> \frac{n!}{(n-2)!}
> &=n(n-1)
> \end{aligned}
> $$
>
> Maka:
>
> $$
> n(n-1)=42
> $$
>
> Kita mencari dua bilangan berurutan yang hasil kalinya 42:
>
> $$
> 7\times6=42
> $$
>
> sehingga:
>
> $$
> \boxed{n=7}
> $$

---

## Soal 8

Diketahui:

$$
\frac{(n+2)!}{n!}=56
$$

Tentukan nilai $n$.

> [!success]- Klik untuk Lihat Jawaban
> Uraikan:
>
> $$
> (n+2)!=(n+2)(n+1)n!
> $$
>
> sehingga:
>
> $$
> \begin{aligned}
> \frac{(n+2)!}{n!}
> &=
> \frac{(n+2)(n+1)n!}{n!}\\
> &=(n+2)(n+1)
> \end{aligned}
> $$
>
> Maka:
>
> $$
> (n+2)(n+1)=56
> $$
>
> Kita mencari dua bilangan berurutan yang hasil kalinya 56:
>
> $$
> 8\times7=56
> $$
>
> sehingga:
>
> $$
> n+2=8
> $$
>
> maka:
>
> $$
> n=6
> $$
>
> Jadi:
>
> $$
> \boxed{n=6}
> $$

---

# Rangkuman

Faktorial dari bilangan bulat positif $n$ didefinisikan sebagai:

$$
n!=n(n-1)(n-2)\cdots2\cdot1
$$

Secara khusus:

$$
0!=1
$$

Hubungan penting dalam faktorial adalah:

$$
n!=n(n-1)!
$$

Dalam pembagian faktorial, faktorial yang lebih besar dapat diuraikan sampai muncul faktorial yang terdapat pada penyebut.

Contohnya:

$$
\frac{10!}{8!}
=
10\times9
$$

Faktorial merupakan bentuk ringkas dari aturan perkalian ketika banyak pilihan berkurang satu demi satu.

Konsep ini menjadi dasar untuk mempelajari **permutasi** dan **kombinasi**.

---

> [!important]
> Jangan langsung menghitung nilai faktorial yang besar.
>
> Jika terdapat pembagian, sederhanakan terlebih dahulu dengan menguraikan faktorial secukupnya.
>
> Contoh:
>
> $$
> \frac{20!}{18!}
> $$
>
> cukup ditulis:
>
> $$
> 20\times19
> $$
>
> bukan menghitung nilai $20!$ dan $18!$ secara terpisah.

---

## Konsep Terkait

- [[Materi Baru Kaidah Pencacahan dan Peluang/01 - Konsep Dasar Pencacahan]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/03 - Permutasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/04 - Kombinasi]]