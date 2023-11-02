# EX-06-6c-STUDENT-INFORMATION-USING-STRUCTURE
## AIM 
To write a C Program to store the student information and display it using 
structure. 
## ALGORITHM 
1. Start the program. 
2. Create a student structure with name, roll number and marks as members. 
3. Using structure variable read the structure members and print them. 
4. Stop the program. 
## PROGRAM 
```
#include<stdio.h> 
struct student 
{ 
 char name[50]; 
 int rno; 
 float marks; 
}s; 
int main() 
{ 
 scanf("%s %d %f",s.name,&s.rno,&s.marks); 
 printf("Displaying Information:\n"); 
 printf("Name: %s\n Roll number: %d\n Marks: %.1f ",s.name,s.rno,s.marks); 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/EX-06-6c-STUDENT-INFORMATION-USING-STRUCTURE/assets/118899387/efcb75b1-ffee-4d36-b81a-e055169cd524)
## RESULT 
Thus the program to store the student information and display it using structure 
has been executed successfully
