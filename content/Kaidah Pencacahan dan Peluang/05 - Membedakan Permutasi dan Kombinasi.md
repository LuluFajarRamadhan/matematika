# Membedakan Permutasi dan Kombinasi

Permutasi dan kombinasi sama-sama digunakan untuk menentukan banyak kemungkinan dari beberapa objek.

Perbedaannya terletak pada satu hal utama:

$$
\boxed{\text{Apakah urutan berpengaruh?}}
$$

Jika perubahan urutan menghasilkan hasil yang berbeda, gunakan **permutasi**.

Jika perubahan urutan tidak menghasilkan hasil yang berbeda, gunakan **kombinasi**.

---

# Ide Dasar

Misalkan terdapat tiga siswa:

$$
A,\ B,\ C
$$

dan kita memilih dua siswa.

Jika siswa yang dipilih adalah:

$$
A \text{ dan } B
$$

kita perlu melihat konteksnya.

---

## Kasus 1: Menentukan Ketua dan Sekretaris

Jika:

- $A$ menjadi ketua,
- $B$ menjadi sekretaris,

maka hasil tersebut berbeda dengan:

- $B$ menjadi ketua,
- $A$ menjadi sekretaris.

Artinya:

$$
AB\neq BA
$$

Urutan atau posisi berpengaruh.

Maka digunakan:

$$
\boxed{\text{Permutasi}}
$$

---

## Kasus 2: Memilih Dua Anggota Tim

Jika yang dipilih adalah $A$ dan $B$, maka:

$$
AB=BA
$$

karena keduanya hanya menjadi anggota tim dengan kedudukan yang sama.

Urutan tidak berpengaruh.

Maka digunakan:

$$
\boxed{\text{Kombinasi}}
$$

---

# Perbandingan Permutasi dan Kombinasi

| Permutasi | Kombinasi |
|---|---|
| Urutan diperhatikan | Urutan tidak diperhatikan |
| Posisi atau jabatan berbeda | Kedudukan sama |
| $AB\neq BA$ | $AB=BA$ |
| Digunakan untuk penyusunan | Digunakan untuk pemilihan kelompok |
| Rumus: ${}_nP_r$ | Rumus: ${}_nC_r$ |

---

# Rumus Permutasi

Jika $r$ objek dipilih dan disusun dari $n$ objek berbeda:

$$
\boxed{
{}_nP_r=
\frac{n!}{(n-r)!}
}
$$

---

# Rumus Kombinasi

Jika $r$ objek dipilih dari $n$ objek berbeda tanpa memperhatikan urutan:

$$
\boxed{
{}_nC_r=
\frac{n!}{r!(n-r)!}
}
$$

---

# Hubungan Permutasi dan Kombinasi

Permutasi dan kombinasi memiliki hubungan:

$$
{}_nP_r
=
{}_nC_r\times r!
$$

atau:

$$
\boxed{
{}_nC_r
=
\frac{{}_nP_r}{r!}
}
$$

Artinya, setelah kita memilih $r$ objek menggunakan kombinasi, objek tersebut dapat disusun sebanyak:

$$
r!
$$

cara.

---

## Contoh 1

Dari 6 siswa akan dipilih 3 siswa.

### Jika hanya sebagai anggota tim

Urutan tidak berpengaruh.

Gunakan:

$$
{}_6C_3
$$

Maka:

$$
{}_6C_3=20
$$

---

### Jika dipilih sebagai Ketua, Sekretaris, dan Bendahara

Urutan berpengaruh karena setiap jabatan berbeda.

Gunakan:

$$
{}_6P_3
$$

Maka:

$$
{}_6P_3=120
$$

Perhatikan:

$$
120=20\times3!
$$

---

# Jangan Bergantung pada Kata "Memilih"

Salah satu kesalahan yang sering terjadi adalah menganggap:

> jika ada kata "memilih", maka selalu menggunakan kombinasi.

Hal tersebut tidak selalu benar.

Perhatikan dua contoh berikut.

---

## Contoh 2

Dari 8 siswa akan dipilih 3 siswa sebagai anggota kelompok.

Karena ketiganya memiliki kedudukan yang sama:

$$
\boxed{\text{Kombinasi}}
$$

---

## Contoh 3

Dari 8 siswa akan dipilih seorang ketua, wakil ketua, dan sekretaris.

Walaupun soal menggunakan kata **dipilih**, setiap posisi berbeda.

Maka:

$$
\boxed{\text{Permutasi}}
$$

---

> [!important]
> Jangan menentukan metode hanya berdasarkan kata yang digunakan dalam soal.
>
> Perhatikan **peran objek setelah dipilih**.

---

# Pertanyaan Kunci

Untuk menentukan apakah suatu soal menggunakan permutasi atau kombinasi, gunakan pertanyaan berikut:

> Jika dua objek yang sudah dipilih bertukar posisi, apakah hasilnya menjadi berbeda?

Jika jawabannya:

$$
\boxed{\text{Ya}}
$$

gunakan permutasi.

Jika jawabannya:

$$
\boxed{\text{Tidak}}
$$

gunakan kombinasi.

---

# Contoh 4

Dari 10 peserta akan ditentukan juara 1, juara 2, dan juara 3.

Jika:

$$
A,B,C
$$

berarti:

- $A$ juara 1,
- $B$ juara 2,
- $C$ juara 3.

Susunan:

$$
B,A,C
$$

memberikan hasil berbeda.

Maka urutan berpengaruh.

Gunakan:

$$
{}_{10}P_3
$$

---

# Contoh 5

Dari 10 peserta akan dipilih 3 orang untuk mengikuti pelatihan.

Kelompok:

$$
A,B,C
$$

sama dengan:

$$
C,B,A
$$

karena ketiganya hanya menjadi peserta pelatihan.

Maka urutan tidak berpengaruh.

Gunakan:

$$
{}_{10}C_3
$$

---

# Permutasi dan Kombinasi dalam Satu Soal

Dalam beberapa permasalahan, permutasi dan kombinasi dapat muncul dalam satu proses.

---

## Contoh 6

Dari 8 siswa akan dipilih 4 siswa sebagai pengurus.

Dari 4 siswa tersebut kemudian ditentukan:

- 1 ketua,
- 1 sekretaris.

### Langkah 1: Memilih 4 Pengurus

Karena pada tahap ini kita hanya memilih anggota:

$$
{}_8C_4
$$

### Langkah 2: Menentukan Ketua dan Sekretaris

Dari 4 siswa terpilih, akan dipilih 2 siswa untuk jabatan berbeda.

Gunakan:

$$
{}_4P_2
$$

Maka:

$$
{}_8C_4\times{}_4P_2
$$

atau:

$$
70\times12
$$

sehingga:

$$
\boxed{840}
$$

kemungkinan.

---

# Membandingkan Hasil Permutasi dan Kombinasi

Untuk nilai $n$ dan $r$ yang sama:

$$
{}_nP_r
$$

selalu lebih besar atau sama dengan:

$$
{}_nC_r
$$

karena dalam permutasi, satu kelompok yang sama dapat menghasilkan beberapa susunan berbeda.

---

## Contoh 7

Dari 5 objek dipilih 3.

Permutasi:

$$
{}_5P_3
=
5\times4\times3
=
60
$$

Kombinasi:

$$
{}_5C_3
=
10
$$

Hubungannya:

$$
60=10\times3!
$$

---

# Kasus yang Sering Membingungkan

## 1. Memilih Anggota Tim

Urutan tidak berpengaruh.

$$
\boxed{\text{Kombinasi}}
$$

---

## 2. Menentukan Jabatan

Posisi berbeda.

$$
\boxed{\text{Permutasi}}
$$

---

## 3. Menentukan Juara

Urutan juara berbeda.

$$
\boxed{\text{Permutasi}}
$$

---

## 4. Memilih Buku untuk Dibawa

Urutan pemilihan tidak berpengaruh.

$$
\boxed{\text{Kombinasi}}
$$

---

## 5. Menyusun Buku pada Rak

Posisi buku berbeda.

$$
\boxed{\text{Permutasi}}
$$

---

## 6. Memilih Soal untuk Dikerjakan

Jika siswa hanya menentukan soal mana yang dikerjakan tanpa memperhatikan urutan pengerjaan:

$$
\boxed{\text{Kombinasi}}
$$

---

## 7. Membuat Bilangan atau Kode

Posisi setiap digit atau simbol berpengaruh.

$$
\boxed{\text{Permutasi atau aturan perkalian}}
$$

---

## 8. Memilih Titik untuk Membentuk Segitiga

Urutan titik tidak berpengaruh.

$$
\boxed{\text{Kombinasi}}
$$

---

# Diagram Keputusan

Gunakan alur berikut saat menghadapi soal.

```text
Apakah terdapat proses memilih atau menyusun objek?
                    │
                    ▼
       Apakah urutan/posisi berpengaruh?
               /                 \
             YA                  TIDAK
             │                     │
             ▼                     ▼
        PERMUTASI              KOMBINASI
```

Jika terdapat pembatasan, analisis syarat tersebut setelah menentukan jenis pencacahannya.

---

# Strategi Menentukan Metode

Sebelum menggunakan rumus, lakukan langkah berikut.

### Langkah 1

Tentukan objek yang tersedia.

### Langkah 2

Tentukan berapa banyak objek yang akan digunakan.

### Langkah 3

Perhatikan peran objek setelah dipilih.

### Langkah 4

Bayangkan dua objek bertukar posisi.

### Langkah 5

Tanyakan:

> Apakah hasil akhirnya berubah?

Jika ya:

$$
\boxed{\text{Permutasi}}
$$

Jika tidak:

$$
\boxed{\text{Kombinasi}}
$$

---

# Soal Latihan

## Soal 1

Dari 8 siswa akan dipilih 3 siswa sebagai perwakilan kelas.

Tentukan apakah digunakan permutasi atau kombinasi, kemudian hitung banyak kelompok yang dapat dibentuk.

> [!success]- Klik untuk Lihat Jawaban
> Ketiga siswa memiliki kedudukan yang sama sebagai perwakilan kelas.
>
> Jika urutan ketiga siswa ditukar, kelompoknya tetap sama.
>
> Maka digunakan **kombinasi**.
>
> $$
> \begin{aligned}
> {}_8C_3
> &=
> \frac{8!}{3!5!}\\
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

## Soal 2

Dari 8 siswa akan dipilih seorang ketua, seorang sekretaris, dan seorang bendahara.

Tentukan apakah digunakan permutasi atau kombinasi, kemudian hitung banyak susunan yang dapat dibentuk.

> [!success]- Klik untuk Lihat Jawaban
> Ketua, sekretaris, dan bendahara merupakan jabatan yang berbeda.
>
> Jika dua siswa bertukar jabatan, hasilnya berubah.
>
> Maka digunakan **permutasi**.
>
> $$
> \begin{aligned}
> {}_8P_3
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

Dari 10 buku berbeda akan dipilih 4 buku untuk dibawa dalam perjalanan.

Berapa banyak pilihan yang dapat dibuat?

> [!success]- Klik untuk Lihat Jawaban
> Kita hanya menentukan buku mana yang dipilih.
>
> Urutan buku tidak berpengaruh.
>
> Maka digunakan kombinasi:
>
> $$
> \begin{aligned}
> {}_{10}C_4
> &=210
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{210}
> $$
>
> pilihan dapat dibuat.

---

## Soal 4

Dari 10 peserta lomba akan ditentukan juara 1, juara 2, juara 3, dan juara harapan 1.

Berapa banyak kemungkinan susunan pemenang?

> [!success]- Klik untuk Lihat Jawaban
> Setiap posisi berbeda.
>
> Jika peserta bertukar posisi, hasilnya berubah.
>
> Maka digunakan permutasi.
>
> $$
> \begin{aligned}
> {}_{10}P_4
> &=
> 10\times9\times8\times7\\
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
> susunan pemenang dapat dibentuk.

---

## Soal 5

Terdapat 9 titik berbeda dan tidak ada 3 titik yang segaris.

Berapa banyak segitiga yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Sebuah segitiga dibentuk dengan memilih 3 titik.
>
> Urutan ketiga titik tidak menghasilkan segitiga baru.
>
> Maka digunakan kombinasi.
>
> $$
> \begin{aligned}
> {}_9C_3
> &=
> \frac{9\times8\times7}{3\times2\times1}\\
> &=84
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{84}
> $$
>
> segitiga dapat dibentuk.

---

## Soal 6

Dari 12 siswa akan dipilih 5 siswa sebagai pengurus kelas.

Dari 5 siswa tersebut akan ditentukan seorang ketua dan seorang wakil ketua.

Berapa banyak kemungkinan yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Soal terdiri atas dua tahap.
>
> ### Tahap 1: Memilih 5 Siswa
>
> Urutan tidak berpengaruh.
>
> Gunakan kombinasi:
>
> $$
> {}_{12}C_5
> $$
>
> $$
> {}_{12}C_5=792
> $$
>
> ### Tahap 2: Menentukan Ketua dan Wakil
>
> Dari 5 siswa terpilih, ketua dan wakil merupakan posisi berbeda.
>
> Gunakan permutasi:
>
> $$
> {}_5P_2
> $$
>
> $$
> {}_5P_2=20
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> n
> &=792\times20\\
> &=15840
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{15840}
> $$
>
> kemungkinan dapat dibentuk.

---

## Soal 7

Dalam sebuah kelas terdapat 7 siswa laki-laki dan 6 siswa perempuan.

Akan dipilih 4 siswa untuk mengikuti lomba dengan syarat tepat 2 siswa laki-laki dan 2 siswa perempuan.

Tentukan metode yang digunakan dan hitung banyak kelompok yang dapat dibentuk.

> [!success]- Klik untuk Lihat Jawaban
> Siswa hanya dipilih sebagai anggota kelompok.
>
> Urutan tidak berpengaruh.
>
> Maka digunakan kombinasi.
>
> Pilih 2 siswa laki-laki:
>
> $$
> {}_7C_2=21
> $$
>
> Pilih 2 siswa perempuan:
>
> $$
> {}_6C_2=15
> $$
>
> Karena kedua pemilihan harus dilakukan:
>
> $$
> \begin{aligned}
> n
> &=21\times15\\
> &=315
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{315}
> $$
>
> kelompok dapat dibentuk.

---

## Soal 8

Dari 10 siswa akan dipilih 4 siswa sebagai tim inti.

Dari 4 siswa tersebut kemudian akan ditentukan:

- seorang ketua,
- seorang wakil ketua,
- dua siswa lainnya sebagai anggota.

Tentukan banyak kemungkinan yang dapat dibentuk.

> [!success]- Klik untuk Lihat Jawaban
> Soal terdiri atas dua bagian.
>
> ### Langkah 1: Memilih Tim Inti
>
> Pilih 4 siswa dari 10.
>
> Karena pada tahap ini urutan tidak berpengaruh:
>
> $$
> {}_{10}C_4
> $$
>
> $$
> {}_{10}C_4=210
> $$
>
> ### Langkah 2: Menentukan Ketua dan Wakil
>
> Dari 4 siswa terpilih, dipilih:
>
> - 1 ketua,
> - 1 wakil.
>
> Kedua posisi berbeda.
>
> Maka digunakan permutasi:
>
> $$
> {}_4P_2
> $$
>
> $$
> {}_4P_2=12
> $$
>
> Dua siswa yang tersisa otomatis menjadi anggota.
>
> Maka:
>
> $$
> \begin{aligned}
> n
> &=210\times12\\
> &=2520
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{2520}
> $$
>
> kemungkinan dapat dibentuk.

---

# Rangkuman

Permutasi dan kombinasi sama-sama digunakan dalam pencacahan.

Perbedaannya adalah:

### Permutasi

Urutan diperhatikan.

$$
AB\neq BA
$$

Rumus:

$$
\boxed{
{}_nP_r=
\frac{n!}{(n-r)!}
}
$$

### Kombinasi

Urutan tidak diperhatikan.

$$
AB=BA
$$

Rumus:

$$
\boxed{
{}_nC_r=
\frac{n!}{r!(n-r)!}
}
$$

Hubungan keduanya:

$$
\boxed{
{}_nP_r={}_nC_r\times r!
}
$$

Dalam satu soal, kombinasi dan permutasi dapat digunakan secara bersamaan jika terdapat beberapa tahap dengan karakter yang berbeda.

---

> [!important]
> Gunakan pertanyaan berikut sebelum memilih rumus:
>
> **Jika objek yang sudah dipilih bertukar posisi, apakah hasil akhirnya berubah?**
>
> Jika:
>
> $$
> \boxed{\text{berubah}}
> $$
>
> gunakan permutasi.
>
> Jika:
>
> $$
> \boxed{\text{tidak berubah}}
> $$
>
> gunakan kombinasi.

---

# Inti Materi

Jangan menghafal:

> "menyusun = permutasi"

atau:

> "memilih = kombinasi"

Kedua cara tersebut dapat menyebabkan kesalahan.

Fokus pada struktur hasil akhirnya.

$$
\boxed{
\text{Urutan penting}
\Rightarrow
\text{Permutasi}
}
$$

$$
\boxed{
\text{Urutan tidak penting}
\Rightarrow
\text{Kombinasi}
}
$$

Kemampuan membedakan keduanya sangat penting karena pada materi peluang berikutnya, siswa akan sering menentukan $n(S)$ dan $n(A)$ menggunakan permutasi atau kombinasi.

---

## Konsep Terkait

- [[Kaidah Pencacahan dan Peluang/03 - Permutasi]]
- [[Kaidah Pencacahan dan Peluang/04 - Kombinasi]]
- [[Kaidah Pencacahan dan Peluang/06 - Konsep Dasar Peluang]]
- [[Kaidah Pencacahan dan Peluang/11 - Penerapan Kaidah Pencacahan dalam Peluang]]