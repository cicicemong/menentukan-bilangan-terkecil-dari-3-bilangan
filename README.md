# menentukan-bilangan-terkecil-dari-3-bilangan


    #include<iostream>
    #include<conio.h>

    int minimum (int a,int b,int c);
    int main (void)
    {
    int a,b,c,min;
    printf("Bilangan 1 : ");scanf("%d",&a);
    printf("Bilangan 2 : ");scanf("%d",&b);
    printf("Bilangan 3 : ");scanf("%d",&c);
    min=minimum(a,b,c);
    printf("Bilangan terkecil adalah : %d",min);
    getch();
    }
        int minimum(int a,int b,int c)
        {
            int min;
            if(a>b){min=b;}
            else
            {
                min=a;
            }
            if(c<min){min=c;}
        }
