# Patika.dev-veriYapilari  
# Selection Sort Projesi




[22,27,16,2,18,6] -> Insertion Sort <br>
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.<br>
22 27 16 2 18 6<br>
16 22 27 2 18 6 <br>
2 16 22 27 18 6<br>
2 16 18 22 27 6<br>
2 6 16 18 22 27 <br>
Bu şekilde dizi sıralanmış olur.<br>

Big-O gösterimini yazınız.<br>
Eleman sayısının n olduğunu varsayarsak bir sonraki aşamada  küçük elemanı bulduğumuz için geriye kalan n-1 tane elemanı kontrol etmemiz yeterlidir.Bundan sonraki aşamalarda bir önceki aşamanın eleman sayısının bir eksiği kadar devam eder.Sonuçta n+(n-1)+(n-2)+…1 bu ifade n(n+1)/2 ‘ye eşittir.<br> 
Big-O(n^2) şeklinde ifade edilir.<br>





Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
1.	Average case: Aradığımız sayının ortada olması
2.	Worst case: Aradığımız sayının sonda olması
3.	Best case: Aradığımız sayının dizinin en başında olması.

Average case: Aradığımız sayının ortada olması kapsamına girer.
.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
 
Öncelikle dizinin en küçük elemanı belirlenir.Daha sonra 0.indexten başlanarak kontrol edilir eğer elemandan küçükse yer değiştirme işlemini uygulanır.<br>
2 3 5 8 7 9 4 15 6<br>
2 3 4 8 7 9 5 15 6<br>
2 3 4 5 7 9 8 15 6<br>
2 3 4 5 6 9 8 15 7<br>




 

