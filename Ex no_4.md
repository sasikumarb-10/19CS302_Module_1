# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Start. 
2. Declare a variable value of type char. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Check eligible for marriage. 
6. If age >= 21, print "Eligible". 
7. If false, print " Not Eligible". 
8. End.   

## Program:
```
/*
Program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
Developed by: Sasi Kumar B
RegisterNumber:  212223060252
*/

#include<stdio.h> 
int main(){ 
char p1; 
scanf("%c", &p1); 
if(p1>=21) 
{ 
printf("Eligible"); 
}else{
printf("Not Eligible");
return 0; 
}
}
```

## Output:

![Screenshot 2025-05-12 102240](https://github.com/user-attachments/assets/ecd32329-b311-4e50-b030-af87b25baaaf)


## Result:
Thus the program was executed and the output was verified successfully.
