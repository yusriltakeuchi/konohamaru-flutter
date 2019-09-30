# 02 - Comments
Comment adalah sebuah syntax yang dapat diterapkan dalam kode tapi tidak akan dieksekusi oleh compiler. Dalam artian comment di sini berfungsi hanya sebagai penanda saja dan tidak akan dieksekusi.

Biasanya programmer memberikan comment untuk menandakan sebuah baris kode terhadap keterangan tertentu. Pada bahasa Dart kita bisa membuat comment menggunakan dua cara.

### Cara Pertama
```javascript
//Ini adalah komentar
var nama = "Yusril Rapsanjani";
print ("Hello ${nama}!");
//Ini komentar selanjutnya
```

### Cara Kedua
```javascript
/* Komentar panjang lebih dari
satu line ini tidak akan dibaca oleh compiler
*/
var umur = 20;
print("Saya berusia ${umur.toString()} tahun!");
```

Tetapi perlu diperhatikan, comment diberikan dengan sejelas-jelasnya dan tidak berbelit-belit, hal ini berguna untuk menghemat jumlah baris kode yang terlalu banyak sehingga membuat file size menjadi lebih besar.
