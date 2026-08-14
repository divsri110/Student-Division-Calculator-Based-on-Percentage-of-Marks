# Student-Division-Calculator-Based-on-Percentage-of-Marks
A C program that takes marks in five subjects as input, calculates the overall percentage, and determines the student's division (First, Second, Third, or Fail) using conditional statements based on standard percentage cutoffs.


// Method 2: Short Method

#include <stdio.h>
#include <math.h>

int main(){
int m1, m2, m3, m4, m5, per;

printf("Enter the marks in five subjects");
scanf("%d%d%d%d%d", &m1, &m2, &m3, &m4, &m5);

per=(m1+m2+m3+m4+m5)*100/500;

if (per>=60)
printf("First Division\n");

if ((per>=50)&&(per<60))
printf("Second Division\n");

if ((per>=40)&&(per<50))
printf("Third Division\n");

if(per<40)
printf("Fail\n");

return 0;

}
