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
<hr>


# Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort<br>
•	Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.<br>
Dizi her aşamada ikiye bölünür ve en sonda sıralama yapılır<br>
        [16 21 11 ]                                               [ 8   12  22]<br>
[16  21]           [ 11]                                       [ 8   12]                 [22]<br>
[16]         [21]         [11]                                  [8]              [12]                  [22]<br>
[16  21]           [11]                                         [8       12]                            [22]<br>
[11 16 20]                                                       [8   12 22]<br>
----->  [8 11 12 16 20 22]<br>



Big-O gösterimini yazınız.<br>
Her itersayonda n-1 kadar kontrol işlemi yapılır.Time complexity n olarak alınabilir,aynı zamanda dizi  boyutu her adımda yarıya ineceğinden 2^x=n’den log2n=x yani logn olarak alınabilir.<br>
Bu durumda O(nlogn)şeklinde ifade edilir.(çalışma zamanı X iterasyon sayısı)<br>
<hr>


# Binary Search Projesi <br>
Kök düğüm 3 olarak alınırsa sol kısımda 3 den küçük ,sağda 3’den büyük değerler sıralanacaktır. <br>



  &nbsp; 3 <br>
       / &nbsp;\ <br>
    1&nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; 7 <br>
   /&nbsp;\ &nbsp;  &nbsp; &nbsp; / &nbsp; \ <br>
  0&nbsp; 2  &nbsp; 5 &nbsp; &nbsp; 8 <br>
&nbsp; &nbsp;&nbsp;&nbsp; &nbsp; / &nbsp;\ &nbsp;  &nbsp; &nbsp; \ <br>
&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 4 &nbsp;  &nbsp;6 &nbsp;&nbsp;&nbsp; &nbsp;9





















 

