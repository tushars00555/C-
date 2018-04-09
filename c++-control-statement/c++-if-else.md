# C++ if-else

In C++ programming, if statement is used to test the condition. There are various types of if statements in C++.

* if statement
* if-else statement
* nested if statement
* if-else-if ladder

## C++ IF Statement

The C++ if statement tests the condition. It is executed if condition is true.

if\(condition\){

//code to be executed

}

## C++ If Example

\#include &lt;iostream&gt;

using  namespace std;

int  main \(\) {

int num = 10;

if \(num % 2 == 0\)

{

```
cout<<"It is even number";
```

}

return 0;

}

**Output:**

```cpp
It is even number




```

## C++ IF-else Statement

The C++ if-else statement also tests the condition. It executes if block if condition is true otherwise else block is executed.

if\(condition\){    

//code if condition is true  

}else{    

//code if condition is false  

} 

## C++ If-else Example

\#include &lt;iostream&gt;

using  namespace std;  

int main \(\) {  

int num = 11;    

if \(num % 2 == 0\)    

   {    

      cout&lt;&lt;"It is even number";    

}   else{   

cout&lt;&lt;"It is odd number";    }  

return 0;  

}  

Output:

```
It is odd number
```

## C++ If-else Example: with input from user

\#include &lt;iostream&gt;

using namespace std;  

int main \(\) {  

int num;  

cout&lt;&lt;"Enter a Number: ";  

    cin&gt;&gt;num;  

if \(num % 2 == 0\)    

            {    

                cout&lt;&lt;"It is even number"&lt;&lt;endl;    

            }   else

            {    

                cout&lt;&lt;"It is odd number"&lt;&lt;endl;    

            }  

return 0;  

}  

Output:

```
Enter a number:11
It is odd number

```

Output:

```
Enter a number:12
It is even number

```

## C++ IF-else-if ladder Statement

The C++ if-else-if ladder statement executes one condition from multiple statements.

if\(condition1\){    

//code to be executed if condition1 is true  

}else if\(condition2\){    

//code to be executed if condition2 is true  

}    else if\(condition3\){    

//code to be executed if condition3 is true  

}    

...    

else{    

//code to be executed if all the conditions are false  

}    

## C++ If else-if Example

\#include &lt;iostream&gt;

using namespace std;  

int main \(\) {  

int num;  

       cout&lt;&lt;"Enter a number to check grade:";    

       cin&gt;&gt;num;  

if \(num &lt;0 \|\| num &gt;100\)    

{    

   cout&lt;&lt;"wrong number";   

}    else if\(num &gt;= 0 && num &lt;50\){    

cout&lt;&lt;"Fail";    

 }    else if\(num &gt;= 50 && num &lt;60\)    

{                   

 cout&lt;&lt;"D Grade";    

 }    else if\(num &gt;= 60 &&num &lt;70\)    

            {    

cout&lt;&lt;"C Grade";    

}    else if\(num &gt;= 70 &&num &lt;80\)    

{    

   cout&lt;&lt;"B Grade;    

}    else if \(num &gt;= 80 &&num &lt;90\)    

{                    cout&lt;&lt;"A Grade";    

           

}    else if\(num &gt;= 90 &&num &lt;= 100\)    

{                    cout&lt;&lt;"A+ Grade";           

   }    

    }    

Output:

```
Enter a number to check grade:66
C Grade


Output:
Enter a number to check grade:-2
wrong number
```

```

```







