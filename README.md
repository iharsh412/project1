# project1
overview of game
#include<stdlib.h>
#include<stdio.h>
#include<time.h>

//Compiler version gcc  6.3.0

int main()
{int a,b,c;
srand(time(NULL));
c=rand()%6;

  printf("           CHOOSE and WIN\n");
  printf("you have to choose a no. between 0 to 5 \n");
  printf(" how many round you want to play\n");
  scanf("%d",&a);
  while(a--){
  printf("now, choose your number\n");
  scanf("%d",&b);
    if(b==c)
    printf("you win\n");
    else if(b>=6)
    printf("please read the instruction carefully\n");
    else 
   { printf("you lose\n");
    printf("number is %d\n",c);
  }
  
  }
  printf("\nGame over");
return 0;
}


