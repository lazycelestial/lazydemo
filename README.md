#include<stdio.h>
#include<conio.h>
void main()
{
    int a;
    
    printf("Who is the PM of India : ");
    printf("\n1. Lalu Yadav\n2. Yogi Adityanath\n3. Narendra Modi\n4. Arvind Kejrival\n");
    printf("\n");
    
    while(1)
    {
        printf("Enter your answer : ");
        scanf("%d", &a);
        
        if (a==0)
            break;
            
        switch(a)
        {
            case 1:
                printf("Galat Jawab (Yadav ji Bihari hai)\n");
                break;
            case 2:
                printf("Kuch aur choose kar\n");
                break;
            case 3:
                printf("Bilkul Sahi Jawab!\n");
                break;
            case 4:
                printf("Wo Muflar wala PM banega? Nice joke!\n");
                break;
            default:
                printf("bsdk sahi imput daal\n");
        }
        printf("\n");
     }
     getch();
}