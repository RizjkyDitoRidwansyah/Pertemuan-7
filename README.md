Pertemuan 7

Tugas Struktur Kondisi

Latihan 1

Buat program sederhada dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.

> #Masukan input   
> bil1 = int (input("Masukan bilangan : "))  
> bil2 = int (input("Masukan bilangan : "))  

> #Nilai terbesar  

> if (bil1 > bil2):  
>   print("Bilangan terbesar :",bil1)  

> #Nilai terkecil  

> if (bil1 < bil2):  
>   print("Bilangan terbesar :",bil2)  

Hasil Program 
![gambar 1](https://user-images.githubusercontent.com/116090827/200701877-d2016ece-1d85-4236-b6a3-859e802c34bd.png)

Latihan 2

Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.

>  #Masukan inputan  
>  bil1 = int(input("Bilangan ke-1: "))  
>  bil2 = int(input("Bilangan ke-2: "))  
>  bil3 = int(input("Bilangan ke-3: "))  
 
>  #Buat variable data  
>  data = [bil1, bil2, bil3]  

>  #Menampilkan data  
>  print("Data sebelum di urutkan :", data)  
>  list.sort(data)  
>  print("Data setelah di urutkan :", data)

Hasil Program

![gambar 3](https://user-images.githubusercontent.com/116090827/200703378-d6648bdd-447a-4847-a1a2-9a69a936b76c.png)

Tugas Perulangan

Latihan 1

Buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut:

> baris = 10  
> kolom = baris  

> for bar in range(baris):  
>     for col in range(kolom):  
>         tab = bar+col  
>         print("{0:>5}".format(tab), end='')  
>     print()  

Hasil Program

![gambar 6](https://user-images.githubusercontent.com/116090827/200704234-46ff5c64-2937-4c50-9fee-5deb8ed92fff.png)


Latihan 2

Tampilkan n bilangan acak yang lebih kecil dari 0.5. nilai n diisi pada saat runtime anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya.

> import random  
> print("===========================================")  
> print("= Bilangan acak yang lebih kecil dari 0,5 =")  
> print("===========================================")  

> jum = int( input("Masukan nilai: "))  
> i = 0  
> while i in range(jum):  
>     i += 1  
>     angkarandom = random.uniform(0,0.5)  
>     print("Bilangan ke :", i, " : ", angkarandom)  

Hasil Program


![gambar 8](https://user-images.githubusercontent.com/116090827/200704802-faac9040-b271-413d-bff6-42db73d6a634.png)

Tugas Modul Praktikum 2

Latihan 1

Buat program sederhana dengan input tiga buah bilangan, dari ketiga bilangan tersebut tampilkan bilangan terbesarnya. Gunakan statement if.

> a = int(input("Masukan bilangan ke-1 :"))  
> b = int(input("Masukan bilangan ke-2 :"))  
> c = int(input("Masukan bilangan ke-3 :"))  

> max = a  

> if b > max:  
>    max = b  

> if c > max:  
>    max = c  

> print()  
> print("Nilai terbesar :", max)  

Hasil Program

![praktikum 2 1](https://user-images.githubusercontent.com/116090827/200705257-17761f3d-5d56-4c2f-a049-372289460d19.png)

Tugas Modul Praktikum 3



