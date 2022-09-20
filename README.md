# Binary Search Tree Proje Ödevi
>**[patika.dev](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje) platformu öğrenme projesidir.**
Profil için tıklayınız: [app.patika.dev/nmelihkutlu](https://app.patika.dev/nmelihkutlu)

Binary Search Tree Projesi


## Soru

![](https://github.com/nmelihkutlu/binarySearchTreeProjeOdevi/blob/main/binarySortProjeOdevi.png?raw=true)

```
Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
```


## Cevap
Binary Search Tree aşamaları:

```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1. Dizi sıralanıyor (Sort işlemi):
    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

2. Dizinin ilk terimi en düşük (low) ve son terimi en yüksek (high) olsun. Ortadaki değeri (mid) seçelim. Bu örnekte ortada 4 ve 5 var. Mid değeri 4 olsun:
    [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
    low          Mid            high
        
3. Aranan değer (örneğin 3) mid değerinden büyükse sol taraf, büyükse sağ taraf siliniyor. 3 değeri için: sıradan, değer küçük ise sola, büyük ise sağa yazılıyor. yeni high değeri 5 ve yeni mid değeri ortadaki terim olan 2 olsun: 
    [0, 1, 2, 3, 4]
    low    Mid   high

4. İşlem tekrar yapılıyor:
    [2, 3, 4]
    low Mid high

5. Son durumda ortadaki değere bakıldığında, sonuç bulunmuş oldu:
    [3] 
```
