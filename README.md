# 📘 C Programming Theory — Complete Q&A Guide

> **Prepred by Husen** | Expected Questions & Answers for Examinations  
> All 5 Units · 2-Mark · 5-Mark · 10-Mark Questions · Previous Year Papers

![Language](https://img.shields.io/badge/Language-C-blue?logo=c&logoColor=white)
![Units](https://img.shields.io/badge/Units-5-green)
![Questions](https://img.shields.io/badge/Questions-100%2B-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Year](https://img.shields.io/badge/Year-2025-yellow)

---

## 📋 Table of Contents

- [Unit I — Problem Solving & Introduction to C](#unit-i--problem-solving--introduction-to-c)
- [Unit II — Input/Output and Operators](#unit-ii--inputoutput-and-operators)
- [Unit III — Control Structures, Arrays & Strings](#unit-iii--control-structures-arrays--strings)
- [Unit IV — Functions and Pointers](#unit-iv--functions-and-pointers)
- [Unit V — Structures, Unions & File Management](#unit-v--structures-unions--file-management)
- [Previous Year Papers](#previous-year-papers)

---

## Unit I — Problem Solving & Introduction to C

### ✅ 2-Mark Questions

---

**Q1. Define an algorithm.**

An algorithm is a step-by-step procedure designed to perform a specific task or solve a particular problem.

**Example — Add Two Numbers:**
```
1. Start
2. Read two numbers A and B
3. Add A and B and store in C
4. Display C
5. Stop
```

---

**Q2. What are the characteristics of a good algorithm?**

A good algorithm should have:
1. **Clear and simple steps** — no confusion in instructions
2. **Finite steps** — it must finish after a limited number of steps
3. **Correct output** — it should give the right result for all valid inputs
4. **Efficiency** — it should use minimum time and memory

---

**Q3. What is a flowchart?**

A flowchart is a graphical representation of an algorithm or process using symbols to show the flow of steps.

---

**Q4. Mention any two symbols used in flowcharts.**

| Symbol | Shape | Meaning |
|--------|-------|---------|
| Oval | `( )` | Start / Stop |
| Parallelogram | `/ /` | Input / Output |
| Rectangle | `[ ]` | Process |
| Diamond | `< >` | Decision |

---

**Q5. What are keywords in C?**

Keywords are reserved words in C that have special meaning and cannot be used as variable names.

```c
// Examples of keywords:
int, return, float, char, if, else, while, for, do,
switch, break, continue, void, struct, union, typedef
```

---

**Q6. What is a variable in C?**

A variable is a named memory location used to store data that can change during program execution.

```c
int age = 20;       // integer variable
float marks = 89.5; // float variable
char grade = 'A';   // character variable
```

---

**Q7. What is meant by symbolic constant?**

A symbolic constant is a name that represents a fixed value defined using `#define` or `const`. It cannot be changed during program execution.

```c
#define PI 3.14
#define MAX 100
const int SIZE = 50;
```

---

**Q8. Name any two features of C language.**

- **Portability** — write once, run anywhere
- **Modularity** — programs can be divided into functions

> Other features: Fast execution, Rich library, Structured language

---

### ✅ 5-Mark Questions

---

**Q1. Explain the steps involved in creating and executing a C program.**

1. **Creating the Program (Editing)**
   - Programmer writes source code using a text editor
   - Saved with extension `.c`

2. **Compilation**
   - Compiler checks for syntax/semantic errors
   - Converts source code into an object file (`.obj` or `.o`)

3. **Linking**
   - Linker combines object file with library files
   - Creates an executable file (`.exe`)

4. **Loading**
   - Loader loads the executable file into main memory

5. **Execution**
   - CPU executes the instructions and displays the output

---

**Q2. Write a short note on the structure of a C program with an example.**

A C program has the following basic structure:

```c
/* 1. Documentation Section */
/* Program to add two numbers */

/* 2. Link Section */
#include <stdio.h>

/* 3. Definition Section */
#define PI 3.14

/* 4. Global Declaration Section */
int x;
void display();

/* 5. main() Function Section */
int main() {
    int a, b, sum;   // Declaration part
    a = 5;
    b = 10;
    sum = a + b;     // Execution part
    printf("Sum = %d", sum);
    return 0;
}

/* 6. User-Defined Function Section */
void display() {
    printf("Hello");
}
```

---

**Q3. Explain the compilation process in C.**

| Stage | What Happens |
|-------|-------------|
| **1. Preprocessing** | Handles `#include`, `#define` directives; creates expanded source code |
| **2. Compilation** | Converts expanded code into assembly language |
| **3. Assembly** | Translates assembly into machine code; generates `.o` object file |
| **4. Linking** | Links object file with standard library functions → creates executable |
| **5. Loading & Execution** | Loader loads file into memory; CPU executes the program |

---

**Q4. Discuss the different data types in C with examples.**

**1. Basic Data Types:**

| Data Type | Meaning | Size | Example |
|-----------|---------|------|---------|
| `int` | Integer numbers | 4 bytes | `int a = 10;` |
| `float` | Decimal values | 4 bytes | `float x = 3.14;` |
| `char` | Single character | 1 byte | `char c = 'A';` |
| `double` | Double-precision decimal | 8 bytes | `double d = 10.3456;` |

**2. Derived Data Types:**
```c
int a[5];           // Arrays
int *p;             // Pointers
struct student {};  // Structures
```

**3. Enumeration Data Type:**
```c
enum days {Mon, Tue, Wed, Thu, Fri};
```

**4. Void Data Type:**
```c
void display();     // No return value
```

---

**Q5. Describe the basic C tokens with examples.**

C tokens are the smallest individual units of a C program:

| Token | Description | Example |
|-------|-------------|---------|
| **Keywords** | Reserved words | `int`, `return`, `while` |
| **Identifiers** | Names for variables/functions | `sum`, `main`, `age` |
| **Constants** | Fixed values | `10`, `3.14`, `'A'` |
| **Strings** | Sequence of characters | `"Hello"` |
| **Operators** | Symbols for operations | `+`, `-`, `*`, `/`, `==` |
| **Special Symbols** | Special meaning symbols | `{ }`, `( )`, `[ ]`, `;` |
| **Punctuators** | Separate statements | `,`, `;` |

---

### ✅ 10-Mark Questions

---

**Q1. Explain the algorithm and flowchart with a suitable example.**

**Algorithm:**

An algorithm is a step-by-step, finite set of instructions to solve a problem.

**Characteristics:**
- Clear and unambiguous
- Stepwise
- Finite
- Effective
- Input/output defined

**Example — Add Two Numbers:**
```
1. Start
2. Read two numbers A and B
3. Add A and B → SUM
4. Display SUM
5. Stop
```

**Flowchart:**

```
        [ Start ]
            |
            v
      [ Input A, B ]
            |
            v
      [ SUM = A + B ]
            |
            v
      [ Print SUM ]
            |
            v
         [ Stop ]
```

**Flowchart Symbols:**

| Symbol | Shape | Meaning |
|--------|-------|---------|
| Oval | Rounded rectangle | Start / Stop |
| Parallelogram | Slanted box | Input / Output |
| Rectangle | Plain box | Process |
| Diamond | Diamond shape | Decision |

---

**Q2. Describe the structure of a C program and explain each section.**

```c
/* === 1. DOCUMENTATION SECTION === */
/* Program to add two numbers
   Author: Husen
   Date: 2025 */

/* === 2. LINK SECTION === */
#include <stdio.h>
#include <math.h>

/* === 3. DEFINITION SECTION === */
#define PI 3.14
#define MAX 100

/* === 4. GLOBAL DECLARATION SECTION === */
int x;
void display();

/* === 5. main() FUNCTION SECTION === */
int main() {
    int a, b, sum;  // Declaration Part
    a = 5;
    b = 10;
    sum = a + b;    // Execution Part
    printf("Sum = %d", sum);
    return 0;
}

/* === 6. USER-DEFINED FUNCTION SECTION === */
void display() {
    printf("Hello from user-defined function!");
}
```

**Section Explanations:**

| Section | Purpose |
|---------|---------|
| Documentation | Comments about program purpose, author, date |
| Link | Header file inclusions using `#include` |
| Definition | Symbolic constants using `#define` |
| Global Declaration | Variables/prototypes accessible throughout program |
| `main()` | Entry point — contains declaration + execution parts |
| User-Defined Functions | Programmer-created functions for modularity |

---

**Q3. Explain the different data types and declaration of variables in C.**

**Categories of Data Types:**

**1. Basic (Primary) Data Types:**

| Data Type | Meaning | Size | Example |
|-----------|---------|------|---------|
| `int` | Integer numbers | 4 bytes | `int age = 20;` |
| `float` | Single-precision decimal | 4 bytes | `float x = 3.5;` |
| `double` | Double-precision decimal | 8 bytes | `double pi = 3.14159;` |
| `char` | Single character | 1 byte | `char grade = 'A';` |

**2. Derived Data Types:**
```c
int a[10];              // Arrays
int *p;                 // Pointers
struct student {...};   // Structures
union data {...};       // Unions
```

**3. Enumeration:**
```c
enum days {Mon, Tue, Wed, Thu, Fri, Sat, Sun};
```

**4. Void:**
```c
void display();  // represents "nothing" / no return type
```

**Variable Declaration:**

```c
// Syntax:
data_type variable_name;

// Single declarations:
int age;
float marks;
char ch;
double salary;

// Multiple declarations:
int a, b, c;
float x, y;

// Initialization during declaration:
int a = 10;
char c = 'A';
float pi = 3.14;
```

---

## Unit II — Input/Output and Operators

### ✅ 2-Mark Questions

---

**Q1. Differentiate between formatted and unformatted I/O functions.**

| Feature | Formatted I/O | Unformatted I/O |
|---------|--------------|-----------------|
| Format control | Yes — uses format specifiers | No — no formatting |
| Functions | `printf()`, `scanf()` | `getchar()`, `putchar()`, `gets()`, `puts()` |
| Data types | Works with all types | Works with char/strings |
| Flexibility | More flexible | Less flexible |
| Speed | Slower | Faster |

---

**Q2. Write the syntax of `printf()` and `scanf()`.**

```c
// printf() — Formatted Output
printf("format string", arguments);

// Example:
printf("Name: %s, Age: %d", name, age);

// scanf() — Formatted Input
scanf("format string", &variables);

// Example:
scanf("%d %f", &age, &salary);
```

---

**Q3. What are escape sequences? Give examples.**

Escape sequences are special character combinations that represent non-printable characters.

| Escape Sequence | Meaning |
|----------------|---------|
| `\n` | New line |
| `\t` | Horizontal tab |
| `\\` | Backslash |
| `\"` | Double quote |
| `\0` | Null character |
| `\r` | Carriage return |

---

**Q4. What is an arithmetic operator?**

Arithmetic operators perform mathematical operations on numeric values.

```c
int a = 10, b = 3;
a + b  // 13  — Addition
a - b  // 7   — Subtraction
a * b  // 30  — Multiplication
a / b  // 3   — Division (integer)
a % b  // 1   — Modulus (remainder)
```

---

**Q5. Define relational operators.**

Relational operators compare two values and return either true (`1`) or false (`0`).

```c
a > b   // greater than
a < b   // less than
a >= b  // greater than or equal
a <= b  // less than or equal
a == b  // equal to
a != b  // not equal to
```

---

**Q6. What are increment and decrement operators?**

These operators increase or decrease a variable's value by 1.

```c
// Increment operator: ++
int i = 5;
i++;    // Post-increment: use then increment → i becomes 6
++i;    // Pre-increment:  increment then use → i becomes 7

// Decrement operator: --
i--;    // Post-decrement
--i;    // Pre-decrement
```

---

**Q7. Define type conversion.**

Type conversion is the process of converting one data type into another.

```c
// Implicit (automatic by compiler):
int i = 5;
float f = 2.0;
float r = i + f;  // i automatically promoted to float → r = 7.0

// Explicit (forced by programmer using casting):
float x = 5.0 / (float)2;  // → 2.5
int a = (int)3.9;           // → 3 (truncated)
```

---

**Q8. What is operator precedence?**

Operator precedence defines the order in which operators are evaluated in an expression.

```c
// * and / have higher precedence than + and -
int result = 2 + 3 * 4;    // = 14 (not 20)
int result2 = (2 + 3) * 4; // = 20 (parentheses override)
```

---

**Q9. What is formatted I/O?**

Formatted I/O uses `printf()` and `scanf()` with format specifiers like `%d`, `%f`, `%c` to read/display data in a specific format.

---

**Q10. Define bitwise operators.**

Bitwise operators perform operations on individual bits of integer data.

| Operator | Name | Example |
|----------|------|---------|
| `&` | AND | `a & b` |
| `\|` | OR | `a \| b` |
| `^` | XOR | `a ^ b` |
| `~` | NOT | `~a` |
| `<<` | Left shift | `a << 2` |
| `>>` | Right shift | `a >> 2` |

---

**Q11. What is the conditional operator?**

The conditional (ternary) operator `?:` makes a decision based on a condition.

```c
// Syntax:
condition ? expression1 : expression2;

// Example:
int max = (a > b) ? a : b;
// If a > b → max = a, else max = b
```

---

### ✅ 5-Mark Questions

---

**Q1. Explain formatted I/O functions in detail.**

**`printf()` — Formatted Output:**
```c
// Syntax:
printf("format string", variable1, variable2, ...);

// Examples:
int a = 10;
float b = 5.5;
printf("a = %d, b = %.2f\n", a, b);
printf("Name: %s, Grade: %c\n", name, grade);
```

**`scanf()` — Formatted Input:**
```c
// Syntax:
scanf("format string", &variable1, &variable2, ...);

// Examples:
int x;
float y;
scanf("%d", &x);
scanf("%d %f", &x, &y);
```

**Common Format Specifiers:**

| Specifier | Data Type |
|-----------|-----------|
| `%d` | int |
| `%f` | float |
| `%c` | char |
| `%s` | string |
| `%lf` | double |
| `%u` | unsigned int |
| `%x` | hexadecimal |
| `%p` | pointer address |

---

**Q2. Explain the different types of operators in C with examples.**

```c
int a = 10, b = 3;

// 1. Arithmetic
printf("%d", a + b);  // 13
printf("%d", a - b);  // 7
printf("%d", a * b);  // 30
printf("%d", a / b);  // 3  (integer division)
printf("%d", a % b);  // 1  (remainder)

// 2. Relational
a > b   // 1 (true)
a == b  // 0 (false)
a != b  // 1 (true)

// 3. Logical
a > 0 && b > 0   // AND → 1
a > 0 || b < 0   // OR  → 1
!a               // NOT → 0

// 4. Assignment
int x = 5;
x += 5;   // x = x + 5  → 10
x -= 2;   // x = x - 2  → 8
x *= 3;   // x = x * 3  → 24

// 5. Increment / Decrement
int i = 5;
int b1 = ++i;  // i=6, b1=6 (pre-increment)
int b2 = i++;  // b2=6, i=7 (post-increment)

// 6. Bitwise
// a=5 (0101), b=3 (0011)
a & b   // 1  (0001) — AND
a | b   // 7  (0111) — OR
a ^ b   // 6  (0110) — XOR
a << 1  // 10 (1010) — left shift

// 7. Ternary
int max = (a > b) ? a : b;

// 8. Comma
int y = (x++, x + 2);  // evaluates left, returns right
```

> **Note:** Use parentheses to make intent clear — e.g., `(a + b) * c`

---

**Q3. Discuss type conversion and type casting with examples.**

**1. Implicit (Automatic) Conversion:**
```c
int i = 5;
float f = 2.0;
float r = i + f;   // i automatically promoted to float → r = 7.0

// Integer division pitfall:
int result = 5 / 2;   // = 2 (NOT 2.5)
```

**2. Explicit Conversion (Type Casting):**
```c
float x = 5.0 / (float)2;       // → 2.5
int a = (int)3.9;                // → 3 (truncated, not rounded)
double result = (double)sum / count;  // force floating division
```

**Key Cautions:**

| Scenario | Risk |
|----------|------|
| Implicit int→float | Loss of precision |
| Integer division `5/2` | Result is `2`, not `2.5` |
| Cast large `long` → `int` | Truncation / overflow |

---

**Q4. Program: Demonstrate arithmetic and relational operators.**

```c
#include <stdio.h>

int main(void) {
    int a = 10, b = 3;
    float fa = 10.0f, fb = 3.0f;

    /* --- Arithmetic Operators --- */
    printf("Integer arithmetic with a=%d, b=%d\n", a, b);
    printf("a + b = %d\n", a + b);           // 13
    printf("a - b = %d\n", a - b);           // 7
    printf("a * b = %d\n", a * b);           // 30
    printf("a / b = %d  (integer division)\n", a / b); // 3
    printf("a %% b = %d (remainder)\n\n", a % b);      // 1

    printf("Float arithmetic: fa=%.2f, fb=%.2f\n", fa, fb);
    printf("fa / fb = %.6f\n\n", fa / fb);   // 3.333333

    /* --- Relational Operators --- */
    printf("Relational comparisons (1=true, 0=false):\n");
    printf("a == b: %d\n", a == b);  // 0
    printf("a != b: %d\n", a != b);  // 1
    printf("a >  b: %d\n", a > b);   // 1
    printf("a <  b: %d\n", a < b);   // 0
    printf("a >= b: %d\n", a >= b);  // 1
    printf("a <= b: %d\n\n", a <= b); // 0

    /* --- Type conversion demo --- */
    int result_int   = a / b;             // 3
    float result_flt = a / (float)b;      // 3.333333
    printf("Int division:   %d\n", result_int);
    printf("Float division: %.6f\n", result_flt);

    return 0;
}
```

**Sample Output:**
```
Integer arithmetic with a=10, b=3
a + b = 13
a - b = 7
a * b = 30
a / b = 3  (integer division)
a % b = 1  (remainder)

Float arithmetic: fa=10.00, fb=3.00
fa / fb = 3.333333

Relational comparisons (1=true, 0=false):
a == b: 0
a != b: 1
a >  b: 1
a <  b: 0
a >= b: 1
a <= b: 0

Int division:   3
Float division: 3.333333
```

---

### ✅ 10-Mark Questions

---

**Q1. Explain all operators in C language with suitable examples.**

**1. Arithmetic Operators:**
```c
int a = 10, b = 3;
// a + b = 13 | a - b = 7 | a * b = 30
// a / b = 3  | a % b = 1
```

**2. Relational Operators:**
```c
a > b   // 1     a < b   // 0
a >= b  // 1     a <= b  // 0
a == b  // 0     a != b  // 1
```

**3. Logical Operators:**
```c
if (a > 0 && b > 0)  // AND — both true
if (a > 0 || b < 0)  // OR  — at least one true
if (!a)              // NOT — inverts
```

**4. Assignment Operators:**
```c
x  = 5;   // assign
x += 5;   // x = x + 5
x -= 2;   // x = x - 2
x *= 3;   // x = x * 3
x /= 4;   // x = x / 4
x %= 2;   // x = x % 2
```

**5. Increment & Decrement:**
```c
int a = 5;
int b = ++a;  // a=6, b=6  (pre-increment)
int c = a++;  // c=6, a=7  (post-increment)
```

**6. Bitwise Operators:**
```c
// a=5 → 0101,  b=3 → 0011
a & b   // 1  → 0001  (AND)
a | b   // 7  → 0111  (OR)
a ^ b   // 6  → 0110  (XOR)
~a      // -6          (NOT)
a << 1  // 10 → 1010  (left shift)
a >> 1  // 2  → 0010  (right shift)
```

**7. Conditional/Ternary Operator:**
```c
int max = (a > b) ? a : b;
// If a > b → max = a, else max = b
```

**8. Special Operators:**
```c
// sizeof — memory size
sizeof(int);   // 4
sizeof(a);     // size of variable a

// Comma operator
int x = (a = 5, a + 10);  // x = 15

// Pointer operators
int a = 10;
int *p = &a;        // & → address-of
printf("%d", *p);   // * → dereference → prints 10
```

**9. Member Access Operators:**
```c
struct student s;
s.age;       // dot operator — direct member access
ptr->age;    // arrow operator — pointer member access
```

**10. Cast Operator:**
```c
float x = (float)5 / 2;  // 2.5
```

---

**Q2. Explain formatted and unformatted I/O functions in detail.**

**Formatted I/O Functions:**

```c
// printf() — Formatted Output
printf("format string", variables);
printf("Sum = %d", a + b);

// fprintf() — Write to file
fprintf(fp, "Name: %s", name);

// sprintf() — Write to string buffer
char str[50];
sprintf(str, "Value = %d", x);

// scanf() — Formatted Input
scanf("format specifiers", &variables);
scanf("%d %f", &a, &b);

// fscanf() — Read from file
fscanf(fp, "%d", &num);

// sscanf() — Read from string
sscanf(str, "%d", &num);
```

**Format Specifiers:**

| Specifier | Type |
|-----------|------|
| `%d` | int |
| `%f` | float |
| `%c` | char |
| `%s` | string |
| `%lf` | double |
| `%u` | unsigned int |
| `%x` / `%X` | hexadecimal |
| `%p` | address |

**Escape Sequences:**

| Sequence | Meaning |
|----------|---------|
| `\n` | Newline |
| `\t` | Tab |
| `\\` | Backslash |
| `\"` | Double quote |

**Unformatted I/O Functions:**

```c
// putchar() — write single character
putchar('A');

// puts() — write string + newline
puts("Hello World");

// fputc() / fputs() — file output
fputc('A', fp);
fputs("Hello", fp);

// getchar() — read single character
char ch = getchar();

// fgets() — safe string input (replaces gets())
fgets(str, 20, stdin);
```

**Comparison Table:**

| Feature | Formatted I/O | Unformatted I/O |
|---------|--------------|-----------------|
| Format specifiers | Yes | No |
| Data types | All | char / strings only |
| Speed | Slower | Faster |
| Functions | `printf`, `scanf` | `getchar`, `putchar`, `gets`, `puts` |
| Flexibility | More flexible | Less flexible |

---

## Unit III — Control Structures, Arrays & Strings

### ✅ 2-Mark Questions

---

**Q1. What is a control statement?**

A control statement controls the flow of execution of a program based on conditions or loops.

```c
// Examples:
if, if-else, switch   // Decision making
while, for, do-while  // Looping
break, continue, goto // Jump statements
```

---

**Q2. Write the syntax of `if–else` statement.**

```c
if (condition) {
    // statements if condition is true
} else {
    // statements if condition is false
}
```

---

**Q3. What is a loop? Name any two types.**

A loop is a control structure that repeats a block of code until a condition becomes false.

```c
// Two types:
for (int i = 0; i < 5; i++) { /* for loop */ }

int i = 0;
while (i < 5) { i++; }        /* while loop */
```

---

**Q4. What is a `break` statement?**

`break` terminates a loop or `switch` immediately and transfers control to the next statement after the loop/switch.

```c
for (int i = 1; i <= 10; i++) {
    if (i == 5) break;  // exits loop when i == 5
    printf("%d ", i);   // prints 1 2 3 4
}
```

---

**Q5. What is an array?**

An array is a collection of elements of the same data type stored in contiguous memory locations, accessed using an index (starting from 0).

```c
int a[5] = {10, 20, 30, 40, 50};
printf("%d", a[2]);  // Output: 30
```

---

**Q6. Define a two-dimensional array.**

A two-dimensional array is an array of arrays used to store elements in rows and columns (matrix format).

```c
int a[3][3];             // 3x3 matrix
a[1][2] = 6;             // row 1, column 2
printf("%d", a[1][2]);   // 6
```

---

**Q7. What is a string in C?**

A string in C is a character array terminated with a null character `'\0'`.

```c
char name[10] = "Husen";
// Stored as: H u s e n \0
```

---

**Q8. Mention any two string handling functions.**

```c
#include <string.h>

strlen("Hello");          // returns 5 — length of string
strcpy(dest, src);        // copies src into dest

// Other examples:
strcat(s1, s2);           // concatenate
strcmp(s1, s2);           // compare
```

---

### ✅ 5-Mark Questions

---

**Q1. Explain different types of control statements in C.**

**1. Decision Control Statements:**
```c
// if
if (a > b) { printf("A is greater"); }

// if-else
if (n % 2 == 0)
    printf("Even");
else
    printf("Odd");

// if-else ladder
if (score >= 90)      printf("A grade");
else if (score >= 75) printf("B grade");
else if (score >= 50) printf("C grade");
else                  printf("Fail");

// switch
switch (ch) {
    case 'a': printf("vowel"); break;
    case 'b': printf("consonant"); break;
    default:  printf("other");
}
```

**2. Looping Statements:**
```c
// for loop
for (int i = 1; i <= 5; i++) {
    printf("%d ", i);
}

// while loop
int i = 1;
while (i <= 5) { printf("%d ", i); i++; }

// do-while loop
int i = 1;
do { printf("%d ", i); i++; } while (i <= 5);
```

**3. Jump Statements:**
```c
// break
for (int i = 1; i <= 5; i++) {
    if (i == 3) break;
}

// continue
for (int i = 1; i <= 5; i++) {
    if (i == 3) continue;  // skips 3
    printf("%d ", i);
}

// return
int add(int a, int b) { return a + b; }
```

---

**Q2. Discuss entry-controlled vs exit-controlled loops.**

| Feature | Entry-Controlled | Exit-Controlled |
|---------|-----------------|-----------------|
| Condition check | Before loop body | After loop body |
| Examples | `for`, `while` | `do-while` |
| Min executions | 0 (may never run) | 1 (always runs once) |
| Evaluation order | Test → Execute → Repeat | Execute → Test → Repeat |
| Use case | When repetitions are condition-based | When loop must run at least once |

```c
// Entry-controlled (while) — may not execute
int x = 10;
while (x < 5) {         // condition false immediately
    printf("%d", x);    // never executes
    x++;
}

// Exit-controlled (do-while) — always executes once
int x = 10;
do {
    printf("%d", x);    // executes once even though condition is false
    x++;
} while (x < 5);
```

---

**Q3. Explain 1D and 2D arrays with examples.**

**1. One-Dimensional Array:**
```c
// Declaration
int a[5];

// Initialization
int a[5] = {10, 20, 30, 40, 50};

// Access
printf("%d", a[2]);   // Output: 30

// Full example — print all elements
int a[5] = {10, 20, 30, 40, 50};
for (int i = 0; i < 5; i++) {
    printf("%d ", a[i]);
}
// Output: 10 20 30 40 50
```

**2. Two-Dimensional Array:**
```c
// Declaration
int a[2][3];

// Initialization
int a[2][3] = {
    {1, 2, 3},
    {4, 5, 6}
};

// Access
printf("%d", a[1][2]);  // Output: 6

// Print all elements
for (int i = 0; i < 2; i++) {
    for (int j = 0; j < 3; j++) {
        printf("%d ", a[i][j]);
    }
    printf("\n");
}
// Output:
// 1 2 3
// 4 5 6
```

---

**Q4. Explain any four string handling functions with examples.**

```c
#include <string.h>

// 1. strlen() — find length of string
int len = strlen("Hello");   // len = 5
printf("%d", strlen("World")); // Output: 5

// 2. strcpy() — copy one string into another
char a[10], b[10] = "Apple";
strcpy(a, b);
printf("%s", a);   // Output: Apple

// 3. strcat() — join (concatenate) two strings
char a[20] = "Hello ";
char b[10] = "World";
strcat(a, b);
printf("%s", a);   // Output: Hello World

// 4. strcmp() — compare two strings
int result = strcmp("abc", "abc");  // returns 0 (equal)
int result2 = strcmp("abc", "abd"); // returns negative (a < b)
int result3 = strcmp("abd", "abc"); // returns positive (a > b)
```

---

### ✅ 10-Mark Questions

---

**Q1. Explain looping and decision-making statements in C.**

**Decision-Making Statements:**

```c
// 1. if statement
if (x > 0)
    printf("x is positive\n");

// 2. if-else
if (n % 2 == 0)
    printf("even\n");
else
    printf("odd\n");

// 3. else-if ladder
if (score >= 90)       printf("Distinction");
else if (score >= 75)  printf("First Class");
else if (score >= 50)  printf("Pass");
else                   printf("Fail");

// 4. switch
switch (ch) {
    case 'a': printf("vowel a"); break;
    case 'e': printf("vowel e"); break;
    default:  printf("other");
}

// 5. Ternary
int result = (a > b) ? a : b;
```

**Looping Statements:**

```c
// 1. for loop — best when iterations known
for (int i = 0; i < 5; i++)
    printf("%d ", i);    // 0 1 2 3 4

// 2. while loop — test before each iteration
int n = 10, sum = 0;
while (n > 0) {
    sum += n;
    n--;
}

// 3. do-while — runs at least once
int i = 1;
do {
    printf("%d ", i);
    i++;
} while (i <= 5);

// 4. Nested loops — for 2D arrays
for (int i = 0; i < rows; i++) {
    for (int j = 0; j < cols; j++)
        printf("%d ", a[i][j]);
    printf("\n");
}
```

**Loop Control:**
```c
break;     // exit nearest loop immediately
continue;  // skip rest of iteration, go to next
```

**When to use which loop:**

| Loop | Best Used When |
|------|---------------|
| `for` | Iteration count known / index needed |
| `while` | Condition-driven, unknown iterations |
| `do-while` | Body must run at least once |

**Program — Sum of elements in 2D array:**

```c
#include <stdio.h>

int main(void) {
    int rows, cols;
    printf("Enter number of rows and columns: ");
    scanf("%d %d", &rows, &cols);

    int arr[100][100];
    int i, j;

    printf("Enter %d x %d elements:\n", rows, cols);
    for (i = 0; i < rows; i++)
        for (j = 0; j < cols; j++)
            scanf("%d", &arr[i][j]);

    long sum = 0;
    for (i = 0; i < rows; i++)
        for (j = 0; j < cols; j++)
            sum += arr[i][j];

    printf("Sum of elements = %ld\n", sum);
    return 0;
}
```

**Sample Run:**
```
Enter number of rows and columns: 2 3
Enter 2 x 3 elements:
1 2 3 4 5 6
Sum of elements = 21
```

---

**Q2. String handling functions in C with examples.**

```c
#include <stdio.h>
#include <string.h>

int main(void) {
    /* strlen — count characters before \0 */
    size_t n = strlen("hello");    // n = 5

    /* strcpy — copy src to dest */
    char src[] = "hello";
    char dest[10];
    strcpy(dest, src);             // dest = "hello"

    /* strncpy — safer copy (up to n chars) */
    char buf[6];
    strncpy(buf, "abcdef", 5);
    buf[5] = '\0';                 // manually null-terminate

    /* strcat — append src to dest */
    char a[20] = "Hello, ";
    strcat(a, "World!");           // a = "Hello, World!"

    /* strcmp — compare strings */
    if (strcmp("abc", "abd") < 0)
        printf("abc comes before abd\n");

    /* strchr — find first occurrence of char */
    char *p = strchr("banana", 'n');  // points to first 'n'

    /* strstr — find substring */
    char *q = strstr("hello world", "world");  // points to "world"

    /* Full demo */
    char s1[50] = "Hello";
    char s2[] = " C!";
    strcat(s1, s2);                 // s1 = "Hello C!"
    printf("Length = %zu\n", strlen(s1));
    if (strcmp(s1, "Hello C!") == 0)
        printf("strings equal\n");

    return 0;
}
```

**Important Cautions:**

| Issue | Solution |
|-------|---------|
| Buffer overflow in `strcpy` | Use `strncpy` or `snprintf` |
| `strncpy` may not null-terminate | Manually set `dest[n-1] = '\0'` |
| `strtok` modifies original string | Copy string first |
| `gets()` is unsafe (removed in C11) | Use `fgets()` instead |

---

**Q3. Explain arrays and write a program for matrix addition.**

**Arrays:**
- A collection of elements of the **same data type** stored in **contiguous memory**
- Each element accessed using an **index starting from 0**

**Types:**
1. One-Dimensional — list of elements
2. Two-Dimensional — rows and columns (matrix)

**Advantages:** Store multiple values with one name, easy loop-based access, supports matrix operations.

**Program — Matrix Addition:**

```c
#include <stdio.h>

int main() {
    int a[2][2], b[2][2], sum[2][2];
    int i, j;

    printf("Enter elements of first matrix:\n");
    for (i = 0; i < 2; i++)
        for (j = 0; j < 2; j++)
            scanf("%d", &a[i][j]);

    printf("Enter elements of second matrix:\n");
    for (i = 0; i < 2; i++)
        for (j = 0; j < 2; j++)
            scanf("%d", &b[i][j]);

    // Add corresponding elements
    for (i = 0; i < 2; i++)
        for (j = 0; j < 2; j++)
            sum[i][j] = a[i][j] + b[i][j];

    printf("Sum of matrices:\n");
    for (i = 0; i < 2; i++) {
        for (j = 0; j < 2; j++)
            printf("%d ", sum[i][j]);
        printf("\n");
    }
    return 0;
}
```

**Example Output:**
```
Sum of matrices:
6 8
10 12
```

---

## Unit IV — Functions and Pointers

### ✅ 2-Mark Questions

---

**Q1. What is a user-defined function?**

A user-defined function is a function created by the programmer to perform a specific task. It enables modular, reusable code.

---

**Q2. Define return type.**

The return type specifies the type of value a function returns to the calling function.

```c
int add(int a, int b)   { return a + b; }  // returns int
float avg(float a, float b) { return (a+b)/2; }  // returns float
void display()          { printf("Hi"); }  // returns nothing
```

---

**Q3. What is a function prototype?**

A function prototype is a declaration that tells the compiler the function's name, return type, and parameters before its actual definition.

```c
int add(int, int);      // prototype
float avg(float, float);
void display();
```

---

**Q4. What is a pointer?**

A pointer is a variable that stores the memory address of another variable.

```c
int x = 10;
int *p = &x;            // p stores address of x
printf("%d", *p);       // prints 10 (dereferencing)
```

---

**Q5. What is the use of the address-of (`&`) operator?**

The `&` operator returns the memory address of a variable.

```c
int x = 10;
printf("%p", &x);   // prints address of x
int *p = &x;        // stores address of x in pointer p
```

---

**Q6. What is pointer arithmetic?**

Pointer arithmetic refers to `+` and `-` operations on pointers that move the pointer by the size of the data type it points to.

```c
int a[5] = {1, 2, 3, 4, 5};
int *p = a;
printf("%d", *(p + 2));  // prints 3 (moves 2 × 4 = 8 bytes)
p++;                     // moves to next int (4 bytes ahead)
```

---

**Q7. Mention two advantages of using pointers.**

- Allows dynamic memory allocation (`malloc`, `calloc`)
- Enables efficient array and string handling
- *(Also: passing large structures without copying; complex data structures)*

---

**Q8. Why are functions needed?**

Functions divide a program into smaller modules, making it easy to understand, reuse, test, and maintain. They also reduce code duplication.

---

**Q9. What is recursion?**

Recursion is a process where a function calls itself to solve a problem by breaking it into smaller sub-problems until a base condition is reached.

```c
int factorial(int n) {
    if (n == 0) return 1;        // base condition
    return n * factorial(n - 1); // recursive call
}
```

---

**Q10. Define call by value.**

Call by value passes **copies** of actual arguments to the function. Changes inside the function do **not** affect the original variables.

---

**Q11. Define call by reference.**

Call by reference passes the **addresses** of variables to the function. Changes inside the function **do** affect the original variables.

---

### ✅ 5-Mark Questions

---

**Q1. Explain the components of a user-defined function.**

**1. Function Declaration (Prototype):**
```c
int add(int, int);   // tells compiler: name, return type, params
```

**2. Function Definition:**
```c
int add(int a, int b) {
    return a + b;    // actual code
}
```

**3. Function Call:**
```c
int result = add(10, 20);   // invoke the function
```

**Complete Example:**
```c
#include <stdio.h>

int add(int, int);           // 1. Declaration

int main() {
    int result = add(10, 20); // 3. Call
    printf("Sum = %d", result);
    return 0;
}

int add(int a, int b) {      // 2. Definition
    return a + b;
}
```

---

**Q2. Explain the different categories of functions in C.**

```c
// Category 1: No arguments, no return value
void display() {
    printf("Hello World!");
}
// Call: display();

// Category 2: Arguments but no return value
void sum(int a, int b) {
    printf("Sum = %d", a + b);
}
// Call: sum(10, 20);

// Category 3: No arguments but return value
int getValue() {
    return 50;
}
// Call: int x = getValue();

// Category 4: Arguments AND return value ← most common
int add(int a, int b) {
    return a + b;
}
// Call: int result = add(10, 20);
```

---

**Q3. Explain pointer declaration and initialization with examples.**

```c
// Declaration — using * before variable name
int *p;         // p is a pointer to int
float *fp;      // fp is a pointer to float
char *cp;       // cp is a pointer to char

// Initialization — assign address using &
int x = 10;
int *p;
p = &x;         // p now stores address of x

// Or in one line:
int *p = &x;

// Dereferencing — access value at address using *
printf("%d", *p);   // prints 10 (value at address)
printf("%p", p);    // prints memory address

// Modification through pointer
*p = 25;
printf("%d", x);    // x is now 25
```

---

**Q4. Discuss the advantages and disadvantages of using pointers.**

**Advantages:**

| Advantage | Details |
|-----------|---------|
| Dynamic memory | `malloc()`, `calloc()`, `realloc()`, `free()` |
| Faster array access | Pointer arithmetic is efficient |
| Pass large data | Structures/arrays passed without copying |
| Data structures | Enables linked lists, trees, graphs |
| Call by reference | Functions can modify actual values |

**Disadvantages:**

| Disadvantage | Details |
|-------------|---------|
| Complex | Beginners make errors easily |
| Memory leaks | Forgetting `free()` wastes memory |
| Dangling pointers | Pointing to freed/invalid memory → crash |
| Security issues | Can access restricted memory areas |
| Hard to debug | Pointer errors are difficult to trace |

---

**Q5. Explain call by value and call by reference.**

```c
#include <stdio.h>

// === CALL BY VALUE ===
// Copies values — original NOT changed
void swap_value(int a, int b) {
    int temp = a;
    a = b;
    b = temp;
    printf("Inside function: a=%d b=%d\n", a, b);
}

// === CALL BY REFERENCE ===
// Passes addresses — original IS changed
void swap_reference(int *a, int *b) {
    int temp = *a;
    *a = *b;
    *b = temp;
}

int main() {
    int x = 10, y = 20;

    printf("--- Call by Value ---\n");
    printf("Before: x=%d y=%d\n", x, y);
    swap_value(x, y);
    printf("After:  x=%d y=%d\n\n", x, y);  // unchanged!

    printf("--- Call by Reference ---\n");
    printf("Before: x=%d y=%d\n", x, y);
    swap_reference(&x, &y);
    printf("After:  x=%d y=%d\n", x, y);    // changed!

    return 0;
}
```

**Output:**
```
--- Call by Value ---
Before: x=10 y=20
Inside function: a=20 b=10
After:  x=10 y=20

--- Call by Reference ---
Before: x=10 y=20
After:  x=20 y=10
```

**Comparison Table:**

| Feature | Call by Value | Call by Reference |
|---------|--------------|-------------------|
| What is passed | Copy of value | Address of variable |
| Original modified | No | Yes |
| Memory usage | More | Less |
| Safety | Safer | Less safe |
| Mechanism in C | Default | Requires pointers |

---

### ✅ 10-Mark Questions

---

**Q1. Explain user-defined functions in C with syntax and examples.**

```c
#include <stdio.h>

/* ---- PROTOTYPES ---- */
void greet();                  // No args, no return
void printSum(int a, int b);   // Args, no return
int getNumber();               // No args, returns value
int multiply(int a, int b);    // Args and return (most common)

/* ---- MAIN ---- */
int main() {
    greet();                          // call type 1
    printSum(5, 10);                  // call type 2
    int n = getNumber();              // call type 3
    int result = multiply(4, 5);      // call type 4
    printf("Result = %d\n", result);
    return 0;
}

/* ---- DEFINITIONS ---- */
void greet() {
    printf("Hello!\n");
}

void printSum(int a, int b) {
    printf("Sum = %d\n", a + b);
}

int getNumber() {
    return 50;
}

int multiply(int a, int b) {
    return a * b;
}
```

**Advantages of User-Defined Functions:**

| Advantage | Explanation |
|-----------|------------|
| Reusability | Write once, call many times |
| Modularity | Large program split into manageable parts |
| Readability | Code is easier to understand |
| Debugging | Isolate and fix errors in individual functions |
| Team development | Different functions assigned to different programmers |

---

**Q2. Explain pointers and their applications in C programming.**

```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    /* ---- Basic pointer ---- */
    int x = 10;
    int *p = &x;
    printf("Address: %p\n", p);
    printf("Value:   %d\n", *p);   // 10

    /* ---- Pointer arithmetic ---- */
    int a[5] = {1, 2, 3, 4, 5};
    int *ptr = a;
    printf("%d\n", *(ptr + 2));    // 3

    /* ---- Dynamic memory allocation ---- */
    int *dyn = (int*)malloc(5 * sizeof(int));
    dyn[0] = 10; dyn[1] = 20;
    free(dyn);

    /* ---- Pointer to pointer ---- */
    int val = 100;
    int *q = &val;
    int **qq = &q;
    printf("%d\n", **qq);           // 100

    return 0;
}

/* ---- Call by reference (swap) ---- */
void swap(int *a, int *b) {
    int temp = *a;
    *a = *b;
    *b = temp;
}

/* ---- Function pointer ---- */
int add(int a, int b) { return a + b; }

void demo_func_ptr() {
    int (*fp)(int, int) = add;
    printf("%d\n", fp(10, 20));    // 30
}
```

**Types of Pointers:**

| Type | Description |
|------|-------------|
| NULL pointer | Points to nothing — `int *p = NULL;` |
| Void pointer | Generic pointer — `void *p;` |
| Wild pointer | Uninitialized — dangerous |
| Dangling pointer | Points to freed/out-of-scope memory |
| Function pointer | Points to a function |
| Pointer to pointer | `int **pp` |

**Applications:**

| Application | Example |
|-------------|---------|
| Dynamic memory | `malloc()`, `calloc()`, `free()` |
| Array traversal | `*(ptr + i)` |
| Call by reference | `swap(&a, &b)` |
| Data structures | Linked lists, trees, graphs |
| Function pointers | Callbacks, dynamic dispatch |

---

## Unit V — Structures, Unions & File Management

### ✅ 2-Mark Questions

---

**Q1. What is a structure?**

A structure is a user-defined data type that allows storing different types of data items together under a single name.

```c
struct Student {
    int id;
    char name[20];
    float marks;
};
```

---

**Q2. What is a union?**

A union is a user-defined data type where all members share the same memory location. Only one member can store a value at a time.

```c
union Data {
    int i;
    float f;
    char ch;
};
// Size = size of largest member only
```

---

**Q3. Differentiate between structure and union.**

| Feature | Structure | Union |
|---------|-----------|-------|
| Memory | Separate for each member | All members share same memory |
| Simultaneous use | All members usable at once | Only one member at a time |
| Size | Sum of all members' sizes | Size of the largest member |
| Use case | Store full records | Memory-efficient variant storage |

---

**Q4. What is an array of structures?**

An array of structures stores multiple structure variables sequentially in memory — used to store many records.

```c
struct Student s[50];  // array of 50 student records
s[0].id = 101;
strcpy(s[0].name, "Husen");
```

---

**Q5. What is a file in C?**

A file is a named storage area on disk used to store data permanently, allowing persistent input/output between program runs.

---

**Q6. Mention any two file handling functions.**

```c
FILE *fp = fopen("file.txt", "r");  // open file
fclose(fp);                          // close file

// Others:
fprintf(fp, "%d", x);   // write formatted data
fscanf(fp, "%d", &x);   // read formatted data
fgetc(fp);               // read a character
fputc('A', fp);          // write a character
```

---

**Q7. What is `fopen()`?**

`fopen()` opens a file in a specified mode (read, write, append).

```c
FILE *fp = fopen("file.txt", "r");   // open for reading
if (fp == NULL)
    printf("File not found!");
```

---

### ✅ 5-Mark Questions

---

**Q1. Explain structure declaration and initialization with examples.**

```c
/* === Declaration === */
struct Student {
    int id;
    char name[20];
    float marks;
};

/* === Variable Declaration === */
struct Student s1;          // Method 1: after struct
struct Student s2, s3;

// Method 2: at time of declaration
struct Student {
    int id;
    char name[20];
} s1, s2;

/* === Initialization === */
// Static initialization
struct Student s1 = {101, "Husen", 89.5};

// Member-wise initialization
struct Student s2;
s2.id = 102;
strcpy(s2.name, "Rahul");
s2.marks = 92.0;

/* === Accessing Members === */
printf("%d", s1.id);       // dot operator
printf("%s", s1.name);
printf("%.1f", s1.marks);
```

---

**Q2. Explain the differences between structures and unions.**

```c
#include <stdio.h>

struct StructExample {
    int i;       // 4 bytes
    float f;     // 4 bytes
    char ch;     // 1 byte
    // Total size: ~12 bytes (with padding)
};

union UnionExample {
    int i;       // 4 bytes
    float f;     // 4 bytes
    char ch;     // 1 byte
    // Total size: 4 bytes (only largest member)
};

int main() {
    printf("Size of struct: %lu\n", sizeof(struct StructExample));  // 12
    printf("Size of union:  %lu\n", sizeof(union UnionExample));    // 4
    return 0;
}
```

---

**Q3. Discuss file opening modes in C.**

```c
FILE *fp;

fp = fopen("data.txt", "r");   // Read  — file must exist
fp = fopen("data.txt", "w");   // Write — creates or overwrites
fp = fopen("data.txt", "a");   // Append — adds to end
fp = fopen("data.txt", "r+");  // Read + Write (file must exist)
fp = fopen("data.txt", "w+");  // Write + Read (creates or overwrites)
fp = fopen("data.txt", "a+");  // Append + Read

// Binary modes:
fp = fopen("data.bin", "rb");  // binary read
fp = fopen("data.bin", "wb");  // binary write
fp = fopen("data.bin", "ab");  // binary append
```

**File Mode Summary:**

| Mode | Read | Write | Create | Overwrite | Pointer Position |
|------|------|-------|--------|-----------|-----------------|
| `"r"` | ✅ | ❌ | ❌ | ❌ | Beginning |
| `"w"` | ❌ | ✅ | ✅ | ✅ | Beginning |
| `"a"` | ❌ | ✅ | ✅ | ❌ | End |
| `"r+"` | ✅ | ✅ | ❌ | ❌ | Beginning |
| `"w+"` | ✅ | ✅ | ✅ | ✅ | Beginning |
| `"a+"` | ✅ | ✅ | ✅ | ❌ | End |

---

**Q4. Explain file error handling functions in C.**

```c
#include <stdio.h>

int main() {
    FILE *fp;

    // 1. Check if fopen() failed (returns NULL)
    fp = fopen("data.txt", "r");
    if (fp == NULL) {
        printf("Unable to open file\n");
        return 1;
    }

    // 2. ferror() — check if error occurred
    if (ferror(fp)) {
        printf("File error occurred\n");
    }

    // 3. feof() — check if end of file reached
    char ch;
    while (!feof(fp)) {
        ch = fgetc(fp);
        putchar(ch);
    }

    // 4. perror() — print system error message
    fp = fopen("info.txt", "r");
    if (!fp)
        perror("Error opening file");
    // Output: Error opening file: No such file or directory

    // 5. clearerr() — clear error and EOF indicators
    clearerr(fp);

    fclose(fp);
    return 0;
}
```

---

### ✅ 10-Mark Questions

---

**Q1. Explain structures in C with syntax and examples.**

```c
#include <stdio.h>
#include <string.h>

/* Basic structure */
struct Student {
    int roll;
    char name[20];
    float marks;
};

/* Nested structure */
struct Address {
    char city[20];
    int pincode;
};
struct Employee {
    char name[20];
    struct Address addr;   // nested
};

/* Structure with function */
void display(struct Student s) {
    printf("Roll: %d | Name: %s | Marks: %.1f\n",
           s.roll, s.name, s.marks);
}

int main() {
    /* Static initialization */
    struct Student s1 = {101, "Husen", 92.5};

    /* Member-wise initialization */
    struct Student s2;
    s2.roll = 102;
    strcpy(s2.name, "Rahul");
    s2.marks = 88.0;

    /* Display */
    display(s1);
    display(s2);

    /* Array of structures */
    struct Student class[3];
    class[0] = s1;
    class[1] = s2;

    /* Nested structure */
    struct Employee emp;
    strcpy(emp.name, "Ahmed");
    strcpy(emp.addr.city, "Mumbai");
    emp.addr.pincode = 400001;
    printf("City: %s\n", emp.addr.city);

    return 0;
}
```

---

**Q2. Explain file management in C — opening, reading, writing, closing.**

```c
#include <stdio.h>

int main() {
    FILE *fp;
    char ch;
    char str[100];

    /* ===== 1. WRITE TO FILE ===== */
    fp = fopen("sample.txt", "w");
    if (fp == NULL) {
        printf("Cannot open file for writing\n");
        return 1;
    }
    fprintf(fp, "Hello, File Handling!\n");   // formatted write
    fputs("Second line\n", fp);               // string write
    fputc('Z', fp);                           // character write
    fclose(fp);

    /* ===== 2. READ FROM FILE ===== */
    fp = fopen("sample.txt", "r");
    if (fp == NULL) {
        printf("Cannot open file for reading\n");
        return 1;
    }

    // Method 1: character by character
    printf("--- Character read ---\n");
    while ((ch = fgetc(fp)) != EOF)
        putchar(ch);
    rewind(fp);   // go back to beginning

    // Method 2: line by line
    printf("\n--- Line read ---\n");
    while (fgets(str, 100, fp) != NULL)
        printf("%s", str);

    fclose(fp);

    /* ===== 3. APPEND TO FILE ===== */
    fp = fopen("sample.txt", "a");
    fprintf(fp, "\nAppended line");
    fclose(fp);

    return 0;
}
```

**File Functions Summary:**

| Function | Purpose | Syntax |
|----------|---------|--------|
| `fopen()` | Open a file | `FILE *fp = fopen("file", "mode")` |
| `fclose()` | Close a file | `fclose(fp)` |
| `fprintf()` | Formatted write | `fprintf(fp, "%d", x)` |
| `fscanf()` | Formatted read | `fscanf(fp, "%d", &x)` |
| `fputc()` | Write a char | `fputc('A', fp)` |
| `fgetc()` | Read a char | `ch = fgetc(fp)` |
| `fputs()` | Write a string | `fputs("hello", fp)` |
| `fgets()` | Read a string | `fgets(str, 100, fp)` |
| `feof()` | Check end of file | `while(!feof(fp))` |
| `ferror()` | Check error | `if(ferror(fp))` |
| `rewind()` | Reset to beginning | `rewind(fp)` |

---

**Q3. Explain structure and union with suitable examples.**

```c
#include <stdio.h>

/* === STRUCTURE === */
struct Student {
    int roll;
    char name[20];
    float marks;
};

/* === UNION === */
union Data {
    int i;
    float f;
    char ch;
};

int main() {
    /* Structure — all members accessible simultaneously */
    struct Student s = {101, "Husen", 90.5};
    printf("Roll: %d | Name: %s | Marks: %.1f\n",
           s.roll, s.name, s.marks);
    printf("Size of struct: %lu bytes\n\n", sizeof(s));

    /* Union — only one member valid at a time */
    union Data d;

    d.i = 10;
    printf("Union int:   %d\n", d.i);

    d.f = 3.14;             // overwrites previous value
    printf("Union float: %f\n", d.f);
    printf("Size of union: %lu bytes\n", sizeof(d));

    return 0;
}
```

**Output:**
```
Roll: 101 | Name: Husen | Marks: 90.5
Size of struct: 28 bytes

Union int:   10
Union float: 3.140000
Size of union: 4 bytes
```

---

**Q4. Write a C program to create, write, read and close a file.**

```c
#include <stdio.h>

int main() {
    FILE *fp;
    char ch;

    /* ---- Step 1: Create and Write ---- */
    fp = fopen("sample.txt", "w");
    if (fp == NULL) {
        printf("File cannot be opened\n");
        return 1;
    }
    printf("Writing data into file...\n");
    fprintf(fp, "Welcome to C File Handling\n");
    fprintf(fp, "Unit 5 — Structures and Files\n");
    fclose(fp);

    /* ---- Step 2: Open and Read ---- */
    fp = fopen("sample.txt", "r");
    if (fp == NULL) {
        printf("File cannot be opened\n");
        return 1;
    }
    printf("Reading data from file:\n");
    printf("----------------------------\n");
    while ((ch = fgetc(fp)) != EOF) {
        printf("%c", ch);
    }
    printf("----------------------------\n");
    fclose(fp);

    return 0;
}
```

**Output:**
```
Writing data into file...
Reading data from file:
----------------------------
Welcome to C File Handling
Unit 5 — Structures and Files
----------------------------
```

**Functions Used:**

| Function | Purpose |
|----------|---------|
| `fopen("file", "w")` | Create/open file for writing |
| `fprintf()` | Write formatted data |
| `fclose()` | Save and close file |
| `fopen("file", "r")` | Open for reading |
| `fgetc()` | Read one character at a time |

---

## Previous Year Papers

### 📄 Section A — January/February 2025 (2 Marks Each)

---

**Q1(a). Define flowchart. Mention any two symbols.**

A flowchart is a diagram that represents algorithm steps using standard symbols.

| Symbol | Meaning |
|--------|---------|
| Oval | Start / Stop |
| Parallelogram | Input / Output |
| Rectangle | Process |
| Diamond | Decision |

---

**Q1(b). What is a C character set?**

The C character set includes all characters used in C programs:
- Letters: `A–Z`, `a–z`
- Digits: `0–9`
- Special symbols: `+`, `-`, `*`, `/`, `%`, `&`, `#`, etc.
- White spaces: space, newline, tab

---

**Q1(c). Write syntax of `scanf()` function.**

```c
scanf("format specifier", &variable);

// Example:
scanf("%d %f", &a, &b);
```

---

**Q1(d). What are bitwise operators in C?**

```c
// Operators used to manipulate individual bits:
& (AND), | (OR), ^ (XOR), ~ (NOT), << (left shift), >> (right shift)

// Example:
int a = 5;   // 0101
int b = 3;   // 0011
printf("%d", a & b);  // 1 (0001)
printf("%d", a | b);  // 7 (0111)
```

---

**Q1(e). Write syntax of `if-else` ladder.**

```c
if (condition1) {
    // block 1
}
else if (condition2) {
    // block 2
}
else if (condition3) {
    // block 3
}
else {
    // default block
}
```

---

**Q1(f). How do you declare a one-dimensional array?**

```c
int arr[10];           // array of 10 integers
float marks[50];       // array of 50 floats
char name[20];         // array of 20 characters

// With initialization:
int a[5] = {1, 2, 3, 4, 5};
```

---

**Q1(g). Define pointers in C.**

A pointer is a variable that stores the memory address of another variable.

```c
int x = 10;
int *p = &x;   // p is a pointer storing address of x
```

---

**Q1(h). What is a user-defined function?**

A function created by the programmer to perform a specific task, separate from library functions.

---

**Q1(i). What is a structure in C?**

A structure is a user-defined data type that groups different types of data under one name.

---

**Q1(j). How do you declare and initialize a union in C?**

```c
union Data {
    int x;
    float y;
    char ch;
};

union Data d1 = {10};   // initializes first member (x = 10)
```

---

### 📄 Section B — January/February 2025 (5 Marks Each)

---

**Q2. Program — Sum of two integers.**

```c
#include <stdio.h>

int main() {
    int a, b, sum;
    printf("Enter two integers: ");
    scanf("%d %d", &a, &b);
    sum = a + b;
    printf("Sum = %d\n", sum);
    return 0;
}
```

---

**Q3. Arithmetic operators in C with examples.**

```c
#include <stdio.h>

int main() {
    int a = 10, b = 3;
    printf("a + b = %d\n", a + b);  // 13 — Addition
    printf("a - b = %d\n", a - b);  // 7  — Subtraction
    printf("a * b = %d\n", a * b);  // 30 — Multiplication
    printf("a / b = %d\n", a / b);  // 3  — Division (integer)
    printf("a %% b = %d\n", a % b); // 1  — Modulus (remainder)
    return 0;
}
```

---

**Q4. Declare, initialize and process a 2D array.**

```c
#include <stdio.h>

int main() {
    // Declaration
    int a[3][3];

    // Initialization
    int b[3][3] = { {1,2,3}, {4,5,6}, {7,8,9} };

    // Processing — display all elements
    int i, j;
    for (i = 0; i < 3; i++) {
        for (j = 0; j < 3; j++)
            printf("%d ", b[i][j]);
        printf("\n");
    }
    return 0;
}
```

---

**Q5. User-defined function with C program.**

```c
#include <stdio.h>

// Prototype
int add(int x, int y);

int main() {
    int a = 10, b = 20;
    printf("Sum = %d\n", add(a, b));
    return 0;
}

// Definition
int add(int x, int y) {
    return x + y;
}
```

---

**Q6. Define and initialize a union with examples.**

```c
#include <stdio.h>

union Data {
    int i;
    float f;
    char c;
};

int main() {
    union Data d;

    d.i = 10;
    printf("i = %d\n", d.i);

    d.f = 12.5;
    printf("f = %f\n", d.f);   // i is now overwritten

    d.c = 'A';
    printf("c = %c\n", d.c);   // f is now overwritten

    printf("Size = %lu\n", sizeof(d));  // size of largest member
    return 0;
}
```

---

**Q7. Program — Check whether a number is prime.**

```c
#include <stdio.h>

int main() {
    int n, i, flag = 0;
    printf("Enter a number: ");
    scanf("%d", &n);

    if (n <= 1) {
        printf("Not Prime\n");
    } else {
        for (i = 2; i <= n / 2; i++) {
            if (n % i == 0) {
                flag = 1;
                break;
            }
        }
        if (flag == 0)
            printf("%d is Prime\n", n);
        else
            printf("%d is Not Prime\n", n);
    }
    return 0;
}
```

---

### 📄 Section C — January/February 2025 (10 Marks Each)

---

**Q8. Describe the structure of a C program with example.**

```c
/* === 1. Documentation Section === */
/* Program: Demonstrate C program structure
   Author:  Husen
   Date:    2025                          */

/* === 2. Link Section === */
#include <stdio.h>
#include <math.h>

/* === 3. Definition Section === */
#define PI 3.14
#define MAX 100

/* === 4. Global Declaration Section === */
int x;
int add(int, int);   // function prototype

/* === 5. main() Function Section === */
int main() {
    int a = 10, b = 20;           // local declaration
    int result = add(a, b);        // execution
    printf("Sum = %d\n", result);
    return 0;
}

/* === 6. User-Defined Function Section === */
int add(int a, int b) {
    return a + b;
}
```

---

**Q9(a). Explain formatted I/O functions in C.**

```c
#include <stdio.h>

int main() {
    int age;
    float salary;
    char name[20];

    // scanf — formatted input
    printf("Enter name, age, salary: ");
    scanf("%s %d %f", name, &age, &salary);

    // printf — formatted output
    printf("\nName:   %s\n", name);
    printf("Age:    %d\n", age);
    printf("Salary: %.2f\n", salary);

    return 0;
}
```

---

**Q9(b). Program — Read and display int, float and char.**

```c
#include <stdio.h>

int main() {
    int a;
    float b;
    char c;

    printf("Enter an integer, float, and character:\n");
    scanf("%d %f %c", &a, &b, &c);

    printf("\nInteger   = %d\n", a);
    printf("Float     = %.2f\n", b);
    printf("Character = %c\n", c);

    return 0;
}
```

---

**Q10. Explain looping statements in C with examples.**

```c
#include <stdio.h>

int main() {
    int i;

    /* 1. while loop — entry controlled */
    i = 1;
    while (i <= 5) {
        printf("%d ", i);   // 1 2 3 4 5
        i++;
    }
    printf("\n");

    /* 2. for loop — entry controlled, compact */
    for (i = 1; i <= 5; i++) {
        printf("%d ", i);   // 1 2 3 4 5
    }
    printf("\n");

    /* 3. do-while loop — exit controlled, runs at least once */
    i = 1;
    do {
        printf("%d ", i);   // 1 2 3 4 5
        i++;
    } while (i <= 5);
    printf("\n");

    /* 4. break — exit loop early */
    for (i = 1; i <= 10; i++) {
        if (i == 6) break;
        printf("%d ", i);   // 1 2 3 4 5
    }
    printf("\n");

    /* 5. continue — skip iteration */
    for (i = 1; i <= 5; i++) {
        if (i == 3) continue;
        printf("%d ", i);   // 1 2 4 5
    }
    printf("\n");

    return 0;
}
```

---

**Q11(a). Demonstrate relationship between pointers and arrays.**

```c
#include <stdio.h>

int main() {
    int a[5] = {10, 20, 30, 40, 50};
    int *p;

    p = a;   // array name = base address of first element

    printf("Using pointer arithmetic:\n");
    for (int i = 0; i < 5; i++) {
        printf("a[%d] = %d  |  Address = %p\n",
               i, *(p + i), (p + i));
    }

    return 0;
}
// Array name 'a' == &a[0] == pointer to first element
// *(p + i) is equivalent to a[i]
```

---

**Q11(b). Explain concept of pointer.**

```c
#include <stdio.h>

int main() {
    int x = 10;
    int *p = &x;

    printf("Value of x:       %d\n", x);     // 10
    printf("Address of x:     %p\n", &x);    // e.g. 0x7ffd...
    printf("Value of p:       %p\n", p);     // same address
    printf("Value at *p:      %d\n", *p);    // 10

    // Modify x through pointer
    *p = 99;
    printf("x after *p = 99:  %d\n", x);     // 99

    return 0;
}
```

---

**Q12(a). Explain difference between structures and unions.**

```c
// Structure
struct S { int i; float f; char c; };
// sizeof(S) ≈ 9+ bytes (each member has its own memory)

// Union
union U { int i; float f; char c; };
// sizeof(U) = 4 bytes (only largest member's size)
```

---

**Q12(b). Program — Show memory usage in structure and union.**

```c
#include <stdio.h>

struct Student {
    int roll;     // 4 bytes
    float marks;  // 4 bytes
    char grade;   // 1 byte
    // Total (with padding): ~12 bytes
};

union Data {
    int roll;     // 4 bytes
    float marks;  // 4 bytes
    char grade;   // 1 byte
    // Total: 4 bytes (only largest)
};

int main() {
    struct Student s;
    union Data d;

    printf("Size of structure = %lu bytes\n", sizeof(s));  // ~12
    printf("Size of union     = %lu bytes\n", sizeof(d));  // 4
    return 0;
}
```

---

**Q13(a). Explain `strlen()`, `strcmp()`, `strcpy()`, `strcat()`.**

```c
#include <string.h>

// 1. strlen(s) — returns length (excludes \0)
strlen("Hello");       // returns 5

// 2. strcmp(s1, s2) — compares strings
strcmp("abc", "abc");  // 0  (equal)
strcmp("abc", "abd");  // <0 (s1 < s2)
strcmp("abd", "abc");  // >0 (s1 > s2)

// 3. strcpy(dest, src) — copies src into dest
char dest[20];
strcpy(dest, "Hello");  // dest = "Hello"

// 4. strcat(dest, src) — appends src to dest
char a[20] = "Hello ";
strcat(a, "World");     // a = "Hello World"
```

---

**Q13(b). Program — Demonstrate string handling functions.**

```c
#include <stdio.h>
#include <string.h>

int main() {
    char s1[50] = "Hello";
    char s2[50] = "World";
    char s3[50];

    printf("s1 = %s\n", s1);
    printf("s2 = %s\n\n", s2);

    // strlen
    printf("Length of s1 = %lu\n", strlen(s1));   // 5

    // strcpy
    strcpy(s3, s1);
    printf("Copy of s1   = %s\n", s3);             // Hello

    // strcat
    strcat(s1, s2);
    printf("Concatenated = %s\n", s1);             // HelloWorld

    // strcmp
    int result = strcmp("A", "B");
    printf("strcmp A,B   = %d\n", result);         // negative

    return 0;
}
```

---

### 📄 Preparatory Question Paper 2025

---

**Q: Program — Convert Celsius to Fahrenheit.**

```c
#include <stdio.h>

int main() {
    float c, f;
    printf("Enter temperature in Celsius: ");
    scanf("%f", &c);
    f = (c * 9.0 / 5.0) + 32;
    printf("Temperature in Fahrenheit = %.2f\n", f);
    return 0;
}
```

---

**Q: Explain `break` and `continue` statements.**

```c
// break — exits the loop immediately
for (int i = 1; i <= 10; i++) {
    if (i == 5) break;
    printf("%d ", i);   // Output: 1 2 3 4
}

// continue — skips current iteration, moves to next
for (int i = 1; i <= 5; i++) {
    if (i == 3) continue;
    printf("%d ", i);   // Output: 1 2 4 5
}
```

---

**Q: Program — Display employee details using array of structures.**

```c
#include <stdio.h>

struct Employee {
    int id;
    char name[30];
    float salary;
};

int main() {
    struct Employee emp[3];
    int i;

    printf("Enter details of 3 employees:\n");
    for (i = 0; i < 3; i++) {
        printf("\nEmployee %d\n", i + 1);
        printf("ID: ");     scanf("%d", &emp[i].id);
        printf("Name: ");   scanf("%s", emp[i].name);
        printf("Salary: "); scanf("%f", &emp[i].salary);
    }

    printf("\n===== Employee Details =====\n");
    for (i = 0; i < 3; i++) {
        printf("\nID:     %d\n", emp[i].id);
        printf("Name:   %s\n", emp[i].name);
        printf("Salary: %.2f\n", emp[i].salary);
    }

    return 0;
}
```

---

**Q: Program — Find even or odd using a function.**

```c
#include <stdio.h>

int isEven(int n);   // prototype

int main() {
    int num;
    printf("Enter an integer: ");
    scanf("%d", &num);

    if (isEven(num))
        printf("%d is Even\n", num);
    else
        printf("%d is Odd\n", num);

    return 0;
}

int isEven(int n) {
    return (n % 2 == 0) ? 1 : 0;
}
```

---

**Q: Program — Find roots of a quadratic equation.**

```c
#include <stdio.h>
#include <math.h>

int main() {
    float a, b, c, disc, r1, r2;
    printf("Enter a, b, c: ");
    scanf("%f %f %f", &a, &b, &c);

    disc = b*b - 4*a*c;

    if (disc > 0) {
        r1 = (-b + sqrt(disc)) / (2*a);
        r2 = (-b - sqrt(disc)) / (2*a);
        printf("Real & distinct: %.2f and %.2f\n", r1, r2);
    } else if (disc == 0) {
        r1 = -b / (2*a);
        printf("Real & equal: %.2f\n", r1);
    } else {
        float real = -b / (2*a);
        float imag = sqrt(-disc) / (2*a);
        printf("Complex: %.2f + %.2fi  and  %.2f - %.2fi\n",
               real, imag, real, imag);
    }
    return 0;
}
```

---

**Q: Program — Find trace of a square matrix.**

```c
#include <stdio.h>

int main() {
    int n, i, j, trace = 0;
    int a[10][10];

    printf("Enter size of square matrix: ");
    scanf("%d", &n);

    printf("Enter matrix elements:\n");
    for (i = 0; i < n; i++)
        for (j = 0; j < n; j++)
            scanf("%d", &a[i][j]);

    printf("\nMatrix:\n");
    for (i = 0; i < n; i++) {
        for (j = 0; j < n; j++)
            printf("%d ", a[i][j]);
        printf("\n");
    }

    for (i = 0; i < n; i++)
        trace += a[i][i];   // sum of diagonal elements

    printf("\nTrace = %d\n", trace);
    return 0;
}
```

---

**Q: Describe the categories of user-defined functions.**

```c
#include <stdio.h>

/* Type 1: No arguments, no return value */
void display() {
    printf("Hello World!\n");
}

/* Type 2: Arguments, no return value */
void printSum(int a, int b) {
    printf("Sum = %d\n", a + b);
}

/* Type 3: No arguments, return value */
int getNumber() {
    return 42;
}

/* Type 4: Arguments AND return value (most common) */
int add(int a, int b) {
    return a + b;
}

int main() {
    display();               // type 1
    printSum(10, 20);        // type 2
    int n = getNumber();     // type 3
    int r = add(5, 7);       // type 4
    printf("n=%d, r=%d\n", n, r);
    return 0;
}
```

---

*Prepared by  Husen** | Best of luck for your examinations!*

*Read carefully · Code daily · Stay consistent 💪*
