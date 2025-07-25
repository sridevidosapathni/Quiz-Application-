## Quiz-Application
This is a Java-based console application that conducts a multiple-choice quiz on Java programming. It displays a set of predefined questions with four options each, accepts user input as answers, evaluates them against correct answers, and finally presents a performance summary including the total number of correct and wrong answers, percentage score, and performance category.

- The application demonstrates key Java concepts such as:

- OOP (Object-Oriented Programming) — via the Questions class

- Collections API — using HashMap

- Control flow, user input, and string handling
# Java Console-Based Quiz Application

This is a simple **Java console application** that acts as a multiple-choice quiz platform focused on Java programming knowledge.

## Features

- 5 Multiple-choice Java questions
- Takes user input for answers
- Compares input with correct answer
- Displays score, correct/wrong counts, and performance level

## Technologies Used

- Java (JDK)
- Object-Oriented Programming (OOP)
- Java Collections (HashMap)
- Scanner for user input

## How it Works

1. The `Questions` class represents a single quiz question and its 4 options.
2. The `Quiz` class in `Main.java` holds:
   - List of questions
   - Correct answers stored in a `HashMap`
   - Logic to display questions, read user input, and evaluate answers
3. After all questions are answered, it calculates:
   - Total correct and wrong answers
   - Percentage score
   - Performance grade (Very Good, Medium, Very Low)

## Run the application

## Sample Output
 Which statement is true about Java?
A. Java is a sequence-dependent programming language 
B. Java is a code dependent programming language 
C. Java is a platform-dependent programming language 
D. Java is a platform-independent programming language 
Enter Your Answer: 
D
Correct
...
