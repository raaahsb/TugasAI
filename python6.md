1) APLIKASI TERBILANG
```py
numbers = input("Masukkan angka : ")

number_mapping = {
    "1":"Satu",
    "2":"Dua",
    "3":"Tiga",
    "4":"Empat",
    "5":"Lima",
    "6":"Enam",
    "7":"Tujuh",
    "8":"Delapan",
    "9":"Sembilan",
}
output = ""
for n in numbers:
    terbilang = number_mapping.get(n, "Tidak Terdefinisi")
    output = output + terbilang + " "
print(output)
```

![image](https://user-images.githubusercontent.com/92993689/141115663-7820463d-9cce-49e8-bb91-0602ef6415cc.png)

2)  EMOJI CONVERTER
```py
kalimat = input(">>>  : ")

emoji_mapping = {
    ":)": "😊",
    ":(": "😞",
    ":P": "😛"

}
output = ""
words = kalimat.split(" ")
for w in words:
    output = output+emoji_mapping.get(w , w)+ " "
print(output)
```

![image](https://user-images.githubusercontent.com/92993689/141118456-30ea862a-2470-4d6b-adba-b39aab8385ac.png)


3) FUNGSI
```py

