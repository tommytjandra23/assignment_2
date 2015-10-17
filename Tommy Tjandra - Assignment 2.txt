#include <iostream>

using namespace std;

int main()
{
   int myId = 20250853;
   int nLet = 7;

   cout << "My last (family) name is Tjandra\n";
   cout << "My Foothill Student ID is 20250853\n";
   cout << "The number of characters in my last name is 7\n\n";

   int exOne = myId % 2;

   cout << "Expression #1: " << exOne << endl;

   int exTwo = myId % nLet;

   cout << "Expression #2: " << exTwo << endl;

   double exThree = myId * 1.0 / (nLet * 1.0 + 1000);

   cout.setf(ios::fixed);
   cout.precision(12);

   cout << "Expression #3: " << exThree << endl;

   int exFour = 1 + 2 + 3 + 4 + 5 + 6 + nLet;

   cout << "Expression #4: " << exFour << endl;

   double exFive = 10000.0 / (99.0 + (((myId - 543210) * 1.0) /

                                      ((nLet + 30) * (nLet + 30))));

   cout << "Expression #5: " << exFive << endl;

   return 0;

}

/* ------------------------------- Paste of Run ------------------------------
 
My last (family) name is Tjandra
My Foothill Student ID is 20250853
The number of characters in my last name is 7

Expression #1: 1
Expression #2: 0
Expression #3: 20110.082423038730
Expression #4: 28
Expression #5: 0.689909789633

--------------------------------------------------------------------------- */
