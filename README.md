# 100daysofdsa

29 feb

#include <iostream> // header file
using namespace std;

int main() {
  cout << "Hello World!";
  return 0;
}

1. `#include <iostream>` is a library for input and output (e.g., cout on line 5). Header files enhance C++ programs.
2. `using namespace std` allows using standard library names.
3. Blank lines enhance code readability.
4. `int main()` initiates program execution.
5. `cout` and `<<` print text (e.g., "Hello World!" on line 5).
6. `;` ends C++ statements.
7. `int main () { cout << "Hello World! "; return 0; }` is an alternative main body.
8. `return 0` terminates `main()`.
9. `}` closes `main()` block.


std::cout << "Hello World!"; //

C++ Variables
Variables are containers for storing data values.

int - stores integers (whole numbers), without decimals, such as 123 or -123
double - stores floating point numbers, with decimals, such as 19.99 or -19.99
char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
string - stores text, such as "Hello World". String values are surrounded by double quotes
bool - stores values with two states: true or false

int myNum = 5;               // Integer (whole number)
float myFloatNum = 5.99;     // Floating point number
double myDoubleNum = 9.98;   // Floating point number
char myLetter = 'D';         // Character
bool myBoolean = true;       // Boolean
string myText = "Hello";     // String


Basic Data Types
The data type specifies the size and type of information the variable will store:

Data Type	Size	Description
boolean	1 byte	Stores true or false values
char	1 byte	Stores a single character/letter/number, or ASCII values
int	2 or 4 bytes	Stores whole numbers, without decimals
float	4 bytes	Stores fractional numbers, containing one or more decimals. Sufficient for storing 6-7 decimal digits
double	8 bytes	Stores fractional numbers, containing one or more decimals. Sufficient for storing 15 decimal digits
