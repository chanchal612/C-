# C-
## Programme 1 
```
#include <iostream>
using namespace std;
int globalVar = 10;
int main() {
    int localVar = 20;
    int* heapVar = new int(30);

    cout << "Address of Global Variable  : " << &globalVar << endl;
    cout << "Address of Local Variable   : " << &localVar << endl;
    cout << "Address of Heap Variable    : " << heapVar << endl;

    return 0;
}
```
## Programme 2
```
#include <iostream>
using namespace std;

int main() {
    int c = 25;      
    int* a = &c;   

    cout << "Value of variable c        : " << c << endl;
    cout << "Address of variable c      : " << &c << endl;
    cout << "Value in pointer a: " << a << endl;

    return 0;
}
```
## Program 3
```
#include <iostream>
using namespace std;

int main() {
    int c = 25;      
    int* a = &c;   
    int b;
    
    b =*a;

    cout << "Value of variable c        : " << c << endl;
    cout << "Address of variable c      : " << &c << endl;
    cout << "Value in pointer a: " << a << endl;
    cout << "Value copied to b : " << b << endl;

    return 0;
}
```
## Programme 4
output:
```
What will be the output:
int x = 5;
int *p = &x;
*p = 10;
cout << x;
```
input:
10
## Programme 5
output:
```
int a = 1, b = 2;
int *p = &a;
p = &b;
*p = 5;
cout << a << " " << b;
```
input:
1 5
