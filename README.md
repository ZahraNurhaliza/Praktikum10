# Praktikum10
## Python String
* String adalah jenis yang paling populer di Python.
* Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.
* Python memperlakukan tanda kutip tunggal ('') sama dengan tanda kutip ganda ("").
* Membuat string semudah memberi nilai pada sebuah variabel.

## Latihan 1
`txt = 'Hello World`
* Hitung jumlah karakternya
* Aambil karakter terakhir
* Amnbil karakter index ke-2 sampai index ke-4 (llo)
* Hilangkan spasi pada text tersebut (Helloworld)
* Ubah text menjadi huruf besar
* Ubah text menjadi huruf kecil
* Ganti karakter H dengan karakter J 
![image](https://github.com/ZahraNurhaliza/Praktikum10/blob/main/screenshot/Latihan1.png)

### Penjelasn Latihan 1
* Untuk menghitung jumlah karakter, gunakan fungsi `len()`
* Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku `[]` dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya.
* Untuk mengambil karakter terakhir, gunakan `index[-1]`. Sedangkan untuk mengambil karakter index ke-2 sampai ke-4, gunakan `index[2:5]`
* Jika ingin menghilangkan spasi pada string, gunakan method `replace(). Method replace() menganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.
* Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan
`(txt.replace(" ", ""))`
kedua dengan cara
`(txt.replace(txt[5], ""))`
python 
# Menghilangkan spasi pada text tersebut (HelloWorld)
print(txt.replace(" ", ""))

* Untuk mengubah huruf menjadi besar, gunakan method `upper()`. Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method `lower()`
python
# Mengubah text menjadi huruf besar 
print(txt.upper())
# Mengubah text menjadi huruf kecil
print(txt.lower())

* Untuk menganti karakter H dengan J, gunakan method `replace()`
python
print(txt.replace("H", "J"))
print()


### RUN Latihan 1
![image](https://github.com/ZahraNurhaliza/Praktikum10/blob/main/screenshot/Latihan1(RUN).png)

## Latihan 2
![image](https://github.com/ZahraNurhaliza/Praktikum10/blob/main/screenshot/Latihan2.png)

### Penjelasan Latihan 2
* Untuk memasukkan variabel ke dalam string, tambahkan kurung kurawal, untuk menempatkan variable sebelumnya.
python
umur= 24
txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n"
print(txt.format(umur))

### RUN Latihan 2
![image](https://github.com/ZahraNurhaliza/Praktikum10/blob/main/screenshot/Latihan2(RUN).png)

## SELESAI