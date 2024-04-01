# Ex.No: 6   Logic Programming – Factorial of number   
### DATE:18/3/2024                                                                            
### REGISTER NUMBER : 212221060074
### AIM: 
To  write  a logic program  to solve Towers of Hanoi problem  using SWI-PROLOG. 
### Algorithm:
1. Start the program
2.  Write a rules for finding solution of Towers of Hanoi in SWI-PROLOG.
3.  a )	If only one disk  => Move disk from X to Y.
4.  b)	If Number of disk greater than 0 then
5.        i)	Move  N-1 disks from X to Z.
6.        ii)	Move  Nth disk from X to Y
7.        iii)	Move  N-1 disks from Y to X.
8. Run the program  to find answer of  query.

### Program:
``` .py
factorial(0,1).
factorial(A,B) :-  
           A > 0, 
           C is A-1,
           factorial(C,D),
           B is A*D.
```

### Output:
![image](https://github.com/GuruSelvam2003/AI_Lab_2023-24/assets/159774358/81ac7fb4-3cc4-49f2-a034-5ae93344790f)



### Result:
Thus the solution of Towers of Hanoi problem was found by logic programming.
