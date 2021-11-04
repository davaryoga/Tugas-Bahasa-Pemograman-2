# Tugas-Bahasa-Pemograman-2
Berikut adalah output Lab1.py

![Screenshot (36)](https://user-images.githubusercontent.com/92939686/140400355-6bba65f4-860d-4a6d-ad39-7bfc248bdfc9.png)


## Penjelasan Lab1.py
###	Penggunaan End
Pertama kita menggunakan perintah ‘print’  dan kita lanjutkan memasukan input yang akan kita `print` pada output, dan diakhiri dengan fungsi 'end' untuk manghasilkan output pada baris yang sama dengan output `print` selanjutnya
#### Contoh:
```
print('A', end='')
print('B', end='')
print('C', end='')
perintah 'print' diatas akan menghasilkna output: ABC
```

![Screenshot (37)](https://user-images.githubusercontent.com/92939686/140401262-894f3b5e-f8de-4994-853c-8f3225d51fac.png)

### Penggunaan Separator
Separator digunakan untuk memberikan pembatas pada variabel
#### Contoh:
```
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```
#### Akan mengghasilkan output:
```
10 15 20 25
10,15,20,25
10152025
10:15:20:25
10-----15-----20-----25
```

![Screenshot (39)](https://user-images.githubusercontent.com/92939686/140402728-834c3a74-d663-4ede-bb27-b438547736eb.png)


### String Format
Adalah fungsi yang digunakan untuk mengganti, atau mengkonversi string dengan placeholder dengan nilai yang valid dalam string akhir. Ini adalah fungsi bawaan dari kelas string Python, yang mengembalikan string yang diformat sebagai output. Placeholder di dalam string didefinisikan dalam tanda kurung keriting.
#### Contoh:
```
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
```
#### Akan menghasilkan output:
```
0 1
1 10
2 100
3 1000
4 10000
5 100000
6 1000000
7 10000000
8 100000000
9 1000000000
10 10000000000
 ```
 
 ![Screenshot (40)](https://user-images.githubusercontent.com/92939686/140403703-ea0af75e-422d-43c7-b6eb-6917c4c32f46.png)
 
 Jika kita ingin menggunakannya dengan arah sebaliknya kita bisa lakukan seperti contoh berikut
 #### Contoh:
```
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
```
#### Akan menghasilkan output:
```
 0                1
 1               10
 2              100
 3             1000
 4            10000
 5           100000
 6          1000000
 7         10000000
 8        100000000
 9       1000000000
 10      10000000000
```
 
![Screenshot (41)](https://user-images.githubusercontent.com/92939686/140404564-ef729e04-5ecb-4db4-8309-7ff9e70c0541.png)
 
## Penjelasan Lab2.py
Berikut adalah output dari Lab2.py
 
![Screenshot (43)](https://user-images.githubusercontent.com/92939686/140405206-8ca3af4e-a715-4180-a379-03fddb75ed31.png)
 
Pertama kita gunakan tipe data 'int', lalu kita input variabelnya
```
a=int(input("masukan nilai a:"))
b=int(input("masukan nilai b:"))
print("variable a=",a)
print("variabel b=",b)
print("hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))
```
Kemudian kita konversikan nilai variabelnya
```
a=int(a)
b=int(b)
print("hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%f".format(a,b) %(a/b))
```
Jika kita 'Run' kita akan diperintahkan untuk memasukan nilai

![Screenshot (45)](https://user-images.githubusercontent.com/92939686/140406088-fa237e0f-9435-4c69-af33-807890af809d.png)

Misalkan kita input nilai 80 dan 99

![Screenshot (46)](https://user-images.githubusercontent.com/92939686/140406476-e4b3942e-1b9d-40ab-bf02-d59a260ae08e.png)

Dan kemudian akan menghasilkan output

![Screenshot (43)](https://user-images.githubusercontent.com/92939686/140405206-8ca3af4e-a715-4180-a379-03fddb75ed31.png)

## Penjelasan Luas_dan_keliling_lingkaran.py
#### Flowchart

![Flowchart Luas dan Keliling Lingkaran](https://user-images.githubusercontent.com/92939686/140412716-68204954-f3c9-4b2e-b790-976c4e1f3fbe.png)

Berikut adalah output dari Luas_dan_keliling_lingkaran.py

![Screenshot (48)](https://user-images.githubusercontent.com/92939686/140408639-98af18cf-d4f5-4301-ba3b-50aa0453190e.png)


Pertama kita akan `import math`, dimana fungsi modul `math` ini bisa kita gunakan untuk menampilkan nilai `phi` (3.14).
```
import math
math.phi
```
Lalu kita memerlukan jari-jari, kita akan menggunakan fungsi input kemudian akan saya konversikan nilainya ke tipe data float
```
r = float(input("Masukan Jari-jari : "))
```
Kemudian kita masukan rumus Luas dan keliling lingkaran (Luas = π × r², Keliling = 2 x π × r), kita gunakan modul `mtah.phi` untuk menampilkan phi
```
luas = math.pi*(r*r)
keliling = 2*math.pi*r
```
Lalu kita gunakan perintah `print` untuk menampilkan hasil dari perhitungan rumus tadi
```
print ("Luas Lingkaran \t\t= ",luas)
print ("Keliling Lingkaran\t= ",keliling)
```
Jika kita `Run` akan ditampilkan sebagai berikut

![Screenshot (50)](https://user-images.githubusercontent.com/92939686/140410519-05ba9e68-e78b-4156-941d-aca17bc8a8e1.png)

Misalkan kita masukan nilai jari-jarinya 14

![Screenshot (48)](https://user-images.githubusercontent.com/92939686/140408639-98af18cf-d4f5-4301-ba3b-50aa0453190e.png)


## Sekian Terima Kasih
