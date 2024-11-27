# ICS3203-CAT2-Assembly--Muchai-Riungu-136592-.
# Assembly Programming with NASM - Project Overview

---

## **Program 1: Number Classification**

### **Description:**
This program prompts the user for input and classifies the entered number as positive, negative, or zero. The result is then displayed.

### **Execution Steps:**
1. Save the code as a `.asm` file.
2. Assemble the code using NASM.
3. Link the file and run the resulting executable.

### **Key Learnings:**
- Gained insights into how input and output operations are handled in assembly.
- Understood the branching logic and flow control mechanisms in low-level programming.
  
---

## **Program 2: Reversing an Array of Integers**

### **Description:**
The program asks the user to input 5 integers, then reverses the array using pointer-based swapping from both ends until they meet in the middle.

### **Execution Steps:**
1. Save the code as a `.asm` file.
2. Assemble the code using NASM.
3. Link the file and run the resulting executable.

### **Challenges Faced:**
- Addressing errors and incorrect length handling led to unexpected outputs or crashes.
- Ensuring all edge cases were properly handled to avoid unintended behavior or fall-throughs.

---

## **Program 3: Stack Frame and Recursion**

### **Description:**
This program demonstrates stack management and recursive function calls using NASM. 

### **Stack Operations Summary:**
- `push ebp` - Saves the caller’s base pointer.
- `mov ebp, esp` - Sets up a new stack frame.
- `push ebx` - Saves the caller’s `ebx` value.
- `push eax` - Passes the argument `(n-1)` for recursion.
- `pop ebx` - Restores the caller’s `ebx` value.
- `mov esp, ebp` - Restores the stack pointer.
- `pop ebp` - Restores the base pointer.

---

## **Program 4: Sensor-Based Water Level Control System**

### **Description:**
This program interacts with a memory-mapped sensor to monitor water levels. Based on the sensor's reading stored in the `AL` register, the program triggers different actions:
- **Low water level:** Turns on the motor.
- **High water level:** Activates an alarm.
- **Moderate water level:** Stops the motor.

---


