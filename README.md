#include <stdio.h>
#include <conio.h>

int main()
{
    printf( " Berikut adalah bilangan genap dari 1 - 20\n");
    for (int i=1;i<=20;i++)
    if (i%2==0)
    {
        printf( "\n%d",i);
    }
    getch();
}
