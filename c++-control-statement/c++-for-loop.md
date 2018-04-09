# C++ For Loop

The C++ for loop is used to iterate a part of the program several times. If the number of iteration is fixed, it is recommended to use for loop than while or do-while loops.

The C++ for loop is same as C/C\#. We can initialize variable, check condition and increment/decrement value.



for\(initialization; condition; incr/decr\){    

//code to be executed  

} 

## C++ For Loop Example

\#include &lt;iostream&gt;

using namespace std;  

int main\(\) {  

for\(int i=1;i&lt;=10;i++\){      

            cout&lt;&lt;i &lt;&lt;"\n";      

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

## C++ Nested For Loop

In C++, we can use for loop inside another for loop, it is known as nested for loop. The inner loop is executed fully when outer loop is executed one time. So if outer loop and inner loop are executed 4 times, inner loop will be executed 4 times for each outer loop i.e. total 16 times.

## C++ Nested For Loop Example

\#include &lt;iostream&gt;

using namespace std;  

int main \(\) {  

for\(int i=1;i&lt;=3;i++\){      

for\(int j=1;j&lt;=3;j++\){      

            cout&lt;&lt;i&lt;&lt;" "&lt;&lt;j&lt;&lt;"\n";      

          }     

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



