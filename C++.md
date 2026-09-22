<div align = "center">
    <img src="smollz.png" alt="smollz">
</div>
# C++ BEGINNER

## Table of content:

1. [Variables](#variables)
2. [Data types](#data-types)
3. [Loops](#loops)
4. [Conditional statements](#condition-statements)
5. [Arrays](#arrays)
6. [Pointers and Reference](#pointers-and-reference)
7. [Function](#function)

---

## Naming conventions

There are three (3) common naming conventions in C++:

1. **camelCase** - The first word is lowercase, and every following word is capitalized. (e.g., `myName`)
2. **PascalCase** - Capitalizes the first letter of *every* word, including the first one. (e.g., `MyName`)
3. **snake_case** - Every word is lowercase and separated with an underscore. (e.g., `my_name`)

> **NOTE:**
> 1. Capitalize every word if you use the `const` keyword: `const double PI = 3.14; // const keyword prevents modifying the value stored in 'PI'.`
> 2. You cannot use any characters apart from letters 'A-Z', 'a-z', digits '0-9', and underscores '_'.
> 3. All names can only begin with an underscore '_' or a letter, never a number.

### Code Example
```cpp
#include <iostream>
using namespace std;

int main() {
    string myName = "SmollZcoDY";  // camelCase
    string MyName = "SmollZcoDY";  // PascalCase
    string my_name = "SmollZcoDY"; // snake_case

    // string 1myName = "SmollZcoDY"; // ERROR: numbers at the front are not allowed
    string _myName = "SmollZcoDY";  // ALLOWED: underscores at the front are okay
 
    return 0;
}
```

---

## Variables

A **Variable** is like a container that stores elements or values in your program. You must give meaningful names to your variables.

Example: 
```cpp
int my_age = 25; // my_age is the variable name holding an integer value
```

---

## Data types

Every variable stores data depending on the type of data it is assigned to.

### Common data types:

| Data Type | Element type | Size |
| :--- | :--- | :--- |
| `int` | integers (whole numbers) | 4 bytes |
| `float` | decimal values (6-7 digits precision) | 4 bytes |
| `double` | decimal values (15 digits precision) | 8 bytes |
| `char` | single characters | 1 byte |
| `string` | text (used to hold words/sentences) | 32 bytes |

---

### Code Example
```cpp
#include <iostream>
using namespace std;

int main() {
   int number = 3;
   float area = 33.33f;
   double pi = 3.1423352;
   string name = "SmollZcoDY";
   char dollar = '$';
   
   return 0;
}
```

---

## Operators

*(Add your operators content here)*

---

## Condition Statements

Conditional statements consist of **blocks of code** where each statement only executes if its condition evaluates to **true**.

There are four main types of conditional statements:

* **if** statement - Executes only if the condition is true.
* **if-else** statement - The `if` block executes if the condition is true; otherwise, the `else` block executes.
* **else if (elif)** statement - Checks multiple conditions sequentially; only the first block that evaluates to true executes.
* **switch** statement - Selects one of many code blocks to be executed based on a matching case value.
