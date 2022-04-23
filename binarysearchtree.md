### Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 
Eğer root olarak 6'yı seçer isek.

* 6'nın solunda kendinden daha küçük sayılar olan [0,1,2,3,4,5] bulunacak iken.
* Root yani 6'nın sağında kendinden daha büyük sayılar olan [7,8,9] bulunacaktır.

[0,1,2,3,4,5] bu dizinin rootunu 3 seçer isek.

```
                             [3]
                        [1]        [4]
                    [0]     [2]         [5]
#Şeklinde son hali oluşacaktır.
```

[7,8,9] bu dizinin rootunu 8 seçer isek
```
            [8]
         [7]   [9]
#Şeklinde son hali oluşacaktır.
```

### Tüm dizinin son haline bakacak isek

```
                                [6]
                      [3]                    [8]     
                [1]         [4]          [7]     [9]  
            [0]     [2]          [5]
