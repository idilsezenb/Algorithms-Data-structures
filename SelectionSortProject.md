# [22,27,16,2,18,6] -> Selection Sort  

- [**2**,27,16,22,18,6] -> All numbers were compared and the smallest number was found.Thus, replace 22 with 2.=**n comparisons**  
- [2,**6**,16,22,18,27] -> For the second position, where 27 is present, again traverse the rest of the array in a sequential manner.I found that 6 is the second lowest value in the array thus swap these values. =  **(n-1) comparisons**    
- [2,6,**16**,22,18,27] -> Similarly, for third position I traversed rest of the array and found the third least element in the array.= **(n-2) comparisons**  
As 16 is the 3th lowest value hence, it will place at the third position.= **(n-3) comparisons**  
- [2,6,16,**18**,22,27] -> For fourth position, 18 is the lowest value so I replaced 18 with 22. = **(n-4) comparisons**  
- [2,6,16,18,**22**,27] -> Again, I traversed rest of the array and 22 is the lowest value hence, it'll place at the same position. = **(n-5) comparisons**  
- [2,6,16,18,22,**27**] -> Now, I have only 27 and this is also iteraiton but it's clear that 27 will place at the last position. = **1 comparisons**  
All comparisons = 1+(n-5)+(n-4)+(n-3)+(n-2)+(n-1)+n=[n(n+1)]/2=(n^2+n)/2 --> **Big O Notation= O(n^2)**  


-----------------------------------------------------------------------------------------------------------------------------------------------------

 After sorting, we can see that '18' is almost in the middle. So looking for the number 18 is **average case.**  
 
-----------------------------------------------------------------------------------------------------------------------------------------------------

# [7,3,5,8,2,9,4,15,6] -> Selection Sort(first four steps)

**1** [2,3,5,8,7,9,4,15,6]  
**2** [2,3,5,8,7,9,4,15,6]  
**3** [2,3,4,8,7,9,5,15,6]  
**4** [2,3,4,5,7,9,8,15,6]  








