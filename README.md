# Template_Prakfiskom
Repository ini hanya untuk template Praktikum Fisika Komputasi

Nama Kelompok :
Anggota Kelompok :
1. A
2. B
3. C
4. D
5. E

Project Metode Numerik
1. Integral Trapezoid Fungsi sin(x)
2. Integral Trapezoid Fungsi cos(x)

Berikut Flowchart Integral Trapezoid Fungsi sin(x)
```mermaid
graph TD
    A[Input Batas bawah, atas, dan Jumlah grid] --> B[trapezoid f, a, b, n]
    B --> C[Print Integral]
    B --> D[Menghasilkan nilai x pada grid]
    D --> E[Menghitung nilai fungsi pada setiap titik x]
    E --> F[Menghitung lebar setiap subinterval delta x]
    F --> G[Menghitung Integral Riemann menggunakan metode trapesium]
    G --> H[Plot fungsi dan batang grid trapesium]
    H --> I[Menampilkan hasil]
```
