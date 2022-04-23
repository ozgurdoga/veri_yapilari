## İnsertion Sort
İlk soruyu çözümlemek gerekir ise:
[22,27,16,2,18,6] sayılarından oluşan küme

``` 
[2,27,16,22,18,6]   
[2,6,16,22,18,27]   
[2,6,16,18,22,27]
```
Yukarıda görülen 3 kümeyi oluşturur.

# İkinci Soru

Her bir sıralama evresinde yer değiştirir bu yüzden insertion sort'un total yapacağı işlem sayısı (n*n-1)/2 dir.
Bu sebeple ***(Big-O) = O^2***
***********************************
# Üçüncü ve Dördüncü Soru
* Sıralandıktan sonra 18 sayısının ortalarda kümenin medyan sayısına yakın olduğundan dolayı işlem avarage case kapsamına girer.
*************
# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
* [7,3,5,8,2,9,4,15,6]
* [2,3,5,8,7,9,4,15,6]
* [2,3,4,8,7,9,5,15,6]
* [2,3,4,5,7,9,8,15,6]
* [2,3,4,5,6,9,8,15,7]
