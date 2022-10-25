# Binary-Search-Tree-Projesi
Binary Search Tree (İkili Ağaç Yapısı) node'lardan oluşur.

Node, bir veri yapısının en temel birimidir.

Algoritmada en üstte bulunan node'a root adı verilir.

Sırasıyla node'ları root ile kıyaslayarak yerleştirilir.

Node root değerinden küçükse soluna,büyükse sağına yerleştirilir.

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları:

7 root olarak seçilir. 5 değeri root değerinden küçük olduğu için sol tarafa yazılır.

![1](https://user-images.githubusercontent.com/116086983/197846276-1b1e85d9-1348-41d1-b318-4143fbf37a12.png)

1 değeri 7'den küçük olduğu için sola 5'ten de küçük olduğu için yine sola yazılır.

![2](https://user-images.githubusercontent.com/116086983/197847051-5770c5aa-7e0c-4c06-9db7-b6257a47c991.png)

8 değeri 7'den büyük olduğu için sağ tarafa yerleştiririz.

![3](https://user-images.githubusercontent.com/116086983/197847736-238498b5-2e23-4026-9732-9e071215b56d.png)

3 değeri 7'den küçüktür, 5'ten küçüktür ama 1'den büyüktür, bu yüzden 1'in sağ tarafına yazılır.

![4](https://user-images.githubusercontent.com/116086983/197850771-452768de-2722-4fd7-b286-394f5723451c.png)

6 değeri 7'den küçüktür, 5'ten büyüktür,5'in sağına yazılır.

![5](https://user-images.githubusercontent.com/116086983/197850966-29dc3167-0a84-4147-b753-23265915a261.png)

0 değeri 7'den, 5'ten ve 1'den küçüktür, bu yüzden 0'ın soluna yazılır.

![6](https://user-images.githubusercontent.com/116086983/197851034-6393b47c-194f-491c-94e3-a7c23c4922cb.png)


9 değeri 7'den ve 8'den büyüktür,  8'in sağına yazılır.

![7](https://user-images.githubusercontent.com/116086983/197851054-75a4f3b8-0fc5-4b70-9fa5-f56c0cf63ac4.png)

4 değeri 7'den ve 5'den küçüktür, 1'den ve 3'ten büyüktür, 3'ün sağına yazılır.

![8](https://user-images.githubusercontent.com/116086983/197851202-eec99fe9-71a2-4ec9-9382-58f6b6d6a69e.png)


2 değeri 7'den ve 5'den küçüktür, 1'den büyük ama 3'den küçüktür, 3'ün soluna yazılır.

Ve son olarak binary search tree görünümümüz böyledir:

![9](https://user-images.githubusercontent.com/116086983/197851343-4e7e45c5-5010-4016-8ab8-d893bbffa3e7.png)

http://www.patika.dev/
