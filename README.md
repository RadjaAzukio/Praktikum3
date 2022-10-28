# Praktikum 3
## Latihan 1
### Penggunaan End
#### - Pengunaan end pada Python berfungsi untuk memberi parameter (pemisah) antara quotes yang kita buat 
![Gambar1](Pk3/latihan1.1.png)
![Gambar1](Pk3/latihan1.2.png)
## Pengunaan Separator
#### - Pengunaan separator pada Python berfungsi sebagai pemisah setiap variabel yang telah diberi nilai 
![Gambar1](Pk3/latihan1.3.png)
![Gambar1](Pk3/latihan1.4.png)
## String Format
#### - String Formatting atau Pemformatan string memungkinkan kita menyuntikkan item ke dalam string daripada kita mencoba menggabungkan string menggunakan koma atau string concatenation.
![Gambar1](Pk3/latihan1.5.png)
![Gambar1](Pk3/latihan1.6.png)
#### - Ini adalah contoh string concatenation
![Gambar1](Pk3/latihan1.7.png)
![Gambar1](Pk3/latihan1.8.png)
#### - Ini adalah contoh string formatting
#### - Ada tiga cara untuk melakukan peformatan string
##### - Metode lama menggunakan placeholder menggunakan karakter '%'(modulo)'
##### - Teknik yang diingatkan menggunakan metode string .format()
##### - Metode terbaru, diperkenalkan dengan Python 3.6, menggunakan string literal yang diformat, disebut *f-string*
## Latihan 2 
#### - Tentukan variabel terlebih dahulu, saya memakai dua variabel, yaitu a dan b
#### - Beri inputan pada variabel
#### - Setelah diberi input, ekspresikan variabel yang telah diberi inputan
#### - Lalu kita mencoba menggabungkan variabel a dan b dengan *Formatting String*
![Gambar1](Pk3/latihan2.1.png)
### Konversi nilai variabel
#### - Konversi nilai variabel yang masih berbentuk 'string' pada 'intreger'
#### - Setelah itu menjumlahkan dan membagi dengan mengepresikan dalam bentuk *Formatting String*
![Gambar1](Pk3/latihan2.2.png)
![Gambar1](Pk3/latihan2.3.png)
## Latihan 3
### Buatlah kode program menggunakan string formattting untuk menghasilkan output seperti gambar dibawah ini
![Gambar1](Pk3/latihan3.1.png)
```
string = ""
x = int(input("Masukkan angka :"))
a = x
while a >= 0:
    b = a
    while b > 0:
        string = string + "   "
        b = b - 1
    l = 1
    while l < (x - (a-1)):
        string = string + " * "
        l = l + 1
    r = 1
    while r < l -1:
        string = string + " * "
        r = r + 1
    string = string + "\n\n"
    a = a -1
a = 1
while a <= x:
    b = a + 1
    while b > 1:
        string = string + "   "
        b = b -1
    l = 0
    while l < (x - a):
        string = string + " * "
        l = l + 1
    r = l
    while r > 1:
        string = string + " * "
        r = r - 1
    string = string + "\n\n"
    a = a + 1
print(string)
```
#### - Agar menampilkan output yang sama dengan latihan3.1 yaitu dengan menjalankan hasil dari statement yang telah dibuat dan seletah itu kita disuruh menginputkan *numeric* 5 
![Gambar1](Pk3/latihan3.2.png)
![Gambar1](Pk3/latihan3.3.png)
#### - Anda dapat bebas menentukan angka yang angka yang ingin diinputkan ^^ 
#### - Seperti ini contohnya
![Gambar1](Pk3/latihan3.4.png)
![Gambar1](Pk3/latihan3.5.png)
## Praktikum 3 
![Gambar1](Pk3/Praktikum3.2.png)
### Hasil praktikum 3 yang telah saya lakukan yaitu :
#### - Dapat memahami algoritma lingkarang yang diproses dalam Python
#### - Dapat menjelaskan bagaimana langkah-langkah membuat algoritma lingkaran pada Python
#### - Dapat membuat *Flowchart* algoritma dengan baik dan benar
#### - Dapat mengoperasikan langsung algoritma lingkarang pada Python
![Gambar1](Pk3/Praktikum3.1.png)
###### Thank You ######
###### huhu ^^^ ######
###### NoNe~'. ######
