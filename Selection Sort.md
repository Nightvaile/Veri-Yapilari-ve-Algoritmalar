#SELECTION SORT PROJESİ

[22,27,16,2,18,6] -> Insertion Sort (Araya ekleme)
 
 Insertion Sort öncelikle dizideki ikinci eleman başlangıç elemanı olarak seçilir(birinci eleman sıralı kabul edilir) ve kendisinden önce gelen yani solunda eleman ile kıyaslanır. Eğer birinci eleman ikinci elemandan büyükse yer değiştirirler. Değilse bir sonraki elemana geçilir. İkinci eleman birinci indise alınır ilk eleman ikincisi indise alınır ve üçüncü eleman ile ikinci eleman kıyaslanır.  Bu şekilde dizi elemanlarının hepsine bakılana kadar ve doğru sıralama elde edilene kadar işlem devam eder. 

1- 27yi 22 ile kıyaslıyoruz  >> [22,27,16,2,18,6] >> O(n)
2- 16 ekleyip kıyaslıyoruz >> [16,22,27,2,18,6] >> O(n-1)
3- 2 yi ekleyip kıyaslıyoruz >> [2,16,22,27,18,6] >> O(n-2)
4- 18 i ekleyip kıyaslıyoruz >> [2,16,18,22,27,6] >> O(n-3)
5- son olarak 6 yı eklıyoruz >>  [2,6,16,18,22,27] >> O(n-4)

Karmaşıklığı O(n^2) dir.

18 Average case yani Aradığımız sayının ortada olması durumundadır.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı

[2,3,5,8,7,9,4,15,6] >> 1.Adım
[2,3,5,8,7,9,4,15,6] >> 2.Adım
[2,3,4,8,7,9,5,15,6] >> 3.Adım
[2,3,4,5,7,9,8,15,6] >> 4.Adım

Selection Sort sıralanmamış eleman kalmayana kadar tekrarla:
En küçük değeri bulmak için verilerin sıralanmamış kısmını ara.
Bulunan en küçük değeri, sıralanmam1ş parçanın ilk elemanıyla değiştir.Bunu sırayla kalan bütün elemanlar için yapar.