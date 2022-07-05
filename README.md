# Insertion Sort Projesi

 
https://github.com/cmilakonur/projem/tree/9429f4db9f4ce918d907e562511448928872a8aa <br />
patika.dev linkim: https://app.patika.dev/cmilakonur

[22,27,16,2,18,6] -> Insertion Sort 

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. 

-En küçük olan ilk sıradaki sayı ile yer değiştirir. <br />
 [2,27,16,22,18,6]
 
-İkinci sıra için 2'den sonra gelen en küçük sayı ile ikinci sırada olan sayı yer değiştirir. <br />
 [2,6,16,22,18,27]
 
-3.sıradaki sayı zaten en küçük olduğundan yer değiştirmez. <br />
 [2,6,16,22,18,27]
 
-18 ile 22 yer değiştirir. <br />
 [2,6,16,18,22,27]
 
-5.sıradaki sayı en küçük olduğundan yer değiştirmez. <br />
 [2,6,16,18,22,27
 
-6.sıradaki eleman en büyük olur ve dizin sort türüne göre küçükten büyüğe sıralanmış olur. <br />
 [2,6,16,18,22,27]
 
 2-Big-O gösterimini yazınız. <br />
 O(n^2)
 
 3-Time Complexity: <br />
 Average case: Aradığımız sayının ortada olması 16, 18 <br />
 Worst case: Aradığımız sayının sonda olması 27 <br />
 Best case: Aradığımız sayının dizinin en başında olması 2 <br />
 
 4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. <br />
 Average case
 
 5-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 
[2,3,5,8,7,9,4,15,6] <br />
[2,3,5,8,7,9,4,15,6] <br />
[2,3,4,8,7,9,5,15,6] <br />
[2,3,4,5,7,9,8,15,6] <br />
