# Veri-Yapilari-ve-Algoritmalar3
 www.patika.dev
# Binary Search Tree Projesi - Patika.dev
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
## Binary Search Tree Aşamaları
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] root olarak 4 ü seçtim ve büyüklük küçüklük durumuna göre soldan diziye başlayıp ağaca ekliyoruz 
 ```
 4
 ```
 ```
 4
  \
   7
 ```
  ```
     4
      \
       7
      /
     5
 ```
   ```
     4
    /  \
   1    7
       /
      5
 ```
  ```
      4
    /   \
   1     7
        / \
       5   8
 ```
   ```
      4
   /     \
  1       7
   \     / \
    3   5   8
 ```
 ```
      4
   /     \
  1       7
   \     / \
    3   5   8
         \
          6
  ```
 ```
      4
   /     \
  1       7
 / \     / \
0   3   5   8
         \
          6
  ```
 ```
      4
   /     \
  1       7
 / \     / \
0   3   5   8
         \   \
          6   9
   ```
   
  ```
      4
   /     \
  1       7
 / \     / \
0   3   5   8
     \    \   \
      4    6   9
  ```
  ```
      4
   /     \
  1       7
 / \     / \
0   3   5   8
   / \   \   \
  2  4     6   9
  ```

