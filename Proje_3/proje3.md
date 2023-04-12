# proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisi Binary Search Tree olarak aşağıdaki şekilde oluşturulabilir:

İlk eleman (7) ağacın kökü olarak belirlenir.
5, kökün soluna eklenir.
1, 5'in soluna eklenir.
8, kökün sağına eklenir.
3, 1'in sağına eklenir.
6, 5'in sağına eklenir.
0, 1'in soluna eklenir.
9, 8'in sağına eklenir.
4, 3'ün sağına eklenir.
2, 1'in sağına eklenir.
Böylece aşağıdaki BST yapısı oluşur:

         7
        / \
       5   8
      / \   \
     1   6   9
    / \     /
    0   3   4
      /    
     2     

BST'nin yapısında, her sol alt ağaç, üstündeki düğümden daha küçük olan elemanları içerir. Her sağ alt ağaç ise üstündeki düğümden daha büyük olan elemanları içerir.