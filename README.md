# assignment2.
1. Find the output for this code. Let input:- 2 3 6


#include <iostream>
using namespace std;
int main()
{
int x;
cout << "Enter first number\n";
cin >> x; // user will give ‘x’ a value.
int y, m;
cout << "Enter second number and value for taking modulus\n";
cin >> y >> m; // user will give ‘y’ a value.
int Z = (x * y) % m;
cout << "Output is: " << Z;
}


output = 0     




2. Find the output for this code. Let input:- 3 2

#include <iostream>
using namespace std;
int main()
{
int x;
cout<<"Enter first number\n";
cin>>x; // user will give 'x' a value.
int y;
cout<<"Enter second number\n";
cin>>y; // user will give 'y' a value.
cout<<(x!=y)<<" "<<(x>=y);
}


output = 1  0






3. Find the output for this code. Let input:- 2 3


#include <iostream>
using namespace std;
int main()
{
int x,y;
cin>>x>>y;
x+=y;
x-=y;
x%=y;
cout<<x;
}


output = 2





 solution 4. WAP for finding the volume of the cylinder by taking radius and height as input.

#include<iostream>
using namespace std;
int main(){
    float r;
    cout<<"Enter the value of radius: ";
    cin>>r;

    float h;
    cout<<"Enter the value of height: ";
    cin>>h;

    float volume;
    volume = 3.14 * r*r*h;

    cout<<"The volume of the given cylinder is: ";
    cout<<volume;


}



solution 6.  couldn't make the program.


 6. Find the output of the below code


#include <iostream>
using namespace std;
int main()
{
int i = ( 4 + 7 / 5 * 6 * 6+9 )% 100 ;
cout<<i;
}



output = 49






