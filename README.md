# C Programming Daily Tasks 

📅 **Submitted by:** Aishwarya Shrivastava  
🎯 **Objective:** Hands-on programming tasks using C for learning basic concepts such as variables, data types, operations, and input/output.

---

## 📁 File Structure

Each program is saved in a separate `.c` file and solves a specific problem. The filenames reflect the task number and title.

## C  Programming Daily Tasks -2nd June 2025
1. Declare and Print Integer Variable
Question:
Write a C program to declare an integer variable, assign a value to it, and print the value.
________________________________________
2. Add Two Float Numbers
Question:
Write a C program to add two float numbers and print the result.
________________________________________
3. Find Size of Data Types
Question:
Write a C program to display the size (in bytes) of int, float, double, and char data types.
________________________________________
4. Swap Two Variables Using a Temporary Variable
Question:
Write a C program to swap the values of two variables using a temporary variable.
________________________________________
5. Swap Two Variables Without Using a Temporary Variable
Question:
Write a C program to swap two integer variables without using a temporary variable.
________________________________________
6. Display ASCII Value of a Character
Question:
Write a C program to display the ASCII value of a character.
________________________________________
7. Calculate Simple Interest
Question:
Write a C program to calculate simple interest using the formula:
SI = (P × R × T) / 100,
where P is principal, R is rate, and T is time.
________________________________________
8. Multiply Two Integers
Question:
Write a C program to multiply two integers and display the result.
________________________________________
9. Find the Average of Three Numbers
Question:
Write a C program to calculate the average of three float numbers.

## C code for tasks on 3rd June - Operators in C

C Programming Questions on Operators
 1. Write a C program to demonstrate arithmetic operators (+, -, *, /, %).
 2. Write a C program to demonstrate relational operators (>, <, ==, !=, >=, <=).
 3. Write a C program to demonstrate logical operators (&&, ||, !).
 4. Write a C program to demonstrate bitwise operators (&, |, ^, ~, <<, >>).
 5. Write a C program to demonstrate compound assignment operators (+=, -=, *=, /=, %=).
 6. Write a C program to demonstrate increment and decrement operators (++ and --).
 7. Write a C program to find the maximum of two numbers using the ternary operator.
 8. Write a C program to display the size of various data types using the sizeof operator

###Daily life based C programming practice questions

Here’s a set of **daily-life-based C programming practice questions** focusing on the following topics:

* **Bitwise operators**
* **Shift operators**
* **`if` / `if-else` / nested `if-else`**
* **Looping statements** (`for`, `while`, `do-while`)

These problems are designed to reflect real-world scenarios, making learning more intuitive and interesting.

---

### 🔹 **1. Bitwise Operators – Daily Life Problem**

**Problem: Home Light Switches**

You have 8 lights in your home, each represented by a bit (1 = ON, 0 = OFF). Write a C program that:

* Turns ON light 3 and light 7.
* Toggles the state of light 5.
* Checks whether light 2 is ON or OFF.

> Use bitwise operators: `|`, `&`, `^`, `~`

---

### 🔹 **2. Shift Operators – Digital Clock Timer**

**Problem: Digital Clock Multiplication**

Imagine you're building a basic clock that counts seconds. To convert seconds into milliseconds (by multiplying by 1000), instead try to optimize:

* Multiply a number by 2, 4, 8 using **left shift (`<<`)**.
* Divide a number by 2, 4, 8 using **right shift (`>>`)**.

> Write a program that asks for seconds and displays the result using only shift operations.

---

### 🔹 **3. If Statement – Traffic Light System**

**Problem: Pedestrian Crossing**

Ask the user to input the color of a traffic light (`R`, `Y`, `G`):

* If it's Red (`R`), print: "Stop".
* If it's Yellow (`Y`), print: "Get Ready".
* If it's Green (`G`), print: "Go".

> Use simple `if` statements (no `else`).

---

### 🔹 **4. If-Else – Temperature Monitor**

**Problem: Room AC Controller**

Get the current room temperature as input.

* If it's greater than 30°C, print "Turn on AC".
* If it's 30°C or below, print "No need for AC".

> Use `if-else`.

---

### 🔹 **5. Nested If-Else – Bus Ticket Fare**

**Problem: Bus Fare Discount System**

Ask the user for:

* Age
* Gender

Apply discounts:

* If age < 12: 50% discount
* Else if age >= 60:

  * If female: 40% discount
  * Else: 30% discount
* Else: No discount

> Use nested `if-else`.

---

### 🔹 **6. For Loop – Electricity Bill**

**Problem: Monthly Electricity Calculation**

Assume you use a smart meter that records electricity usage per day for 30 days. Ask the user to enter daily usage in units (one value per day), and calculate total and average.

> Use a `for` loop to iterate over 30 days.

---

### 🔹 **7. While Loop – Password Retry**

**Problem: ATM PIN Entry**

Ask the user to enter a 4-digit PIN. Allow up to 3 attempts. If correct, print “Access granted”, otherwise print “Card blocked”.

> Use a `while` loop.

---

### 🔹 **8. Do-While Loop – Washing Machine Timer**

**Problem: Countdown Timer**

Ask the user for wash cycle time in seconds. Print a countdown from that number to 0, one per second.

> Use a `do-while` loop.

---

### 🔹 **9. Bitwise Logic – Smart Home Control**

**Problem: Sensor Alerts**

You have sensors in 4 rooms. Each bit in a 4-bit number represents if a room is occupied (1) or empty (0). Write a program that:

* Takes a 4-bit value (e.g. 0b1011).
* Counts how many rooms are occupied.

> Use bitwise AND and right shift in a loop.

---

### 🔹 **10. Combined Task – Water Purifier Status**

**Problem: Maintenance Alert System**

You have a system that:

* Uses bitwise flags to check filter health.
* Uses `if` statements to decide what to do.
* Uses a loop to monitor status for 7 days.

**Write a program that:**

* For each day, randomly sets filter status (good or bad using bits).
* If filter is bad for more than 3 days, print “Service Required”.


# 8th June C Programming Task – Type Casting in C

This project contains a set of beginner-friendly C programs focused on exploring and practicing **type casting** in C programming. Each program is designed to demonstrate specific scenarios where either **implicit** or **explicit** type conversions are used in practical applications.

---

## 📂 Task Overview

### 1. Fahrenheit to Celsius Conversion
- Converts a temperature from Fahrenheit to Celsius.
- Uses **explicit type casting** to print the Celsius temperature as an integer.

### 2. Integer Division with Float Result
- Divides two integers and displays the result as a **float**.
- Demonstrates **explicit type casting** for accurate decimal division.

### 3. Implicit vs Explicit Casting
- Adds an integer and a float together.
- Highlights the difference between **implicit casting** (automatically handled by compiler) and **explicit casting** (done manually).

### 4. Character to ASCII Conversion
- Takes a **character input** and prints its **ASCII value**.
- Uses explicit type casting to convert the character to its integer representation.

### 5. Float Salary to Integer for Reporting
- A float salary value is converted to an **integer** for reporting purposes.
- Demonstrates loss of precision when truncating decimal parts.

### 6. Average Marks as Float
- Calculates the **average of three integer marks**.
- Converts the result to float to ensure accurate decimal output.

### 7. Double to Int Conversion
- Converts a **double** value to **int**.
- Highlights **precision loss** due to truncation of decimal values.

### 8. Weight Conversion for Packaging
- A float weight is **rounded down** using type casting to fit packaging rules.
- Uses explicit cast to truncate decimal and return whole number.

### 9. Mixed-Type Billing Calculation
- Combines **rupees (int)** and **paise (float)** to compute total amount.
- Uses casting to normalize both values into a single float total.

### 10. Compare Results With and Without Casting
- Performs the same division operation using **int** and **float**.
- Compares results to show the importance of casting in avoiding integer truncation.


