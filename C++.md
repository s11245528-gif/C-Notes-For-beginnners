# C++ BEGINNER

## Table of content:

1. [Variables](Variables)
2. [Data types](Data-types)
3. [Loops](Loops)
4. [Conditional statements](Conditional-statements)
5. [Arrays](Arrays)
6. [Pointers and Reference](Pointers-and-Reference)
7. [Function](Function)

---

## Naming conventions

There are three (3) naming conventions in C++ <br>

1. pascalCase - Capitalized every first letter of every word exept for the first word
2. CamelCase  - Capitalized every first letter of every word
3. snake_case - Every word is lower case and separated with underscore

<br>
>**NOTE:**
><br>1. Capitalized every word if you use `const` keyword: `const double PI = 3.14; // const keyword prevents modifying of the value stored in 'PI'.`
><br>2. You cannot use any other characters apart from letters 'A-Z' , 'a-z', digits '0-9' and underscore '_'.
><br>3. All names can only begin with underscore '_' or letters not numbers.<br>
### Code Example
```cpp
#include <iostream>
using namespace std;

int main(){
string myName = "SmollZcoDY"; //pascalCase
string MyName = "SmollZcoDY"; //CamelCase
string my_name = "SmollZcoDY"; //snake\_case

&#x20;   string 1myName = "SmollZcoDY"; // numbers in front of a variable name is not allowed
    string _myName = "SmollZcoDY"; // underscore in front is allowed
 
    return 0;

}

```

---

## Variables

**Variable** is like a container which store a element(s)/value(s) 
<br> in your program. You must give a meaningful names to your variables.
<br>
<br>
Example: `int my_name = "Banana" // my_name is the variable `

---

## Data types
Every variable stores variables depend on the type of data it is assigned to.
<br>Common data types:
|Data Type|Element type|Size|
|:--- |:--- |:---|
|`int`|integers(whole numbers)|4 bytes|
|`float`|decimal values(6-7 precission)|4 bytes|
|`double`|decimal values(15-15 precission)|8 bytes|
|`char`|single characters|1 byte|
|`string`|text(used to take in names)|32 bytes|

---
### Code Example
```cpp
#include <iostream>
using namespace std;

int main(){

   int number = 3;
   float area = 33.33;
   double pi = 3.1423352;
   string name = "SmollZcoDY";
   char dollar = '$';
   return 0;
}
```

---

### Operators



## Condition Statements

Conditional statements are statements that consist of **block codes** , each statement get to execute if the condition is ture.
<br>There are four main types of conditional statements: <br>

* *if* statement - Executes only if the condtion is true.
* *if-else* statement - if statement executes if condition is true, otherwise else get executed.
* *elif* statement - condition of multiple statements get checked, only statement that has it's condition *true* get executed.
* *switch* statement - Multiple statement, only one statement get to executed provided that the condition is true.

