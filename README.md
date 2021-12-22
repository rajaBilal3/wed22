# pointers
#include <iostream>

using namespace std;

int main() { 
    cout<<"Hello World"; 
    int num = 23;
    int *p;
    int **dp;
    
    dp=&p;
    cout << "simple "<<num<<endl; 
    cout << "pointer address "<<p<<endl;
    cout << "pointer "<<*p<<endl; 
    cout << "D pointer"<<dp<<endl;
    cout << "D pointer"<<*dp<<endl; 
    cout << "D pointer"<<**dp<<endl;

    return 0;

}
