---
toc: true
layout: post
title: AP Exam Prep Study Guide (MC Content)
description: Yippeee
courses: { csse: {week: 4}, csp: {week: 4, categories: [4.A]}, csa: {week: 25}}
type: hacks
---

<h1>Unit 1 Primitive Types (2.5-5%)</h1>

<h2>Unit 1.1 Why Programming? Why Java?</h2>

- Comments → /*....*/
- Class Declaration → public class HelloWorld {} (class MUST match file name) 
- Main Method → public static void main (String[] args) {} (controls action in program)

Output
- System.out.print(“”);
- System.out.println(“”); (move cursor to next line) 
- String literal = exact sequence of characters which are enclosed between 2 quotation marks 

3 Error Types 
- Syntax/Compiler error Ex. System.ot.print(“Hi”); 
- Exception: occurs while program is running and will cause the program to terminate abnormally. “Throws an exception” Ex. Program attempts to divide a number by 0 
- Logic error: Detected after a program has been run when actual output is compared to anticipated output Ex. Programmer accidentally uses - instead of + when finding sum of 2 numbers

<h2>Unit 1.2 Variables and Data Types </h2>

- Variable = name given to a memory location that is holding a specified type of value 

Naming 
- May not start with digit, spaces not allowed, may not use any other characters such &, @, $
- Good practice use “camel case” → helloWorld
- Can’t use reserved Java words (public, static, void, main)

Declaring variables in code 
- int total; 
- double intRate
- boolean isTrue

- Declaring variable that cannot be changed once give it a value (underscores and all caps) → <mark>what’s the point of variable if just a set value…??</mark>
- Ex. final double PI, final int DAYS_IN_WEEK; 

Primitive data = determines size and type of information, already part of Java language
1. Boolean - 1 bit 
2. Int (whole number) - 32 bits
3. Double (floating-point numbers) - 54 bits

Non-primitive data = use methods to perform actions 
1. String 

<h2>Unit 1.3 Expressions and Assignment Statements </h2>

- Literal vs String Literal 
- Concatenation: System.out.print(“3” + “3”); → prints out 33
- Arithmetic operators: +, -, *, /, % (remainder) 
- Same data types → stays same data type 
- If mixed data types in arithmetic operation, output is always bigger data type Ex. double + int = double 
- Java rounds DOWN for integer division Ex. 3/2 = 1 

Compound Expressions (PEMDAS, left to right) 
- Divide by 0 → ArithmeticException 

Assignment operator = assign value on right to variable on left 
- Ex. x = y = x = 7;  x = 7 

<h2>Unit 1.4 Compound Assignment Operators </h2>

+= (other words → x = x + 7), -=, *=, /=, %=
Increment (++) and decrement (--) 
x++; (add 1) x--; (subtract 1)

Describe behavior of identified code segment 
- Terms: define, initial value, current value, assign, display, variable

<h2>Unit 1.5 Casting and Ranges of Variables </h2>

- Casting = temporarily changing the data type of a variable 
Ex. System.out.println( (double) 6 / 4); #displays 1.5 
Ex. int roundedNumber = (int) (number + 0.5); 

- Data types have limit to how much info can store 
Int → 2,147,483,647 (or Integer.MAX_VALUE)max value, min value (Integer.MIN_VALUE) is that but - 
Double → up to 14-15 digits 





