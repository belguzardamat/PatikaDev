# PatikaDev Veri Yapıları ve Algoritmalar - Insertion Sort Projesi

Proje 1
[22,27,16,2,18,6] -> Insertion Sort
# Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Örüntüye ait en küçük elemanı bulup en baştaki sayı ile yer değiştirerek ilerleyeceğiz. (n,n-1,n-2,...1)
[22,27,16,2,18,6] - 5
[2,27,16,22,18,6] - 4
[2,6,16,22,18,27] - 3
[2,6,16,22,18,27] - 2
[2,6,16,18,22,27] - 1

# Big-O gösterimini yazınız.
O(n^2)

# Time Complexity: 
Average case: Aradığımız sayının ortada olması : 16,18
Worst case: Aradığımız sayının sonda olması : 27
Best case: Aradığımız sayının dizinin en başında olması : 2

# Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Average Case

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] 
[2,3,5,8,7,9,4,15,6] 
[2,3,4,8,7,9,5,15,6] 
[2,3,4,5,7,9,8,15,6] 
...
[2,3,4,5,6,7,8,9,15] 
