# patika.dev-ilk-dev
Insertion sort ödevi projesi
Ilk-Insertion-Sort-Projem
[22,27,16,2,18,6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
Yukarıda verilen dizinin sort türüne göre aşamaları:
Insetion sort'a göre önce ilk eleman ile en küçük eleman yer değiştirir.
[22,27,16,2,18,6] ---> [2,27,16,22,18,6] bu 1. aşamaydı.
Artık ilk elemanı yerleştirmiş olduk ve onunla ilgilenmiyoruz. 
Kalan elemanlar arasında sıralama yapacağız. 
Sonra elde ettiğimiz yeni dizide 2.elemanla en küçük eleman yer değiştirecek. 
27 iel en küçük eleman olan 6 yer değiştirecek şimdi. [2,27,16,22,18,6]---> [2,6,16,22,18,27] . 
Bu 2. aşamaydı. Aynı işlemi tekrarlamaya 3. ve diğer en küçük elemanla devam ediyoruz.
[2,6,16,22,18,27]---> ve burada görüyoruz ki 3. eleman zaten sıralanmış. 
Ona dokunmuyoruz ve sonrakileri sıralamaya devam ediyoruz. 
[2,6,16,22,18,27]---> [2,6,16,18,22,27] burada da 18 ve 22 nin yerini değiştirdik ve dizimiz tamamen sıralanmış oldu.
2.Big-O gösterimini yazınız. Burada n eleman için n kee arama yaptığımız için n*n'den big-o notasyonumuz O(n^2) oluyor.

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. Dizi sıralandıktan sonra 18 sayısı ortada yer aldığı için Average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1.adım : ilk sıradaki eleman olan 7 ile en küçük eleman olan 2 nin yerini değiştiririz ilk olarak.
[7,3,5,8,2,9,4,15,6]---> [2,3,5,8,7,9,4,15,6] . 
Bu 1. aşamaydı. 2.adım : 3 elemanı zaten sıralı ona dokunmuyoruz. 
Bu sefer sıradaki en küçük eleman olan 4 ile 5 in yerini değiştiriyoruz.
[2,3,5,8,7,9,4,15,6]---> [2,3,4,8,7,9,5,15,6] . Bu 2. aşamaydı. 
Şimdi de 8 ile sıradaki en küçük elemanımız olan 5 in yerini değiştiriyoruz. 
[2,3,4,8,7,9,5,15,6]--->[2,3,4,5,7,9,8,15,6] .
Bu 3. aşamaydı. 
4.adım : Bu adımda da 7 ile yeni en küçük elemanımız olan 6 nın yerini değiştiriyoruz. 
[2,3,4,5,7,9,8,15,6]--->[2,3,4,5,6,9,8,15,7] .
Bu son.
