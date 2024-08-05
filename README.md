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

CODE:-<br>
#include <iostream><br>
using namespace std;<br>
int main()<br>
{<br>
    int a;<br>
    char b;<br>
    short int c;<br>
    long int d;<br>
    float e;<br>
    double f;<br>
    wchar_t g;<br>
    signed short int h;<br>
    unsigned short int i;<br>
    signed long int j;<br>
    unsigned long int k;<br>
    long long int l;<br>
    unsigned long long int m;<br>
    long double n;<br>
    cout<<"Size of integer: "<<sizeof(a)<<" bytes"<<endl;<br>
    cout<<"Size of character: "<<sizeof(b)<<" byte"<<endl;<br>
    cout<<"Size of short int: "<<sizeof(c)<<" bytes"<<endl;<br>
    cout<<"Size of long int: "<<sizeof(d)<<" bytes"<<endl;<br>
    cout<<"Size of float: "<<sizeof(e)<<" bytes"<<endl;<br>
    cout<<"Size of double: "<<sizeof(f)<<" bytes"<<endl;<br>
    cout<<"Size of wide character: "<<sizeof(g)<<" bytes"<<endl;<br>
    cout<<"Size of signed short int: "<<sizeof(h)<<" bytes"<<endl;<br>
    cout<<"Size of unsigned short int: "<<sizeof(i)<<" bytes"<<endl;<br>
    cout<<"Size of signed long int: "<<sizeof(j)<<" bytes"<<endl;<br>
    cout<<"Size of unsigned long int: "<<sizeof(k)<<" bytes"<<endl;<br>
    cout<<"Size of long long int: "<<sizeof(l)<<" bytes"<<endl;<br>
    cout<<"Size of unsigned long long int: "<<sizeof(m)<<" bytes"<<endl;<br>
    cout<<"Size of long double: "<<sizeof(n)<<" bytes"<<endl;<br>
    return 0;<br>

}<br>

Conclusion:- in this experiment we learnt to check the size of data types and made program using storage class
