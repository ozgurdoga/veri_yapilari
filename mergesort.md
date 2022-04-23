## [16,21,11,8,12,22]
# Sort İşlemleri

```
[16,21,11,8,12,22]
[16,21,11] [8,12,22]
[16] [21,11] [8,12] [22]
[16] [21] [11] [8] [12] [22]
[16] [11,21] [8,12] [22]
[11,16,21] [8,12,22]
[8,11,12,16,21,22] #son hali
```

* Bir sort işleminin sonsuza giderken big-o değerinin değişmeyeceğini düşünüyorum. Case ne olursa olsun her zaman sonsuza baktığımızda big-o değeri aynı olacaktır.
* Buna göre Merge Sort **Big-O = n(logn)**