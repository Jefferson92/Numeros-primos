# Numeros-primos
Meu 1º repositório no github

#include <stdio.h>
int main()
    { 
      int n1,n2, x,y, i;

      scanf("%d",&n1);

       for(i=1;i<=n1;i++){
       x=0;
       scanf("%d",&n2);
       
        for(y=1;y<=n2;y++){                      
        if(n2%y==0){
        x++;
        }
        }
     if(x==2){
              printf("%d eh primo\n",n2);
              }
      
     else{
          printf("%d nao eh primo\n",n2);
          }
         }
   }
