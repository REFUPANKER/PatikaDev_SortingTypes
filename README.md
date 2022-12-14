# PatikaDev - Sorting Types
[Patika Dev](www.patika.dev) - Veri Yapıları ve Algoritmalar Projeleri
### Titles
* [Insertion Sort](https://github.com/REFUPANKER/PatikaDev_SortingTypes#insertion-sort)
* [Merge Sort](https://github.com/REFUPANKER/PatikaDev_SortingTypes#merge-sort)
* [Binary Search Tree](https://github.com/REFUPANKER/PatikaDev_SortingTypes#binary-search-tree)
---
## Insertion Sort
```java
[22,27,16,2,18,6]
```
1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```Java
 1| [16,22,27,2,18,6]
 2| [2,16,22,27,18,6]
 3| [2,16,18,22,27,6]
 4| [2,6,16,18,22,27]
 5| [     Sorted    ]
```
2- Big-O gösterimini yazınız.
> O(  N^2 ) -> N:6 -> O(6^2) -> O(36)  
#### Time Complexity
* Average case  : Aradığımız sayının ortada olması
* Worst case    : Aradığımız sayının sonda olması 
* Best case     : Aradığımız sayının dizinin en başında olması

3- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
> Average Case


4- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```java
1|-> 3,7,5,8,2,9,4,15,6
2|-> 3,5,7,8,2,9,4,15,6
3|-> 2,3,5,7,8,9,4,15,6
4|-> 2,3,4,5,7,8,9,15,6
```
## Merge Sort
```java
[16,21,11,8,12,22]
```
1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
<br/>
<img width="400" height="300" algin="left" src="https://user-images.githubusercontent.com/68808212/187883638-5d0316b4-7349-4427-ab4f-8984066f85f1.png"/>
<br/>
2- Big-O gösterimini yazınız.
> O(nLogn) -> O(6log6) -> O(4.6689075023)

## Binary Search Tree
1- [7,5,1,8,3,6,0,9,4,2] Dizisinin Binary-Search-Tree aşamalarını yazınız.
<br/>
<img width="600" height="280" src="https://user-images.githubusercontent.com/68808212/187891975-bb02b65d-7a2f-47b4-855e-079dfed2698c.png"/>
<br/>
---
### Veri Yapıları ve Algoritmalar [ Insertion Sort,Merge sort ve Binary Search Tree Projeleri ] 
<br/>
www.patika.dev
