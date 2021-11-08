1) PERCABANGAN IF
```py
is_day = False
is_night = False

if is_day :
    print("Selamat Siang")
elif is_night :
    print("Selamat Malam")
else :
    print("Selamat Error bertemu Ara")
```
![image](https://user-images.githubusercontent.com/92993689/140693321-6016c624-c13b-44e3-8378-9b10d30d8577.png)

2) OPERATOR PERBANDINGAN
```py
grade = 9

if grade >= 6:
    print("Nilai Kamu A")
elif grade >= 7 :
    print("Nilai Kamu B")
elif grade >= 4:
    print("Nilai Kamu C")
else :
    print("Belajar lagi! JANGAN mageran teruss")   
```
![image](https://user-images.githubusercontent.com/92993689/140694737-f59fcf39-d5e4-4a5e-95a4-83148f53f120.png)

3) OPERATOR LOGIKA
```py
name = "Sahara  Hasibuan"
by_pass_validation = False

if len(name) > 2 and by_pass_validation : 
    print("Welcome")
else:
    print("Nama terlalu pendek")
```
![image](https://user-images.githubusercontent.com/92993689/140697596-79ac5251-2951-47ee-a3f3-25a8fb550b72.png)

4) PERULANGAN WHILE
```py
index = 1

while index <= 6:
    print("*" * index)
    index += 1

print("Finish")
```
![image](https://user-images.githubusercontent.com/92993689/140700744-576a2528-ad8f-4199-90c5-d124b372da36.png)

5) GAME TEBAK ANGKA 
```py
trying = 0
secret_number = 5
limit = 4

while trying < limit :
    guess_number = input("Masukkan angka (2-6) : ")
    guess_number = int(guess_number)

    if guess_number ==secret_number:
        print("Selamat, Anda kena tipu")
        break 
    trying += 1
```
![image](https://user-images.githubusercontent.com/92993689/140703850-a72a2115-c1a4-4b09-af39-544f3cad55c2.png)

6) APLIKASI KALKULATOR
```py
# (+ - * / exit)
command =""

while command != "exit" :
    command = input("perintah :")

    if command =="exit" :
        break

    if command != "+" and command != "-" and command != "/":
        print("Perintah tidak dikenali")
        continue

    a = int(input("Angka pertama :"))
    b = int(input("Angka Kedua :"))

    if command =="+" :
        result = a+b
    elif command =="-" :
        result = a-b
    elif command == "*" :
        result = a*b
    elif command == "/" :
        result = a/b

        print(f"Hasil : {result}")

    print("Terima Kasih Sudah Berkunjung")
```

![image](https://user-images.githubusercontent.com/92993689/140713224-8bc706fe-6698-401f-bac2-25a75311904f.png)
![image](https://user-images.githubusercontent.com/92993689/140713038-dbc0d248-96c6-4b0d-b4d3-d54ad36fe01a.png)




