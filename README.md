# Binary Converter in C++

This simple C++ program converts a **binary number** entered by the user into its **decimal** equivalents.

## 📘 How It Works
1. The program asks the user to enter a binary number.
2. It converts the binary string to a decimal value using a loop.
3. It then displays:
   - Decimal value
     
## 🧩 Code Overview
Key parts of the program:
- Uses `<iostream>` and `<string>` for input/output and string handling.
- The conversion logic multiplies the current decimal value by 2 and adds the next binary digit.

## ▶️ How to Run
1. Copy the code into a file named `binary_converter.cpp`.
2. Compile using any C++ compiler:
   ```bash
   g++ binary_converter.cpp -o binary_converter
