# C++ Continue Statement

The C++ continue statement is used to continue loop. It continues the current flow of the program and skips the remaining code at specified condition. In case of inner loop, it continues only inner loop.

## C++ Continue Statement Example

\#include &lt;iostream&gt;

using namespace std;  

int main\(\)  

{  

for\(int i=1;i&lt;=10;i++\){      

if\(i==5\){      

continue;      

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
6
7
8
9
10
```

```

```

---



