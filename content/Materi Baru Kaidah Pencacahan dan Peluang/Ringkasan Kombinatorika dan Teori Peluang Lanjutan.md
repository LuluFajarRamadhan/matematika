---
title:
---
# Ringkasan Kombinatorika dan Teori Peluang Lanjutan

Bab ini menyatukan dua pilar utama dalam analisis matematika diskret: **Kombinatorika** sebagai teknik menghitung ruang kemungkinan secara efisien, dan **Teori Peluang Lanjutan** sebagai instrumen logis untuk mengukur kepastian suatu peristiwa di tengah ketidakpastian.

### 1. Intisari Alat Pencacahan (Kombinatorika)
* **Aturan Dasar:** Gunakan **Aturan Penjumlahan** jika kejadian bersifat saling lepas (opsi pilihan, kata hubung *"atau"*). Gunakan **Aturan Perkalian** jika kejadian bersifat berkelanjutan/simultan (tahapan proses, kata hubung *"dan"*).
* **Permutasi:** Digunakan ketika ==**URUTAN OBJEK SANGAT PENTING ($AB \neq BA$)**==. Melekat pada kasus posisi jabatan, peringkat juara, atau penyusunan kode/angka khusus.
* **Kombinasi:** Digunakan ketika ==**URUTAN OBJEK DIABAIKAN ($AB = BA$)**==. Melekat pada kasus pemilihan anggota tim, jabat tangan, pengambilan objek acak sekaligus, dan penentuan koefisien Binomial Newton.

### 2. Intisari Probabilitas Majemuk (Teori Peluang Lanjutan)
* **Peluang Tunggal Lanjutan:** Menghitung $P(A) = \frac{n(A)}{n(S)}$ di mana nilai pembilang dan penyebutnya dicari terlebih dahulu menggunakan rumus kombinatorika karena ukurannya yang raksasa.
* **Gabungan Dua Kejadian (Aturannya: "Atau" / $\cup$):**
  * *Saling Lepas:* Tidak bisa terjadi bersamaan $\rightarrow P(A \cup B) = P(A) + P(B)$
  * *Tidak Saling Lepas:* Ada irisan yang bisa terjadi bersamaan $\rightarrow P(A \cup B) = P(A) + P(B) - P(A \cap B)$
* **Hubungan Dua Kejadian (Aturannya: "Dan" / $\cap$):**
  * *Saling Bebas:* Kejadian pertama tidak mempengaruhi peluang kejadian kedua (contoh: koin + dadu, atau pengambilan dengan pengembalian) $\rightarrow P(A \cap B) = P(A) \times P(B)$
  * *Tidak Saling Bebas (Bersyarat Dasar):* Kejadian pertama mengubah peluang kejadian kedua (contoh: pengambilan objek tanpa pengembalian) $\rightarrow P(A \cap B) = P(A) \times P(B|A)$
* **Peluang Bersyarat Tinggi ($P(A|B)$):** Menghitung peluang kejadian $A$ dengan memanfaatkan informasi bahwa kejadian $B$ sudah pasti terjadi terlebih dahulu. Fokusnya adalah mempersempit ruang sampel semesta menjadi hanya sebesar ruang sampel pembatasnya ($n(B)$).

---
## Contoh Soal Campuran
Dalam sebuah seleksi wawancara kerja, peluang seorang kandidat lulus tes kompetensi bidang adalah 0,7. Jika ia dinyatakan lulus tes kompetensi bidang, peluang ia lulus tes wawancara akhir adalah 0,8. Namun, jika ia gagal pada tes kompetensi bidang, peluang ia lulus wawancara akhir hanya 0,2. Berapakah peluang total seorang kandidat untuk bisa lulus dalam tes wawancara akhir tersebut?

> [!success]- Klik untuk Lihat Jawaban
> **Langkah 1: Identifikasi Notasi dan Nilai Peluang.**
> * Misalkan $K$ = Lulus Tes Kompetensi $\rightarrow P(K) = 0,7$
> * Maka $K'$ = Gagal Tes Kompetensi $\rightarrow P(K') = 1 - 0,7 = 0,3$
> * Misalkan $W$ = Lulus Wancara Akhir
> * Peluang lulus wawancara dengan syarat lulus kompetensi $\rightarrow P(W|K) = 0,8$
> * Peluang lulus wawancara dengan syarat gagal kompetensi $\rightarrow P(W|K') = 0,2$
> 
> **Langkah 2: Analisis Alur Logika Kejadian.**
> Seorang kandidat bisa lulus wawancara akhir melalui dua jalur alternatif yang saling lepas, yaitu:
> * **Jalur 1:** Ia lulus tes kompetensi **dan** lulus wawancara $\rightarrow P(K \cap W)$
> * **Jalur 2:** Ia gagal tes kompetensi **tapi** lulus wawancara $\rightarrow P(K' \cap W)$
> 
> Selesaikan masing-masing jalur menggunakan aturan perkalian peluang tidak saling bebas (bersyarat):
> * $P(K \cap W) = P(K) \times P(W|K) = 0,7 \times 0,8 = 0,56$
> * $P(K' \cap W) = P(K') \times P(W|K') = 0,3 \times 0,2 = 0,06$
> 
> **Langkah 3: Hitung Peluang Total (Aturan Penjumlahan).**
> Karena Jalur 1 dan Jalur 2 bersifat saling lepas (tidak mungkin seseorang lulus sekaligus gagal tes kompetensi secara bersamaan), gabungkan kedua hasil dengan penjumlahan:
> $$
> \begin{aligned}
> P(W) &= P(K \cap W) + P(K' \cap W) \\
> &= 0,56 + 0,06 \\
> &= 0,62
> \end{aligned}
> $$
> Jadi, peluang total seorang kandidat untuk lulus dalam tes wawancara akhir tersebut adalah **0,62 (atau 62%)**.

---

## Konsep Terkait

- [[Materi Baru Kaidah Pencacahan dan Peluang/00 - Peta Konsep Kaidah Pencacahan dan Teori Peluang]]
- [[Kombinatorika dan Teori Peluang Lanjutan/04 - Teori Kombinasi dan Ekspansi Binomial Newton]]
- [[Kaidah Pencacahan dan Peluang/11 - Peluang Bersyarat dan Pengantar Teorema Bayes]]