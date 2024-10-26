## Membuat tugas kode program lewat flowchart
Nama :Sayidina Ramadhan


Nim :312410112
## Deks Program:
1. Meminta user memasukkan 3 bilangan berbeda
2. Membandingkan ketiga bilangan tersebut
3. Menentukan bilangan mana yang terbesar
4. Menampilkan hasilnya ke layar
## Flowchart:
![saiiii](https://github.com/user-attachments/assets/8677a0c9-975a-4735-949f-8b7316a50bce)
## Kode Program :
````pyhton
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))

if a > b:
    if a > c:
        print("Terbesar adalah A")
        terbesar = a
    else:
        print("Terbesar adalah c")
        terbesar = c
else:
    if b > c:
        print("Terbesar adalah B")
        terbesar = b
    else:
        print("Terbesar adalah C")

print(f"Bilangan terbesar adalah: {terbesar}")
````
## Contoh Output Program :
````markdown
Masukkan bilangan A: 30
Masukkan bilangan B: 50
Masukkan bilangan C: 70
Terbesar adalah C
````
## cara kerja program : 
rogram ini meminta pengguna untuk memasukkan tiga bilangan (A, B, dan C) dan menentukan bilangan terbesar di antara ketiganya.

Input: Mengambil tiga bilangan dari pengguna.
Logika:
Memeriksa apakah A lebih besar dari B.
Jika ya, periksa apakah A lebih besar dari C. Jika ya, A adalah terbesar; jika tidak, C adalah terbesar.
Jika A tidak lebih besar dari B, periksa apakah B lebih besar dari C. Jika ya, B adalah terbesar; jika tidak, C adalah terbesar.
Output: Menampilkan bilangan terbesar.
Program ini bekerja dengan membandingkan bilangan satu sama lain menggunakan pernyataan if.
