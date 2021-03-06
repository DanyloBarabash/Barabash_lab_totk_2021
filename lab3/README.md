# Лабораторна робота 3
## Тема: _Методи обходу та модифікації графів_
## Мета роботи: _Навчитись застосовувати алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева_

## Хід роботи
У роботі використовується онлайн ресурс для генерування графів [Graph Online](https://graphonline.ru/).
1. За допомогою лабораторного макету побудувати випадковий неорієнтований граф `G={8,12}`:
    
    ![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/Graf1.png "Граф")

    
    1. Побудувати дерево за алгоритмом обходу в ширину (BFS); (для 2-х різних вершин)
          
           Порядок обхода: 0 1 2 3 4 5 6 7
           
          ![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/Tree1.png "Дерево1")
          
           
           Порядок обхода: 4 1 2 3 5 6 7 0
           
          ![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/Tree2.png "Дерево2")
           
    3. Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?
    
           Ні, не будуть однаковими
          
    5. Побудувати дерево за алгоритмом обходу в глибину (DFS); (для 2-х різних вершин)

           Порядок обхода: 1 0 2 4 3 5 6 7
           
          ![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/DFS.png "DFS")
          
            Порядок обхода: 5 2 0 1 3 4 6 7
            
          ![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/DFS2.png "DFS2")
           
    7. Чи будуть однаковими топології дерев побудованих з різних кореневих вершин? Чому?
    
             Ні, не будуть однаковими

1. За допомогою лабораторного макету побудувати випадковий орієнтований граф `G={6,10}`:

     ![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/Graf2.png "Граф2")
 
    1. Побудувати дерево за алгоритмом обходу в ширину (BFS);

           
           
          ![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/BFS.png "BFS")
          
    3. Яка вершина (вершини) буде знайдена останньою?

            4 
            
    5. Визначити чи існують цикли. Вказати послідовність ребер і їх довжину.

           Так граф має цикл, 0=>5=>2=>1=>0 довжина 4
           
     
    7. Визначити кількість хвиль, які пройдуть по ребрах доки буде виявлена остання вершина.
    
            Для цього потрібно 3 хвилі
              
    9. Побудувати дерево за алгоритмом обходу в глибину (DFS);

![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/DFS3.png "DFS")



1. Побудувати дерево шляхів рангом `r=4` для випадкового графа `G={6,9}`.

![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/Graf6_9.png "Tree6_9")

![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/tree6_9.jpg "Tree9_6")


1. Побудувати мінімальне зв’язне дерево для графа `G`. Вказати його вагу.

![alt text](https://github.com/BobasB/lab_example/blob/master/lab_guidance/3_/images/graph.png "Знайти вагу графа")

![alt text](https://github.com/DanyloBarabash/Barabash_lab_totk_2021/blob/main/lab3/last.jpg)

        Вага = 39
       

## Висновок
    
    В цій лабораторінй роботі були вивчені алгоритми обходу графів, побудови дерева шляхів та мінімального зв’язного дерева. В процесі виконання були побудованні різні графи, та застосовані до них вивчені алгоритми.
