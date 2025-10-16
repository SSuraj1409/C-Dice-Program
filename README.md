# 🎲 Dice Program – C Project

A customizable C program that simulates dice rolls and calculates the percentage of times each face appears. It uses arrays, loops, and randomness to model real-world dice behavior in the terminal.

---

## 👥 Team Members

- Chris Edappady 
- Suraj Srinivasan 

---

## 📄 Description

This C program simulates rolling a die based on user-defined inputs — the number of faces and the number of throws. It demonstrates the use of `rand()` and `srand()` functions from the standard library to produce random outcomes, and utilizes time-based seeding to ensure randomness across runs.

### 🔍 How It Works:

- The program begins by including `<stdlib.h>` for random number generation and `<time.h>` to seed the generator using the current time.
- It asks the user to input the number of faces and number of throws using a `do-while` loop to validate correct input.
- An array `OccurrencesofFaces` is used to track how often each face appears during the simulation.
- After generating the outcomes for the given number of throws, the program calculates the percentage frequency of each face.
- The final output displays how many times each face occurred and its percentage over total throws.

This project is ideal for learning control structures, user input handling, arrays, and probability simulation in C.

---

## 🛠 Technologies Used

- C Programming Language
- `stdlib.h`, `stdio.h`, `time.h`

---

## 📷 Output Screenshot

<h3>On entering the valid input:</h3>  
<div align="center">
<img src="https://i.imgur.com/dqoD6zc.png" width="80%" alt="StudySpace Home Page"/>
</div>

<br/>


<h3>On entering the invalid input:</h3>  
<div align="center">
<img src="https://i.imgur.com/huWwc9f.png" width="80%" alt="StudySpace Home Page"/>
</div>

<br/>

---

## ## **🔒 Full source code available in a private repository. Please contact me for access.**
