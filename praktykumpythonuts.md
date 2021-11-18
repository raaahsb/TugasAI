1) Program mencari bilangan genap dari 3 buah bilangin 
```py
angka = []
banyak = int(input("Masukan banyak bilangan :"))

for n in range(banyak):
    nilai = int(input("Masukan angka :"))
    angka.append(nilai)

  
print("\nbanyak bilangan : ",banyak) 
print("bilangan genap :")    
for n in angka:
    if n % 2 == 0:
        print(n)
```

![image](https://user-images.githubusercontent.com/92993689/142434201-394c4882-013a-41fb-8e09-f1abd856adce.png)

