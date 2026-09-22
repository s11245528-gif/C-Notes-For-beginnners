# C++ Notes-For-beginnners
This Repository contains all the fundamental concepts I've learned so far on my journey in learning C++ 

In This Repository you going to cover all the fundamental concepts required in studying C++ as a complete beginner

# Table of contents
[Basic Program Structure](#1-basic-structure-of-a-c-program)

# 1. Basic Structure of a C++ program
Below is the basic structure of any C++ program 
```cpp
#include <iostream> //enable the usage of 'cin' and 'cout'
using namespace std;//

//the main function (entry point)
int main(){
    //your code
    return 0;
}
```
Every C++ program has these main parts:
* **Header Files** : you can include headers from STL or your user defined files
* **Using namespace std** : Prevents naming conflicts from the libraries that you include
* **The main function** : The main function is entry point for all c++ programs

# 2. VARIABLES & DATA TYEPS
Variables is like a container that stores values correspond to the data type.

## C++ Naming Conventions Reference

Using consistent naming rules makes your code readable, professional, and easy for other developers to maintain. Here is the standard guide for naming entities in C++:

| Entity Type | Style / Case | Rule / Convention | Good Examples |
| :--- | :--- | :--- | :--- |
| **Variables** | `camelCase` | Start with a lowercase letter. Capitalize the first letter of each subsequent word. | `int playerScore;`<br>`double itemPrice;` |
| **Constants** | `UPPER_SNAKE` | Use all capital letters. Separate individual words with an underscore. | `const int MAX_LEVEL = 100;`<br>`const double PI = 3.14159;` |
| **Functions** | `camelCase` | Start with a lowercase letter. Usually begins with a verb indicating an action. | `void printScore();`<br>`int calculateTotal();` |
| **Classes / Structs** | `PascalCase` | Capitalize the very first letter and the first letter of each subsequent word. | `class PlayerAccount;`<br>`struct EnemyTarget;` |
| **Private Members** | `camelCase_` or `_camelCase` | Standard camelCase but with a leading or trailing underscore to denote private scope. | `int _health;`<br>`double speed_;` |

---

> [!TIP]
> Always use clear, descriptive names instead of single letters. Writing `int dayCount;` is much easier to read and understand six months from now than writing `int d;`. 

> [!WARNING]
> Avoid starting your names with a double underscore (`__`) or a single underscore followed by a capital letter (e.g., `_MyVariable`). These are explicitly reserved for the C++ compiler and standard implementation—using them can cause unexpected errors!


## Data Types
Data type is the type of the data that you want to store in a variable
Basic data types are:
|**Data type**|**Element type**|**Size(in bytes)**|**Example**|
|:--- |:--- |:--- |:--- |
|`**int**`|stores integers(whole numbers)|4 bytes|`int number = 54;`|
|`**double**`|Stores decimals with high
<br> precission(15-16 decimals)|8 bytes|`const double PI = 3.141592653589793;`|





