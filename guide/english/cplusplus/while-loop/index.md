---
title: While-loop
---

A while loop statement repeatedly executes a target statement as long as a given condition is true. It is often used when the number of iterations is unknown.

Syntax:
```cpp
while(condition) {
   statement(s);
}
```

A key point of the while loop is that the loop might not ever run.
When the condition is tested and the result is false, the loop body will be skipped and the first statement after the while loop will be executed.

Another important point about the while loop is to remember to increment/decrement/modify the variable used for checking the given condition at the beginning of each iteration, at the end of your loop, otherwise the loop will enter into an infinite loop.

Example:

```cpp
#include <iostream>
using namespace std;

int main () {
   // Local variable declaration:
   int a = 10;

   // while loop execution
   while( a < 20 ) {
      cout << "value of a: " << a << endl;
      a++;
   }

   return 0;
}
```

Output:

```
value of a: 10
value of a: 11
value of a: 12
value of a: 13
value of a: 14
value of a: 15
value of a: 16
value of a: 17
value of a: 18
value of a: 19
```

Example of Skipped Loop Body:
```cpp
#include<iostream>
using namespace std;

int main(){
   //Local variable declaration
   int age=10;
   
   //while loop execution
   while(age>21) {
   cout<<"The citizen is an adult."<<endl;
   }
   
   return 0;
}
```

Output:

```
```

### Sources
* www.tutorialspoint.com
