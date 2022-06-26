#include <stdio.h>

int main() {
  int category;
  int temperatureChoice;
  int currencyChoice;
  int VolumeChoice;
  int userinputF; 
  int userinputC; 
  int userinputUSDtoEuro;
  int userinputUSDtoJPY; 
  int userinputUSDtoINR; 
  int userinputLiter;
  int userinputliter;
  int fahrenheitToCelcius;
  int celciusToFahrenheit; 
  float USDtoEURO ; 
  float USDtoJPY;
  float USDtoINR;
  float litertogallon;
  float litertoounce;

  printf("Welcome to Unit Converter! \n\n\n");
  printf("Please enter the Number you want to convert.\n\n");
  printf("Temperature(1),Volume(2),Currency(3) \n");
 
  scanf("%d",&category);
  
  if(category == 1){
      printf("Temperature Converter! \n");
      printf("Choose the conversion: \n");
      printf("Press 1 for Fahrenheit to Celsius. \n");
      printf("Press 2 for Celsius to Fahrenheit. \n");
      scanf("%d",&temperatureChoice);
      if(temperatureChoice == 1){
          printf("Please enter the Fahrenheit degree: \n");
          scanf("%d",&userinputF);
          fahrenheitToCelcius =  ((userinputF-32) * (5.0/9.0));
          printf("Celcius: %d",fahrenheitToCelcius);
      }
      else if(temperatureChoice == 2){
        printf("Please enter the Celcius degree: \n");
        scanf("%d",&userinputC);
        celciusToFahrenheit = ((9.0/5.0)*userinputC + 32);
        printf("Fahrenheit: %d",celciusToFahrenheit);
      }
      else
        printf("Enter Valid Choice \n");
  }
    else if(category == 2){
      printf("Volume Converter! \n");
      printf("Here is a list of conversations to choose from: \n");
      printf("Press 1 for liter to gallon. \n");
      printf("Press 2 for liter to volume ounce. \n");
      scanf("%d",&VolumeChoice);
      if(VolumeChoice == 1){
          printf("Please enter the amount in liter: \n");
          scanf("%d",&userinputLiter);
          litertogallon = userinputLiter * 0.264172;
          printf("Pounds: %.2f",litertogallon);
      }
      else if(VolumeChoice == 2) {
          printf("Please enter the gram amount: \n");
          scanf("%d",&userinputliter);
          litertoounce = userinputliter * 33.814;
          printf("Pounds: %.2f",litertoounce);
      }
      else 
        printf("Enter Valid Choice \n");
   }
  
  else if(category == 3) {
      printf("Currency Converter! \n");
      printf("Here is a list of conversations to choose from: \n");
      printf("Press 1 for USD to INR. \n");
      printf("Press 2 for USD to JPY. \n");
      printf("Press 3 for USD to Euro. \n");
      scanf("%d",&currencyChoice);
      if(currencyChoice == 1){
        printf("Please enter the USD amount: \n");
        scanf("%d",&userinputUSDtoINR);
        USDtoINR = userinputUSDtoINR * 78.0;
        printf("RMB: %.2f",USDtoINR);
      }
      else if(currencyChoice == 2){
          printf("Please enter the USD amount: \n");
          scanf("%d",&userinputUSDtoJPY);
          USDtoJPY = userinputUSDtoJPY * 111.09;
          printf("JPY: %.2f",USDtoJPY);
      }
      else if(currencyChoice == 3) {
          printf("Please enter the USD amount: \n");
          scanf("%d",&userinputUSDtoEuro);
          USDtoEURO = userinputUSDtoEuro * 0.87;
          printf("Euro: %.2f",USDtoEURO);
        
      }
      else
        printf("Enter Valid Choice \n");
   }

  return 0;
}
