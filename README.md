# PatikaDev-Veri-Yap-lar-ve-Algoritmalar-Merge-Sort-Projesi


[16,21,11,8,12,22] -> Merge Sort

1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

[16,21,11,8,12,22]

[16,21,11] --------- [8,12,22]

[16] -- [21,11] --------- [8] -- [12,22]

[16] - [21] - [11] --------- [8] - [12] - [22]

[16,21] - [11] --------- [8,12] - [22]

[11,16,21] --------- [8,12,22]

[8,11,12,16,21,22]


2) Big-O gösterimini yazınız.

Her dizinin kendi içinde sıralanması O(n) notasyonu şeklinde gösterilir.
Merge sort algoritmasında baştan sona ortadan ikiye bölerek ilerliyoruz.
Bu yüzden 2^x = n olursa, x = logn olur. logn işlem sayımız. => O(nlogn)
