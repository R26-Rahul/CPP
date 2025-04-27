# C++ Learning 
- C++ is a popular programming language.
- C++ is used to create computer programs, and is one of the most used language in game development.
- C++ was developed as an extension of C, and both languages have almost the same syntax.
#### What is C++?
- C++ is a cross-platform language that can be used to create high-performance applications.
- C++ was developed by Bjarne Stroustrup, as an extension to the C language.
- C++ gives programmers a high level of control over system resources and memory.
- The language was updated 5 major times in 2011, 2014, 2017, 2020, and 2023 to C++11, C++14, C++17, C++20, and C++23.

#### Why Use C++
- C++ is one of the world's most popular programming languages.
- C++ can be found in today's operating systems, Graphical User Interfaces, and embedded systems.
- C++ is an object-oriented programming language which gives a clear structure to programs and allows code to be reused, lowering development costs.
- C++ is portable and can be used to develop applications that can be adapted to multiple platforms.
- C++ is fun and easy to learn!
- As C++ is close to C, C# and Java, it makes it easy for programmers to switch to C++ or vice versa.
#### Difference between C and C++
- C++ was developed as an extension of C, and both languages have almost the same syntax.
- The main difference between C and C++ is that C++ supports classes and objects, while C does not.


#### software requirements (to compiler the code)
- Turbo C
- CodeBlocks
- Line Editor 
#### start learning C++ 
- Hellow.cpp for c++ extention ".cpp" 
- ANSI - If your programing in C language not requirment header files but your writing C++ then you have to write header files
- ex 1:` #include<iostream>`is a header file library that lets us work with input and output objects, such as cout (used in line 5). Header files add functionality to C++ programs.
- 2:`#include<conio>`
- 3: `using namespace std;` means that we can use names for objects and variables from the standard library.
- tree line all the programing required 
- 4: `main(){};` compiler find main run the progam
- Example first Code:
```
#include<iostream>
#include<conio.h>
using namespace std;
main()
{
cout<< "Hello Friends";
}

```
- This is use for new line `"\n"` , Another way to insert a new line, is with the `endl` manipulator.
- Ex: 
```
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World!" << endl; - new line
  cout << "I am learning C++"<< \n - new line
  cout << "I am learning C++"<< \t  - hizontal tab
  cout << "I am learning \\ C++ "   - insert backshlash
  return 0;
}


```
- `int main()` - This is called a function. Any code inside its curly brackets `{}` will be executed.
- cout (pronounced "see-out") is an object used together with the insertion operator "`<<`" to output/print text. In our example, it will output "Hello World!".
- C++ is case-sensitive: "cout" and "Cout" has different meaning.
- Every C++ statement ends with a semicolon "`;`".
- The body of `int main()` could also been written as: `int main () { cout << "Hello World! "; return 0; }`
- Remember: The compiler ignores white spaces. However, multiple lines makes the code more readable.
- `return 0;` ends the main function.
- Do not forget to add the closing curly bracket `}` to actually end the main function.
- You might see some C++ programs that runs without the standard namespace library. The using namespace std line can be omitted and replaced with the std keyword, followed by the :: operator for some objects:
```
#include <iostream>

int main() {
  std::cout << "Hello World!";
  return 0;
}
```
- It is up to you if you want to include the standard namespace library or not.
#### we have three statements
- It is important that you end the statement with a semicolon `;`.
- `cout << "Hello World!";`
- `cout << "Have a good day!";`
- `return 0;`
- Just remember to surround the text with double quotes (`""`).
- Single (`//`) or multi-line comments (`/* */`): 
## C++ Variables
#### In C++, there are different types of variables 
- int - stores integers (whole numbers), without decimals, such as 123 or -123
- double - stores floating point numbers, with decimals, such as 19.99 or -19.99
- char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
- string - stores text, such as "Hello World". String values are surrounded by double quotes
- bool - stores values with two states: true or false

#### To create a variable, specify the type and assign it a value
`type variableName = value;`
```
int myNum = 5;               // Integer (whole number without decimals)
double myFloatNum = 5.99;    // Floating point number (with decimals)
char myLetter = 'D';         // Character
string myText = "Hello";     // String (text)
bool myBoolean = true;       // Boolean (true or false)
```
#### C++ Identifiers (The general rules for naming variables are)
- Names can contain letters, digits and underscores
- Names must begin with a letter or an underscore (_)
- Names are case-sensitive (myVar and myvar are different variables)
- Names cannot contain whitespaces or special characters like !, #, %, etc.
- Reserved words (like C++ keywords, such as int) cannot be used as names
#### C++ Constants(unchangeable and read-only)
```
#include<iostream>
#include<conio.h>
using namespace std;
main()
{
 const int myNum = 20;  // myNum will always be 20
 myNum=45;    // error: assignment of read-only variable 'myNum'
 cout << myNum;
 return 0;
}
```
#### C++ User Input
- `cout` is pronounced "see-out". Used for output, and uses the insertion operator (`<<`)

- `cin` is pronounced "see-in". Used for input, and uses the extraction operator (`>>`)
```
int x; 
cout << "Type a number: "; // Type a number and press enter
cin >> x; // Get user input from the keyboard
cout << "Your number is: " << x; // Display the input value 
```


Tips: Both cin and cout belongs to the <iostream> library, which is short for standard input / output streams. For a complete reference of <iostream> objects along with detailed information,

## different types of variables (defined with different keywords),
- int - stores integers (whole numbers), without decimals, such as 123 or -123
- double - stores floating point numbers, with decimals, such as 19.99 or -19.99
- char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
- string - stores text, such as "Hello World". String values are surrounded by double quotes
- bool - stores values with two states: true or false
