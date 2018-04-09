# C++ switch

The C++ switch statement executes one statement from multiple conditions. It is like if-else-if ladder statement in C++.

switch\(expression\){      

case value1:      

//code to be executed;    

break;    

case value2:      

//code to be executed;    

break;    

......      



default:       

//code to be executed if all cases are not matched;    

break;    

}   



## C++ Switch Example

\#include &lt;iostream&gt;

using namespace std;  

int main \(\) {  

int num;  

       cout&lt;&lt;"Enter a number to check grade:";    

       cin&gt;&gt;num;  

switch \(num\)    

          {    

cas 10: cout&lt;&lt;"It is 10"; 

break;    

case 20: cout&lt;&lt;"It is 20"; 

break;    

case 30: cout&lt;&lt;"It is 30"; 

break;    

default: cout&lt;&lt;"Not 10, 20 or 30"; 

break;    

          }    

    }    

Output:

```
Enter a number:
10
It is 10

```

Output:

```
Enter a number:
55
Not 10, 20 or 30

```



