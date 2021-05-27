# a005: Eva 的回家作業
[a005: Eva 的回家作業](https://zerojudge.tw/ShowProblem?problemid=a005)

~~~ cpp
#include <iostream>
using namespace std;

int main()
{
    float input;
    int a, b, c, d, e, n, i;
    cin >> n;
    i = 0;
    while(n > i)
    {
    cin >> a >> b >> c >> d;
    if(d - c == b - a)
        {e = d + (b - a);}

    if(d % c == b % a)
        {e = d * (b / a);}
    i = i + 1;
    cout << a << " " << b << " " << c << " " << d << " " << e << endl;
    }
return 0;
}
