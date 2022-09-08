# String
This is a program for printing name using string using function and different format specifier such as gets and puts in C programming.
#include <stdio.h>
int main()
{
    char s[10];
    printf("Enter string:");
    gets(s);
    printf("Using custom function prints:\n");
    prints(s);
    printf("Using printf %s\n", s);
    printf("Using puts:\n");
    puts(s);
    return 0;
}
void prints(char s[])
{
    int i;
    for (i = 0; s[i] != '\0'; i++)
    {
        printf("%c", s[i]);
    }
    printf("\n");
}
