[22,27,16,2,18,6] -> Insertion Sort

0.indexteki eleman ele alınır.
Dizideki diğer elemanlarla kıyaslanır ve dizinin en küçük elemanı 0. indeksteki olan elemanı ile hemen yer değiştirme yaparız.
Dizi [2,27,16,22,18,6] olur.
indexteki eleman ele alınır  dizide kalan diğer elemanlarla 1. indexteki eleman karşılastırılır ve en küçük elemanla 1. indexteki eleman yer değiştirir.
Dizi [2,6,16,22,18,27] olur.
indexteki eleman ele alınır  2. indexteki eleman kıyaslanır ve en küçük elemanımızla 2. indexteki eleman yer değiştirir.  
Dizi [2,6,16,22,18,27] olur.
indexteki eleman ele alınır  3. indexteki elemanla kıyaslanır ve en küçük elemanla 3. indexteki eleman yer değiştirir.
Dizi [2,6,16,18,22,27] olur.
Dizimiz sıralanmış oldu  , dizide n-1 eleman kalana kadar bu işlemi yapar ve böylelikle dizi sıralı halinin getirilmiş olur.
Big-O gösterimini yazınız.
Insertion Sort algoritması sıralama yaparken her aşamada dizideki sıralanmamış bütün elemanları kıyaslıyor.
n tane elemanı olan bir dizide ilk aşamada n kere işlem yapıyor. ikinci aşamada n-1 tane ve dizide bir eleman kalana kadar  devam eder
Big-O Notation için n+(n-1)+(n-2)...burada n ardışık sayının toplamı formülünden n*(n+1)/2 bu formülü açtığımınzda (n^2+2n+1)/2 gelir bu formülde baskın olan n^2 olduğu için Big-o Notation n^2 oluyor.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Burada da diziyi sıraladığımızda 18 sayısı dizinin orta kısmına denk geldiğini söyleyebilirz ve aradığımız sayı Worst Case kapsamına daha yakındır.
