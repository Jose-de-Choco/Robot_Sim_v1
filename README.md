**Robot Simulator**

This project written in C++ aims to simulate how a simple walking robot could
move by using printed messages and Numerical input and character and word
commands.

Controls:

**Lexical Commands**

* **_r_** Puts the robot into **reverse** gear.
* **_f_** Puuts the robot back into  **forward** gear.
* **_displace_** displays the robot's linear displacement.
* **_off_** breaks the 'while' loop and completes the code.

**Numerical Commands**

* Every **_5_** Entered into the input window will make the robot move 1cm in the desired direction.
* Every **_7_** Entered into the input window will make the robot face 5 degrees to the right.
* Every **_3_** Entered into the input window will make the robot face 5 degrees to the left.

---------------------------------------

The code works by assigning functions called **move**, **right**, and **left**.
They are called upon when certain conditions are met, and with variables that dictate
how far the robot moves/turns: **cMove**, **cRight**, and **cLeft**.
e.g.
```c++
if (cRight > 0) {
    right(cRight);
}
```
---
**Jose de-Choco** | 2026

My first Project and made to learn C++.
All future projects can be found at my [Github Page](
