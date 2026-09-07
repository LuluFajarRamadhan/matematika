# Konsep Dasar Pencacahan

Dalam berbagai situasi, kita sering ingin mengetahui **berapa banyak kemungkinan yang dapat terjadi**.

Contohnya:

- berapa banyak pasangan pakaian yang dapat dipilih,
- berapa banyak rute perjalanan yang tersedia,
- berapa banyak kode yang dapat dibuat,
- berapa banyak pilihan makanan yang tersedia,
- berapa banyak susunan yang mungkin terbentuk.

Jika jumlah kemungkinan masih sedikit, kita dapat menuliskan seluruh kemungkinan satu per satu. Namun, ketika jumlahnya semakin banyak, cara tersebut menjadi tidak praktis.

Untuk itu, digunakan **kaidah pencacahan**, yaitu cara menentukan banyaknya kemungkinan tanpa harus selalu menuliskan semua kemungkinan tersebut.

---

# Mendaftar Seluruh Kemungkinan

Cara paling sederhana untuk melakukan pencacahan adalah dengan menuliskan seluruh hasil yang mungkin.

## Contoh 1

Dina mempunyai:

- 2 baju, yaitu merah $(M)$ dan putih $(P)$,
- 2 celana, yaitu hitam $(H)$ dan biru $(B)$.

Pasangan pakaian yang dapat digunakan adalah:

$$
(M,H)
$$

$$
(M,B)
$$

$$
(P,H)
$$

$$
(P,B)
$$

Jadi, terdapat:

$$
\boxed{4}
$$

pasangan pakaian.

Cara ini mudah dilakukan karena jumlah kemungkinannya masih sedikit.

Namun, jika tersedia 10 baju dan 8 celana, menuliskan semua pasangan satu per satu tentu membutuhkan waktu lebih lama.

---

# Diagram Pohon

**Diagram pohon** digunakan untuk menggambarkan pilihan yang terjadi secara bertahap.

Misalnya, Dina mempunyai:

- 2 baju, yaitu merah $(M)$ dan putih $(P)$,
- 3 celana, yaitu hitam $(H)$, biru $(B)$, dan abu-abu $(A)$.

Kemungkinan pilihan dapat digambarkan sebagai berikut.

```text
                 ┌── H → (M,H)
        ┌── M ───┼── B → (M,B)
        │        └── A → (M,A)
Mulai ──┤
        │        ┌── H → (P,H)
        └── P ───┼── B → (P,B)
                 └── A → (P,A)
```

Dari diagram tersebut diperoleh:

$$
6
$$

kemungkinan pasangan pakaian.

Diagram pohon membantu kita melihat bahwa setiap pilihan pada tahap pertama dapat dipasangkan dengan setiap pilihan pada tahap berikutnya.

---

# Tabel Kemungkinan

Kemungkinan juga dapat disajikan menggunakan tabel.

Dengan contoh yang sama:

| Baju | Hitam | Biru | Abu-abu |
|---|---|---|---|
| Merah | $(M,H)$ | $(M,B)$ | $(M,A)$ |
| Putih | $(P,H)$ | $(P,B)$ | $(P,A)$ |

Dari tabel terlihat bahwa terdapat:

$$
6
$$

pasangan.

Banyaknya kemungkinan tersebut juga dapat dihitung dengan:

$$
2\times3=6
$$

---

> [!note]
> Diagram pohon dan tabel sangat membantu ketika kita baru mempelajari pencacahan.
>
> Setelah memahami polanya, banyak kemungkinan dapat dihitung lebih cepat menggunakan **aturan penjumlahan** dan **aturan perkalian**.

---

# Aturan Penjumlahan

Aturan penjumlahan digunakan ketika suatu pilihan dapat dilakukan melalui beberapa **alternatif yang berbeda**.

Jika suatu kegiatan dapat dilakukan dengan:

- $m$ cara melalui alternatif pertama,
- $n$ cara melalui alternatif kedua,

dan kedua alternatif tersebut tidak dilakukan secara bersamaan, maka banyak kemungkinan seluruhnya adalah:

$$
m+n
$$

---

## Contoh 2

Sebuah perpustakaan menyediakan:

- 5 novel,
- 4 buku sejarah.

Seorang siswa ingin meminjam **satu buku**, yaitu sebuah novel **atau** sebuah buku sejarah.

Banyak pilihan yang tersedia adalah:

$$
5+4=9
$$

Jadi:

$$
\boxed{9}
$$

buku dapat dipilih.

---

## Contoh 3

Untuk menuju suatu tempat, Andi dapat menggunakan:

- 3 rute bus, atau
- 2 rute kereta.

Jika Andi hanya memilih salah satu jenis perjalanan, maka banyak pilihan rute adalah:

$$
3+2=5
$$

Jadi:

$$
\boxed{5}
$$

rute dapat dipilih.

---

> [!important]
> Aturan penjumlahan biasanya digunakan ketika kita memilih **salah satu dari beberapa alternatif**.
>
> Bentuk sederhananya:
>
> $$
> \boxed{\text{Pilihan A atau Pilihan B}}
> $$
>
> Namun, jangan hanya bergantung pada kata **atau**. Perhatikan hubungan antarpilihan dalam masalah.

---

# Aturan Perkalian

Aturan perkalian digunakan jika suatu kegiatan terdiri atas beberapa **tahap yang dilakukan secara berurutan**.

Jika:

- tahap pertama dapat dilakukan dengan $m$ cara,
- tahap kedua dapat dilakukan dengan $n$ cara,

maka seluruh kegiatan dapat dilakukan dengan:

$$
m\times n
$$

cara.

Secara umum, jika terdapat $k$ tahap dengan banyak pilihan:

$$
n_1,n_2,n_3,\ldots,n_k
$$

maka banyak seluruh kemungkinan adalah:

$$
n_1\times n_2\times n_3\times\cdots\times n_k
$$

---

## Contoh 4

Sebuah rumah makan menyediakan:

- 3 pilihan makanan,
- 4 pilihan minuman.

Jika seorang pelanggan memilih satu makanan dan satu minuman, maka terdapat dua tahap:

1. memilih makanan,
2. memilih minuman.

Banyak paket yang dapat dibuat adalah:

$$
3\times4=12
$$

Jadi:

$$
\boxed{12}
$$

paket berbeda dapat dibuat.

---

# Mengapa Menggunakan Perkalian?

Misalkan pilihan makanan adalah:

$$
A,B,C
$$

sedangkan pilihan minuman adalah:

$$
1,2,3,4
$$

Untuk makanan $A$, terdapat:

$$
A1,A2,A3,A4
$$

yaitu 4 kemungkinan.

Untuk makanan $B$, juga terdapat 4 kemungkinan.

Untuk makanan $C$, juga terdapat 4 kemungkinan.

Jadi:

$$
4+4+4=12
$$

Karena terdapat 3 kelompok yang masing-masing mempunyai 4 kemungkinan, perhitungan dapat ditulis lebih sederhana sebagai:

$$
3\times4=12
$$

Inilah ide dasar dari aturan perkalian.

---

> [!important]
> Aturan perkalian digunakan ketika suatu proses terdiri atas **beberapa tahap**.
>
> Bentuk sederhananya:
>
> $$
> \boxed{\text{Tahap 1 dan Tahap 2}}
> $$

---

# Membedakan Aturan Penjumlahan dan Aturan Perkalian

Perbedaan utama kedua aturan tersebut terletak pada struktur masalah.

## Aturan Penjumlahan

Digunakan ketika kita memilih **salah satu alternatif**.

$$
\boxed{\text{Alternatif A atau Alternatif B}}
$$

Banyak kemungkinan:

$$
n(A)+n(B)
$$

---

## Aturan Perkalian

Digunakan ketika suatu kegiatan terdiri atas **beberapa tahap**.

$$
\boxed{\text{Tahap A kemudian Tahap B}}
$$

Banyak kemungkinan:

$$
n(A)\times n(B)
$$

---

## Contoh 5

Sebuah kantin menyediakan:

- 4 jenis nasi,
- 3 jenis mi,
- 5 jenis minuman.

### Kasus 1

Seorang siswa ingin membeli **satu makanan**, yaitu nasi atau mi.

Banyak pilihan makanan:

$$
4+3=7
$$

Digunakan aturan penjumlahan.

### Kasus 2

Seorang siswa ingin membeli **satu makanan dan satu minuman**.

Banyak pilihan makanan:

$$
4+3=7
$$

Terdapat 5 pilihan minuman.

Maka:

$$
7\times5=35
$$

Jadi:

$$
\boxed{35}
$$

paket dapat dibuat.

Pada contoh ini, aturan penjumlahan dan aturan perkalian digunakan dalam satu permasalahan.

---

# Pencacahan dengan Beberapa Tahap

Aturan perkalian tidak terbatas pada dua tahap.

Misalnya, sebuah kode terdiri atas:

- 1 huruf,
- diikuti 2 angka.

Huruf dapat dipilih dari:

$$
A,B,C
$$

sedangkan setiap angka dapat dipilih dari:

$$
0,1,2,3,4
$$

Jika angka boleh berulang, maka:

- posisi pertama memiliki 3 pilihan,
- posisi kedua memiliki 5 pilihan,
- posisi ketiga memiliki 5 pilihan.

Banyak kode yang dapat dibuat:

$$
3\times5\times5=75
$$

Jadi:

$$
\boxed{75}
$$

kode dapat dibuat.

---

# Pencacahan dengan Pembatasan

Dalam beberapa masalah, jumlah pilihan pada setiap tahap tidak selalu sama.

Hal ini dapat terjadi karena:

- suatu objek sudah digunakan,
- suatu angka tidak boleh berada pada posisi tertentu,
- terdapat syarat khusus,
- pengulangan tidak diperbolehkan.

---

## Contoh 6

Dari angka:

$$
1,2,3,4
$$

akan dibentuk bilangan 3 digit tanpa pengulangan angka.

Untuk digit pertama tersedia:

$$
4
$$

pilihan.

Setelah satu angka digunakan, digit kedua hanya memiliki:

$$
3
$$

pilihan.

Digit ketiga kemudian memiliki:

$$
2
$$

pilihan.

Maka:

$$
4\times3\times2=24
$$

Jadi:

$$
\boxed{24}
$$

bilangan dapat dibentuk.

---

## Contoh 7

Dari angka:

$$
0,1,2,3,4
$$

akan dibentuk bilangan 3 digit tanpa pengulangan.

Digit pertama **tidak boleh 0**, karena jika digit pertama 0 maka bilangan tersebut bukan bilangan 3 digit.

Maka:

- digit pertama memiliki 4 pilihan,
- digit kedua memiliki 4 pilihan,
- digit ketiga memiliki 3 pilihan.

Sehingga:

$$
4\times4\times3=48
$$

Jadi:

$$
\boxed{48}
$$

bilangan dapat dibentuk.

---

> [!note]
> Dalam soal dengan pembatasan, jangan langsung mengalikan jumlah seluruh pilihan.
>
> Tentukan banyak pilihan yang tersedia **pada setiap posisi atau tahap** setelah memperhatikan syarat soal.

---

# Strategi Menyelesaikan Masalah Pencacahan

Sebelum menghitung, lakukan langkah berikut.

### Langkah 1

Tentukan apa yang ingin dihitung.

### Langkah 2

Identifikasi apakah masalah terdiri atas:

- beberapa alternatif, atau
- beberapa tahap.

### Langkah 3

Perhatikan apakah terdapat syarat atau pembatasan.

### Langkah 4

Tentukan banyak pilihan pada setiap alternatif atau tahap.

### Langkah 5

Gunakan:

$$
\boxed{\text{penjumlahan}}
$$

untuk beberapa alternatif, atau:

$$
\boxed{\text{perkalian}}
$$

untuk beberapa tahap.

---

# Soal Latihan

## Soal 1

Sebuah toko menyediakan 7 jenis buku tulis dan 5 jenis buku gambar.

Rani ingin membeli tepat satu buku, yaitu buku tulis atau buku gambar.

Berapa banyak pilihan buku yang tersedia?

> [!success]- Klik untuk Lihat Jawaban
> Karena Rani memilih **buku tulis atau buku gambar**, digunakan aturan penjumlahan.
>
> $$
> 7+5=12
> $$
>
> Jadi, terdapat:
>
> $$
> \boxed{12}
> $$
>
> pilihan buku.

---

## Soal 2

Sebuah kantin menyediakan:

- 5 pilihan makanan,
- 4 pilihan minuman.

Jika seorang siswa memilih satu makanan dan satu minuman, tentukan banyak paket yang dapat dibuat.

> [!success]- Klik untuk Lihat Jawaban
> Pemilihan terdiri atas dua tahap.
>
> Tahap pertama memilih makanan:
>
> $$
> 5
> $$
>
> pilihan.
>
> Tahap kedua memilih minuman:
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
> 5\times4=20
> $$
>
> Jadi:
>
> $$
> \boxed{20}
> $$
>
> paket dapat dibuat.

---

## Soal 3

Untuk melakukan perjalanan dari kota $A$ ke kota $C$, seseorang harus melalui kota $B$.

Terdapat:

- 4 jalan dari $A$ ke $B$,
- 5 jalan dari $B$ ke $C$.

Berapa banyak rute perjalanan dari $A$ ke $C$ melalui $B$?

> [!success]- Klik untuk Lihat Jawaban
> Perjalanan dilakukan dalam dua tahap:
>
> $$
> A\rightarrow B
> $$
>
> dan:
>
> $$
> B\rightarrow C
> $$
>
> Maka:
>
> $$
> 4\times5=20
> $$
>
> Jadi:
>
> $$
> \boxed{20}
> $$
>
> rute perjalanan dapat dipilih.

---

## Soal 4

Sebuah restoran menyediakan:

- 5 jenis nasi,
- 3 jenis mi,
- 4 jenis minuman.

Seorang pelanggan memilih satu makanan, yaitu nasi atau mi, kemudian memilih satu minuman.

Berapa banyak paket berbeda yang dapat dibuat?

> [!success]- Klik untuk Lihat Jawaban
> **Langkah 1: Menentukan pilihan makanan.**
>
> Pelanggan dapat memilih nasi atau mi.
>
> $$
> 5+3=8
> $$
>
> Jadi, terdapat 8 pilihan makanan.
>
> **Langkah 2: Memilih minuman.**
>
> Terdapat:
>
> $$
> 4
> $$
>
> pilihan minuman.
>
> Maka:
>
> $$
> 8\times4=32
> $$
>
> Jadi:
>
> $$
> \boxed{32}
> $$
>
> paket dapat dibuat.

---

## Soal 5

Sebuah kode terdiri atas 2 huruf yang diikuti oleh 3 angka.

Huruf dapat dipilih dari:

$$
A,B,C,D
$$

sedangkan angka dapat dipilih dari:

$$
0,1,2,3,4
$$

Jika huruf dan angka boleh digunakan berulang, berapa banyak kode yang dapat dibuat?

> [!success]- Klik untuk Lihat Jawaban
> Kode mempunyai lima posisi:
>
> $$
> \boxed{H_1}
> \boxed{H_2}
> \boxed{A_1}
> \boxed{A_2}
> \boxed{A_3}
> $$
>
> Banyak pilihan pada setiap posisi adalah:
>
> $$
> 4,\ 4,\ 5,\ 5,\ 5
> $$
>
> Maka:
>
> $$
> \begin{aligned}
> n
> &=4\times4\times5\times5\times5\\
> &=2000
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{2000}
> $$
>
> kode dapat dibuat.

---

## Soal 6

Dari angka:

$$
1,2,3,4,5,6
$$

akan dibentuk bilangan tiga digit tanpa pengulangan angka.

Berapa banyak bilangan yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Digit pertama mempunyai:
>
> $$
> 6
> $$
>
> pilihan.
>
> Setelah satu angka digunakan, digit kedua mempunyai:
>
> $$
> 5
> $$
>
> pilihan.
>
> Digit ketiga mempunyai:
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
> 6\times5\times4=120
> $$
>
> Jadi:
>
> $$
> \boxed{120}
> $$
>
> bilangan dapat dibentuk.

---

## Soal 7

Dari angka:

$$
0,1,2,3,4,5,6
$$

akan dibentuk bilangan 4 digit tanpa pengulangan angka.

Berapa banyak bilangan yang dapat dibentuk?

> [!success]- Klik untuk Lihat Jawaban
> Digit pertama tidak boleh 0.
>
> Maka digit pertama mempunyai:
>
> $$
> 6
> $$
>
> pilihan, yaitu:
>
> $$
> 1,2,3,4,5,6
> $$
>
> Setelah digit pertama dipilih, masih terdapat 6 angka yang dapat digunakan untuk digit kedua, termasuk angka 0.
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
> n
> &=6\times6\times5\times4\\
> &=720
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{720}
> $$
>
> bilangan dapat dibentuk.

---

## Soal 8

Dari angka:

$$
0,1,2,3,4,5,6,7
$$

akan dibentuk bilangan 4 digit tanpa pengulangan angka.

Tentukan banyak bilangan yang dapat dibentuk jika bilangan tersebut harus **genap**.

> [!success]- Klik untuk Lihat Jawaban
> Karena bilangan harus genap, digit terakhir harus merupakan:
>
> $$
> 0,2,4,6
> $$
>
> Namun, angka 0 membutuhkan perhatian khusus karena digit pertama tidak boleh 0.
>
> Kita bagi menjadi dua kasus.
>
> ### Kasus 1: Digit terakhir adalah 0
>
> Digit terakhir sudah ditentukan:
>
> $$
> 1
> $$
>
> cara.
>
> Digit pertama dapat dipilih dari:
>
> $$
> 1,2,3,4,5,6,7
> $$
>
> sehingga terdapat:
>
> $$
> 7
> $$
>
> pilihan.
>
> Digit kedua mempunyai:
>
> $$
> 6
> $$
>
> pilihan.
>
> Digit ketiga mempunyai:
>
> $$
> 5
> $$
>
> pilihan.
>
> Banyak bilangan:
>
> $$
> 7\times6\times5=210
> $$
>
> ### Kasus 2: Digit terakhir adalah 2, 4, atau 6
>
> Digit terakhir mempunyai:
>
> $$
> 3
> $$
>
> pilihan.
>
> Setelah digit terakhir dipilih, digit pertama tidak boleh 0 dan tidak boleh sama dengan digit terakhir.
>
> Dari angka 1 sampai 7, tersisa:
>
> $$
> 6
> $$
>
> pilihan untuk digit pertama.
>
> Digit kedua mempunyai:
>
> $$
> 6
> $$
>
> pilihan.
>
> Digit ketiga mempunyai:
>
> $$
> 5
> $$
>
> pilihan.
>
> Maka:
>
> $$
> 3\times6\times6\times5=540
> $$
>
> Jumlah seluruh bilangan:
>
> $$
> \begin{aligned}
> n
> &=210+540\\
> &=750
> \end{aligned}
> $$
>
> Jadi:
>
> $$
> \boxed{750}
> $$
>
> bilangan genap 4 digit dapat dibentuk.

---

# Rangkuman

Kaidah pencacahan digunakan untuk menentukan banyak kemungkinan yang dapat terjadi.

Jika seluruh kemungkinan masih sedikit, pencacahan dapat dilakukan menggunakan:

- daftar kemungkinan,
- diagram pohon,
- tabel kemungkinan.

Jika terdapat beberapa alternatif yang dipilih salah satu, digunakan **aturan penjumlahan**:

$$
n=n_1+n_2+\cdots+n_k
$$

Jika suatu kegiatan terdiri atas beberapa tahap, digunakan **aturan perkalian**:

$$
n=n_1\times n_2\times\cdots\times n_k
$$

Jika terdapat syarat atau pembatasan, banyak pilihan pada setiap tahap harus dihitung setelah memperhatikan syarat tersebut.

---

> [!important]
> Sebelum menggunakan rumus, tanyakan:
>
> 1. Apa yang ingin dihitung?
> 2. Apakah terdapat beberapa alternatif?
> 3. Apakah terdapat beberapa tahap?
> 4. Apakah objek boleh digunakan kembali?
> 5. Apakah terdapat syarat pada posisi tertentu?
>
> Setelah struktur masalah dipahami, barulah tentukan cara pencacahan yang sesuai.

---

## Konsep Terkait

- [[Materi Baru Kaidah Pencacahan dan Peluang/00 - Peta Konsep Kaidah Pencacahan dan Teori Peluang Lanjutan]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/02 - Faktorial]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/03 - Permutasi]]
- [[Materi Baru Kaidah Pencacahan dan Peluang/04 - Kombinasi]]