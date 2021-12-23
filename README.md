# Patika-Homework Veri Yapıları ve Algoritmalar

## 1. Insertion Sort

##### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız

                                                            [22,27,16,2,18,6] - (n)

                                                            [2,27,16,22,18,6] - (n-1)

                                                            [2,6,16,22,18,27] - (n-2)

                                                            [2,6,16,18,22,27] - (1)

##### 2. Big-O gösterimini yazınız.

                                                            n + (n-1) + (n-2) + 1

                                                            n.(n+1) / 2 

                                                            (n^2 + n) / 2 

                                                            O(n^2)

##### 3. Average case, Worst case, Best case.

                                                            Average Case
                                                            [2,6,16,18,22,27] =  16, 18

                                                            Worst Case
                                                            [2,6,16,18,22,27] =  27

                                                            Best Case 
                                                            [2,6,16,18,22,27] =  2

##### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

                                                            Average case

#### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

                                                            [7,3,5,8,2,9,4,15,6]  =-> (n) 

                                                            [2,3,5,8,7,9,4,15,6] =-> (n-1) 

                                                            [2,3,4,8,7,9,5,15,6] =-> (n-2)

                                                            [2,3,4,5,7,9,8,15,6] =-> (n-3)



## 2. Merge Sort

1.                                                       [16, 21, 11, 8, 12, 22]
                                                           
                                             [16, 21, 11]                      [8, 12, 22]  
                                               /        \                      /        \
                                       [16, 21]         [11]            [8, 12]         [22]
                                         /   \            |              /   \           |
                                     [16]     [21]      [11]          [8]     [12]      [22]
                                           |              |                 |            |
                                       [16, 21]         [11]             [8, 12]        [22]
                                               \        /                      \       /
                                             [11, 16, 21]                     [8, 12, 22]
                                              
                                                         [8, 11, 12, 16, 21, 22]

2. Big O gösterimi


                                                            n =-> 2^x

                                                            logn = x

                                                            O(n logn)



                                                         
## 3. Binary Search Tree Projesi

#### Soru.) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


[0, 1, 2, 3, 4, 5, 6, 7, 8, 9](sorted array)

root  = 5
on the right side of the root = 7
on the left side of root = 3

                                                                   5       
                                                               /       \
                                                             3           7
                                                           /   \       /   \
                                                          1     4     6     8 
                                                         / \                |  
                                                        0   2               9


                                                     
