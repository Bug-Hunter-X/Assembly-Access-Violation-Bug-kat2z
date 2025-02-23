# Assembly Access Violation Bug

This repository demonstrates a common error in assembly programming: an access violation caused by dereferencing invalid memory addresses.  The bug involves a sequence of instructions that could lead to a crash if the pointers are not properly handled. The solution shows how to prevent the access violation by adding necessary checks before dereferencing memory locations. 

## Bug Report

The bug is in `bug.asm`. The code attempts to dereference memory addresses without checking if they're valid.  This can lead to an access violation and program termination. 

## Solution

The solution is provided in `bugSolution.asm`. Before accessing memory, it verifies pointer validity. This helps prevent access violations. 