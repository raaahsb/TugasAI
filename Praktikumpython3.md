1) program menampilkan tabel harga
```py
print("PROGRAM MENAMPILAKAN HARGA BENSIN")
print("-"*40)
satuan = 0
harga = 0
a = 0
b = float(input("Masukkan Bensin yang akan di beli : "))
print("_"*40)
print("Satuan        |       Harga         |")
while a < 100:
    a += 1
    satuan = a * 0.5
    harga = a * 800
    
        
    print("-"*40)
    print(f"{satuan} ltr       |   Rp.  {harga}          |")
    if satuan == b:
        break

print(f"""\nAnda Membeli {b} liter Bensin, 
Maka Anda Harus Membayar Rp. {harga}""")
```

![image](https://user-images.githubusercontent.com/92993689/142557052-3e7ef43a-df48-44b4-9524-8f62e55ee871.png)

2) menampilkan deret geometri
```py
awal = int(input ("masukan nilai awal : "))
suku = int(input("masukan nilai akhir : "))
rasio = int(input("masukan rasio : "))


while awal <= suku :
    deret = awal
    awal += rasio
    print(deret)
```

![image](https://user-images.githubusercontent.com/92993689/142557456-6a11c449-70d9-4b6b-b450-c8c60de4ec6a.png)


34 program menginput sejumllah N
```py
x = float(input("Masukkan bilangan real (x) : "))
y = int(input("Masukkan bilangan bulat (y) : "))

z= x ** y
print(f"maka jumlah pangkat (x pangkat y) = {z}")
```

![image](https://user-images.githubusercontent.com/92993689/142557918-04166f05-ea1e-4686-b1e5-7643480c8658.png)


5) menghitung n masukan
```py
def fa(n):
    if n == 0:
        return 1
    else:
        return n*fa(n-1)


n = int(input("Masukkan nomor : "))
print(f"{n}! = ",' * '.join(map(str, range(n, 0, -1))), " = ", fa(n))
```

![image](https://user-images.githubusercontent.com/92993689/142558242-3ebc199a-ed79-47ef-a762-d2bf9c0a7d1f.png)


