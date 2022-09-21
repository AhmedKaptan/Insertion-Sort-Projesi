# Proje 3
Bu dosya [patika.dev](https://www.patika.dev/)'e ait olan Ahmet sait tarafından yapılmış ''[Veri Yapıları ve Algoritmaları](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar)''  dersinin [Binary Search Tree Projesi](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje) ödevini içermektedir.

## [7,5,1,8,3,6,0,9,4,2] dizisin Binary Search Tree aşamalarını yazınız.
---
İlk olarak root belirlenir.Ardından küçükler sol tarafına büyükler sağ tarafına yazılır.

1.Adım: Root:7

2.Adım: 5<7

         7
       /
      5

3.Adım 1<7

         7
        /
       5
      /
     1

4.Adım: 8>7

          7
         / \
        5   8
       /
      1

5.Adım: 3<7

          7
         / \
        5   8
       /
      1
       \
        3

6.Adım: 6<7

          7
         / \
        5   8
       / \
      1   6
       \
        3

7.Adım: 0<7

          7
         / \
        5   8
       / \
      1   6
     / \
    0   3

8.Adım: 9>7

          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3

9.Adım: 4<7

          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
         \
          4

10.Adım: 2<7

           7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
       / \
      2   4
