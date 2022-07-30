# Insertion Sort
####[22,27,16,2,18,6]
1) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.
* Time Complexity: Average case: Aradığımız sayının ortada bulunduğu durum.
* Worst case: Aradığımız sayının sonda bulunduğu durum.
* Best case: Aradığımız sayının dizinin en başında bulunduğu durum.
3) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
### Insertion Sort Aşamaları

[22,27,16,2,18,6] - (n)  en küçük değer olan 2 değeri ile serinin başındaki 22 değeri yer değiştirir.
[2,27,16,22,18,6] - (n-1)  6 değeri ile 27 değeri yer değiştirir.
[2,6,16,22,18,27] - (n-2)  22 değeri ile 18 değeri yer değiştirir.
[2,6,16,18,22,27] - (n-3)
### Big-O Gösterimi
[22,27,16,2,18,6] dizisi için O(n²) sırasız bir dizi olduğu için 2 çevrim gerçekleşir.

* Average case: O(n²)
* Worst case: O(n²)
* Best case: O(n) Sıralı bir dizi olduğunda tek çevrimde tamamlanır.
Dizi sıralandıktan sonra 18 sayısı dizinin ortasında bulunduğu için "average case" kapsamına girer.


## [7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı
1) [2,3,5,8,7,9,4,15,6]
2) [2,3,4,8,7,9,5,15,6]
3) [2,3,4,5,7,9,8,15,6]
4) [2,3,4,5,6,9,8,15,7]