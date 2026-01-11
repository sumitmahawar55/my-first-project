#include <stdio.h>
#include <conio.h>
#include <string.h>

void main() {
    char str1[100], str2[100];

    clrscr();
    printf("Enter first string: ");
    gets(str1);

    printf("Enter second string: ");
    gets(str2);

    // Concatenate second string to first string
    strcat(str1, str2);

    printf("\nAfter concatenation, string is: %s", str1);

    getch();
}

