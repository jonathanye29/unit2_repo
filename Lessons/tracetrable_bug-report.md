# Bug Report for Trace Table

After completing the trace table, my team and I noticed some bugs within it. After realizing what the issue was, we consulted with you, and created new and accurate data that could be processed. 
Here were the bugs:

1. In instruction register 15, the operation code instructs the computer to jump back to the instruction register given (10), if the previous operation is not equal to zero . In instruction register 10, it instructs the computer to store the number 5. Since instruction register 15 instructs the computer to return to instruction register 10, it will create an infinite loop everytime it gets to 10, and the previous operation will never be equal to zero. In order to fix this bug, we changed the instruction register from 10 to 12, so the computer will have the chance to exit the loop once the operation before 15 equals zero.

2. In instruction register 17, the operation code given instructs the computer to save the decimal digit 15 to Register B, however, there was already a decimal digit there. In order to fix this bug, we changed the location to Register A since there was no information there.

3. In instruction register 19, the operation code given instructs the computer to save the value in Register B to the instruction register indicated in the 8-bit number that follows that instruction. The problem was that the instruction register indicated by the 8-bit number was outside of the computer's memory range. In order to fix this bug, we just changed the 8-bit number to a value that was inside of the computer's memory range and that wouldn't also interfere with the computer's operation. We matched the operation code of instruction register 17 so it would not create further bugs, but just follow the operation.

I hope my team and I identified the bugs and resolved them accurately.
