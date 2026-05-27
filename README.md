# Praktikum Kecerdasan Buatan - Pertemuan 9
## Algoritma Genetika 1

Repository ini berisi implementasi Algoritma Genetika untuk menyelesaikan kasus Knapsack Problem pada praktikum Kecerdasan Buatan pertemuan 9.

---

## Struktur File

```bash
AlgoritmaGenetika/
├── inisiasipopulasi.py
├── EvaluasiFitness.py
├── selection.py
├── crossover.py
├── mutation.py
└── main.py
```

### Fungsi Tiap File

- `inisiasipopulasi.py`  
  Digunakan untuk membuat populasi awal secara acak.

- `EvaluasiFitness.py`  
  Digunakan untuk menghitung nilai fitness setiap individu berdasarkan total keuntungan dan kapasitas maksimum.

- `selection.py`  
  Digunakan untuk proses seleksi parent menggunakan metode Roulette Wheel Selection (RWS) dan Tournament Selection (TS).

- `crossover.py`  
  Digunakan untuk proses crossover antar parent menggunakan metode One-Point, Two-Point, dan Uniform Crossover.

- `mutation.py`  
  Digunakan untuk proses mutasi kromosom menggunakan metode Swap Mutation, Inversion Mutation, dan Uniform Mutation.

- `main.py`  
  Program utama untuk menjalankan seluruh proses Algoritma Genetika mulai dari inisialisasi populasi, evaluasi fitness, seleksi, crossover, mutasi, hingga menampilkan hasil akhir dan grafik fitness.

---

## Data Barang

| Barang  | Nilai | Bobot |
|---------|-------|-------|
| Barang1 | 60    | 10    |
| Barang2 | 100   | 20    |
| Barang3 | 120   | 30    |
| Barang4 | 90    | 25    |
| Barang5 | 69    | 11    |
| Barang6 | 70    | 9     |
| Barang7 | 80    | 15    |
| Barang8 | 90    | 10    |
| Barang9 | 25    | 3     |

Kapasitas tas maksimum: **50**

---

## Parameter Algoritma

- Jumlah Generasi: 50
- Jumlah Populasi: 20
- Probabilitas Crossover: 0.5
- Probabilitas Mutasi: 0.1

---

## Cara Menjalankan

Install library:

```bash
pip install matplotlib
```

Jalankan program:

```bash
python main.py
```

---

## Output Program

Program akan menampilkan:

- Grafik perkembangan nilai fitness
- Nilai fitness terbaik
- Total bobot
- Barang yang terpilih

Contoh output:

```bash
Nilai Fitness Terbaik: 334
Total Bobot: 48
Barang Terpilih:
- Barang5
- Barang6
- Barang7
- Barang8
- Barang9
```

## hasil crossover.py
<img width="468" height="103" alt="{59E93298-DFD8-47CD-9CDF-480FBE3AE1DD}" src="https://github.com/user-attachments/assets/753a8f2d-7615-401b-8309-cec314cf61cf" />

## hasil EvaluasiFitness.py
<img width="475" height="111" alt="{B735A0CE-7F00-485E-823E-2A70E3E68A7C}" src="https://github.com/user-attachments/assets/6e8aad9c-955f-4b68-9e9f-cc08f3bdceba" />

## hasil inisiasipopulasi.py
<img width="475" height="184" alt="{119870A5-905E-4BB9-9351-297FECCDAE34}" src="https://github.com/user-attachments/assets/07d372fe-d16c-4190-a506-1c7b9cf1d2f4" />

## hasil mutation.py
<img width="485" height="94" alt="{21E7F50C-38CB-4496-981D-206DE576DBAC}" src="https://github.com/user-attachments/assets/6e3001b8-94bb-41ab-bc82-8e73c1dafaf4" />

## hasil selection.py
<img width="488" height="83" alt="{16E6EBAF-61BC-477D-88E6-235816298AE4}" src="https://github.com/user-attachments/assets/514a5620-6d77-46a0-a92c-25526f00eaca" />

## hasil main.py
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6b813ed6-f394-4670-8a96-621d48d1e483" />

<img width="494" height="276" alt="{938D8039-959E-41C4-B675-35592D2A5EA0}" src="https://github.com/user-attachments/assets/e3e44e6f-a7f7-4cbf-85cf-291e15367703" />
