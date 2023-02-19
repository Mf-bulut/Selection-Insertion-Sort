## Selection-Insertion Sort Projesi

Soru 1:

[22, 27, 16, 2, 18, 6]

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
```
[2, 27, 16, 22, 18, 6] --> 1. adım (n)

[2, 6, 16, 22, 18, 27] --> 2. adım (n-1)

[2, 6, 16, 22, 18, 27] --> 3. adım (n-2)

[2, 6, 16, 18, 22, 27] --> 4. adım (1)
```

Big O Gösterimi: n + (n-1) + (n-2) + .... 1 = n(n+1)/2 = (n^2+n)/2 Bu sonuçta esas belirleyici olan katsayı n^2 olduğu için
Big O Gösteriminde onu dikkate alacağız. Insertion Sort, Average ve Worst Case durumlarında O(n^2) zaman karmaşıklığına sahiptir.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı Average case kapsamına girer.

Soru 2:

[7 ,3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

```
[2, 3, 5, 8, 7, 9, 4, 15, 6] --> 1. adım

[2, 3, 5, 8, 7, 9, 4, 15, 6] --> 2. adım

[2, 3, 4, 8, 7, 9, 5, 15, 6] --> 3. adım

[2, 3, 4, 5, 7, 9, 8, 15, 6] --> 4. adım
```