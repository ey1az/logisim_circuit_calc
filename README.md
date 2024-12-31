# LogiSim Calculator - Addition and Subtraction of Decimal Unsigned Integers

## Overview
This LogiSim project implements a simple calculator that can add and subtract decimal unsigned integers. The calculator has a display of 5 decimal digits and a number pad with digits 0-9 and operators +, -, and =.

## Features
- **Number Pad**: Includes digits 0-9 for input.
- **Operators**: 
  - **+** (Addition)
  - **-** (Subtraction)
  - **=** (Equals)
- **Display**: 
  - Displays up to 5 decimal digits.
  - Right-aligned display for numbers (up to 4 digits).
  - The display resets after each operator (`+` or `-`).
  - After pressing `=`, the result is shown.

## Functionality
1. **Entering Numbers**: 
   - Type the first number on the number pad. The number will be displayed right-aligned, up to 4 digits.
   
2. **Operators**:
   - Press `+` or `-` to prepare for the next number. The display will be cleared, ready for the second number.
   
3. **Second Number**:
   - Type the second number. The display will again show the number right-aligned.

4. **Result**:
   - Press `=` to calculate the result.
   - The display will show the result. If the result is negative, the leftmost (5th) digit will show a minus sign; otherwise, it will display the positive result.

## Input/Output Specifications
- **Inputs**: 
  - Maximum 4 digits for each number.
  - Only positive numbers are allowed for input (no negative inputs).
- **Output**:
  - Result of the addition or subtraction is displayed with up to 5 digits.
  - For subtraction, if the result is negative, the leftmost (5th) digit will display a minus sign; otherwise, the result is displayed as a positive number.

## Implementation Notes
- The calculator operates directly on **BCD (Binary Coded Decimal)** numbers for both addition and subtraction.
- The display is designed to handle results from both operations, with proper handling for negative results in subtraction.

## How to Use
1. Press the digits (0-9) to input a number.
2. After entering the first number, press `+` or `-` to begin entering the second number.
3. After entering the second number, press `=` to see the result of the calculation.

## File
The LogiSim circuit file for this project is included as `LogiSim_Calc.circ`.

## Requirements
- LogiSim software to run and modify the circuit.

## Disclaimer

This project is open for personal use, modification, and redistribution under the condition that **you do not claim it as your own work**. If you modify or distribute this project, you must provide proper attribution to the original creator (me) and clearly state any modifications made.

By using this project, you agree to follow these guidelines and give credit where it's due.

Thank you for respecting the effort that went into creating this project!
