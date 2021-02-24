#include <stdio.h>
#include <math.h>
#include <stdlib.h>
int main(void) 
{
  float a, b, c, x, x1, x2, delta;

  printf("\nDigite o primeiro termo da equacao: ");
  scanf("%f", &a);
  printf("\nDigite o segundo termo da equacao: ");
  scanf("%f", &b);
  printf("\nDigite o terceiro termo da equacao: ");
  scanf("%f", &c);

  delta = b * b - 4 * a * c;
  
  if(delta > 0)
  {
    x1 = (-b + sqrt(delta))/(2*a);
    x2 = (-b - sqrt(delta))/(2*a);
    printf("\nO primeiro resultado da equacao e: %3f",x1);
    printf("\nO segundo resultado da equacao e: %3f",x2);
  }
  if(delta == 0)
  {
    x = (-b) / (2*a);
    printf("\nO unico resultado da equacao e: %3f", x);
  }
  if(delta < 0)
  {
    printf("\nO delta da equacao e igual a 0, portanto, nao ha resultado. ");
  }
  
    return 0;
}
