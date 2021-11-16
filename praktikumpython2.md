1) MENAMPILKAN BILANGAN TERBESAR 2 BILANGAN

```py
a = int(input("masukan angka ke-1 : "))
b = int(input("masukan angka ke-2 : "))

if a > b :
    hasil = a
else :
    hasil = b

output = f"""
        Menentukan nilai terbesar dua bilangan
    -------------------------------------------------
        Bilangan pertama : {a}
        Bilangan kedua   : {b}
        Nilai terbesar   : {hasil}

"""
print(output)
```
![image](https://user-images.githubusercontent.com/92993689/141999358-e373883a-fb8a-40a3-ad26-191a672f5645.png)

2) MENAMPILKAN BILANGAN TERBESAR 3 BILANGAN
```py
a = int(input("masukan angka ke-1 : "))
b = int(input("masukan angka ke-2 : "))
c = int(input("masukkan angka ke3 : "))

if a>b and a>c:
    hasil = a
elif b>a and b>c:
    hasil= b
else :
    hasil = c

output = f"""
        Menentukan nilai terbesar Tiga bilangan
    -------------------------------------------------
        Bilangan pertama : {a}
        Bilangan kedua   : {b}
        Bilangan ketiga  : {c}
        Nilai terbesar   : {hasil}

"""
print(output)
```

![image](https://user-images.githubusercontent.com/92993689/142000482-70d46c9f-35bd-490a-97b3-93e8dab4a6f1.png)
![image](https://user-images.githubusercontent.com/92993689/142000655-ab1b6ee0-a4a9-437c-b2a2-d860ddfaa2aa.png)

3) MENAMPILKAN BILANGAN SAMA
```py
n1 = int(input("masukan nilai pertama : "))
n2 = int(input("masukan nilai kedua   : "))
n3 = int(input("masukan nilai ketiga  : "))

if n1 == n2 or n1 == n3 :
    hasil = n1
elif n2 == n3 :
    hasil = n2
else : 
    hasil = "tidak ada nilai yang sama"

output = f"""
            Mencari nilai yang sama
        ---------------------------------
            Nilai ke-1 : {n1}
            Nilai ke-2 : {n2}
            Nilai ke-3 : {n3}
            Nilai sama : {hasil}

"""
print(output)
```
![image](https://user-images.githubusercontent.com/92993689/142002720-012495ea-f072-4df1-8d32-aa8c75e1dd71.png)
![image](https://user-images.githubusercontent.com/92993689/142002971-2557d85f-471a-49e1-b4da-c96185374f43.png)

4) MENGHITUNG BERAT BADAN IDEAL SESEORANG
```py
nama = input("siapa nama anda? ")
tinggi = int(input("berapa tinggi anda? "))
berat = tinggi - 100


output = f"""
            Menghitung Berat Badan Ideal
        -------------------------------------
        Nama Anda   : {nama}
        Tinggi      : {tinggi}
        Saudara {nama}, Berat ideal anda adalah {berat} Kg

"""
print(output)
```

![image](https://user-images.githubusercontent.com/92993689/142003496-23a54ec8-921a-479f-b232-9ee68d812e9d.png)

5) PROGRAM MENGHITUNG NILAI AKHIR DAN GRADE MAKUL
```py
nama = input("masukan nama     : ")
tugas = float(input("berapa nilai tugas? "))
uts = float(input("berapa nilai uts? "))
uas = float(input("berapa nilai uas? "))
finish = 25/100 * tugas +  35/100 * uts + 40/100 * uas

if finish >= 75 :
    grade = "A"
elif finish < 75 and finish >= 60 :
    grade = "B"
elif finish < 60 and finish >= 45 :
    grade = "C"
else :
    grade = "D"

output = f"""
                DATA NILAI MAHASISWA
        -----------------------------------
            NAMA    : {nama}
            TUGAS   : {tugas}
            UTS     : {uts}
            UAS     : {uas}
        -----------------------------------

            NILAI AKHIR DAN GRADE
        -----------------------------------
            NAMA        : {nama}
            NILAI AKHIR : {finish}
            GRADE       : {grade}
        -----------------------------------

"""
print(output)
```

![image](https://user-images.githubusercontent.com/92993689/142005759-6782e66c-e6c5-4c0d-9d40-064bd578a8a7.png)

6) MENGHITUNG GAJI SEORANG KARYAWAN
```py


