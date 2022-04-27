#include <stdio.h>

int main() {

  char choice;
  double first, second;
  printf("Enter your choice of operation(+, -, *, /): ");
  scanf("%c", &choice);
  printf("Enter two numbers: ");
  scanf("%lf %lf", &first, &second);

  switch (choice) {
    case '+':
      printf("%.1lf + %.1lf = %.1lf", first, second, first + second);
      break;
    case '-':
      printf("%.1lf - %.1lf = %.1lf", first, second, first - second);
      break;
    case '*':
      printf("%.1lf * %.1lf = %.1lf", first, second, first * second);
      break;
    case '/':
      printf("%.1lf / %.1lf = %.1lf", first, second, first / second);
      break;
    default:
      printf("Error! operator is not correct");
  }

  return 0;
}