# Patika - Veri Yapıları ve Algoritmalar Eğitimi

[Patika - Veri Yapıları ve Algoritmalar Eğitimi](https://academy.patika.dev/courses/veri-yapilari-ve-algoritmalar)


## Projeler

### Proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması <br>
Worst case: Aradığımız sayının sonda olması <br>
Best case: Aradığımız sayının dizinin en başında olması. <br>


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

---
Çözüm

22| 27 16 2 18 6 <br>
22 27| 16 2 18 6 <br>
22 16 27| 2 18 6 <br>
16 22 27| 2 18 6 <br>
16 22 27 2| 18 6 <br>
16 22 2 27| 18 6 <br>
16 2 22 27| 18 6 <br>
2 16 22 27| 18 6 <br>
2 16 22 27 18| 6 <br>
2 16 22 18 27| 6 <br>
2 16 18 22 27| 6 <br>
2 16 18 22 27 6| <br>
2 16 18 22 6 27| <br>
2 16 18 6 22 27| <br>
2 16 6 18 22 27| <br>
2 6 16 18 22 27| <br>

n+(n-1)+(n-2)+(n-3)+...+1 = n.(n+1)/2 <br>
O(n²)

Average case <br>

[22,27,16,2,18,6] <br>
[2,27,16,22,18,6] <br>
[2,6,16,22,18,27] <br>
[2,6,16,18,22,27] <br>

