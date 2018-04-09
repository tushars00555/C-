# C++ While loop

In C++, while loop is used to iterate a part of the program several times. If the number of iteration is not fixed, it is recommended to use while loop than for loop.

while\(condition\){    

//code to be executed  

}    

## C++ While Loop Example

\#include &lt;iostream&gt;

using namespace std;  

int main\(\) {         

int i=1;      

while\(i&lt;=10\)   

       {      

            cout&lt;&lt;i &lt;&lt;"\n";    

            i++;  

          }       

    }  

Output:

```
1
2
3
4
5
6
7
8
9
10

```

## C++ Nested While Loop Example

In C++, we can use while loop inside another while loop, it is known as nested while loop. The nested while loop is executed fully when outer loop is executed once.

\#include &lt;iostream&gt;

using namespace std;  

int main \(\) {  

int i=1;      

while\(i&lt;=3\)     

          {    

int j = 1;    

while \(j &lt;= 3\)    

{                  cout&lt;&lt;i&lt;&lt;" "&lt;&lt;j&lt;&lt;"\n";      

            j++;  

          }     

           i++;  

        }  

    }    

Output:

```
1 1
1 2
1 3
2 1
2 2 
2 3
3 1
3 2
3 3

```



