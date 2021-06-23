# C-2
Multiply two numbers
#include <iostream>
using namespace std;

int main()
{
    double firstNumber, secondNumber, productOfTwoNumbers;
    cout << "Enter two numbers: ";

    // Stores two floating point numbers in variable firstNumber and secondNumber respectively
    cin >> firstNumber >> secondNumber;
 
    // Performs multiplication and stores the result in variable productOfTwoNumbers
    productOfTwoNumbers = firstNumber * secondNumber;  

    cout << "Product = " << productOfTwoNumbers;    
    
    return 0;
}


OUTPUT-

Enter two numbers: 3.4
5.5
Product = 18.7
