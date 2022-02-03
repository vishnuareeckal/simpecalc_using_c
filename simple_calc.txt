#include <stdio.h>
void main()
{
  int a,b;
  char op;
  printf("enter an operator(+,-,/,*)");
  scanf("%c",&op);
  printf("enter two numbers");
  scanf("%d %d",&a,&b);
  switch(op)
  {
    case '+':
      printf("%d+%d=%d",a,b,a+b);
      break;
    case '-':
      printf("%d-%d=%d",a,b,a-b);
      break;
    case '/':
      printf("%d/%d=%d",a,b,a/b);
      break;
    case '*':
      printf("%d*%d=%d",a,b,a*b);
      break;
    default:printf("invalid input");
  }
  getchar();
}
