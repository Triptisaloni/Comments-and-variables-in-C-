# Comments-and-variables-in-C-

2.Comments

Single line comment begins with double slash //
Eg.  //……………..
Multiple line comment begins with /* and end with */
Eg.  /*………………
     …………………..*/
Adding comments to your code is good practice

3.Variables

As like in C, variable is declared just same. C++ is case-sensitive
int a;
int a = 10;
Eg . int main()
{ int a = 10;
cout<< a << endl ;    // Outputs 10
return 0;
}

Operation using variables
#include<iostream>        
using namespace std;
int main()
{
    int a = 10, b= 5, sum;
    sum = a+b;
    cout<<sum;
return 0;
}

User Input
#include<iostream>        
using namespace std;
int main()
{
    int a;
cout << “Enter a value”;
cin >> a;
return 0;
}

Printing multiple outputs
#include<iostream>        
using namespace std;
int main()
{
int a=15 , b=5 , sum ;
sum = a+b;
cout << “Sum is equal to” << sum << endl;
return 0;
}

Increment and Decrements (Prefix and Postfix)
#include<iostream>                    
using namespace std;
int main()
{
int a=10;
a++;
cout << a << endl;
return 0;
}

4.Decision Making (same as C)

If statement
If else statement
While loop
For loop
For(initialization; condition; increment)
{  //statement;   }
Do while loop
do
{
statement;   }
While ( condition )
