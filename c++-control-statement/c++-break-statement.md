# C++ Break Statement

The C++ break is used to break loop or switch statement. It breaks the current flow of the program at the given condition. In case of inner loop, it breaks only inner loop.

## C++ Break Statement Example

\#include &lt;iostream&gt;

using  namespace std;  

int main\(\) {  

for\(inti = 1; i &lt;= 10; i++\)    

{    

if \(i == 5\)                  {    

break;    

              }    

        cout&lt;&lt;i&lt;&lt;"\n";    

          }    

}  

Output:

```
1
2
3
4
```

## C++ Break Statement with Inner Loop

The C++ break statement breaks inner loop only if you use break statement inside the inner loop.

Let's see the example code:

\#include &lt;iostream&gt;

using  namespace std;  

int main\(\)  

{  

for\(int i=1;i&lt;=3;i++\){        

for\(int j=1;j&lt;=3;j++\){        

if\(i==2&&j==2\){        

break;        

                        }        

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
3 1
3 2
3 3

```



