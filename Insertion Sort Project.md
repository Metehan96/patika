Proje 1
-
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Cevap
-
- [22,27,16,2,18,6] #(n)
- 1.Adım --> [2,| 27,16,22,18,6] (2 sayısı ile 22 sayısı değişir.) #(n-1)
- 2.Adım --> [2,6,| 16,22,18,27] (6 sayısı ile 27 sayısı değişir.) #(n-2)
- 3.Adım --> [2,6,16,| 18,22,27] (18 sayısı ile 22 sayısı değişir.) #(1)

Big-O Notation : n+(n-1)+(n-2)+1 --> (n*(n+1))/2 --> (n²+n)/2 --> O(n²)

18 sayısı average case kapsamına girmektedir.

Proje 1
-
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

*İlk Dört Adım*

- 1.Adım --> [2,| 3,5,8,7,9,4,15,6] (2 sayısı ile 7 sayısı değişir.)
- 2.Adım --> [2,3,| 4,8,7,9,5,15,6] (Sayı değişmi yoktur.)
- 3.Adım --> [2,3,| 4,8,7,9,5,15,6] (4 sayısı ile 5 sayısı değişir.)
- 4.Adım --> [2,3,4,| 5,7,9,8,15,6] (5 sayısı ile 8 sayısı değişir.)
- 5.Adım --> [2,3,4,5,| 6,9,8,15,7] (6 sayısı ile 7 sayısı değişir.)


----------------------------------------------------------------
