# Ex.No: 5   Logic Programming – Factorial of number   
### DATE:08-04-2025                                                                            
### REGISTER NUMBER:212222060293 
### AIM: 
To  write  a logic program for finding the factorial of given number using SWI-PROLOG. 
### Algorithm:
1. STEP 1: Start the program
2. STEP 2:  Write a rules for finding factorial of given program in SWI-PROLOG.
3.   a)	factorial of 0 is 1 => written as factorial(0,1).
4.   b)	factorial of number greater than 0 obtained by recursively calling the factorial    function.
5. STEP 3: Run the program  to find answer of  query.
6. STEP 4: Stop the program.

### Program:
```
factorial(0, 1).
factorial(N, F) :-
    N > 0,
    N1 is N - 1,
    factorial(N1, F1),
    F is N * F1.
```

### Output:
![image](https://github.com/user-attachments/assets/1616aac6-df4b-4b90-a05a-e39906a0e0ae)

### Result:
Thus the factorial of given number was found by logic programming. 
