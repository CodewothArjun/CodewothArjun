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



While	Do VS While

It checks the condition first and then executes statement(s)	This loop will execute the statement(s) at least once, then the condition is checked.

While loop allows initialization of counter variables before starting the body of a loop.	Do while loop allows initialization of counter variables before and after starting the body of a loop.

It is an entry controlled loop.	It is an exit controlled loop.

We do not need to add a semicolon at the end of a while condition.	We need to add a semicolon at the end of the while condition.

In case of a single statement, we do need to add brackets.	Brackets are always needed.

In this loop, the condition is mentioned at the starting of the loop.	The loop condition is specified after the block is executed.

Statement(s) can be executed zero times if the condition is false.	Statement is executed at least once.

Generally while loop is written as:

while (condition) {

Statements; // loop body

}

Generally do while loop is written as:

do{

Statements; //loop body

} while (condition);

