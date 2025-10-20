Objectives Report

1. Menurut saya Matrix 5x5 adalah yang paling ideal untuk deteksi segmennya dikarenakan ketebalan garis dari source code adalah 4 pixel (pen.setWidth(4);) sehingga ada ruang didalam window deteksi segmennya, namun disini saya mengecilkan widthnya ke 1 agar tetap menggunakan matrix 3x3 yang lebih kecil.

2. Membuang semua matrix kosong dengan fungsi bool isEmpty pada CustomMatrix.h
dan print semua matrix yang !isEmpty untuk melihat pola

(43, 161):

- 0 0 0 
- 0 0 1 
- 0 0 0 

(359, 262):

- 1 0 0 
- 0 0 0 
- 0 0 0 

(356, 256):

1 1 1 
1 1 1 
0 0 0 

contoh pola




