# Merge-Sort-Projesi

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Bu diziyi merge sort ile sıralamak için aşağıdaki adımları izleyebiliriz:

1.Diziyi iki eşit parçaya bölün. Bu durumda, dizimizin sol tarafında [16, 21] ve sağ tarafında [11, 8, 12, 22] olacaktır.

2.Her iki parçayı da ayrı ayrı sıralayın. Sol parçada [16, 21] dizisi, sağ parçada [8, 11, 12, 22] dizisi olacaktır. 

3.Her iki parçayı birleştirin ve dizinin tüm elemanlarını sıralı bir dizi olarak birleştirin. Bu durumda, dizimizin sıralı hali [8, 11, 12, 16, 21, 22] olacaktır.

Bu sıralama algoritmasının Big-O gösterimini yazdığımızda, O(n * log(n)) olacaktır.
