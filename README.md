# CDS-experiment-2
Aim:To study and implement C++ Program Structure (Data Types) an storage class.<br>

Theory:<br>
In C++, data types have specific sizes which determine how much memory is allocated for each type. For example, an int typically uses 4 bytes, char uses 1 byte, float uses 4 bytes, and double uses 8 bytes. Sizes can vary based on the system and compiler.<br>

Storage classes define the scope, visibility, and lifetime of variables/functions. <br> The four storage classes are:<br>

auto: Default for local variables.<br>
static: Retains value between function calls, local to the file if used in global context.<br>
extern: Extends visibility across multiple files.<br>
register: Suggests storing variable in a CPU register for faster access, though modern compilers often ignore this.<br>
These classes help manage how and where data is stored and accessed within a program.<br>
Code for the program:<br>
Size of Datatypes:<br>

Code:- <br>
#include <iostream>
using namespace std;

int main() 
{
    char a = 's';
    cout << "The size of a character is: "<< sizeof(a) << endl;
    int b = 123456;
    cout << "The size of an integer is: "<< sizeof(b) << endl;
    short int c = 1233;
    cout << "The size of a short integer is: "<< sizeof(c) << endl;
    long int d = 12739482;
    cout << "The size of a long integer is: "<< sizeof(d) << endl;
    long long int e = 122388728;
    cout << "The size of a long long integer is: "<< sizeof(e) << endl;
    float f = 27168.5;
    cout << "The sie of a float is: " << sizeof(f) << endl;
    double g = 84273923.89877;
    cout <<"The size of a double floating point is: "<< sizeof(g) << endl;
    long double h = 8742980.789793;
    cout<< "The size of long double floating point is: "<<sizeof(h) << endl;
    cout<< "The size of a wide character is: "<<sizeof(wchar_t) << endl;
    return 0;
}


Conclusion:- in this experiment we learnt to check the size of data types and made program using storage class
