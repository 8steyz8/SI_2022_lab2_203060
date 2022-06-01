# SI_2022_lab2_203060

2.CFG

![Screenshot 2022-06-01 161207](https://user-images.githubusercontent.com/100214075/171426056-1e61b9ea-105f-4418-bb83-d01709fb8aa7.png)
3.Cyclomatic complexity is the number of regions
Number of regions= number of edges - number of nodes + 2 #EDGES = 27 #NODES = 20 #REGIONS = 27 - 20 + 2 = 9 Cyclomatic Complexity = 9

4.Every statement
![image](https://user-images.githubusercontent.com/100214075/171429075-260e35c5-64e7-4d64-b2d8-4e10115e462e.png)
1)Кога е празна листата влегув во првиот if и се фрла      IllegalArgumentException("List length should be greater than 0"). Поминува низ јазлите 1,2,3..
2)list = [ "#", "#" ] не влегува во првиот услов-јазол2 ,а влегува во вториот услов-јазол6 и се фрла IllegalArgumentException("List length should be a perfect square").Бидејќи големината на листата е 2 и не е perfect square.
3)list = [ "#", "#", "#", "#", "0", "#", "0", "#", "#" ] со # не се влегува во јазол10 и оди во else јазол22.
Првата нула влегува во условот на јазол12 поради тоа што се наоѓа во средина во својата редица.Влегува во јазол17 и јазол19 притоа што има редици што се над неа и редици што се под неа.Втората нула не влегува во услов јазол13 влегува во else-oт поради тоа што се наоѓа на крајот од својата редица.


Изглед на матрицата

![image](https://user-images.githubusercontent.com/100214075/171449640-d84615a7-abbd-49fc-bfbd-9d2301c0de99.png)


5.Every branch

![image](https://user-images.githubusercontent.com/100214075/171441195-9c3b6a1f-5a42-4bb1-867d-4d1f5ccb6fd4.png)

Изглед на матрица

![image](https://user-images.githubusercontent.com/100214075/171452303-0a5a93a2-622c-4b23-aff6-e5211434bdc9.png)

За 1) и 2) е исто како и кај 4.Every statement

3)list=["#","#","0","0","#","0","#","#","#","#","#","#","0","#","#","#"]
Првата нула не влегува во јазол12 бидејќи се наоѓа на крајот и до неа има нула.Не влегува во јазол17 бидејќи е прва редица.
Втората нула влегува и во двете јазол19 и јазол17 поради тоа што има редици над и под.
Третата нула не влегува во јазол19 бидејќи е во последна редица.

