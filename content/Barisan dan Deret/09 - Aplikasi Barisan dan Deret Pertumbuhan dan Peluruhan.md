
# Aplikasi Barisan dan Deret: Pertumbuhan dan Peluruhan

Dalam fenomena alam dan sains, banyak variabel yang nilainya berubah secara berangsur-angsur seiring berjalannya waktu dengan persentase laju yang tetap. Fenomena ini dimodelkan menggunakan dua konsep utama: **Pertumbuhan** (nilai semakin meningkat) dan **Peluruhan** (nilai semakin menyusut). Kedua konsep ini mengadopsi prinsip dasar barisan dan deret geometri.

---

## 1. Pertumbuhan (*Growth*)

Pertumbuhan terjadi ketika jumlah atau nilai suatu objek mengalami kenaikan secara multiplikatif berdasarkan persentase laju tertentu ($i$) dalam periode waktu ($n$).
Contoh: Pertumbuhan jumlah penduduk, pembelahan sel bakteri, pembagian kluster digital.

### Rumus Umum Pertumbuhan:
$$
✮\boxed{M_n = M_0(1 + i)^n}
$$

**Keterangan:**
- $M_n$ = Nilai akhir setelah periode ke-$n$
- $M_0$ = Nilai awal (kondisi mula-mula)
- $i$ = Persentase laju pertumbuhan per periode (dalam bentuk desimal)
- $n$ = Banyaknya periode waktu


---

## 2. Peluruhan (*Decay*)

Peluruhan adalah kebalikan dari pertumbuhan, di mana nilai suatu objek berkurang atau menyusut secara eksponensial dengan laju penurunan tetap ($i$) per periode.
Contoh: Peluruhan zat radioaktif (waktu paruh), penyusutan harga aset fisik/mesin industri (*depreciation*), penurunan dosis obat di dalam darah.



### Rumus Umum Peluruhan:
$$
✮\boxed{M_n = M_0(1 - i)^n}
$$
**Keterangan:**
- $M_n$ = Nilai akhir setelah periode ke-$n$
- $M_0$ = Nilai awal (kondisi mula-mula)
- $i$ = Persentase laju pertumbuhan per periode (dalam bentuk desimal)
- $n$ = Banyaknya periode waktu
---

## Contoh Soal

Sebuah pabrik tekstil membeli mesin produksi baru seharga Rp80.000.000. Karena faktor keausan operasional, nilai jual mesin tersebut mengalami penyusutan (*depreciation*) sebesar $10\%$ setiap tahunnya. Berapakah perkiraan nilai jual buku dari mesin tersebut setelah digunakan selama 3 tahun?

>[!Success]- Klik untuk Lihat Jawaban
> **Penyelesaian:**
> 
> Kasus penyusutan harga barang merupakan penerapan dari rumus **Peluruhan**:
> - Harga awal ($M_0$) = $80.000.000$
> - Laju penyusutan ($i$) = $10\% = 0,1$
> - Periode waktu ($n$) = $3 \text{ tahun}$
> 
> Terapkan rumus peluruhan:
> $$
> \begin{aligned}
> M_n &= M_0(1 - i)^n \\
> M_3 &= 80.000.000 \times (1 - 0,1)^3 \\
> M_3 &= 80.000.000 \times (0,9)^3 \\
> M_3 &= 80.000.000 \times 0,729 \\
> M_3 &= 58.320.000
> \end{aligned}
> $$
> 
> Jadi, perkiraan nilai jual mesin konveksi tersebut setelah digunakan selama 3 tahun adalah **Rp58.320.000**.

---

## Konsep Terkait
* [[Barisan dan Deret/05 - Barisan Geometri|05 - Barisan Geometri]]
* [[Barisan dan Deret/10 - Aplikasi Barisan dan Deret Bunga Majemuk dan Anuitas]]
