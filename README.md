# ARM Assembly Hexadecimal Filter Program

**Computer Architecture & Organization Assignment**  
Course: CSN6114 | Trimester 2510 | Multimedia University

## Overview

ARM assembly program that filters 32-bit hexadecimal values by selectively removing digits 1, 3, 5, 7, and 9 while preserving digits 0, 2, 4, 6, 8, and A-F. The program processes 10 input values with O(8n) time complexity and achieved 100% test accuracy.

## Key Features

- Nibble-level processing of 32-bit values
- Selective digit filtering with conditional logic
- Memory-mapped I/O operations
- Inline processing for efficiency
- Comprehensive test coverage with 10 test cases

## Technical Specifications

- **Input:** 10 32-bit hex values at memory locations 0x2000-0x2024
- **Output:** Filtered results stored at 0x2100-0x2124
- **Processing:** 8 nibbles per value, sequential filtering
- **Time Complexity:** O(8n) where n = number of values
- **Space Complexity:** O(1) constant additional memory

## Implementation Highlights

- ARM instruction set for bitwise operations
- Auto-increment addressing for memory optimization
- Conditional move instructions to reduce branching
- Loop control with pointer management

## Test Results

All 10 test cases passed with 100% accuracy:
- Values with no removable digits preserved correctly
- Partial filtering performed accurately
- Edge cases (all digits removed) handled properly

## Technologies Used

- **Language:** ARM Assembly
- **Platform:** ARM Architecture
- **Tools:** ARM Simulator, Memory Debugger
- **Concepts:** Bitwise Operations, Memory Management, Low-level Programming

## Team Members

- **Eba Mohamed Abbas Ahmed** (Leader) - 242UC243BE
- Lama M. R. Siam - 242UC243B4
- Hamsa Hashim Omer - 242UC241DB
- Siti Zulaikha Binti Abdul Razif - 242UC243TL

## Course Information

**Course:** CSN6114 - Computer Architecture and Organization  
**Tutorial Section:** T21L  
**Group:** 3  
**Trimester:** 2510

