# C++ Do-While Loop

The C++ do-while loop is used to iterate a part of the program several times. If the number of iteration is not fixed and you must have to execute the loop at least once, it is recommended to use do-while loop.

The C++ do-while loop is executed at least once because condition is checked after loop body.

do{

//code to be executed

}while\(condition\);

## C++ do-while Loop Example

\#include &lt;iostream&gt;

using  namespace std;

int main\(\) {

int i = 1;

do{

```
     cout<<i<<"\n";    

      i++;    

  }while\(i <;= 10\) ;    
```

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

## C++ Nested do-while Loop

In C++, if you use do-while loop inside another do-while loop, it is known as nested do-while loop. The nested do-while loop is executed fully for each outer do-while loop.

\#include &lt;iostream&gt;

using namespace std;

int main\(\) {

int i = 1;

do{

int  j = 1;

do{

```
            cout&lt;&lt;i&lt;&lt;"\n";        

           j++;    

    } while\(j &lt;= 3\) ;     
```

i++;

```
      } while \(i &lt;= 3\) ;     
```

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

## C++ Infinitive do-while Loop Example

\#include &lt;iostream&gt;

using namespace std;

int main\(\) {

do{

```
          cout&lt;&lt;"Infinitive do-while Loop";    
```

}while\(true\);

}

Output:

```
Infinitive do-while Loop 
Infinitive do-while Loop
Infinitive do-while Loop
```



