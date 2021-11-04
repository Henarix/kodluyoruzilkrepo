# Merge Sort

## [16,21,11,8,12,22] Aşamaları

 [16,21,11]  [8,12,22] şeklinde olmak üzere ikiye bölünür.

 [16]  [21,11]  [8]  [12,22] bölünenler tekrar ikiye bölünür.

 [16]  [11,21]  [8]  [12,22] ikili veya tekli şekilde küçükten büyüğe tekrar sıralanır.

 [11,16,21]  [8,12,22] tekrar sıralananlar küçükten büyüğe olmak üzere birleştirilir.(tek bir sayıya büyük mü, küçük mü sorusu sorularak en az işlem yapılması hedeflenir.)

 [8,11,12,16,21,22] aynı işlemler uygulanarak, en az işlem sayısı hedeflenerek devam edilir ve sonuca ulaşılır.

## Big-O Gösterimi
 
 O(nlogn)


