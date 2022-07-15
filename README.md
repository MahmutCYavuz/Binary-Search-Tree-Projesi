# Binary-Search-Tree-Projesi
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

```
1) Root 7'dir. Ağacın başına yazılır

        7
```

```
2) 5 yediden küçüktür. 7'nin solundan devam edilir.
        7
       /
      5
```

```
3) 1, 7'den küçüktür, soldan devam edilir. 5'ten de küçüktür tekrar soldan devam edilir.
        7
       /
      5
     /
    1
```

```
4) 8, 7'den büyüktür. Bu sefer sağdan devam edilir.
        7
       / \
      5   8
     /
    1
```

```
5) 3, 7'den küçük, 5'ten küçük, 1'den büyük. 1'in sağından devam edilir.
        7
       / \
      5   8
     /
    1
     \
      3
```

```
6) 6, 7'den küçük, 5'ten büyük. 5'in sağından devam edilir.
        7
       / \
      5   8
     / \
    1   6
     \
      3
```

```
7) 0, 7'den küçük, 5'ten küçük. 1'den de küçük, 1'in solundan devam edilir.
        7
       / \
      5   8
     / \
    1   6
   / \
  0   3
```

```
8) 9, 7'den büyük, 8'den büyük.8'in sağından devam edilir.
        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
```

```
9) 4, 7'den küçük, 5'ten küçük, 1 den büyük, 3'ten büyük. 3'ün sağından devam edilir.
        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
       \
        4
```
```
10) 2, 7' den küçük, 5'ten küçük, 1 den büyük, 3'ten küçük. 3'ün solundan devam edilir.
        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
     / \
    2   4
```






















