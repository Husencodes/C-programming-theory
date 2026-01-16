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
