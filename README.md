# grading-of-student-marks
developed by swathi
#include<stdio.h>
void main()
{
int marks;
printf("enter your marks:");
scanf("%d",&marks);
if(marks<0)
{
printf("wrong entry");
}
elseif(marks<40)
{
printf("Grade F");
}
elseif(marks>=54 && marks<69)
{
printf("Grade D");
}
elseif(marks>=69 && marks<84);
{
printf("Grade C");
}
elseif(marks>=84 && marks<100);
{
printf("Grade B");
}
elseif(marks<=100 && marks>=85);
{
printf("Grade A");
}
getch();
}
