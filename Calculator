#include <iostream>
#include <stdio.h>
#include <cstdlib>
#include <conio.h>

using namespace std;

float x,y;
char chose;


int main()
{
for(;;)
    {
    cout << "Enter 1 number: " << endl;
    cin>>x;
    cout<<"Enter 2 number: "<< endl;
    cin>>y;

    cout<<endl;
    cout<<" Menu" << endl;
    cout<<"-------------" << endl;
    cout<<"1. Addition" << endl;
    cout<<"2. Subtraction" << endl;
    cout<<"3. Multiplication" << endl;
    cout<<"4. Division" << endl;
    cout<<"5. End session" << endl;


    cout<< endl;
    chose=getch();

switch(chose)
        {
    case '1':
        cout<<"Sum = "<<x+y;
    break;

    case '2':
        cout<<"Subtraction = "<<x-y;
    break;

    case '3':
        cout<<"Multiplication = "<<x*y;
    break;

    case '4':
        if (y==0) cout<<"You cant divide by 0!" ;
        else cout<<"Division = "<<x/y;
    break;

    case '5':
        exit(0);
    break;

    default: cout<<"That's not an option!" <<endl;
        }
    getchar();getchar();
    system("cls");
    }
    return 0;
}
