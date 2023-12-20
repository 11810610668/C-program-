[20/12, 10:51 am] Mahasri Ksr Clg: #include <stdio.h>
#include <math.h>
int main()
{
    int a;
    a=sqrt(4);
    printf("%d",a);
    

    return 0;
}
[20/12, 10:51 am] Mahasri Ksr Clg: #include <stdio.h>
void main()
{
    int a;
    printf ("Enter the number :");
    scanf("%d",&a);
    printf ("\ngiven no :%d",a);
    inc (a);
    printf("\nafter increment %d",a);
}
  void inc (int a)
  {
      a=a+1;
      printf("\nincrement value is %d",a);
  }
[20/12, 10:51 am] Mahasri Ksr Clg: #include <stdio.h>
void area ()
{
    int a=5;
    a=a*a;
    printf("area of square is %d",a);
}
void main()
{
    area();
}
[20/12, 10:51 am] Mahasri Ksr Clg: include <stdio.h>
void main()
{
    int a;
    printf ("Enter the number :");
    scanf("%d",&a);
    printf ("\ngiven no :%d",a);
    inc (&a);
    printf("\nafter increment %d",a);
}
  void inc (int *a)
  {
      *a=*a+1;
      printf("\nincrement value is %d",*a);
  }
[20/12, 10:51 am] Mahasri Ksr Clg: #include <stdio.h>
int area (int a)
{
    int c;
    c=a*a;
    return c;
    
}
int main()
{
     int a=5,d;
     d= area(a);
    printf("area of square is %d",d);
}
