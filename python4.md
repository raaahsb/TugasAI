1) PERULANGAN FOR
```py
nama = "Sahara"

for item in nama:
    print(item, end=' ')
print("\n")
    
# perulangan list
print ("\n==========================")
num = [1,2,3]
for i in num:
    print(i)
print("\n")   

# perulangan in range
print ("\n=========================")
for i in range(3):  # list selalu dimulai dari nol
    print(i) 
```

![image](https://user-images.githubusercontent.com/92993689/140890345-7ced169f-5aba-4ed3-b5fc-a562c1b2242f.png)
![image](https://user-images.githubusercontent.com/92993689/140890727-bc60f426-df83-4356-9a87-4d96140aa2ec.png)

2) LIST
```py
kata = ['Ara', 'Kiyowo',]
# mengambil urutan pertama dari list
print(kata[0])

# mengambil urutan terakhir dari list
print(kata[-1])

# mengambil berdasarkan range
print(kata[0:2])
```

![image](https://user-images.githubusercontent.com/92993689/140891524-939694de-77c9-4e0c-a988-e4021646eb1a.png)

3) LIST METHOD
```py
nomor = [9, 6, 7 ,4]
print(nomor)

nomor.append(69) #memasukkan objek pada list
print(nomor)

nomor.insert(0, 3) #memasukkan objek kedalam list pada index tertentu
print(nomor)

nomor.pop(1) #menghapus objek list pada index tertentu
print(nomor)

nomor.remove(69) #menghapus suatu objek didalam array
print(nomor)

nomor.sort() #mengurutkan item dalam list
print(nomor)
```
![image](https://user-images.githubusercontent.com/92993689/140892083-855c340a-1310-41c2-8c88-2a4a2a4988ca.png)

4) MENJUMLAHKAN LIST
```py
nomor2 = [9, 6, 7, 5, 2]

nomor3 = 0

for nomor in nomor2:
    nomor3 = nomor3 + nomor

print(nomor3)
```

![image](https://user-images.githubusercontent.com/92993689/140896389-8064541d-ca15-4607-95a0-3b4142a05f8d.png)

