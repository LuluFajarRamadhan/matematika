---
title:
---
# Pengantar Kombinatorika dan Teori Peluang

Dalam kehidupan sehari-hari, kita sering menghadapi dua pertanyaan yang berkaitan erat.

1. **Ada berapa banyak kemungkinan yang dapat terjadi?**
2. **Seberapa besar kemungkinan suatu kejadian akan terjadi?**

Pertanyaan pertama dipelajari melalui **kaidah pencacahan atau kombinatorika**, sedangkan pertanyaan kedua dipelajari melalui **teori peluang**.

Kaidah pencacahan membantu kita menentukan banyaknya kemungkinan tanpa harus menuliskan seluruh kemungkinan satu per satu. Konsep ini kemudian menjadi dasar untuk menghitung peluang pada situasi yang memiliki ruang sampel cukup besar.

Sebagai contoh, ketika memilih 3 siswa dari 20 siswa, kita tentu dapat mencoba menuliskan seluruh kemungkinan kelompok yang terbentuk. Namun, cara tersebut tidak praktis. Dengan menggunakan kombinasi, banyaknya kemungkinan dapat dihitung secara langsung.

Begitu juga dalam peluang. Untuk menentukan peluang terpilihnya kelompok dengan kriteria tertentu, kita perlu mengetahui:

$$
\text{banyak kemungkinan yang memenuhi kejadian}
$$

dan:

$$
\text{banyak seluruh kemungkinan yang dapat terjadi}
$$

Hubungan tersebut menjadi dasar dari rumus:

$$
P(A)=\frac{n(A)}{n(S)}
$$

Oleh karena itu, kaidah pencacahan dan teori peluang merupakan dua konsep yang saling berkaitan.

---

## Aplikasi Kaidah Pencacahan dan Peluang dalam Kehidupan

### 1. Penyusunan Jadwal dan Pemilihan

Kaidah pencacahan dapat digunakan untuk menentukan banyaknya cara dalam menyusun atau memilih sesuatu.

Contohnya:

- menentukan banyak susunan tempat duduk,
- menyusun jadwal kegiatan,
- memilih anggota suatu tim,
- menentukan urutan peserta,
- memilih beberapa orang dari suatu kelompok.

Masalah seperti ini dapat diselesaikan menggunakan aturan perkalian, permutasi, atau kombinasi.

### 2. Teknologi dan Keamanan Digital

Konsep pencacahan digunakan untuk menghitung banyak kemungkinan kata sandi, kode keamanan, atau PIN.

Misalnya, sebuah PIN terdiri atas 6 digit angka. Banyak kemungkinan PIN dapat dihitung menggunakan aturan perkalian.

Semakin banyak kemungkinan yang tersedia, semakin sulit suatu kode ditebak dengan mencoba seluruh kemungkinan.

### 3. Permainan dan Undian

Teori peluang banyak digunakan dalam permainan yang melibatkan unsur acak.

Contohnya:

- pelemparan koin,
- pelemparan dadu,
- pengambilan kartu,
- undian,
- permainan papan.

Peluang dapat digunakan untuk menentukan seberapa besar kemungkinan suatu hasil tertentu terjadi.

### 4. Pengambilan Keputusan

Peluang juga digunakan untuk memperkirakan risiko dan membuat keputusan berdasarkan kemungkinan suatu kejadian.

Contohnya:

- memperkirakan risiko kerugian,
- menentukan kemungkinan keberhasilan suatu strategi,
- menganalisis hasil survei,
- memperkirakan peluang terjadinya suatu peristiwa.

Dengan memahami peluang, suatu keputusan dapat dibuat berdasarkan perhitungan yang lebih terukur.

---

# Peta Konsep Kaidah Pencacahan dan Peluang

## Bagian 1: Kaidah Pencacahan

### 01. Konsep Dasar Pencacahan

- Mengapa pencacahan diperlukan
- Mendaftar kemungkinan
- Diagram pohon
- Tabel kemungkinan
- Aturan penjumlahan
- Aturan perkalian

[[Materi Baru Kaidah Pencacahan dan Peluang/01 - Konsep Dasar Pencacahan]]


### 02. Faktorial

- Pengertian faktorial
- Notasi $n!$
- Sifat-sifat faktorial
- Penyederhanaan bentuk faktorial
- Hubungan faktorial dengan pencacahan

[[Materi Baru Kaidah Pencacahan dan Peluang/02 - Faktorial]]


### 03. Permutasi

Permutasi digunakan ketika **urutan objek diperhatikan**.

Materi meliputi:

- permutasi seluruh unsur,
- permutasi sebagian unsur,
- permutasi dengan beberapa unsur sama,
- permutasi siklis.

Rumus dasar:

$$
{}_nP_r=\frac{n!}{(n-r)!}
$$

[[Materi Baru Kaidah Pencacahan dan Peluang/03 - Permutasi]]


### 04. Kombinasi

Kombinasi digunakan ketika **urutan objek tidak diperhatikan**.

Rumus dasar:

$$
{}_nC_r=\frac{n!}{r!(n-r)!}
$$

Materi meliputi:

- konsep pemilihan,
- kombinasi $r$ unsur dari $n$ unsur,
- sifat-sifat kombinasi,
- aplikasi kombinasi.

[[Materi Baru Kaidah Pencacahan dan Peluang/04 - Kombinasi]]


### 05. Membedakan Permutasi dan Kombinasi

Bagian ini berfokus pada kemampuan menentukan metode pencacahan yang sesuai.

Pertanyaan utama yang digunakan adalah:

> **Apakah perubahan urutan menghasilkan kemungkinan yang berbeda?**

Jika **ya**, gunakan permutasi.

Jika **tidak**, gunakan kombinasi.

Materi meliputi:

- perbedaan permutasi dan kombinasi,
- mengenali peran urutan,
- memilih rumus yang sesuai,
- soal campuran permutasi dan kombinasi.

[[Materi Baru Kaidah Pencacahan dan Peluang/05 - Membedakan Permutasi dan Kombinasi]]

---

## Bagian 2: Teori Peluang

### 06. Konsep Dasar Peluang

Bagian ini menjadi penghubung antara kaidah pencacahan dengan teori peluang.

Materi meliputi:

- percobaan acak,
- ruang sampel,
- titik sampel,
- kejadian,
- peluang suatu kejadian,
- nilai peluang.

Rumus dasar:

$$
P(A)=\frac{n(A)}{n(S)}
$$

dengan:

$$
0\leq P(A)\leq1
$$

[[Materi Baru Kaidah Pencacahan dan Peluang/06 - Konsep Dasar Peluang]]


### 07. Peluang Komplemen

Komplemen kejadian $A$ adalah kejadian ketika $A$ tidak terjadi.

Jika $A^c$ merupakan komplemen dari $A$, maka:

$$
P(A^c)=1-P(A)
$$

Konsep komplemen sangat berguna untuk menyelesaikan soal seperti:

- tidak terjadi,
- tidak ada,
- minimal satu,
- paling sedikit satu.

[[Materi Baru Kaidah Pencacahan dan Peluang/07 - Peluang Komplemen]]


### 08. Peluang Kejadian Majemuk

Kejadian majemuk melibatkan dua kejadian atau lebih.

Materi meliputi:

- gabungan kejadian,
- irisan kejadian,
- kejadian saling lepas,
- kejadian tidak saling lepas.

Rumus umum:

$$
P(A\cup B)
=
P(A)+P(B)-P(A\cap B)
$$

[[Materi Baru Kaidah Pencacahan dan Peluang/08 - Peluang Kejadian Majemuk]]


### 09. Peluang Bersyarat

Peluang bersyarat digunakan ketika peluang suatu kejadian dipengaruhi oleh informasi bahwa kejadian lain telah terjadi.

Rumus:

$$
P(A\mid B)
=
\frac{P(A\cap B)}{P(B)}
$$

dengan:

$$
P(B)\neq0
$$

[[Materi Baru Kaidah Pencacahan dan Peluang/09 - Peluang Bersyarat]]


### 10. Kejadian Saling Bebas

Dua kejadian disebut saling bebas apabila terjadinya salah satu kejadian tidak memengaruhi peluang kejadian lainnya.

Jika $A$ dan $B$ saling bebas:

$$
P(A\cap B)=P(A)\cdot P(B)
$$

Pada bagian ini juga dipelajari perbedaan antara:

- kejadian saling bebas,
- kejadian saling lepas.

[[Materi Baru Kaidah Pencacahan dan Peluang/10 - Kejadian Saling Bebas]]

---

## Bagian 3: Penerapan Kaidah Pencacahan dalam Peluang

### 11. Penerapan Kaidah Pencacahan dalam Peluang

Pada ruang sampel yang sederhana, seluruh kemungkinan masih dapat dituliskan satu per satu.

Namun, pada permasalahan yang lebih besar, cara tersebut tidak lagi praktis.

Kaidah pencacahan dapat digunakan untuk menentukan:

$$
n(S)
$$

dan:

$$
n(A)
$$

tanpa harus menuliskan seluruh anggota ruang sampel.

Materi meliputi:

- menentukan ruang sampel dengan aturan perkalian,
- menggunakan permutasi dalam peluang,
- menggunakan kombinasi dalam peluang,
- peluang pemilihan anggota kelompok,
- peluang penyusunan objek,
- masalah kontekstual.

[[Materi Baru Kaidah Pencacahan dan Peluang/11 - Penerapan Kaidah Pencacahan dalam Peluang]]

### 12. Latihan Terpadu Kaidah Pencacahan dan Peluang

Bagian terakhir digunakan untuk menggabungkan seluruh konsep yang telah dipelajari.

Soal disusun secara bertahap:

1. soal dasar,
2. soal menengah,
3. soal menantang,
4. soal aplikasi dan penalaran.

Pada bagian ini, siswa perlu menentukan sendiri konsep yang paling tepat digunakan sebelum melakukan perhitungan.

[[Materi Baru Kaidah Pencacahan dan Peluang/12 - Latihan Terpadu Kaidah Pencacahan dan Peluang]]

---

# Ringkasan

- [[Materi Baru Kaidah Pencacahan dan Peluang/Ringkasan Kombinatorika dan Teori Peluang Lanjutan]]