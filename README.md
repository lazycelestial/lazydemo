#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
void main()
{
    int a;
    while(1)
    {
        printf("Who is the PM of India : ");
        printf("\n1. Lalu Yadav\n2. Yogi Adityanath\n3. Narendra Modi\n4. Arvind Kejrival\n");
        scanf("%d", &a);
        switch(a)
        {
            case 1:
                printf("Chal Jhaatu");
                break;
            case 2:
                printf("Kuch aur choose kar");
                break;
            case 3;
                printf("Jai Mata Di");
                break;
            case 4:
                printf("Nitish Kumar Zindabad");
                break;
            Default:
                printf("bsdk sahi imput daal");
        }
        printf("\n");
     }
     getch();
}