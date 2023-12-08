# patika.dev_algoritmalar
## SELECTION SHORT PROJECT

 

<br>

 

1-) <strong>[22,27,16,2,18,6]</strong> Insertion Sort
    Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    
```
- min=2 -> swap 2 and 22 -> [2, | 27, 16, 22, 18, 6]
- min=6 -> swap 27 and 6 -> [2, 6, | 16, 22, 18, 27]
- min=16 -> no need to swap -> [2, 6, 16, | 22, 18, 27]
- min=18 -> swap 18 and 22 -> [2, 6 16 18 ,22, 27]
```

2-) <strong>[22,27,16,2,18,6]</strong> Insertion Sort
    Big-O gösterimini yazınız.
    
```
Step 1 -> n
Step 2 -> n-1
Step 3 -> n-2
....
Step n-1 -> 1

sum = (n*(n-1))/2 -> O(n^2)
```

3-) <strong>[22,27,16,2,18,6]</strong> Insertion Sort
    Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
    
```
Worst Case
```

4-) <strong>[7,3,5,8,2,9,4,15,6]</strong> dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
    
```
- min=2 -> swap 7 and 2 -> [2, | 3, 5, 8, 7, 9, 4, 15, 6]
- min=3 -> no need to swap [2, 3, | 5, 8, 7, 9, 4, 15, 6]
- min=4 -> swap 5 and 4 -> [2, 3, 4, | 8, 7, 9, 5, 15, 6]
- min=5 -> swap 8 and 5 -> [2, 3, 4, 5, | 7, 9, 8, 15, 6]
```


## MERGE SORT PROJECT

 

<br>

 

1-) <strong>[16,21,11,8,12,22]</strong> Merge Sort
    Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    
```
- [16, 21, 11] -- [8, 12, 22]
- [16, 21]  [11] -- [8, 12] [22]
- [16] [21] [11] -- [8] [12] [22]
- [16, 21]  [11] -- [8, 12] [22]
- [11, 16, 21] -- [8, 12, 22]
- [8, 11,12, 16, 21, 22]
```

2-) <strong>[16,21,11,8,12,22]</strong> Merge Sort
    Big-O gösterimini yazınız.
    
```
Step 1 -> n
Step 2 -> n/2
Step 3 -> n/4
....
Step (n-1) -> (n-1)/2^(n-2)

sum = n + n/2 + ... = n(1 + 1/2 + ...) = nlogn
O(nlogn)
```

## BINARY SEARCH TREE PROJECT

 

<br>

 

1-) <strong>[7,5,1,8,3,6,0,9,4,2]</strong> 
    dizisinin Binary-Search-Tree aşamalarını yazınız.
    
```

Dizinin ilk elemanı root olarak kabul edilir bu nedenle root, 7'dir. Her bir adımda kendisinden küçükler sola, büyükler sağa
olacak şekilde ağacın yaprakları yerleştirilir.

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
