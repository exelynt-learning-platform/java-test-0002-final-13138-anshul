# java-test-0002-final-13138-anshul
Final Project Assignment - This repository contains the complete final project code and documentation.

# Mirrored Number Pyramid Pattern in Java

## 📌 Project Overview

This project demonstrates how to generate a **mirrored number pyramid pattern** using **nested loops in Java**.
It is a common programming exercise used in coding assessments to evaluate a candidate’s understanding of **loops, logic building, and pattern printing**.

The program prints a symmetrical pyramid where numbers increase and then decrease in each row.

---

## 🎯 Problem Statement

Write a Java program that prints the following pattern exactly:

```
        1
      1 2 1
    1 2 3 2 1
  1 2 3 4 3 2 1
1 2 3 4 5 4 3 2 1
```

---

## 💻 Technologies Used

* Java
* Nested Loops
* Console Output

---

## 🧠 Logic Explanation

The pattern is created using **three nested loops**:

1. **Outer Loop**

   * Controls the number of rows in the pyramid.

2. **First Inner Loop**

   * Prints spaces to align the pyramid properly.

3. **Second Inner Loop**

   * Prints numbers in **ascending order** from `1` to the current row number.

4. **Third Inner Loop**

   * Prints numbers in **descending order** from `row-1` back to `1`.

This creates the mirrored pyramid structure.

---


## ▶️ How to Run the Program

1. Save the file as **NumberPyramid.java**
2. Open terminal or command prompt.
3. Compile the program:

```
javac NumberPyramid.java
```

4. Run the program:

```
java NumberPyramid
```

---

## 📊 Output

```
        1
      1 2 1
    1 2 3 2 1
  1 2 3 4 3 2 1
1 2 3 4 5 4 3 2 1
```

---

## ⏱ Time Complexity

* **O(n²)** due to nested loops.

---

## 📚 Learning Outcome

After completing this program, you will understand:

* How to use **nested loops in Java**
* Pattern printing logic
* Building symmetrical patterns
* Improving logical thinking for coding interviews

