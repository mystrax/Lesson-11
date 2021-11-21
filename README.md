# Lesson-11
while loops-Rising stars


while loops-Falling Stars
   
    #include <iostream>
    using namespace std;
    int main() {
        int i = 1;
        int j = 1;
        while (i <= 5) {
            j = i;
            while (j <= 5) {
                cout << "*";
                j++;
            }
            cout << endl;
            i++;
        }
        return 0;
    }

while loop- rise and fall

      #include <iostream>
      using namespace std;
      int main() {
          int i = 1;
          int j = 1;
          int x = 1;
          int y = 1;
          while (i <= 5) {
              j = i;
              while (j <= i) {
                  cout << "*";
                  j++;
              }
              cout << endl;
              i++;
          }
          while (x <= 5) {
              y = x;
              while (y <= 5) {
                  cout << "*";
                  x++;
              }
              cout << endl;
              y++;
          }
          return 0;
      }
      
Factorial

      #include<iostream>
      using namespace std;
      int main() {

         int num, factorial = 1;
         cout << " Enter Number To Find Its Factorial:  ";
         cin >> num;
         for (int a = 1;a <= num;a++) {
            factorial = factorial * a;
         }
         cout << "Factorial of the number is =" << factorial << endl;
         return 0;
      }
     
  
Table of any given number till 10

      #include <iostream>
      using namespace std;

      int main()
      {
          int n;
          int i;
          cout << "Enter a number that you want with a table of 10: ";
          cin >> n;
          for (int i = 1; i <= 10; ++i)
          {
              cout << n << " * " << i << " = " << n * i << endl;
          }

          return 0;
      }
      
 Table of any given number till 10 While loop
 
       #include <iostream>
      using namespace std;

      int main()
      {
          int n;
          int i = 0;
          cout << "Enter a number that you want with a table of 10: ";
          cin >> n;
          while (i <= 10)
          {
              cout << n << " * " << i << " = " << n * i << endl;
              i++;
          }
          cout << endl;
          return 0;
      }

Table of any given number till 12

      #include <iostream>
      using namespace std;

      int main()
      {
          int n;
          int i;
          cout << "Enter a number that you want with a table of 10: ";
          cin >> n;
          for (int i = 1; i <= 12; ++i)
          {
              cout << n << " * " << i << " = " << n * i << endl;
          }
      
                return 0;
            }
      
Find the 9s

      #include <iostream>
      using namespace std;

      int main()
      {
          int i, sum = 0;
          cout << "Find the number and sum of all integer between 100 and 200, divisible by 9:\n";
          for (i = 101; i < 200; i++)
          {
              if (i % 9 == 0)
              {
                  cout << " " << i;
                  sum += i;
              }
          }
          cout << "The sum" << sum << endl;
      }
