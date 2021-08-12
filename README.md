# B-CPE-110-STG-1-1-pushswap-timothe.coniel
Sorting algorithm

The game is made up of two lists of numbers named l_a and l_b.

In the beginning, l_b will be empty and l_a will contain a certain amount of positive or negative numbers.

 Goal :
The goal is to sort l_a by using the fewest possible operations.
The program must print the series of operations that enable this list to be sorted (ra, pb...).

Authorized Operations :
  -  sa :\
       swap the first two elements of l_a.
  -  sb :\
       swap the first two elements of l_b.
  -  sc :\
       'sa' and 'sb' at the same time.
  -  pa :\
       take the first element from l_b and move it to the first position of l_a.
  -  pb :\
       take the first element from l_a and move it to the first position of l_b.
  -  ra :\
       rotate l_a toward the beginning, the first element will become the last.
  -  rb :\
       rotate l_b toward the beginning, the first element will become the last.
  -  rr :\
       'ra' and 'rb' at the same time.
  -  rra :\
       rotate l_a toward the end, the last element will become the first.
  -  rrb :\
       rotate l_b toward the end, the last element will become the first.
  -  rrr :\
       'rra' and 'rrb' at the same time.

If the list is empty nothing will happen.

Usage :
     ```make``` to create Bin
     
./my_pushswap N

N can be :
  -  A file of numbers
  -  Number(s) directly paste into command line
