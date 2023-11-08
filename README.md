# kimkimkim
markdown
#include <stdio.h>

int total(int n)
{
  int i;
  int hap = 0;

  for(i = 1; i <= n; i++)
    {
      hap = hap+1;
    }

  return hap;
}

int total_recurcion(int n)
{
  if(n==1)
  {
    return 1;
  }
  else
  {
    re   
  }
}
int main(void) {

  int number;
  
  printf("number? ");
  number = scanf("%d", &number);

  printf("sum from 1 to %d: %d\n", number, total(number));
  return 0;
}

#include <stdio.h>

void add_up()
{
  int a = 1;
  int b = 1;

  a = a + 1;
  b = b + 1;
  printf("a = %d\n", a);
  printf("b = %d\n\n", b);
}


int main() {

 add_up();
 add_up();
 add_up();
  
  return 0;
}
#include <stdio.h>

void add_up()
{
  int a = 1;
  int b = 1;

  a = a + 1;
  b = b + 1;
  printf("a = %d\n", a);
  printf("b = %d\n\n", b);
}


int main() {

 add_up();
 add_up();
 add_up();
  
  return 0;
}

#include <stdio.h>

void add_up()
{
  static int a = 1;
  int b = 1;

  a = a + 1;
  b = b + 1;
  printf("a = %d\n", a);
  printf("b = %d\n\n", b);
}


int main() {

 add_up();
 add_up();
 add_up();
  
  return 0;
}
