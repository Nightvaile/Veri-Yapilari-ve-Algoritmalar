**Merge Sort** Buradaki fikir, daha küçük dizileri sıralamak ve ardından bu dizileri sıralı şekilde bir araya getirip birleştirmektir. Bu algoritmada “recursion” dediğimiz özyinelemeden de yararlanılır.<br>
![Merge Sort](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/merge-sort/figures/merge-sort.png)
-Dizinin sol yarisini sırala (n>1 olduğunu varsayarak).<br>
-Dizinin sağ yarisıni sırala (n<1 olduğunu varsayarak).<br>
-Iki yarim parçayi bir araya getir.<br>
<hr>
[16,21,11,8,12,22] Merge Sort <br>
[16,21,11] <<< >>> [8,12,22]<br>
[16] <<>> [21,11] <<< >>> [8,12] <> [22]<br>
[16] <<>> [21] <> [11]<<< >>> [8] <<>> [12] <> [22]<br>
[16] <> [11,21] <<< >>> [8,12] <> [22]<br>
[11,16,21] <<< >>> [8,12,22]<br>
[8,11,12,16,21,22] <br>

<hr>
Big-O gösterimi O(n log n).

