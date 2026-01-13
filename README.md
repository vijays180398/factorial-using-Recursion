Factorial Calculation Using Recursion (Java)
📌 Project Description

This project is a Java console-based application that calculates the factorial of a number using recursion.
It demonstrates the use of recursive functions, base cases, and error handling for edge cases such as factorial of 0 and negative numbers.

This is a beginner-friendly project and commonly asked in programming interviews.

🎯 Features

Recursive calculation of factorial

Handles factorial of 0

Validates negative number input

Console-based user interaction

Clean separation of logic and execution

🛠️ Technologies Used

Java

Recursion

Scanner (User Input)

Exception Handling

🧱 Project Structure
Factorial-Using-Recursion
│
├── FactorialCalculator.java
├── Main.java
└── README.md

📂 Class Overview
🔹 FactorialCalculator.java

Contains the recursive method:

factorial(int n)

Handles base cases and invalid inputs

🔹 Main.java

Takes user input

Calls the recursive factorial method

Handles exceptions and displays output

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/factorial-using-recursion.git


Navigate to the project directory:

cd factorial-using-recursion


Compile the Java files:

javac FactorialCalculator.java Main.java


Run the program:

java Main

📸 Sample Output
✔ Valid Input
Enter a number: 5
Factorial of 5 is: 120

✔ Edge Case (0)
Enter a number: 0
Factorial of 0 is: 1

❌ Invalid Input (Negative Number)
Enter a number: -4
Error: Factorial is not defined for negative numbers.

🧠 Concepts Used

Recursion

Base case handling

Input validation

Exception handling

Control flow

⚠️ Edge Cases Handled

Factorial of 0

Negative numbers

Non-integer input

🚀 Future Enhancements

Iterative factorial implementation

Large number support using BigInteger

Menu-driven math utilities

Unit testing using JUnit

👨‍💻 Author

Vijay babu
Aspiring Java & DevOps Engineer
