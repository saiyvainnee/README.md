## Membuat tugas kode program lewat flowchart
Nama :Sayidina Ramadhan
Nim :312410112
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
