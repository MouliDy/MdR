#include<iostream>
using namespace std;
 
int main()
{ int n;
    cout << "No. of elements to enter: ";
    cin >> n;
    int a[n];
    cout << "Enter elements: ";
    for( int i=0;i<n;i++)
        cin >> a[i];
    cout << "You entered: ";
    for( int i=0;i<n;i++)
        cout << a[i] << endl;
    return 0;
}
