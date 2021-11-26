- 👋 Hi, I’m @CodewothArjun
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...


Programming with C language

#include<stdio.h>
#include<conio.h>
int main()
 {
   int a,b,sum;
   printf("Enter two numbers:");
   scanf("%d,%d",&a,&b");
   sum=a+b;
   printf("sum of number=%d", sum);
   return 0;
 }
   
Transpose Matrix

#include<stdio.h>
#include<conio.h>
int main() {
    int i,j,r,c;
    int mat[20],tmat[2];
    printf("Enter number of rows and column: ");
    scanf("%d %d",&r,&c);

    for(i=0; i<r; i++) {
        for(j=0; j<c; j++) {
            printf("mat[%d][%d]",i+1,j+1);
            scanf("%d",&mat[i][j]);
        }
    }

    for(i=0; i<r; i++) {
        for(j=0; j<c; j++) {
            tmat[j][i]=mat[i][j];

        }
    }
    for(i=0; i<r; i++) {
        for(j=0; j<c; j++) {
            printf("%d",tmat[i][j]);
        }
        printf("\n");
    }
    return 0;

}

MY name is arjun.

