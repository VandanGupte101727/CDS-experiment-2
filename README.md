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

CODE:-#include <iostream>
using namespace std;
int main()
{
    int a;
    char b;
    short int c;
    long int d;
    float e;
    double f;
    wchar_t g;
    signed short int h;
    unsigned short int i;
    signed long int j;
    unsigned long int k;
    long long int l;
    unsigned long long int m;
    long double n;
    cout<<"Size of integer: "<<sizeof(a)<<" bytes"<<endl;
    cout<<"Size of character: "<<sizeof(b)<<" byte"<<endl;
    cout<<"Size of short int: "<<sizeof(c)<<" bytes"<<endl;
    cout<<"Size of long int: "<<sizeof(d)<<" bytes"<<endl;
    cout<<"Size of float: "<<sizeof(e)<<" bytes"<<endl;
    cout<<"Size of double: "<<sizeof(f)<<" bytes"<<endl;
    cout<<"Size of wide character: "<<sizeof(g)<<" bytes"<<endl;
    cout<<"Size of signed short int: "<<sizeof(h)<<" bytes"<<endl;
    cout<<"Size of unsigned short int: "<<sizeof(i)<<" bytes"<<endl;
    cout<<"Size of signed long int: "<<sizeof(j)<<" bytes"<<endl;
    cout<<"Size of unsigned long int: "<<sizeof(k)<<" bytes"<<endl;
    cout<<"Size of long long int: "<<sizeof(l)<<" bytes"<<endl;
    cout<<"Size of unsigned long long int: "<<sizeof(m)<<" bytes"<<endl;
    cout<<"Size of long double: "<<sizeof(n)<<" bytes"<<endl;
    return 0;

}

Conclusion:- in this experiment we learnt to check the size of data types and made program using storage class
