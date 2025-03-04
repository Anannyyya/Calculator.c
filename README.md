# Colorful CLI Calculator

## 📌 Overview
This **Colorful CLI Calculator** is a simple C program that performs basic arithmetic operations with a visually appealing interface using ANSI escape sequences for color formatting. It also features a loading animation with sound effects using the `Beep` function (Windows-only).

## 🔧 Features
- **Addition**
- **Subtraction**
- **Multiplication**
- **Division**
- **Modulus**
- **Factorial Calculation**
- **Color-coded operations for better readability**
- **Loading animation with beep sound**

## 🖥️ Prerequisites
This program is designed to run on **Windows**, as it uses the `windows.h` library and the `Beep()` function. To compile and run the program, you need:
- A C compiler like **GCC (MinGW)** or **MSVC**

## 🚀 How to Compile and Run
1. **Clone or copy the code**
2. **Compile the code** using GCC:
   ```bash
   gcc calculator.c -o calculator.exe
   ```
3. **Run the program**:
   ```bash
   ./calculator.exe
   ```

## 📜 How to Use
1. The program displays a **menu** with different operations.
2. Choose an operation by entering the corresponding **number**.
3. Enter the required **input values** when prompted.
4. A **loading animation** with a beep sound will play before showing the result.
5. The program repeats until you **exit**.

## ⚠️ Notes
- The **modulus function** mistakenly prints `*` instead of `%`. It should be corrected in `printf("%d * %d = %d", n1, n2, res);` to `printf("%d %% %d = %d", n1, n2, res);`.
- **Factorial calculation** does not handle large values that may cause integer overflow.
- This program is **Windows-specific** due to the usage of `windows.h` and `system("cls")`.

## ✨ Future Improvements
- Add support for **Linux/MacOS** by replacing `windows.h` functionalities.
- Implement **floating-point division** to avoid integer truncation.
- Improve **error handling** for invalid inputs.
- Optimize the **factorial function** for large numbers using **long long int**.

---
💡 *Enjoy using the Colorful CLI Calculator!* 🚀

