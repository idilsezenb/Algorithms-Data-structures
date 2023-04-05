# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree Steps
**1-** Root is "7"  
**2-** 5<7 => 5 is placed to the left.  
**3-** 1<7 1<5 => 1 is located to the left of 5.  
**4-** 8>7 => 8 is placed to the right of 7.   
**5-** 3<7 3<5 3>1 => 3 is placed to the right of 1.    
**6-** 6<7 6>5 => 6 is placed  to the right of 5.  
**7-** 0<7 0<5 0<1 => 0 isplaced to the left of 1.  
**8-** 9>7 9>8 => 9 is located to the left of 8. 
**9-** 4<7 4<5 4>1 4>3 => 4 is placed to the left of 3.  
**10-** 2<7 2<5 2>1 2<3 => 2 is placed to the right of 3.





             7  
           /   \  
          5     8
         / \   / \  
        1   6     9   
       / \   
      0   3  
         / \      
        2   4       
