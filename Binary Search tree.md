## Binary Search Tree <br>
**Binary Search Tree**, node’lardan oluşan ve her bir node’un en fazla 2 child node’a sahip olduğu veri yapılarından bir tanesidir.
### Node nedir? 
    *   Node, bir veri yapısının en temel birimidir.
    *   Node’lar veriler içerebilirler ve aynı zamanda diğer nodelar ile aralarında bir bağlantı bulundurabilirler.
![](https://miro.medium.com/v2/resize:fit:640/format:webp/0*LE91GmAfrWD71cR0.png)   
Görselde gördüğünüz her bir veri node olarak geçmektektedir ve node’lar arasında bağlantılar bulunmaktadır:

    *   Binary Search Treede en üstte bulunan node Root olarak adlandırılır.
    *   Root’tan küçük değere sahip olan node’lar Root’un sol tarafında yer alır.
    *   Root’tan büyük değere sahip olan node’lar Root’un sağ tarafında yer alır.
Bu kural Recursive olarak sol ve sağ tarafta yer alan subtree’ler içinde geçerlidir.
<hr/>
#### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları<br>
    1. 7'yi **root** olarak alıyoruz.
    2. 5'i 7'nin **soluna**  ekliyoruz.
    3. 1'i 5'in **soluna** ekliyoruz
    4. 8'i 7'nin **soluna** ekliyoruz
    5. 3'ü 1'in **sağına** ekliyoruz
    6. 6'yı 5'in **sağına** ekliyoruz.
    7. 0'ı 1'in **soluna** ekliyoruz
    8. 9'ü 8'in **sağına** ekliyoruz
    9. 4'ü 3'in **sağına** ekliyoruz.
    10. 2'yi 3'ün **soluna** ekliyoruz.
<hr/>
### Görünümü
                  7
                /   \
               5      8
             /   \     \
            1     6      9
           / \
          0    3
             /   \         
            2     4