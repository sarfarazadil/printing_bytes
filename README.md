# printing_bytes

#include <stdio.h>

int main() {
   
  int a=400;
  char* p=(char*)&a;
  int n = sizeof(int); 

  for(int index=0;index < n ;index++){
        printf("%u---> %d \n",p,*p);
        p++;
  }

  return 0;
}
