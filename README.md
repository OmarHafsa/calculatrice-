#include<stdio.h>
#include<math.h>
struct calculatrice{
int n1;
char opérateur;
int n2;
};
int main(){
int r;
struct calculatrice calc;
scanf("%d",&calc.n1);
scanf("%s",&calc.opérateur);
scanf("%d",&calc.n2);

switch(calc.opérateur){
case'+':
r=calc.n1+calc.n2;

break;
case'*':
r=calc.n1*calc.n2;

break;
case'-':
r=calc.n1-calc.n2;

break;
case'/':
r=calc.n1/calc.n2;

break;
case'^':
r=pow(calc.n1,calc.n2);
break;
}
printf("%d",r);
return 0;
}# calculatrice-
