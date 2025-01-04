# Integer Division by Zero in Assembly
This repository demonstrates a subtle integer division by zero error in assembly language. The error occurs because a register used in the division is inadvertently set to zero.

## Bug Description
The code attempts to divide by 10. However, due to a mistake in the register assignment, the divisor ends up being 0, resulting in an error. The error is not immediately obvious.

## Solution
The solution corrects the register assignments and ensures that the divisor is never zero. 

## How to reproduce
1. Assemble the code in bug.asm
2. Run the assembled code. You will observe the integer division by zero error.