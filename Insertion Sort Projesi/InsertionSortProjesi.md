#Sorular

[22,27,16,2,18,6] -> Insertion Sort


##### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
#####
1. [22,27,16,2,18,6]
2. [22,27,16,2,18,6]
3. [16,22,27,2,18,6]
4. [2,16,22,27,18,6]
5. [2,16,18,22,27,6]
6. [2,6,16,18,22,27]

#####
##### 2. Big-O gösterimini yazınız.
#####
 n+(n-1)+(n-2)+...+1
n.(n+1)/2 
n^2+1/2
Big-O = O(n^2)

##### 3. Time Complexity: 
###### Worst case: Aradığımız sayının sonda olması, 
0+1+2+..+(n-1)
[n.(n-1)] /2
n^2


###### Average case: Aradığımız sayının ortada olması,
n^2+n/2
n^2


###### Best case: Aradığımız sayının dizinin en başında olması.
n


#####
##### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Sonda veya başta olmadığı için Average Case kapsamına girer.


#####
##### 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. [7,3,5,8,2,9,4,15,6]
2. [3,7,5,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
4. [3,5,7,8,2,9,4,15,6]
