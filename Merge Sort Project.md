# Proje 2

- [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


- 1.adım --> [16,21,11] -- [8,12,22]
- 2.adım --> 16,21] [11] -- [8,12] [22]
- 3.adım --> [16] [21] [11] -- [8] [12] [22]
- 4.adım --> [16,21] [11] -- [8,12] [22]
- 5.adım --> [11,16,21] -- [8,12,22]
- 6.adım --> [8,11,12,16,21,22]

  *Big-O gösterimi*
  - 1.Adım --> n
  - 2.Adım -->n/2
  - 3.Adım -->n/4
  ...
  n+(n/2)+(n/4)+ ... = n(1+(1/2)+(1/4)+...)= nlogn
  Big-O: O(nlogn)
