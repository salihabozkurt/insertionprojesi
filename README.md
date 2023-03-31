# insertionprojesi
22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
 [22, 27, 16, 2, 18, 6]
[22, 27, 16, 2, 18, 6] > 22 zaten sıralıdır
[16, 22, 27, 2, 18, 6]
[2, 16, 22, 27, 18, 6]
[2, 16, 18, 22, 27, 6]
[2, 6, 16, 18, 22, 27] > dizi tamamen sıralıdır
Big-O gösterimi olarak, Insertion Sort algoritması n elemanlı bir dizi için O(n^2) zaman karmaşıklığına sahiptir.
Dizi sıralandıktan sonra 18 sayısı Average case kapsamına girer. Çünkü ortada bir sayı olarak, diğer sayılarla yaklaşık olarak aynı sayıda karşılaştırma yapılması gerekecektir. Best case için 18 sayısı dizinin başında olmalıdır. Worst case için ise 18 sayısı dizinin sonunda olmalıdır ve tüm elemanlar tek tek kontrol edilmelidir.




[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız. 

Verilen dizinin Selection Sort algoritması ile sıralanması için ilk 4 adımı şu şekildedir:

[2, 3, 5, 8, 7, 9, 4, 15, 6] (En küçük eleman 2 olduğu için ilk eleman ile yer değiştirilir)
[2, 3, 4, 8, 7, 9, 5, 15, 6] (4, 2. en küçük elemandır ve 2. sırada yer alır)
[2, 3, 4, 5, 7, 9, 8, 15, 6] (5, 3. en küçük elemandır ve 3. sırada yer alır)
[2, 3, 4, 5, 6, 9, 8, 15, 7] (6, 4. en küçük elemandır ve 4. sırada yer alır)
Bu şekilde devam edilerek dizi tamamen sıralanır.

------------------------------------------------------------------------------------------------------------------


