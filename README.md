# patikadevveriyapilarivealgoritmalar

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6] - [2,22,27,16,18,6] - [2,6,22,27,16,18] - [2,6,16,22,27,18] - [2,6,16,18,22,27]

Big-O gösterimini yazınız.
O (n^2)

Time Complexity: 
  Average case: Aradığımız sayının ortada olması, (6*(6+1)/2) örnek: [18,16,2,6,27,22]
  Worst case: Aradığımız sayının sonda olması, (6^2), örnek: [27,22,18,16,6,2]
  Best case: Aradığımız sayının dizinin en başında olması, yani (n=6), örnek: [2,6,16,22,27,18]
  
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. Worst Case

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1- [2,7,3,5,8,9,4,15,6];
2- [2,3,7,5,8,9,4,15,6]
3- [2,3,4,7,5,8,9,15,6]
4- [2,3,4,5,7,8,9,15,6]
