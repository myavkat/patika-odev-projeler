[Main Page](README.md)

# Proje 1

- [22,27,16,2,18,6] -> Insertion Sort

  1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  2. Big-O gösterimini yazınız.
  3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
  4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# Çözüm

- 1.  1. [22,27,16,2,18,6]
      2. [22,27,2,16,18,6]
      3. [22,2,27,16,18,6]
      4. [2,22,27,16,18,6]
      5. [2,22,27,16,6,18]
      6. [2,22,27,6,16,18]
      7. [2,22,6,27,16,18]
      8. [2,6,22,27,16,18]
      9. [2,6,22,16,27,18]
      10. [2,6,16,22,27,18]
      11. [2,6,16,22,18,27]
      12. [2,6,16,18,22,27]
  2.  O(n\*(n+1)/2)
  3.  Time complexity:
      1. Average Case: O(n/2)
      2. Worst Case: O(n)
      3. Best Case: O(1)
  4.  Average Case

- Insertion Sort'a Göre İlk 4 Adım:

  0. [7,3,5,8,2,9,4,15,6]
  1. [7,3,5,2,8,9,4,15,6]
  2. [7,3,2,5,8,9,4,15,6]
  3. [7,2,3,5,8,9,4,15,6]
  4. [2,7,3,5,8,9,4,15,6]
