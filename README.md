#include <iostream>
#include<array>
#include<cstring>
#include<algorithm>
using namespace std;
int main()
{
cout<<"\"for loop\""<<"\n";
int i=0;
for(;;)
{
    if(i==11)
    {
        break;
    }
        cout<<i<<"\n";
   i ++;
}
i=0;

cout<<"\"while loop\""<<"\n";

while(i<=10)
{
    cout<<i<<"\n";
    i++;
}
cout<<"\"do while loop\""<<"\n";
i=0;
do
{
  cout<<i<<"\n";
  i++;
}while(i<11);
    return 0;
}
