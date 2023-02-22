// grading system 
 #include <stdio.h>
int main()
{
int m1,m2,m3;
float percentage;
printf("Enter the marks of m1\n");
scanf("%d",&m1);
printf("Enter the marks of m2\n");
scanf("%d",&m2);
printf("Enter the marks of m3\n");
scanf("%d",&m3);
percentage=(m1+m2+m3)/3;
printf("percentage=%f\n",percentage);
if(percentage>=70)
{
    printf("Grade A");
}
else if(percentage>60&&percentage<=69)
{
    printf("GRADE B");
}
else if(percentage>50&&percentage<=59)
{
    printf("GRADE C");
}
else if (percentage>40&&percentage<=49)
{
printf("GRADE C");
}
else if(percentage>0&&percentage<=39)
{
    printf("FAIL");
}
return 0;
}
