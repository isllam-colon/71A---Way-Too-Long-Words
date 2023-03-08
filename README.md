# 71A---Way-Too-Long-Words
71A - Way Too Long Words sol
#include <iostream>
using namespace std;
int main() {
int num,i;
string s;
cin>>n;
for(i=0; i<num ;i++)
{
    cin>>s;
    if(s.length()>10)
    {
        cout<< s[0] << s.length() - 2 << s[s.length() - 1 ]<< endl;
    }
    
    else
    {
        cout<< s << endl;
    }
    
}

    return 0;
}
