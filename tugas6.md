Flowchart penyelesaian masalah wadah x=4 dan y=3 kg. dengan goal y=2

- buat flowchart kemudian jalankan sampai menemukan solusi

![image](https://user-images.githubusercontent.com/92993689/139224084-8381c2c3-a400-4f5e-93d5-b5aee55787e0.png)

- SC pada flowgorithm di Vs-code

 ![image](https://user-images.githubusercontent.com/92993689/139224589-fd3ae467-226c-4ed6-b426-8043695158da.png)
  
    
     x = int(input())
     x = int(input())
     y = int(input())
     while True:
         rules = int(input())
         if rules == 1:
             if x < 4:
                 x = 4
         if rules == 2:
             if y < 3:
                 y = 3
         if rules == 4:
             if y > 0:
                x = x
                y = y - 3
        if rules == 5:
             if x > 0:
                x = 0
        if rules == 6:
             if y > 0:
                y = 0
        if rules == 7:
             if x + y >= 4 and y > 0:
                x = 4
                y = y - (4 - x)
        if rules == 8:
             if x + y <= 3 and y > 0:
                x = x - (3 - y)
                y = 3
        if rules == 9:
             if x + y <= 4 and y > 0:
                x = x + y
                y = 0
        if rules == 10:
             if x + y <= 3 and x > 0:
                x = 0
                y = x + y
       print(x)
       print(y)
       if y == 2:
             print("Hasil ini merupakan Goal state")
