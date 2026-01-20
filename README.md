# 📘 C Programming – Theory Notes

This repository contains **C Programming theory notes** prepared for  
**BCA,BE,Bsc students** and **exam preparation**.

---

## 📂 Contents
- Unit-wise C Programming theory
- 2 Marks, 5 Marks & 10 Marks questions
- Exam-oriented answers
- Clear explanations with examples



## 🎯 Useful For
- BCA / BSc / Diploma students
- Semester exams
- C programming revision
- Beginners in C language

---

## 🛠️ Tools & Topics
- C Programming
- Problem Solving
- Algorithms & Flowcharts
- Arrays, Functions, Pointers
- Structures & File Handling

---

## 👤 Author
**Husen**  
**BCA Student at SVK College | Koppal**  
---

⭐ If this helps you, give the repo a star!



# UNIT – I: Problem Solving and Introduction to C 
<br>
## 2 Marks Questions

## 1.Define an algorithm.?
<br>
ANS:- An algorithm is step by step procedure desgine to perform a specific task or solve particular problem<br>
EX:- Algorithm to add two numbers
1. Start<br>
2. Read two numbers A and B<br>
3. Add A and B and store in C<br>
4. Display C<br>
5. Stop<br>

## 2.What are the characteristics of a good algorithm?
<br>
ANS:-
A good algorithm should have:<br>
1. Clear and simple steps – no confusion in instructions.<br>
2. Finite steps – it must finish after a limited number of steps.<br>
3. Correct output – it should give the right result for all valid inputs.<br>
4. Efficiency – it should use minimum time and memory.<br>



## 3. What is a flowchart?<br>
A flowchart is a graphical representation of an algorithm or process using symbols to show the flow of steps.<br>
EX :- alogoritm same

## 4. Mention any two symbols used in flowcharts.<br>
• Oval → Start/Stop<br>
• Parallelogram → Input/Output<br>
(You can also mention: Rectangle → Process, Diamond → Decision)<br>

## 5. What are keywords in C?<br>
Keywords are reserved words in C that have special meaning and cannot be used as variable names. Example: int, return.<br>

## 6. What is a variable in C? <br>
A variable is a named memory location used to store data that can change during program execution.<br>

## 7. What is meant by symbolic constant?<br>
A symbolic constant is a name that represents a fixed value defined using #define or const, and it cannot be changed during program execution.<br>

## 8. Name any two features of C language.<br>
• Portability (write once, run anywhere)<br>
• Modularity (programs can be divided into functions)<br>
(You can also write: Fast execution, Rich library, Structured language)<br>


## 5 Marks Questions<br>

## 1. Explain the steps involved in creating and executing a C program.<br>
The following steps are involved in creating and executing a C program:<br>
1. **Creating the Program (Editing):** The programmer writes the source code using a text editor and saves it with the extension .c.<br>
2. **Compilation:** The compiler checks the program for errors (syntax/semantic) and converts the source code into an object file (.obj or .o).<br>
3. **Linking:** The linker combines the object file with necessary library files and creates an executable file (.exe).<br>
4. **Loading:** The loader loads the executable file into the main memory for execution.<br>
5. **Execution:** The CPU executes the instructions and displays the output.<br>

## 2. Write a short note on the structure of a C program with an example.<br>
A C program has the following basic structure:<br>
1. **Documentation Section:** Comment lines used to describe the program.<br> Example: /* Program to add two numbers */<br>
2. **Link Section:** Contains header file inclusions. Example: #include <stdio.h><br>
3. **Global Declaration Section:** Variables or functions declared globally.<br>
4. **main() Function Section:** The starting point of every C program. It contains:<br>
o  Declaration part<br>
o  Executable part<br>
5. **User-Defined Functions Section:** Additional functions defined by the programmer.<br>

Example:<br>

    #include <stdio.h>
    int main() {<br>
    int a, b, sum;<br>
    a = 5;
    b = 10;
    sum = a + b;

    printf("Sum = %d", sum);

    return 0;
    }<br>

## 3. Explain the compilation process in C.<br>
The compilation process involves several stages:<br>
1. **Preprocessing:** Handles directives such as #include and #define. Creates an expanded source code.<br>
2. **Compilation:** Converts the expanded code into assembly language.<br>
3. **Assembly:** Translates assembly code into machine code and generates an object file.<br>
4. **Linking:** Links the object file with standard library functions to create an executable file.<br>
5.  **Loading and Execution:** The loader loads the file into memory and the CPU executes the program.<br>

## 4. Discuss the different data types in C with examples<br>
C supports several data types:<br>
### 1. Basic Data Types:<br>
o **int →** stores integers → Example: int a = 10;<br>
o **float →** stores decimal values → Example: float x = 3.14;<br>
o **char →** stores single character → Example: char c = 'A';<br>
o **double →** stores double-precision numbers → Example: double d = 10.3456;<br>
### 2. Derived Data Types:<br>
o **arrays** → Example: int a[5];<br>
o **pointers →** Example: int *p;<br>
o **functions →** Example: user-defined functions<br>
o **structures →** Example: struct student { ... };<br>
### 3. Enumeration Data Type:<br>
o **enum →** assigns names to integer constants. Example:<br>
o enum days {Mon, Tue, Wed};<br>
4. **Void Data Type**:<br>
o Represents empty value or no return type. Example: void display();<br>

## 5. Describe the basic C tokens with examples.<br>
C tokens are the smallest individual units of a C program. They include:<br>
1. **Keywords:** Reserved words with special meaning.<br> Example: int, return, while<br>
2. **Identifiers:** Names given to variables, functions, etc. <br>Example: sum, main, age<br>
3. **Constants:** Fixed values that do not change.<br> Example: 10, 3.14, 'A'<br>
4.**Strings:** Sequence of characters.<br> Example: "Hello"<br>
5.** Operators:** Symbols used to perform operations.<br> Example: +, -, *, /, ==<br>
6.**Special Symbols:** Symbols with special meaning.<br> Example: { }, ( ), [ ], ;<br>
7. **Punctuators:** Used to separate statements. <br>Example: comma ,, semicolon ;<br>

# 10 Marks Questions <br>
## 1. Explain the algorithm and flowchart with a suitable example. 
Algorithm <br>
## Algorithm  <br>
An algorithm is a step-by-step, finite set of instructions used to solve a problem. Characteristics of a good algorithm:  <br>
• Clear and unambiguous <br>
• Stepwise  <br>
• Finite  <br>
• Effective <br>
• Input/output defined  <br>

**Example Algorithm: Add Two Numbers** <br>
1. Start<br>
2. Read two numbers A and B<br>
3. Add A and B → SUM<br>
4. Display SUM<br>
5. Stop<br>

## Flowchart <br>
A flowchart is a graphical representation of an algorithm using standard symbols such as: <br>
• Oval → Start/Stop<br
• Parallelogram → Input/Output <br>
• Rectangle → Process<br>
• Diamond → Decision <br>

**Explanation**<br>
• The flowchart visually shows the steps of the algorithm. <br>
• Input/output and processing steps are clearly represented.<br> 


## 2. Describe the structure of a C program and explain each section.<br> 
A C program is divided into several logical sections. The typical structure is:<br>
1. **Documentation Section** o Contains comments describing the program, purpose, and author.<br>
  Example: /* Program to add two numbers */<br>
2. **Link Section** o Includes header files using #include. o Provides access to library functions.<br>
   Example: #include <stdio.h><br>
3.**Definition Section** o Used to define symbolic constants using #define. Example: #define PI 3.14<br>
4. **Global Declaration Section** o Global variables, user-defined function prototypes are declared here.<br>
    Example: int x; void display();<br>
5. **main() Function Section** o The entry point of every C program. o Contains two parts:<br>
   a) **Declaration Part** – local variables are declared<br>
   b) **Execution Part** – program logic is written <br>
Example<br>
**int main() {
 int a, b, sum;   // Declaration
sum = a + b;     // Execution
return 0;
 }**

6. **User-Defined Function Section**
 Functions written by the programmer.
  o Provides modularity and reusability.
   Example:
        void display() {
         printf("Hello");
     } 

## 3. Explain the different data types and declaration of variables in C.
Data Types in C<br>
C supports four major categories:<br>

**1. Basic (Primary) Data Types**<br>
These are fundamental types used to store simple values:<br>
Data Type	Meaning	Example<br>
**Int** 	    Integer numbers	   int age = 20;<br>
**float**	   Single-precision decimal	   float x = 3.5;<br>
**double**	   Double-precision decimal	   double pi = 3.14159;<br>
**char**	   Single character	   char grade = 'A';<br>

**2. Derived Data Types**<br>
Created using basic data types:<br>
•	**Arrays** → int a[10];<br>
•	**Pointers **→ int *p;<br>
•	**Functions** → user-defined<br>
•	**Structures** → struct student {...};<br>
•	**Unions** → memory-shared structure<br>

3. **Enumeration Data Type**<br>
Used to assign names to integral constants.<br>
Example:<br>
enum days {Mon, Tue, Wed, Thu};<br>

4.**Void Data Typ**e<br>
Represents "nothing" or "no value."<br>
Example:<br>
void display();<br>
## **Declaration of Variables**<br>
A variable declaration tells the compiler:<br>
•	the name of the variable<br>
•	the type of data it will store<br>
**Syntax**:<br>
data_type variable_name;<br>
**Examples**:<br>
**int** age;<br>
**float** marks;<br>
**char** ch;<br>
**double** salary;<br>
## **Multiple variable declaration**<br>
**int** a, b, c;<br>
**float** x, y;<br>
## **Initialization during declaration**:<br>
**int** a = 10;<br>
**char** c = 'A';<br>
**float** pi = 3.14;<br>




# UNIT – II: Input/Output and Operators<br>
## 2 Marks Questions<br>

## 1. Differentiate between formatted and unformatted I/O functions.<br>
## Formatted I/O:<br>
•	Functions that allow input/output in a specific format.<br>
•	Examples: printf(), scanf()<br>
•	We can control the type, width, precision, etc.<br>
## Unformatted I/O:<br>
•	Functions that handle data without any specific format.<br>
•	**Examples:** getchar(), putchar(), gets(), puts(), gets_s()<br>
•	Used for single characters or strings.<br>
________________________________________
## 2. Write the syntax of printf() and scanf().<br>
printf():<br>
**printf("format string", arguments);** <br>
scanf():<br>
**scanf("format string", &variables);** <br>

## 3. What are escape sequences? Give examples<br>
Escape sequences are special character combinations that represent non-printable characters in a string.<br>
Examples:<br>
•	**\n** – New line<br>
•	**\t** – Horizontal tab<br>
•	\\ – Backslash<br>
•	**\"** – Double quote<br>

## 4. What is an arithmetic operator? <br>
Arithmetic operators are symbols used to perform mathematical operations like addition, subtraction, multiplication, etc. <br>
**Examples:** +, -, *, /, % <br>

## 5. Define relational operators. <br>
Relational operators are used to compare two values and return either true (1) or false (0).  <br>
Examples: >, <, >=, <=, ==, != <br>

## 6. What are increment and decrement operators? <br>
These operators are used to increase or decrease a variable’s value by 1. <br>
•	Increment operator: ++ (adds 1) <br>
•	Decrement operator: -- (subtracts 1) <br>
**Examples:** i++, --j <br>

## 7. Define type conversion. <br>
Type conversion is the process of converting one data type into another. <br>
It can be: <br>
•	Implicit (automatic by the compiler) <br>
•	Explicit (forced by the programmer using casting) <br>

## 8. What is operator precedence? <br>
Operator precedence defines the order in which operators are evaluated in an expression. <br>
**Example:** * and / have higher precedence than + and -. <br>

## 9. What is formatted I/O?<br>
Formatted input/output refers to input and output operations in C that use a specific format to read or display data.<br>
The functions **printf()** and **scanf()** are used for formatted I/O with format specifiers like %d, %f, %c.<br>

## 10. Define bitwise operators.<br>
Bitwise operators are operators that perform operations on individual bits of integer data.<br>
**Examples**: & (AND), | (OR), ^ (XOR), ~ (NOT), << (left shift), >> (right shift).<br>

## 11. What is the conditional operator?<br>
The conditional operator (?:) is a ternary operator used to make a decision based on a condition.<br>
It returns one value if the condition is true and another value if it is false.<br>
**Syntax**:<br>**
**condition ? expression1 : expression2;** <br>

## 5 Marks Questions<br>

## 1. Explain formatted I/O functions in detail <br>
Explain formatted I/O functions in detail<br>
Formatted Input/Output functions in C are used to read and display data in a specified format. These functions use format specifiers to control the type, size, and appearance of input and output data. The <br><br>commonly used formatted I/O functions are printf() and scanf().<br>

1. **printf()** – Formatted Output Function<br>
•	Used to display output on the screen.<br>
•	It prints data according to the format specified.<br>
•	Format specifiers indicate the type of data to be printed.<br>
**Syntax:**<br>
printf("format string", variable1, variable2, ...);<br>
**Example:**<br>
int a = 10;<br>
float b = 5.5;<br>
printf("a = %d, b = %.2f", a, b);<br>

2.**scanf()** – Formatted Input Function<br>
•	Used to read input from the keyboard.<br>
•	Stores input values into variables.<br>
•	Uses address operator (&) to store values in memory.<br>
**Syntax:**<br>
scanf("format string", &variable1, &variable2, ...);<br>
**Example:**<br>
int x;<br>
scanf("%d", &x);<br>

**Common Format Specifiers**<br>
•	**%d**→ Integer<br>
•	**%f** → Float<br>
•	**%c** → Character<br>
•	**%s** → String<br>

**Advantages of Formatted I/O**<br>
•	Easy to use<br>
•	Supports multiple data types<br>
•	Provides controlled and formatted output<br>

**Conclusion:** <br>
Formatted I/O functions (printf() and scanf()) are essential in C programming as they allow input and output of data in a structured and user-friendly format.<br>


## 2. Explain the different types of operators in C with examples <br>
Operators classify as follows (with short examples):<br>
1.	**Arithmetic operators:** + - * / %<br>
**Example:** a + b, a * b, a / b (integer division truncates), a % b (remainder).<br>
2.	**Relational (comparison) operators:** == != > < >= <=<br>
**Example:** if (a > b) ... returns 1 (true) or 0 (false).<br>
3.	**Logical operators**: && (AND), || (OR), ! (NOT)<br>
**Example:** if (a > 0 && b > 0) ...<br>
4.	**Assignment operators:** = and compound +=, -=, *=, /=, %=, &=, |=, ^=, <<=, >>=<br>
**Example:** x += 5; is x = x + 5;<br>
5.	**Unary operators:** +, -, !, ~ (bitwise NOT), ++, -- (prefix/postfix), & (address), * (dereference), sizeof<br>
**Example:** ++i;, p = &x;, sizeof(int).<br>
6.	**Bitwise operators:** & (AND), | (OR), ^ (XOR), ~ (NOT), << (left shift), >> (right shift)<br>
**Example:** x << 2 shifts left by 2 bits.<br>
7.	**Ternary operator:** ?:<br>
**Example:** max = (a > b) ? a : b;<br>
8.	**Comma operator:** , — evaluates left then right, returns right value.<br>
**Example:** i = (x++, x + 2); (rare in normal code)<br>


## 3. Discuss type conversion and type casting with examples <br>
Type conversion = converting a value from one data type to another. Two kinds: <br>
1. **Implicit (automatic) conversion (type promotion)** <br>
•	Performed automatically by compiler when mixed-type expressions occur. <br>
•	**Example:** int i = 5; float f = 2.0; float r = i + f; — i promoted to float before addition. <br>
•	Usual arithmetic conversions: smaller integer types promoted to int/unsigned int; int and double — int promoted to double. <br>
2. **Explicit conversion (type casting)** <br>
•	Programmer forces conversion using cast syntax (type) expression. <br>
•	**Example:** float x = 5.0 / (float)2; — cast ensures floating division and result 2.5. <br>
•	Another: int a = (int)3.9; — value becomes 3 (fraction truncated). <br>
**Important differences and cautions:** <br>
•	Implicit conversions can lead to loss of precision or unexpected results (e.g., integer division: 5/2 == 2).<br>
•	Casting to narrower type can truncate or overflow (e.g., casting large long to int).<br>
•	Use explicit cast to clarify intent and avoid warnings: (double)sum / count.<br>



## 10 Marks Questions <br>

## 1. Explain all operators in C language with suitable examples.<br>
Operators are special symbols that perform operations on data. C supports a rich set of operators classified into several categories.<br>
**1. Arithmetic Operators**<br>
Used for mathematical operations.<br>
**Operators**: + - * / %<br>
**Example:** <br>
int a = 10, b = 3;<br>
a + b = 13<br>
a - b = 7<br>
a * b = 30<br>
a / b = 3     // integer division<br>
a % b = 1     // remainder<br>

**2. Relational Operators**<br>
Used to compare two values; result is either true (1) or false (0).<br>
**Operators:** == != > < >= <=<br>
**Example:**<br>
a > b   // 1<br>
a == b  // 0<br>

**3. Logical Operators**<br>
Used to combine conditions.<br>
**Operators:** && (AND), || (OR), ! (NOT)<br>
**Example**:<br>
if (a > 0 && b > 0)<br>

**4. Assignment Operators**<br>
Assign values to variables; shorthand form reduces code length.<br>
**Operators:**<br>
= += -= *= /= %= <<= >>= &= |= ^=<br>
**Example:** <br>
x += 5;   // x = x + 5<br>

**5. Increment and Decrement Operators** <br>
Increase or decrease the value by 1.<br>
**Operators:** ++ (increment), -- (decrement)<br>
**Types:** <br>
•	Prefix: ++a (increment then use) <br>
•	Postfix: a++ (use then increment) <br>
**Example:** <br>
int a=5;  <br> 
b = ++a;  // a=6, b=6<br>
b = a++;  // a=7, b=6 <br>

**6. Bitwise Operators** <br>
Operate on individual bits. <br>
**Operators**:<br>
& (AND), | (OR), ^ (XOR), ~ (NOT), << (Left Shift), >> (Right Shift)<br>
 **Example:** <br>
a = 5;        // 0101<br>
b = 3;        // 0011 <br>
a & b = 1     // 0001 <br>
a | b = 7     // 0111 <br>
a ^ b = 6     // 0110 <br>
a << 1 = 10   // 1010 <br>

**7. Conditional / Ternary Operator** <br>
Short form of if-else. <br>
**Syntax:** <br>
(condition) ? expression1 : expression2; <br>
**Example**: <br>
max = (a > b) ? a : b; <br>

**8. Special Operators** <br>
a) **sizeof Operator** <br>
Returns the memory size of a data type or variable.<br>
sizeof(int);      // usually 4 <br>
sizeof(a); <br>
**b) Comma Operator** <br>
Evaluates multiple expressions, returns last value. <br>
int x = (a = 5, a + 10);   // x = 15 <br>
**c) Pointer Operators** <br>
•	& → address-of <br>
•	* → value at address <br>
int a = 10; <br>
int *p = &a;   // p stores address of a <br>
printf("%d", *p); // prints 10 <br>

9. **Member Access Operators** <br>
Used with structures: <br>
•	. → access structure member <br>
•	-> → access through pointer <br>

       **Example**:<br>
       struct student s;<br>
       s.age<br>
       ptr->age<br>

10. **Cast Operator** <br>
Converts one data type to another.<br>

float x = (float)5/2; // 2.5<br>

**Conclusion**: <br>
C supports a wide variety of operators that make it powerful, flexible, and suitable for <br>
system-level programming. Proper understanding of operators helps in efficient coding and <br>
error-free logic.<br>

## 2. Explain formatted and unformatted input/output functions in detail. <br>
C language provides two categories of input/output (I/O) functions through the <stdio.h><br>

**library**:<br>

1.**Formatted Input/Output Functions**<br>
These functions allow the programmer to read/write data in a specific format using format <br>
specifiers.<br>

A. Formatted Output Functions <br>
(i) **printf()** <br>
Used to display formatted output on the screen.<br>
Syntax:<br>
printf("format string", variables);<br>
**Example:** <br>
printf("Sum = %d", a + b);<br>

    **Format Specifiers:**<br>
    • %d → int<br>
    • %f → float<br>
    • %c → char<br>
    • %s → string<br>
    • %lf → double<br>
    • %u → unsigned<br>
    • %x/%X → hexadecimal<br>
    • %p → address<br>

     **Escape Sequences:**  <br>
    •**\n** (newline)<br>
    • **\t**  (tab)<br>
    • **\\**  (backslash)<br>
    • **\"** (double quote)<br>

**(ii) fprintf()** <br>
Writes formatted output to a file.<br>

**Example:** <br>
fprintf(fp, "Name: %s", name);<br>

**(iii) sprintf() / snprintf()** <br>
Writes formatted output to a character array.<br>
sprintf(str, "Value = %d", x);<br>

**B. Formatted Input Functions** <br>
**(i) scanf()** <br>
Reads formatted input from the keyboard.<br>
**Syntax:**<br>
scanf("format specifiers", &variables);<br>
scanf("%d %f", &a, &b);<br>
Points to Remember:<br>
• For %d, %f, %c, %lf, %s → use & (address-of) operator<br>
• %s stops at whitespace<br>
• Use width specifier to avoid overflow: scanf("%19s", name)<br>

**(ii)fscanf()** <br>
Reads formatted input from a file.<br>
fscanf(fp, "%d", &num);<br>

**(iii)sscanf()** <br>
Reads formatted data from a string.<br>
sscanf(str, "%d", &num);<br>

**2. Unformatted Input/Output Functions** <br>
Used for raw character or string handling without any formatting. More efficient for<br>
simpler data.<br>
A. Unformatted Output Functions<br>
**(i)putchar()** <br>
Writes a single character to the screen.<br>
putchar('A');<br>
**(ii)puts()** <br>
Writes a string followed by newline.<br>
puts("Hello World");<br>
**(iii) fputc(), fputs()**  <br>
Used for file operations. <br>
fputc('A', fp); <br>
fputs("Hello", fp); <br>

**B. Unformatted Input Functions** <br>
**(i)getchar()** <br>
Reads a single character. <br>
ch = getchar(); <br>
**(ii)gets()** (unsafe, removed from C11) <br>
Reads a string until newline. <br>
(iii) **fgets()** (safe alternative) <br>
Reads a line including spaces. <br>
fgets(str, 20, stdin); <br>
(iv) **fgetc(), fgets()**  <br>
For file reading <br>

                      **Difference Between Formatted & Unformatted I/O**  <br>
         **Formatted I/O**                                                  **Unformatted I/O** <br>
       Uses format specifiers                                            No formatting <br>
      Works with all data types                                      Works with char/strings  <br>
          Slower                                                            Faster <br>
      Functions: printf, scanf                                      getchar, putchar,gets, puts <br>
       More flexible                                                    Less flexible <br>

## UNIT – III: Control Structures, Arrays, and Strings<br>
## 2 Marks <br>

## 1. What is a control statement?<br>
A control statement is a statement in C that controls the flow of execution of a program<br>
based on conditions or loops.<br>
**Examples**  include if, if-else, switch, while, for, do-while.<br>

## 2. Write the syntax of if–else statement.<br>
    if (condition) {<br>
    // statements<br>
    }
    else {<br>
     // statements<br>
    }
## 3. What is a loop? Name any two types of loops.<br>
A loop is a control structure that repeats a block of code until a condition becomes false.<br>
**Two types:**  for loop, while loop.<br>
## 4. What is a break statement?<br>
The break statement is used to terminate a loop or switch statement immediately, and<br>
control transfers to the next statement after the loop/switch.<br>
## 5. What is an array?<br>
An array is a collection of elements of the same data type, stored in contiguous memory<br>
locations, accessed using an index.<br>
## 6. Define a two-dimensional array. <br>
A two-dimensional array is an array of arrays, used to store elements in rows and columns<br>
(matrix format).<br>
Example: int a[3][3];<br>
## 7. What is a string in C?<br>
A string in C is a character array terminated with a null character ('\0').<br>
Example: char name[10] = "Husen";<br>
## 8. Mention any two string handling functions.<br>
• **strlen(str)** – returns length of string<br>
•**strcpy(dest, src)** – copies one string into another<br>
(Other examples: strcat(), strcmp())<br>
## 5 Marks Questions<br>

## 1. Explain different types of control statements in C.<br>
Control statements in C are used to control the flow of execution of a program. They allow<br>
decisions, repetitions, and jumping in the program.<br>
They are mainly classified into three types:<br>

1. **Decision Control Statements** <br>
Used to make decisions based on conditions.<br>
• if<br>
• if-else<br>
• nested if<br>
• switch<br>
 **Example:** <br>
 if (a > b){<br>
 printf("A is greater");<br>
}<br>

2.**Looping / Iteration Statements**<br>
Used to repeat a set of statements.<br>
     • for loop<br>
     • while loop<br>
     • do-while loop<br>
   **Example:** <br>
   for(int i=1; i<=5; i++){<br>
   printf("%d ", i);<br>
 }<br>
**3. Jump Statements**<br>
Used to jump from one part of the program to another.<br>
• break<br>
• continue<br>
• goto<br>
• return Example:<br>
for(int i=1; i<=5; i++){<br>
 if(i==3)<br>
 break;<br>
}<br>
                                                        

