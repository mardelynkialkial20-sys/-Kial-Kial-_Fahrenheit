#include <stdio.h>

int main() {

   float fahrenheit;
   float celsius;
    
   printf("Enter the fahrenheit value: ");
   scanf("%f", &fahrenheit);
    
   printf("Fahrenheit = %.2f\n", fahrenheit);
   
   celsius =(fahrenheit - 32) * 5 / 9;
     
   
   printf("Celsius = %.2f\n", celsius);
        
        
    return 0;
}