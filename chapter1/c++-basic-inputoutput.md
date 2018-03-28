# C++ Basic Input/Output

C++ I/O operation is using the stream concept. Stream is the sequence of bytes or flow of data. It makes the performance fast.

If bytes flow from main memory to device like printer, display screen, or a network connection, etc, this is called as **output operation.**

If bytes flow from device like printer, display screen, or a network connection, etc to main memory, this is called as **input operation.**

## Standard output stream \(cout\)

The **cout ** is a predefined object of **ostream ** class. It is connected with the standard output device, which is usually a display screen. The cout is used in conjunction with stream insertion operator \(&lt;&lt;\) to display the output on a console

\#include &lt;iostream&gt;

using namespace std;

int main\( \) {

char ary\[\] = "Welcome to C++ tutorial";

cout &lt;&lt;"Value of ary is: "&lt;&lt; ary &lt;&lt; endl;

}

output:

Value of ary is: Welcome to C++ tutorial



## Standard input stream \(cin\)

The **cin** is a predefined object of **istream** class. It is connected with the standard input device, which is usually a keyboard. The cin is used in conjunction with stream extraction operator \(&gt;&gt;\) to read the input from a console.

Let's see the simple example of standard input stream \(cin\):

\#include &lt;iostream&gt;

using namespace std;  

int main\( \) {  

int age;  

   cout &lt;&lt;"Enter your age: ";  

   cin &gt;&gt; age;  

   cout &lt;&lt;"Your age is: "&lt;&lt; age &lt;&lt; endl;  

}  



