# Binary Search Tree Projesi  

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
1. Adım: root 7'dir  
    İlk eleman 7 olduğu için kök (root) olarak 7 seçilir.



                7
2. Adım: root'un solunda 5 bulunur
5, 7'den küçük olduğu için 7'nin soluna yerleşir.  

                7
               /
              5   
3. Adım: root'un solunda 5'in solunda 1 bulunur
1, 7'den ve 5'ten küçük olduğu için 5'in soluna yerleşir.

                7
               /
              5
             /
            1
4. Adım: root'un sağında 8 bulunur
8, 7'den büyük olduğu için 7'nin sağına yerleşir.

               7
              / \
             5   8
            /
           1
5. Adım: 5'in sağında 3 bulunur
3, 5'ten küçük, 1'den büyük olduğu için 1'in sağına yerleşir.

               7
              / \
             5   8
            /
           1
            \
             3
6. Adım: 5'in sağında 6 bulunur
6, 5'ten büyük, 8'den küçük olduğu için 5'in sağına yerleşir.

              7
             / \
            5   8
           / \
          1   6
           \
            3
7. Adım: 1'in solunda 0 bulunur
0, 1'den küçük olduğu için 1'in soluna yerleşir.

              7
             / \
            5   8
           / \
          1   6
         / \
        0   3
8. Adım: 8'in sağında 9 bulunur
9, 8'den büyük olduğu için 8'in sağına yerleşir.

              7
             / \
            5   8
           / \   \
          1   6   9
         / \
        0   3
9. Adım: 3'ün sağında 4 bulunur
4, 3'ten büyük olduğu için 3'ün sağına yerleşir.

              7
             / \
            5   8
           / \   \
          1   6   9
         / \
        0   3
             \
              4
10. Adım: 3'ün solunda 2 bulunur
2, 3'ten küçük, 0'dan büyük olduğu için 3'ün soluna yerleşir.

               7
              / \
             5   8
            / \   \
           1   6   9
          / \
         0   3
            / \
           2   4
### Sonuç olarak, oluşturduğumuz Binary Search Tree (BST):

               7
              / \
             5   8
            / \   \
           1   6   9
          / \
         0   3
            / \
           2   4

