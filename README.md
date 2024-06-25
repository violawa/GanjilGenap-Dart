# printOddEven Program

## Deskripsi
Program ini mencetak angka dari 1 hingga 5 dan menentukan apakah masing-masing angka tersebut genap atau ganjil. 

## Cara Kerja
Fungsi `printOddEven` akan melakukan iterasi dari angka 1 hingga 5. Selama iterasi, fungsi ini akan memeriksa apakah setiap angka adalah genap atau ganjil dan mencetak hasilnya.

## Kode
```dart
void printOddEven() {
  for (int i = 1; i <= 5; i++) {
    if (i % 2 == 0) {
      print('$i adalah genap');
    } else {
      print('$i adalah ganjil');
    }
  }
}

void main() {
  printOddEven();
}
```

## Penjelasan Kode
- Fungsi `printOddEven`:
  - Menggunakan loop `for` untuk iterasi dari angka 1 hingga 5.
  - Di dalam loop, menggunakan kondisi `if` untuk memeriksa apakah angka tersebut genap atau ganjil.
  - Jika angka tersebut genap (`i % 2 == 0`), maka akan mencetak "`$i adalah genap`".
  - Jika angka tersebut ganjil, maka akan mencetak "`$i adalah ganjil`".
  
- Fungsi `main`:
  - Memanggil fungsi `printOddEven` untuk menjalankan logika yang telah dijelaskan di atas.

## Contoh Output
Saat program dijalankan, output yang dihasilkan adalah:
```
1 adalah ganjil
2 adalah genap
3 adalah ganjil
4 adalah genap
5 adalah ganjil
```

## Cara Menjalankan
1. Salin kode di atas ke dalam file dengan ekstensi `.dart` (misalnya, `print_odd_even.dart`).
2. Buka terminal atau command prompt.
3. Arahkan direktori ke tempat file tersebut disimpan.
4. Jalankan perintah berikut:
   ```
   dart print_odd_even.dart
   ```

Program ini akan mencetak hasil sesuai dengan contoh output di atas.
