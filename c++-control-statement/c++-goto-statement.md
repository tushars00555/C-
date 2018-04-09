# C++ Goto Statement

The C++ goto statement is also known as jump statement. It is used to transfer control to the other part of the program. It unconditionally jumps to the specified label.

## C++ Goto Statement Example

\#include &lt;iostream&gt;

using namespace std;  

int main\(\)  

{  

ineligible:    

         cout&lt;&lt;"You are not eligible to vote!\n";    

      cout&lt;&lt;"Enter your age:\n";    

int age;  

      cin&gt;&gt;age;  

if \(age &lt; 18\){    

goto

 ineligible;    

      }    

else

      {    

              cout&lt;&lt;"You are eligible to vote!";     

      }         

}  



