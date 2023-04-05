# [16,21,11,8,12,22] -> Merge Sort  
- [16,21,11]  &  [8,12,22]  -> First I divided the whole array into equal halves.
- [16] & [21,11] & [8] & [12,22] -> I divided these two arrays into further halves, until the atomic units of the array is reached and further division is not possible.
- [16] & [21] , [11]  &  [8] & [12] , [22]
- [16] & **[11,21]**   &  [8]  &  **[12,22]** -> I started merging the elements again based on comparison of size of elements.
- [11,16,21] & [8,12,22] -> I compared the element for each list and then combined them into another list in a sorted manner.
- [8,11,12,16,21,22] -> Final merging
- -------------------------------------------------------------------------------------------------------------------------
##  Big O Notation  
Every merge needs (n-1) comparisons(n=array size) EXP: [16] & [11,21] = [11,16,21] -> So 3 value and 2 coomparisons 
How deep my level? 2^x=n -> x=logn 
n.logn=O(nlogn) --> **Big O Notation**
