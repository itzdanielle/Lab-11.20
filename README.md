# Lab-11.20
#include <iostream>
#include <string> 
using namespace std;

int main() {
  const int SECRET = 7;
  int number;
  
 cout << "Guess the secret number" << endl;
 cin >> number; 

  while (number != 7) {
   cout << "Incorrect! Try again:" << endl;
   cout << "Guess the secret number" << endl;
   cin >> number; 

 }
 
 cout << "Congratulations!" << endl;


}
