# Aplikasi Barisan dan Deret: Bunga Majemuk dan Anuitas

Dalam kehidupan sehari-hari, konsep barisan dan deret dapat digunakan untuk menyelesaikan berbagai persoalan keuangan. Dua contoh yang sering dijumpai adalah **bunga majemuk** pada tabungan atau investasi dan **anuitas** pada sistem pembayaran pinjaman.

Pada bunga majemuk, nilai uang pada setiap periode membentuk **barisan geometri**. Sementara itu, pada anuitas, pembayaran yang dilakukan secara berkala dapat dianalisis menggunakan konsep **deret geometri**.

---

## 1. Bunga Majemuk (*Compound Interest*)

### A. Pengertian Bunga Majemuk

Bunga majemuk adalah bunga yang dihitung berdasarkan jumlah modal pada akhir periode sebelumnya.

Artinya, bunga yang diperoleh pada suatu periode akan menjadi bagian dari modal untuk perhitungan bunga pada periode berikutnya. Oleh karena itu, bunga majemuk sering disebut sebagai **bunga berbunga**.

Misalkan:

- modal awal adalah $M_0$
- suku bunga setiap periode adalah $i$

Setelah satu periode:

$$
M_1=M_0(1+i)
$$

Setelah dua periode:

$$
\begin{aligned}
M_2
&=M_1(1+i)\\
&=M_0(1+i)(1+i)\\
&=M_0(1+i)^2
\end{aligned}
$$

Setelah tiga periode:

$$
M_3=M_0(1+i)^3
$$

Dengan demikian, nilai modal membentuk barisan geometri:

$$
M_0,\ M_0(1+i),\ M_0(1+i)^2,\ M_0(1+i)^3,\ldots
$$

dengan rasio:

$$
r=1+i
$$

---

### B. Rumus Bunga Majemuk

Jika:

- $M_0$ = modal awal
- $M_n$ = modal setelah $n$ periode
- $i$ = suku bunga setiap periode dalam bentuk desimal
- $n$ = banyaknya periode

maka:

$$
\boxed{M_n=M_0(1+i)^n}
$$

> [!important]
> Satuan waktu pada $i$ dan $n$ harus sama.
>
> Jika bunga diberikan per tahun, maka $n$ dinyatakan dalam tahun. Jika bunga diberikan per bulan, maka $n$ dinyatakan dalam bulan.

---

### C. Bunga Majemuk Beberapa Kali dalam Setahun

Bunga tidak selalu diberikan satu kali dalam setahun. Bunga dapat diberikan setiap semester, setiap tiga bulan, atau setiap bulan.

Misalkan:

- $r$ = suku bunga nominal per tahun
- $m$ = banyaknya pemberian bunga dalam satu tahun
- $t$ = lama investasi dalam tahun

Suku bunga untuk setiap periode adalah:

$$
i=\frac{r}{m}
$$

Banyaknya periode adalah:

$$
n=mt
$$

Sehingga:

$$
\boxed{
M_t=M_0\left(1+\frac{r}{m}\right)^{mt}
}
$$

Contoh nilai $m$:

| Periode pemberian bunga | Nilai $m$ |
|---|---:|
| Tahunan | $1$ |
| Semesteran | $2$ |
| Triwulanan | $4$ |
| Bulanan | $12$ |

---

### Contoh 1

Seseorang menyimpan uang sebesar **Rp10.000.000** di bank dengan bunga majemuk $5\%$ per tahun. Uang tersebut disimpan selama $2$ tahun tanpa penarikan.

Tentukan saldo pada akhir tahun ke-2.

> [!success]- Klik untuk Lihat Pembahasan
>
> Diketahui:
>
> $$
> M_0=10.000.000
> $$
>
> $$
> i=5\%=0{,}05
> $$
>
> $$
> n=2
> $$
>
> Gunakan rumus:
>
> $$
> M_n=M_0(1+i)^n
> $$
>
> sehingga:
>
> $$
> \begin{aligned}
> M_2
> &=10.000.000(1+0{,}05)^2\\
> &=10.000.000(1{,}05)^2\\
> &=10.000.000(1{,}1025)\\
> &=11.025.000
> \end{aligned}
> $$
>
> Jadi, saldo pada akhir tahun ke-2 adalah:
>
> $$
> \boxed{\text{Rp11.025.000}}
> $$

---

## 2. Sistem Anuitas (*Annuity*)

### A. Pengertian Anuitas

Anuitas adalah pembayaran atau penerimaan sejumlah uang dengan jumlah yang **tetap** pada setiap periode tertentu.

Anuitas sering digunakan dalam:

- cicilan kendaraan
- kredit rumah
- pinjaman bank
- pembayaran investasi berkala

Dalam sistem pembayaran pinjaman, besar pembayaran setiap periode disebut **anuitas**.

Misalkan besar anuitas adalah $A$.

Setiap pembayaran terdiri atas:

1. **angsuran pokok** $(a_n)$
2. **bunga** $(b_n)$

Hubungannya adalah:

$$
\boxed{A=a_n+b_n}
$$

atau:

$$
\boxed{a_n=A-b_n}
$$

---

### B. Bunga pada Setiap Periode

Bunga dihitung berdasarkan sisa pinjaman sebelum pembayaran dilakukan.

Jika sisa pinjaman sebelum pembayaran ke-$n$ adalah $S_{n-1}$, maka:

$$
\boxed{b_n=iS_{n-1}}
$$

Setelah angsuran pokok dibayarkan, sisa pinjaman menjadi:

$$
\boxed{S_n=S_{n-1}-a_n}
$$

Karena sisa pinjaman semakin kecil, maka bunga yang dibayarkan juga semakin kecil.

Sementara itu, nilai anuitas $A$ tetap.

Akibatnya:

- bunga semakin **kecil**
- angsuran pokok semakin **besar**
- total pembayaran setiap periode tetap sebesar $A$

---

### C. Hubungan Anuitas dengan Deret Geometri

Misalkan seseorang meminjam uang sebesar $M_0$ dan mengembalikannya melalui pembayaran tetap sebesar $A$ sebanyak $n$ kali.

Jika suku bunga setiap periode adalah $i$, maka nilai sekarang dari seluruh pembayaran adalah:

$$
M_0=
\frac{A}{1+i}
+
\frac{A}{(1+i)^2}
+
\frac{A}{(1+i)^3}
+\cdots+
\frac{A}{(1+i)^n}
$$

Bentuk tersebut merupakan **deret geometri** dengan:

$$
a=\frac{A}{1+i}
$$

dan:

$$
r=\frac{1}{1+i}
$$

Dengan menggunakan rumus jumlah deret geometri diperoleh:

$$
M_0=A\frac{1-(1+i)^{-n}}{i}
$$

Sehingga besar anuitas adalah:

$$
\boxed{
A=\frac{M_0i}{1-(1+i)^{-n}}
}
$$

dengan:

- $A$ = pembayaran tetap setiap periode
- $M_0$ = jumlah pinjaman awal
- $i$ = suku bunga setiap periode
- $n$ = banyaknya pembayaran

> [!important]
> Periode suku bunga harus sama dengan periode pembayaran.
>
> Jika pembayaran dilakukan setiap bulan, gunakan suku bunga **per bulan**, bukan langsung suku bunga per tahun.

---

### Contoh 2

Seseorang meminjam uang sebesar **Rp10.000.000**. Pinjaman tersebut akan dilunasi dengan sistem anuitas selama $12$ bulan. Suku bunga pinjaman adalah $1\%$ per bulan.

Tentukan besar pembayaran setiap bulan.

> [!success]- Klik untuk Lihat Pembahasan
>
> Diketahui:
>
> $$
> M_0=10.000.000
> $$
>
> $$
> i=1\%=0{,}01
> $$
>
> $$
> n=12
> $$
>
> Gunakan rumus:
>
> $$
> A=\frac{M_0i}{1-(1+i)^{-n}}
> $$
>
> sehingga:
>
> $$
> A=
> \frac{10.000.000(0{,}01)}
> {1-(1{,}01)^{-12}}
> $$
>
> $$
> A\approx888.487{,}89
> $$
>
> Jadi, pembayaran yang harus dilakukan setiap bulan adalah sekitar:
>
> $$
> \boxed{\text{Rp888.488}}
> $$

---

## 3. Ringkasan

### Bunga Majemuk

Nilai modal setelah $n$ periode:

$$
\boxed{M_n=M_0(1+i)^n}
$$

Jika bunga diberikan $m$ kali dalam satu tahun:

$$
\boxed{
M_t=M_0\left(1+\frac{r}{m}\right)^{mt}
}
$$

Bunga majemuk menghasilkan pola **barisan geometri** dengan rasio:

$$
1+i
$$

### Anuitas

Setiap pembayaran terdiri atas:

$$
\boxed{A=a_n+b_n}
$$

Bunga periode ke-$n$:

$$
\boxed{b_n=iS_{n-1}}
$$

Angsuran pokok:

$$
\boxed{a_n=A-b_n}
$$

Besar anuitas:

$$
\boxed{
A=\frac{M_0i}{1-(1+i)^{-n}}
}
$$

Konsep anuitas diperoleh dari penerapan **deret geometri**.

---

# Latihan Soal

Soal berikut disusun secara bertahap. Kerjakan mulai dari soal pertama sebelum melanjutkan ke soal berikutnya.

---

## Level 1: Pemahaman Dasar

### Soal 1

Dina menabung sebesar **Rp4.000.000** dengan bunga majemuk $10\%$ per tahun. Jika uang tersebut disimpan selama $2$ tahun, tentukan saldo Dina pada akhir tahun ke-2.

> [!success]- Pembahasan
>
> Diketahui:
>
> $$
> M_0=4.000.000,\qquad i=0{,}10,\qquad n=2
> $$
>
> $$
> \begin{aligned}
> M_2
> &=4.000.000(1{,}10)^2\\
> &=4.000.000(1{,}21)\\
> &=4.840.000
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\text{Rp4.840.000}}
> $$

---

### Soal 2

Sebuah investasi sebesar **Rp8.000.000** memperoleh bunga majemuk $6\%$ per tahun. Tentukan nilai investasi tersebut setelah $3$ tahun.

> [!success]- Pembahasan
>
> $$
> M_0=8.000.000,\qquad i=0{,}06,\qquad n=3
> $$
>
> $$
> \begin{aligned}
> M_3
> &=8.000.000(1{,}06)^3\\
> &=8.000.000(1{,}191016)\\
> &=9.528.128
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{\text{Rp9.528.128}}
> $$

---

## Level 2: Penerapan

### Soal 3

Raka menginvestasikan uang sebesar **Rp5.000.000** dengan bunga nominal $12\%$ per tahun. Bunga dihitung dan ditambahkan ke modal setiap bulan.

Tentukan nilai investasi Raka setelah $1$ tahun.

> [!success]- Pembahasan
>
> Karena bunga diberikan setiap bulan:
>
> $$
> m=12
> $$
>
> Suku bunga setiap bulan:
>
> $$
> \frac{12\%}{12}=1\%=0{,}01
> $$
>
> Banyak periode:
>
> $$
> n=12
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> M
> &=5.000.000(1{,}01)^{12}\\
> &\approx5.634.125{,}15
> \end{aligned}
> $$
>
> Jadi nilai investasi setelah satu tahun sekitar:
>
> $$
> \boxed{\text{Rp5.634.125}}
> $$

---

### Soal 4

Setelah disimpan selama $2$ tahun dengan bunga majemuk $10\%$ per tahun, saldo sebuah tabungan menjadi **Rp12.100.000**.

Berapa modal awal tabungan tersebut?

> [!success]- Pembahasan
>
> Diketahui:
>
> $$
> M_2=12.100.000
> $$
>
> $$
> i=0{,}10
> $$
>
> Dari:
>
> $$
> M_n=M_0(1+i)^n
> $$
>
> diperoleh:
>
> $$
> M_0=\frac{M_n}{(1+i)^n}
> $$
>
> sehingga:
>
> $$
> \begin{aligned}
> M_0
> &=\frac{12.100.000}{(1{,}10)^2}\\
> &=\frac{12.100.000}{1{,}21}\\
> &=10.000.000
> \end{aligned}
> $$
>
> Jadi modal awalnya adalah:
>
> $$
> \boxed{\text{Rp10.000.000}}
> $$

---

### Soal 5

Sebuah pinjaman sebesar **Rp12.000.000** akan dilunasi dengan sistem anuitas selama $12$ bulan. Suku bunga adalah $1\%$ per bulan.

Tentukan besar pembayaran tetap setiap bulan.

> [!success]- Pembahasan
>
> Diketahui:
>
> $$
> M_0=12.000.000,\qquad i=0{,}01,\qquad n=12
> $$
>
> Gunakan:
>
> $$
> A=\frac{M_0i}{1-(1+i)^{-n}}
> $$
>
> $$
> \begin{aligned}
> A
> &=
> \frac{12.000.000(0{,}01)}
> {1-(1{,}01)^{-12}}\\
> &\approx1.066.185{,}46
> \end{aligned}
> $$
>
> Jadi pembayaran setiap bulan sekitar:
>
> $$
> \boxed{\text{Rp1.066.185}}
> $$

---

## Level 3: Analisis

### Soal 6

Sebuah pinjaman sebesar **Rp20.000.000** dilunasi selama $10$ bulan dengan bunga $1\%$ per bulan.

Tentukan:

1. besar anuitas setiap bulan
2. bunga pada pembayaran pertama
3. angsuran pokok pada pembayaran pertama
4. sisa pinjaman setelah pembayaran pertama

> [!success]- Pembahasan
>
> Besar anuitas:
>
> $$
> A=
> \frac{20.000.000(0{,}01)}
> {1-(1{,}01)^{-10}}
> $$
>
> $$
> A\approx2.111.641{,}53
> $$
>
> Bunga pembayaran pertama:
>
> $$
> b_1=20.000.000(0{,}01)=200.000
> $$
>
> Angsuran pokok:
>
> $$
> \begin{aligned}
> a_1
> &=A-b_1\\
> &=2.111.641{,}53-200.000\\
> &=1.911.641{,}53
> \end{aligned}
> $$
>
> Sisa pinjaman:
>
> $$
> \begin{aligned}
> S_1
> &=20.000.000-1.911.641{,}53\\
> &=18.088.358{,}47
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{A\approx\text{Rp2.111.642}}
> $$
>
> $$
> \boxed{b_1=\text{Rp200.000}}
> $$
>
> $$
> \boxed{a_1\approx\text{Rp1.911.642}}
> $$
>
> $$
> \boxed{S_1\approx\text{Rp18.088.358}}
> $$

---

### Soal 7

Dua bank menawarkan pilihan investasi berikut untuk modal awal **Rp10.000.000** selama $3$ tahun.

**Bank A**

Bunga majemuk $8\%$ per tahun dan diberikan satu kali setiap tahun.

**Bank B**

Bunga nominal $7{,}8\%$ per tahun dan diberikan setiap tiga bulan.

Tentukan investasi mana yang menghasilkan saldo akhir lebih besar.

> [!success]- Pembahasan
>
> **Bank A**
>
> $$
> \begin{aligned}
> M_A
> &=10.000.000(1{,}08)^3\\
> &=12.597.120
> \end{aligned}
> $$
>
> **Bank B**
>
> Karena bunga diberikan empat kali setiap tahun:
>
> $$
> m=4
> $$
>
> Suku bunga setiap periode:
>
> $$
> \frac{0{,}078}{4}=0{,}0195
> $$
>
> Banyak periode selama tiga tahun:
>
> $$
> 3(4)=12
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> M_B
> &=10.000.000(1+0{,}0195)^{12}\\
> &\approx12.608.016{,}29
> \end{aligned}
> $$
>
> Karena:
>
> $$
> 12.608.016{,}29>12.597.120
> $$
>
> maka **Bank B memberikan saldo akhir yang sedikit lebih besar**.
>
> Selisihnya sekitar:
>
> $$
> \boxed{\text{Rp10.896}}
> $$
>
> Soal ini menunjukkan bahwa besarnya bunga tahunan saja belum cukup untuk membandingkan dua investasi. **Frekuensi pemberian bunga juga memengaruhi hasil akhir.**

---

### Soal 8

Seseorang memperoleh pinjaman sebesar **Rp30.000.000** yang harus dilunasi selama $24$ bulan dengan sistem anuitas. Suku bunga pinjaman adalah $1\%$ per bulan.

Tentukan:

1. besar pembayaran setiap bulan
2. bunga dan angsuran pokok pada pembayaran pertama
3. sisa pinjaman setelah pembayaran pertama
4. bunga dan angsuran pokok pada pembayaran kedua
5. sisa pinjaman setelah pembayaran kedua
6. jelaskan mengapa angsuran pokok pada pembayaran kedua lebih besar daripada pembayaran pertama

> [!success]- Pembahasan
>
> **1. Besar anuitas**
>
> $$
> A=
> \frac{30.000.000(0{,}01)}
> {1-(1{,}01)^{-24}}
> $$
>
> $$
> A\approx1.412.204{,}17
> $$
>
> ---
>
> **2. Pembayaran pertama**
>
> Bunga pertama:
>
> $$
> b_1=30.000.000(0{,}01)=300.000
> $$
>
> Angsuran pokok:
>
> $$
> \begin{aligned}
> a_1
> &=A-b_1\\
> &=1.412.204{,}17-300.000\\
> &=1.112.204{,}17
> \end{aligned}
> $$
>
> ---
>
> **3. Sisa pinjaman setelah pembayaran pertama**
>
> $$
> \begin{aligned}
> S_1
> &=30.000.000-1.112.204{,}17\\
> &=28.887.795{,}83
> \end{aligned}
> $$
>
> ---
>
> **4. Pembayaran kedua**
>
> Bunga kedua dihitung dari sisa pinjaman:
>
> $$
> \begin{aligned}
> b_2
> &=28.887.795{,}83(0{,}01)\\
> &=288.877{,}96
> \end{aligned}
> $$
>
> Angsuran pokok kedua:
>
> $$
> \begin{aligned}
> a_2
> &=A-b_2\\
> &=1.412.204{,}17-288.877{,}96\\
> &=1.123.326{,}21
> \end{aligned}
> $$
>
> ---
>
> **5. Sisa pinjaman setelah pembayaran kedua**
>
> $$
> \begin{aligned}
> S_2
> &=28.887.795{,}83-1.123.326{,}21\\
> &=27.764.469{,}62
> \end{aligned}
> $$
>
> ---
>
> **6. Analisis**
>
> Besar anuitas setiap bulan tetap, yaitu sekitar Rp1.412.204.
>
> Namun, bunga dihitung berdasarkan **sisa pinjaman**. Setelah pembayaran pertama, sisa pinjaman berkurang sehingga bunga pada pembayaran kedua juga berkurang.
>
> Karena:
>
> $$
> A=a_n+b_n
> $$
>
> dan nilai $A$ tetap, ketika nilai bunga $b_n$ semakin kecil, nilai angsuran pokok $a_n$ akan semakin besar.
>
> Inilah karakteristik utama sistem anuitas.

---

## Konsep Terkait

- [[Barisan dan Deret/06 - Deret Geometri|06 - Deret Geometri]]
- [[Barisan dan Deret/09 - Aplikasi Barisan dan Deret Pertumbuhan dan Peluruhan|09 - Aplikasi Barisan dan Deret Pertumbuhan dan Peluruhan]]